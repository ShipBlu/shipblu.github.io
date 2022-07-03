---
layout: default
title: Tutorial
nav_order: 3
description: "Tutorial on Using Our API"
permalink: /tutorial
---

<style>
.point{
    color: #0f81a2
}
.list{
    color: #000
}
</style>

# ShipBlu API Tutorial

In this tutorial we will tell a story of a merchant who wants to integrate their online e-commerce store to our delivery service.

## Geographic Availability

The first question is "Where does ShipBlu operate?" To answer this question, you can explore what governorates we cover:

```
$ curl -H 'Authorization: Api-Key <YOUR-API-KEY>' -X GET https://api.shipblu.com/api/v1/governorates/
```

The response gives you back a list of governorates that are covered by ShipBlu Service.

```
[
    {
        "id": 1,
        "name": "القاهرة - Cairo"
    },
    {
        "id": 2,
        "name": "الاسكندرية - Alexandria"
    },
    ,
    {
        "id": 3,
        "name": "الساحل الشمالي - North Coast"
    },
    :
    :
    <response trimmed for clarity>
]
```

In each governorate, you can list the cities under it using:

```
$ curl -H 'Authorization: Api-Key <YOUR-API-KEY>' -X GET https://api.shipblu.com/api/v1/governorates/<governorate-id>/cities/
```

The response gives you back a list of cities that are served in that governorate. For example, querying for Cairo will give you:

```
[
    {
        "id": 1,
        "name": "القاهرة الجديدة - New Cairo",
        "governorate": {
            "id": 1,
            "name": "القاهرة - Cairo"
        }
    },
    {
        "id": 2,
        "name": "وسط البلد - Downtown Cairo",
        "governorate": {
            "id": 1,
            "name": "القاهرة - Cairo"
        }
    },
    {
        "id": 3,
        "name": "اكتوبر - October",
        "governorate": {
            "id": 1,
            "name": "القاهرة - Cairo"
        }
    }
    :
    :
    <response trimmed for clarity>
]
```

We divide each city to zones to ensure delivering packages within the customer's preferred delivery window.
In order to get the zones of a city, call:

```
$ curl -H 'Authorization: Api-Key <YOUR-API-KEY>' -X GET https://api.shipblu.com/api/v1/cities/<city-id>/zones/
```

The response gives you back the list of zones covered in that city.

```
[
    {
        "id": 1,
        "name": "التجمع الثالث - 3rd Settlement",
    },
    {
        "id": 2,
        "name": "التجمع الخامس - 5th Settlement",
    }
    :
    :
    <response trimmed for clarity>
]
```

## Service Levels

At ShipBlu, we strive to meet our service level agreements.
We take it seriously to plan a package delivery on the exact day we promise to delivery the package on.

In order to get the service levels for a governorate, you can use:

```
$ curl -H 'Authorization: Api-Key <YOUR-API-KEY>' -X GET https://api.shipblu.com/api/v1/service-availability/?governorate_id=<Governorate-ID>&subscription_id=<Subscription-ID>
```

where `subscription_id` is retrieved from the merchant info. The response object looks like:

```
[
    {
        "governorate": {
            "id": 1,
            "name": "القاهرة - Cairo"
        },
        "service_level": {
            "id": 3,
            "name": "2 Days",
            "short_code": "2D",
            "description": "2 Business Days"
        },
        "package_size": {
            "id": 1,
            "name": "Small Flyer (25x35cm)",
            "short_code": "S-FLY",
            "description": "Small Flyer (25x35cm)"
        }
    },
    :
    :
    <response trimmed for clarity>
]
```

This represents a list of service availability where each object contains a `governorate`, a `service_level` and a `package_size`.
For example, a governorate that has 2 service levels (e.g. Overnight and 2 Days) and 2 package sizes (e.g. Small Flyer and Large Flyer) will return a list of 4 objects.

> **Why are they separate?**
  In some governorates, we are able to deliver mailers in a given service level, but large boxes take more time.
  That's why we cannot return this as a flat list of available service levels and package sizes.
  If you want to flatten the result, use a functional programming transformation, such as `unique`, to get unique service levels and/or package sizes.


## Orders

At this point, you are all set up to start creating orders on our system.
ShipBlu offers delivery, return, exchange and cash collection services.

### Delivery Orders

#### List

```
$ curl -H 'Authorization: Api-Key <YOUR-API-KEY>' -X GET https://api.shipblu.com/api/v1/delivery-orders/?limit=10
```

Response

```
{
    "count": Number,
    "next": "https://api.shipblu.com/api/v1/delivery-orders/?limit=10&offset=10",
    "previous": null,
    "results": [
        {
            "id": Number,
            :
            :
        },
        :
        <response trimmed for clarity>
    ]
}
```

#### Create

```
$ curl -H 'Authorization: Api-Key <YOUR-API-KEY>' -H "Content-Type: application/json" -X POST -d '<request-body>' https://api.shipblu.com/api/v1/delivery-orders/
```

where `<request-body>` is:

```
{
    "customer": {
        "full_name": String,
        "phone": String,
        "address":{
            "line_1": String,
            "line_2": String,
            "zone": Integer
        }
    },
    "packages": [
        {
            "package_size": Integer
        }
    ]
}
```

These are the minimum number of parameters that you need to send.
Refer to the [API Reference](api-reference) for a full documentation on the other parameters you can set.

#### Update

```
$ curl -H 'Authorization: Api-Key <YOUR-API-KEY>' -H 'Content-Type: application/json' -d '<request-body>' -X PATCH https://api.shipblu.com/api/v1/delivery-orders/
```

where `<request-body>` is the same as the used in the `POST` request.


### Other Orders

Returns, exchanges and cash collection orders follow the same scheme.
Please, refer to the complete API reference for detailed signatures.


## What's Next?

Bravoo! You made it to this point.

You can explore the full API functionality in the [API Reference](api-reference).
