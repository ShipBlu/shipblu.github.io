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
{: .fs-9 }

In this tutorial we will tell a story of a merchant who wants to integrate their online e-commerce store to our delivery service.

Before start we need to introduce only two major concept:

1. <span class="point">Customer Agent (CA):</span> Is a person that deliver shipment to customer.
2. <span class="point">Merchant Agent (MA):</span> Is a person that deal with merchant.

After we introduce above two concepts let's don't waste a lot of time and let's start.

We will start tutorial by passing on following points:

[geo availability](api-reference#geographic-availability), to [service availability](api-reference#service-availability) to placing an [orders](api-reference#orders) and viewing orders.

## Geo Availability
<br />
ShipBlu offers four major concepts that illustrate  geo availability that introduce it.

<div style="text-align:left"><img src="/assets/img/geo.png" width="340px" /></div>

1. <span class="point">Governorates</span>

   ShipBlu introduce his service in all egypt governorates from Alexandria to Aswan.
   <br />
   You can deliver your shipment to any place in egypt without any  headache about how deliver it.
   <hr />
2. <span class="point">Cities & Zones</span>

   AS we know each governorate has many cities, and each city consist of some zones.
   <br /> 
   For good ShipBlu can deliver your shipment to any place within city.
   <hr />
3. <span class="point">PUDOs</span>

   We can define PUDOs as drop off points that CA can drop shipments on it and the Customer receive it from this PUDO.

   ShipBlu provide this service to save merchant and customer order shipment cost.
   <hr />


You can discover geo availability ShipBlu APIs from [here](api-reference#geographic-availability). 

Now after we talked about [geo availability](#geo-availability) and how ShipBlu categories it and deal with it.<br />
let's talk about other concept called service availability.

## Service Availability
<br />
Service availability is the services that ShipBlu can introduce it to merchants. This services is represented in the following points:

- <span class="point">Service Level</span>

  ShipBlu introduce service level concept that determine periods that shipment delivered to customer within. Service level determined by merchant based on his governorate and subscription, it consist of four categories.

  Availabel service level:

  - <span class="list">overnight</span>
  - <span class="list">2 days</span>
  - <span class="list">3 to 5 days</span>
  - <span class="list">5 to 7 days</span>

  <hr />
- <span class="point">Package Size</span>

  ShipBlu introduce two package size option:

  - <span class="list">Small Flyer (25x35cm)</span>
  - <span class="list">Large Flyer (50x45cm)</span>

  <hr />
- <span class="point">Handshake Type</span>

   ShipBlu introduce handshake type concept that determine how CA will deliver shipment to customer. it consist of two categories:

   - <span class="list">D2D (Door To Door)</span>

        From its name, CA will deliver shipment to customer door.

   - <span class="list">PUDO</span>

        As we mention [PUDO](#geo-availability) is drop off points that CA can drop shipments on it and the Customer receive it from this point.

You can discover service availability ShipBlu APIs from [here](api-reference#service-availability).   

Now after we talked about [geo availability](#geo-availability) and [service availability](#service-availability). let's talk about how placing an orders and viewing it.  

## Orders
<br />
ShipBlu introduce awesome features to merchant to control his orders.<br />

Before discover these features let's talk shortly and quickly about orders types.

Orders are divided into three categoricals:

- <span class="point">Delivery</span>

    Delivery order: is order that merchant want to deliver it to customer.

  <hr />
- <span class="point">Return</span>

    Return order: is order that merchant want to get it from customer.

  <hr />
- <span class="point">Exchanges</span>

    exchange order: is order to deliver shipment to customer and get another shipment from him.

<hr />
Now after we talked about orders types, Let's discover these features together:

- <span class="point">List all orders</span>

    Merchant can show all (delivery, return, and exchange) orders info that he has created its.
    <hr />
- <span class="point">Create new one</span>

    Merchant can create new (delivery, return, and exchange) orders.
    <hr />
- <span class="point">Retrieve specific one</span>

    Merchant can show specific (delivery, return, and exchange) order info.
    <hr />
- <span class="point">Update specific one</span>

    Merchant can update all info of specific (delivery, return, and exchange) order.
    <hr />
- <span class="point">Partial update specific one</span>

    Merchant can update some info of specific (delivery, return, and exchange) order.
    <hr />
- <span class="point">Delete update specific one</span>

    Merchant can delete specific (delivery, return, and exchange) order.
    <hr />

You can discover ShipBlu APIs of all above features from following links: 

- [Delivery](api-reference#delivery)
- [Return](api-reference#return)
- [Exchanges](api-reference#exchanges)

There is other feature ShipBlu introduce it to merchant to save his time to create multiple delivery order. 

- <span class="point">Create multiple delivery orders</span>

    This feature divides into two steps:

    - <span class="list">Download template file</span>

        In this step you can download delivery order template file to add multiple delivery orders.

    - <span class="list">Upload template file</span>

        In this step you can create your multiple delivery orders by upload this file.

You can discover this feature from [here](api-reference#delivery-order-upload)

And you can discover more full features that ShipBlu introduce it to merchant from [API Reference](api-reference) page.
    

## API Reference

Refer to our [Tutorial](tutorial) or the [API Reference](api-reference)
for detailed API functionality.
