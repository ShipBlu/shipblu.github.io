---
layout: default
title: Quick Start
nav_order: 2
description: "Getting Started with ShipBlu Developer API"
permalink: /quick-start
---

# Quick Start
{: .fs-9 }

In this part, we will learn how to:

1. Get your API key
2. Test your setup


## Getting Your API Key
<br />

In order to use ShipBlu APIs, you need to generate an API key from your merchant account.
Follow the below steps to generate your API key.
 
1. <span style="color: #7453ee">Login to the merchant account</span>

    Go to [https://shipblu.com](https://shipblu.com) and click Sign In from the top-right corner.
    After that, click to loging and enter your merchant user credentials.

    <div style="text-align:center"><img src="/assets/img/01_quick_start_login_form.png" /></div>


2. <span style="color: #7453ee">Go to Account Settings</span>
    
    After successfully logging in, click on the profile avatar and select Account Settings.<br />

    <div style="text-align:center"><img src="/assets/img/02_quick_start_avatar.png" /></div>

3. <span style="color: #7453ee">Generate an API key</span>

    Click (+) from the top right corner to generate an API key
    <div style="text-align:center"><img src="/assets/img/03_quick_start_api_keys.png" /></div>

    This will generate a new API key that you can use to interact with the API.
    <div style="text-align:center"><img src="/assets/img/04_quick_start_api_key.png" /></div>


## Test Your Setup

Let's start by testing your setup using `curl`.
Open the terminal and execute the following command to get your merchant account info:

```
$ curl -H 'Authorization: Api-Key <YOUR-API-KEY>' -X GET https://api.shipblu.com/api/v1/merchants/
```

Response
```
{
    "count": 1,
    "next": null,
    "previous": null,
    "results": [
        {
            "id": Number,
            "name": String,
            "store_url": String,
            "logo": String,
            "store_phone": String,
            "address": Object,
            "store_email": String,
            "status": String,
            "cash_processing_fees": Number,
            "cash_processing_fees_max": Number,
            "cash_processing_percentage": Number,
            "cash_processing_threshold": Number,
            "subscription": Object,
            "pickup_days": List,
            "billing_days": List,
            "pricing_lookup_delivery": Object,
            "pricing_lookup_return": Object,
            "pricing_lookup_exchange": Object,
            "pricing_lookup_cash_collection": Object
        }
    ]
}
```

**Congratulations!** Your are all set for integrating your app with our API!


## API Reference

Refer to our [Tutorial](tutorial) or the [API Reference](api-reference)
for detailed API functionality.
