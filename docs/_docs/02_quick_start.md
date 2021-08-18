---
layout: default
title: Quick Start
nav_order: 2
description: "Getting Started with ShipBlu Developer API"
permalink: /quick-start
---

# Quick Start
{: .fs-9 }

IN this part you will know only two things to deal with ShipBlu API's<br />

1. Getting Your API Key
2. Test Your Setup

Don't waste a lot of time and let's go.

## Getting Your API Key
<br />
In this part we will show to you how get your API key.
 
1. <span style="color: #7453ee">Login page</span>

    This is login page that you will see it when visit ShipBlu site.

    <div style="text-align:center"><img src="/assets/img/login_page.png" /></div>

2. <span style="color: #7453ee">Login form</span>

    This is a login form page that will appear for you when click on login button
    <div style="text-align:center"><img src="/assets/img/login_form.png" /></div>

3. <span style="color: #7453ee">Deal with merchant portal</span>
    
    After successfully login you will see merchant portal that you can use it for many awsome thing.<br />

    This is a navigation bar of merchant portal.
    <div style="text-align:center"><img src="/assets/img/merchant_portal_nav.png" /></div>

4. <span style="color: #7453ee">Get your API key</span>

    <span style="color: #000">Step 1:</span> click on your picture as viewed in below picture.
    <div style="text-align:center"><img src="/assets/img/api_key_step_1.png" /></div>

    <span style="color: #000">Step 2:</span> choose Account Settings from drop down menu. After click on account settings you will see this page. then choose API Keys at bottom left.
    <div style="text-align:center"><img src="/assets/img/api_key_step_2.png" /></div>

    <span style="color: #000">Step 3:</span> click on (+) button at the right then choose New API Key from drop down menu.
    <div style="text-align:center"><img src="/assets/img/api_key_step_3.png" /></div>

    <span style="color: #000">Step 4:</span> congratulations you get your API key
    <div style="text-align:center"><img src="/assets/img/api_key_step_4.png" /></div>

## Test Your Setup

Hello World

Let's start by testing our setup. Open up a command prompt and enter the following command that retrieve specific merchant info based on merchant id:

<div style='background: #f6f8fa; padding: 11px; box-sizing: border-box; overflow: scroll; color: #24292e;'>
curl -X GET https://api.staging.shipblu.com/api/v1/merchants/1/ \ <br />
-H 'authorization: Api-Key YOUR_API_KEY'

<pre>
{
    "id":1,
    "name":"Souq",
    "store_url":"https://souq.com",
    "logo":"https://staging-publicstorage1123538a-1p8k71zpb6h3c.s3.eu-west-3.amazonaws.com/auth0.5f633d876f356400703ba94a.unnamed.png",
    "store_phone":"01012345678",
    "address":{
        "id":137,
        "line_1":"10 شارع قصر النيل",
        "line_2":"متفرع من الميدان الكبير",
        "line_3":null,
        "zip_code":null,
        "google_maps_link":null,
        "zone":{
            "id":17,
            "name":"الياسمين 4  - El-Yasmeen 4",
            "city":{
                "id":1,
                "name":"القاهرة الجديدة - New Cairo",
                "governorate":{
                    "id":1,
                    "name":"القاهرة - Cairo"
                }
            },"zone_group":[9]
        }
    },
    "store_email":"info@souq.com",
    "status":"active",
    "api_key":"API_KEY",
    "cash_processing_fees":5.0,
    "cash_processing_fees_max":50.0,
    "cash_processing_percentage":2.0,
    "cash_processing_threshold":5.0,
    "subscription":{
        "id":2,"name":
        "Super Saver"
    },
    "pickup_days":[1,3],
    "billing_days":[6],
    "pricing_lookup_delivery":{
        "id":19,
        "status":"ready",
        "service_type":"delivery",
        "package":{
            "google_sheet_url":"https://docs.google.com/spreadsheets/d/1gCpdQAIYAm1o_mFU2bsPw-FvM8X5IgRYfydo1e1laSg"
        }
    },
    "pricing_lookup_return":{
        "id":20,
        "status":"ready",
        "service_type":"return",
        "package":{
            "google_sheet_url":"https://docs.google.com/spreadsheets/d/1gCpdQAIYAm1o_mFU2bsPw-FvM8X5IgRYfydo1e1laSg"
        }
    },"pricing_lookup_exchange":{
        "id":21,
        "status":"ready",
        "service_type":"exchange",
        "package":{
            "google_sheet_url":"https://docs.google.com/spreadsheets/d/1gCpdQAIYAm1o_mFU2bsPw-FvM8X5IgRYfydo1e1laSg"
        }
    },
    "pricing_lookup_cash_collection":{
        "id":22,
        "status":"ready",
        "service_type":"cash_collection",
        "package":{
            "google_sheet_url":"https://docs.google.com/spreadsheets/d/1gCpdQAIYAm1o_mFU2bsPw-FvM8X5IgRYfydo1e1laSg"
        }
    }
}
</pre>

</div>

## API Reference

Refer to our [Tutorial](tutorial) or the [API Reference](api-reference)
for detailed API functionality.
