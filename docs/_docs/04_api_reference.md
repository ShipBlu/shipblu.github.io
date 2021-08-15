---
layout: default
title: API Reference
nav_order: 4
description: "Full API Reference"
permalink: /api-reference
---
<head>
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.0/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-KyZXEAg3QhqLMpG8r+8fhAXLRk2vvoC2f3B09zVXn8CA5QIVfZOJ3BCsw2P0p/We" crossorigin="anonymous">

<style>
.request{
    padding:5px 10px; 
    margin-right: 15px;
    color:#FFF; 
}
.get{
    background:#60affe; 
}
.get-desc{
    background:#ebf3fb;
    border:1px solid #60affe;
}
.post{
    background:#49cc90; 
}
.post-desc{
    background:#e8f6f0;
    border:1px solid #49cc90;
}
.put{ 
    background:#fca130; 
}
.put-desc{
    background:#fbf1e6;
    border:1px solid #fca130;
}
.patch{ 
    background:#50e3c2; 
}
.patch-desc{
    background:#e9f8f5;
    border:1px solid #50e3c2;
}
.delete{
    background:#f93e3e; 
}
.delete-desc{
    background:#fbe7e7;
    border:1px solid #f93e3e; 
}
.desc{
    color:#000;
    padding:7px;
    font-weight:bold;
    margin-bottom: 7px;
    margin-top: 10px;
}
.black{
    background:#4c4848
}
.accordion-body{
    font-size: 17px;
    font-weight: normal;

}
</style>
</head>

# API Reference
{: .fs-9 }

TO BE DOCUMENTED 


## Geographic Availability

- [pudos](#) <br />

  We can define pudos as meeting points between customer and CA.<br />

  Now after know what is pudos, let's play with his API end-points.<br />

    1. <div class='desc get-desc'><span class='request get'>GET</span>/v1/pudos/
          <div>
           <p class='request black'>Request body exampel</p>
           <p class='request black'>Response header exampel</p>
           <p class='request black'>Response body exampel</p>
          </div>
        </div>
        This end-point allow you to list all pudos.

    2. <div class='desc post-desc'><span class='request post' >POST</span>/v1/pudos/
          <div>
           <p class='request black'>Request body exampel</p>
           <p class='request black'>Response header exampel</p>
           <p class='request black'>Response body exampel</p>
          </div>
        </div>
        This end-point allow you to create new pudo point.  

    3. <div class='desc get-desc'><span class='request get'>GET</span>/v1/pudos/{id}/
          <div>
           <p class='request black'>Request body exampel</p>
           <p class='request black'>Response header exampel</p>
           <p class='request black'>Response body exampel</p>
          </div>
       </div>
        This end-point allow you retrieve specific pudo based on his id.  

    4. <div class='desc put-desc'><span class='request put' >PUT</span>/v1/pudos/{id}/
          <div>
           <p class='request black'>Request body exampel</p>
           <p class='request black'>Response header exampel</p>
           <p class='request black'>Response body exampel</p>
          </div>
       </div>
        This end-point allow you update specific pudo based on his id.

    5. <div class='desc patch-desc'><span class='request patch'>PATCH</span>/v1/pudos/{id}/
         <div>
           <p class='request black'>Request body exampel</p>
           <p class='request black'>Response header exampel</p>
           <p class='request black'>Response body exampel</p>
          </div>
       </div>
        This end-point allow you partial update specific pudo based on his id.  

    6. <div class='desc delete-desc'><span class='request delete' >DELETE</span>/v1/pudos/{id}/
          <div>
           <p class='request black'>Request body exampel</p>
           <p class='request black'>Response header exampel</p>
           <p class='request black'>Response body exampel</p>
          </div>
       </div>
        This end-point allow you delete specific pudo based on his id.  

    7. <div class='desc get-desc'><span class='request get' >GET</span>/v1/pudo/cities/{city_id}/
          <div>
           <p class='request black'>Request body exampel</p>
           <p class='request black'>Response header exampel</p>
           <p class='request black'>Response body exampel</p>
          </div>
       </div>
        This end-point allow you retrieve pudos in specific city based on city id.     

- [governorates](#) <br />

    1. <div class='desc get-desc'><span class='request get'>GET</span>/v1/governorates/
          <div>
           <p class='request black'>Request body exampel</p>
           <p class='request black'>Response header exampel</p>
           <p class='request black'>Response body exampel</p>
          </div> 
       </div>
        This end-point allow you to list all governorates.

    2. <div class='desc post-desc'><span class='request post' >POST</span>/v1/governorates/
          <div>
           <p class='request black'>Request body exampel</p>
           <p class='request black'>Response header exampel</p>
           <p class='request black'>Response body exampel</p>
          </div>
       </div>
        This end-point allow you to create new governorate.

    3. <div class='desc get-desc'><span class='request get'>GET</span>/v1/governorates/{id}/
          <div>
           <p class='request black'>Request body exampel</p>
           <p class='request black'>Response header exampel</p>
           <p class='request black'>Response body exampel</p>
          </div> 
       </div>
        This end-point allow you to retrieve specific governorate based on his id.

    4. <div class='desc put-desc'><span class='request put'>PUT</span>/v1/governorates/{id}/
          <div>
           <p class='request black'>Request body exampel</p>
           <p class='request black'>Response header exampel</p>
           <p class='request black'>Response body exampel</p>
          </div> 
       </div>
        This end-point allow you to update specific governorate based on his id.

    5. <div class='desc patch-desc'><span class='request patch'>PATCH</span>/v1/governorates/{id}/
          <div>
           <p class='request black'>Request body exampel</p>
           <p class='request black'>Response header exampel</p>
           <p class='request black'>Response body exampel</p>
          </div> 
       </div>
        This end-point allow you to partial update specific governorate based on his id.

    5. <div class='desc delete-desc'><span class='request delete'>DELETE</span>/v1/governorates/{id}/
          <div>
           <p class='request black'>Request body exampel</p>
           <p class='request black'>Response header exampel</p>
           <p class='request black'>Response body exampel</p>
          </div> 
       </div>
        This end-point allow you to delete specific governorate based on his id.                

    6. <div class='desc get-desc'><span class='request get'>GET</span>/v1/governorates/{governorate_id}/cities/
          <div>
           <p class='request black'>Request body exampel</p>
           <p class='request black'>Response header exampel</p>
           <p class='request black'>Response body exampel</p>
          </div>
       </div>
        This end-point allow you retrieve all cities in specific governorate based on governorates id.
- [warehouses](#) <br />

    A large building where shipments may be stored before their export or distribution for sale.

    1. <div class='desc get-desc'><span class='request get'>GET</span>/v1/warehouses/
          <div>
           <p class='request black'>Request body exampel</p>
           <p class='request black'>Response header exampel</p>
           <p class='request black'>Response body exampel</p>
          </div>
       </div>
        This end-point allow you to list all warehouses.

    2. <div class='desc get-desc'><span class='request get'>GET</span>/v1/warehouses/{warehouse_code}/zone-groups/
          <div>
           <p class='request black'>Request body exampel</p>
           <p class='request black'>Response header exampel</p>
           <p class='request black'>Response body exampel</p>
          </div>
       </div>
        This end-point allow you to retrieve all zone-groups served by specific warehouse based on warehouse code.

    3. <div class='desc post-desc'><span class='request post'>POST</span>/v1/warehouses/{warehouse_code}/zone-groups/
          <div>
           <p class='request black'>Request body exampel</p>
           <p class='request black'>Response header exampel</p>
           <p class='request black'>Response body exampel</p>
          </div>
       </div>
        This end-point allow you to create new zone-groups served by specific warehouse.

    4. <div class='desc get-desc'><span class='request get'>GET</span>/v1/warehouses/{warehouse_code}/zones/
          <div>
           <p class='request black'>Request body exampel</p>
           <p class='request black'>Response header exampel</p>
           <p class='request black'>Response body exampel</p>
          </div>
       </div>
        This end-point allow you to retrieve all zones served by specific warehouse based on warehouse code.

    5. <div class='desc get-desc'><span class='request get'>GET</span>/v1/warehouse/{warehouse_code}/agents/{agent_type}/
          <div>
           <p class='request black'>Request body exampel</p>
           <div>
           In this end-point no request body needed but two parameters are required
           <br />
           <code>agent_type, warehouse_code</code>
           </div>

           <p class='request black'>Response header exampel</p>
           <pre>
            allow: GET,HEAD,OPTIONS 
            content-length: 58 
            content-type: application/json 
            date: Sun,15 Aug 2021 08:36:49 GMT 
            referrer-policy: same-origin 
            server: WSGIServer/0.2 CPython/3.9.6 
            vary: Accept,Origin,Cookie 
            www-authenticate: Bearer realm="api" 
            x-content-type-options: nosniff 
            x-frame-options: DENY 
            x-queryinspect-duplicate-sql-queries: 0 
            x-queryinspect-num-sql-queries: 0 
            x-queryinspect-total-request-time: 7 ms 
            x-queryinspect-total-sql-time: 0 ms 
            x-xss-protection: 1; mode=bloc
           </pre>
           <p class='request black'>Response body exampel</p>
           <pre>
           {
                "count": integer,
                "next": string,
                "previous": string,
                "results": [
                    {
                        "id": integer,
                        "created": string,
                        "modified": string,
                        "uid": string,
                        "email": string,
                        "first_name": string,
                        "last_name": string,
                        "phone_number": string,
                        "national_id": string,
                        "primary_warehouse": integer,
                        "zone_group": integer,
                        "act_cash_account": string
                    }
                ]
            }
           </pre>
          </div>
       </div>
        This end-point allow you to retrieve all agents based on warehouse code and agent type.

    6. <div class='desc get-desc'><span class='request get'>GET</span>/v1/warehouse/{warehouse_code}/task-sheets/
          <div>
           <p class='request black'>Request body exampel</p>
           <p class='request black'>Response header exampel</p>
           <p class='request black'>Response body exampel</p>
          </div>
       </div>
        This end-point allow you to retrieve all task sheets based on warehouse code. 

- [zones](#) <br />

    We can define zones as specific areas in city.<br />

    Now after know what is zones, let's play with his API end-points.<br />

    1. <div class='desc get-desc'><span class='request get'>GET</span>/v1/cities/{city_id}/zones/
          <div>
           <p class='request black'>Request body exampel</p>
           <div>
           In this end-point no request body needed but only one parameter is required
           <br />
           <code>city_id</code>
           </div>
           <p class='request black'>Response header exampel</p>
           <pre>
            allow: GET,HEAD,OPTIONS 
            content-length: 58 
            content-type: application/json 
            date: Sun,15 Aug 2021 09:18:53 GMT 
            referrer-policy: same-origin 
            server: WSGIServer/0.2 CPython/3.9.6 
            vary: Accept,Origin,Cookie 
            www-authenticate: Bearer realm="api" 
            x-content-type-options: nosniff 
            x-frame-options: DENY 
            x-queryinspect-duplicate-sql-queries: 0 
            x-queryinspect-num-sql-queries: 0 
            x-queryinspect-total-request-time: 7 ms 
            x-queryinspect-total-sql-time: 0 ms 
            x-xss-protection: 1; mode=block
           </pre>
           <p class='request black'>Response body exampel</p>
           <pre>
           [
                {
                    "id": integer,
                    "name": string,
                    "radius": float,
                    "city": integer,
                    "served_by": integer,
                    "zone_group": list
                },
                ....
           ]
           </pre>
          </div>
       </div>
        This end-point allow you retrieve zones in specific city based on city id.
 
- [zone groups](#) <br />

    1. <div class='desc get-desc'><span class='request get'>GET</span>/v1/zone-groups/{id}/
          <div>
           <p class='request black'>Request body exampel</p>
           <p class='request black'>Response header exampel</p>
           <p class='request black'>Response body exampel</p>
          </div> 
       </div>
        This end-point allow you retrieve specific zone group based on his id.  

    2. <div class='desc put-desc'><span class='request put' >PUT</span>/v1/zone-groups/{id}/
          <div>
           <p class='request black'>Request body exampel</p>
           <p class='request black'>Response header exampel</p>
           <p class='request black'>Response body exampel</p>
          </div>
       </div>
        This end-point allow you update specific zone group based on his id.

    3. <div class='desc patch-desc'><span class='request patch'>PATCH</span>/v1/zone-groups/{id}/
          <div>
           <p class='request black'>Request body exampel</p>
           <p class='request black'>Response header exampel</p>
           <p class='request black'>Response body exampel</p>
          </div>
       </div>
        This end-point allow you partial update specific zone group based on his id.  

    4. <div class='desc delete-desc'><span class='request delete' >DELETE</span>/v1/zone-groups/{id}/
          <div>
           <p class='request black'>Request body exampel</p>
           <p class='request black'>Response header exampel</p>
           <p class='request black'>Response body exampel</p>
          </div>
       </div>
        This end-point allow you delete specific zone group based on his id.

- [cities](#) <br />

    1. <div class='desc get-desc'><span class='request get'>GET</span>/v1/cities/{id}/
          <div>
           <p class='request black'>Request body exampel</p>
           <p class='request black'>Response header exampel</p>
           <p class='request black'>Response body exampel</p>
          </div>
       </div>
        This end-point allow you retrieve specific city based on his id.  

    2. <div class='desc post-desc'><span class='request post'>POST</span>/v1/cities/{id}/
          <div>
           <p class='request black'>Request body exampel</p>
           <p class='request black'>Response header exampel</p>
           <p class='request black'>Response body exampel</p>
          </div> 
       </div>
        check...     

    3. <div class='desc put-desc'><span class='request put' >PUT</span>/v1/cities/{id}/
          <div>
           <p class='request black'>Request body exampel</p>
           <p class='request black'>Response header exampel</p>
           <p class='request black'>Response body exampel</p>
          </div>
       </div>
        This end-point allow you update specific city based on his id.

    4. <div class='desc patch-desc'><span class='request patch'>PATCH</span>/v1/cities/{id}/
          <div>
           <p class='request black'>Request body exampel</p>
           <p class='request black'>Response header exampel</p>
           <p class='request black'>Response body exampel</p>
          </div>
       </div>
        This end-point allow you partial update specific city based on his id.  

    5. <div class='desc delete-desc'><span class='request delete' >DELETE</span>/v1/cities/{id}/
          <div>
           <p class='request black'>Request body exampel</p>
           <p class='request black'>Response header exampel</p>
           <p class='request black'>Response body exampel</p>
          </div>  
       </div>
        This end-point allow you delete specific city based on his id.

## Service Availability

- [service availability](#) <br />

  To be document

   1. <div class='desc get-desc'><span class='request get'>GET</span>/v1/services-availability/
          <div>
           <p class='request black'>Request body exampel</p>
           <p class='request black'>Response header exampel</p>
           <p class='request black'>Response body exampel</p>
          </div>
        </div>
        checks...

    2. <div class='desc post-desc'><span class='request post' >POST</span>/v1/services-availability/
          <div>
           <p class='request black'>Request body exampel</p>
           <p class='request black'>Response header exampel</p>
           <p class='request black'>Response body exampel</p>
          </div>
        </div>
        checks... 

    3. <div class='desc get-desc'><span class='request get'>GET</span>/v1/services-availability/{id}/
          <div>
           <p class='request black'>Request body exampel</p>
           <p class='request black'>Response header exampel</p>
           <p class='request black'>Response body exampel</p>
          </div>
       </div>
        checks... 

    4. <div class='desc put-desc'><span class='request put' >PUT</span>/v1/services-availability/{id}/
          <div>
           <p class='request black'>Request body exampel</p>
           <p class='request black'>Response header exampel</p>
           <p class='request black'>Response body exampel</p>
          </div>
       </div>
        checks...

    5. <div class='desc patch-desc'><span class='request patch'>PATCH</span>/v1/services-availability/{id}/
         <div>
           <p class='request black'>Request body exampel</p>
           <p class='request black'>Response header exampel</p>
           <p class='request black'>Response body exampel</p>
          </div>
       </div>
        This end-point allow you partial update specific pudo based on his id.  

    6. <div class='desc delete-desc'><span class='request delete' >DELETE</span>/v1/services-availability/{id}/
          <div>
           <p class='request black'>Request body exampel</p>
           <p class='request black'>Response header exampel</p>
           <p class='request black'>Response body exampel</p>
          </div>
       </div>
        checks...    

## Pickup Points

- [pickup points](#) <br />

   Meeting points between merchant and merchant agent.

    1. <div class='desc get-desc'><span class='request get'>GET</span>/v1/merchants/{merchant_id}/pickup-points/
          <div>
           <p class='request black'>Request body exampel</p>
           <p class='request black'>Response header exampel</p>
           <p class='request black'>Response body exampel</p>
          </div>
       </div>
        This end-point allow you to list all pickup point of specific merchant based on merchant id.

    2. <div class='desc post-desc'><span class='request post' >POST</span>/v1/merchants/{merchant_id}/pickup-points/
          <div>
           <p class='request black'>Request body exampel</p>
           <p class='request black'>Response header exampel</p>
           <p class='request black'>Response body exampel</p>
          </div>
       </div>
        This end-point allow you to create new pickup point to specific merchant based on merchant id.  

    3. <div class='desc get-desc'><span class='request get'>GET</span>/v1/merchants/{merchant_id}/pickup-points/{id}/
          <div>
           <p class='request black'>Request body exampel</p>
           <p class='request black'>Response header exampel</p>
           <p class='request black'>Response body exampel</p>
          </div>
       </div>
        This end-point allow you retrieve specific pickup point based on merchant id and his id.  

    4. <div class='desc put-desc'><span class='request put' >PUT</span>/v1/merchants/{merchant_id}/pickup-points/{id}/
          <div>
           <p class='request black'>Request body exampel</p>
           <p class='request black'>Response header exampel</p>
           <p class='request black'>Response body exampel</p>
          </div>
       </div>
        This end-point allow you update specific pickup point based on merchant id and his id.

    5. <div class='desc patch-desc'><span class='request patch'>PATCH</span>/v1/merchants/{merchant_id}/pickup-points/{id}/
          <div>
           <p class='request black'>Request body exampel</p>
           <p class='request black'>Response header exampel</p>
           <p class='request black'>Response body exampel</p>
          </div>
       </div>
        This end-point allow you partial update pickup point based on merchant id and his id.  

    6. <div class='desc delete-desc'><span class='request delete' >DELETE</span>/v1/merchants/{merchant_id}/pickup-points/{id}/
          <div>
           <p class='request black'>Request body exampel</p>
           <p class='request black'>Response header exampel</p>
           <p class='request black'>Response body exampel</p>
          </div>
       </div>
        This end-point allow you delete specific pickup point based on merchant id and his id.

## Orders

Orders divided on three categoricals
- Delivery
- Return
- Exchanges

### Delivery
- [delivery order](#) <br />
    1. <div id='accordionExample_1' class='desc get-desc accordion'><span class='request get'>GET</span>/v1/delivery-orders/
          <div style='margin-top: 15px;'>

           <h2 class="accordion-header" id="deliveryHeadingOne">
           <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#deliveryCollapseOne" aria-expanded="true" aria-controls="collapseOne">
                Request body exampel
           </button>
           </h2>
           <div id="deliveryCollapseOne" class="accordion-collapse collapse" aria-labelledby="deliveryHeadingOne" data-bs-parent="#accordionExample">
           <div class="accordion-body">
           In this end-point no request body needed.
           </div>
           </div>

           <h2 class="accordion-header" id="deliveryHeadingTwo">
           <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#deliveryCollapseTwo" aria-expanded="true" aria-controls="collapseOne">
                Response header exampel
           </button>
           </h2>
           <div id="deliveryCollapseTwo" class="accordion-collapse collapse" aria-labelledby="deliveryHeadingTwo" data-bs-parent="#accordionExample">
           <div class="accordion-body">
           <pre>
            allow: GET,POST,HEAD,OPTIONS 
            content-length: 58 
            content-type: application/json 
            date: Sun,15 Aug 2021 09:53:24 GMT 
            referrer-policy: same-origin 
            server: WSGIServer/0.2 CPython/3.9.6 
            vary: Accept,Origin,Cookie 
            www-authenticate: Bearer realm="api" 
            x-content-type-options: nosniff 
            x-frame-options: DENY 
            x-queryinspect-duplicate-sql-queries: 0 
            x-queryinspect-num-sql-queries: 0 
            x-queryinspect-total-request-time: 10 ms 
            x-queryinspect-total-sql-time: 0 ms 
            x-xss-protection: 1; mode=block
           </pre>
           </div>
           </div>

           <h2 class="accordion-header" id="deliveryHeadingThree">
           <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#deliveryCollapseThree" aria-expanded="true" aria-controls="collapseOne">
                Response body exampel
           </button>
           </h2>
           <div id="deliveryCollapseThree" class="accordion-collapse collapse" aria-labelledby="deliveryHeadingThree" data-bs-parent="#accordionExample">
           <div class="accordion-body">
           <pre>
            {
                    "count": integer,
                    "next": string,
                    "previous": string,
                    "results": [
                        {
                            "id": integer,
                            "packages": [
                                {
                                    "id": integer,
                                    "supplies_required": boolean,
                                    "sms_confirmation_code": string,
                                    "package": {
                                        "id": integer,
                                        "created": string,
                                        "modified": string,
                                        "description": string,
                                        "weight": number,
                                        "volume": number,
                                        "fragile": boolean,
                                        "package_size": {
                                            "id": integer,
                                            "name": string,
                                            "short_code": string,
                                            "description": string
                                        }
                                    },
                                    "package_location": string
                                }
                            ],
                            "delivery_attempts": string,
                            "pickup_date": string,
                            "cash_deposited": boolean
                            "delivered_date": string,
                            "created": string,
                            "modified": string,
                            "tracking_number": string,
                            "merchant_order_reference": string,
                            "order_notes": string,
                            "is_exchange": boolean,
                            "is_pudo": boolean,
                            "is_counter_dropoff": boolean,
                            "cash_processing": boolean,
                            "cash_amount": number,
                            "preferred_date": string,
                            "estimated_date": string,
                            "status": string,
                            "intermediate_warehouses": [string],
                            "dispatch_early": string,
                            "dispatch_late": string,
                            "merchant": {
                                "id": integer,
                                "created": string,
                                "modified": string,
                                "name": string,
                                "store_url": string,
                                "logo": string,
                                "store_phone": string,
                                "store_email": string,
                                "status": string",
                                "api_key": string,
                                "cash_processing_fees": number,
                                "cash_processing_fees_max": number,
                                "cash_processing_percentage": number,
                                "cash_processing_threshold": number,
                                "address": {
                                    "id": integer,
                                    "created": string,
                                    "modified": string,
                                    "nickname": string,
                                    "line_1": string,
                                    "line_2": string,
                                    "line_3": string,
                                    "zip_code": string,
                                    "latitude": number,
                                    "longitude": number,
                                    "google_maps_link": number,
                                    "notes": number,
                                    "zone": {
                                        "id": integer,
                                        "name": string,
                                        "radius": number,
                                        "city": {
                                            "id": integer,
                                            "name": string,
                                            "population": integer,
                                            "is_captial": boolean,
                                            "governorate": {
                                                "id": integer,
                                                "name": string
                                            }
                                        },
                                        "served_by": {
                                            "id": integer,
                                            "name": string,
                                            "code": string,
                                            "capacity": number,
                                            "current_utilization": number,
                                            "size": number,
                                            "latitude": number,
                                            "longitude": number,
                                            "address": string,
                                            "is_virtual": boolean
                                        },
                                        "zone_group": [{
                                            "id": integer,
                                            "created": string,
                                            "modified": string,
                                            "name": string,
                                            "served_by": {
                                                "id": integer,
                                                "name": string,
                                                "code": string,
                                                "capacity": number,
                                                "current_utilization": number,
                                                "size": number,
                                                "latitude": number,
                                                "longitude": number,
                                                "address": string,
                                                "is_virtual": boolean
                                            },
                                        }]
                                    }
                                },
                                "subscription": {
                                    "id": integer,
                                    "name": string
                                },
                                "pricing_lookup_delivery": {
                                    "id": integer,
                                    "created": string,
                                    "modified": string,
                                    "status": string,
                                    "service_type": string,
                                    "package": {
                                        "id": integer,
                                        "created": string,
                                        "modified": string,
                                        "status": string,
                                        "name": string,
                                        "google_sheet_url": string
                                    }
                                },
                                "pricing_lookup_return": {
                                    "id": integer,
                                    "created": string,
                                    "modified": string,
                                    "status": string,
                                    "service_type": string,
                                    "package": {
                                        "id": integer,
                                        "created": string,
                                        "modified": string,
                                        "status": string,
                                        "name": string,
                                        "google_sheet_url": string
                                    }
                                },
                                "pricing_lookup_exchange": {
                                    "id": integer,
                                    "created": string,
                                    "modified": string,
                                    "status": string,
                                    "service_type": string,
                                    "package": {
                                        "id": integer,
                                        "created": string,
                                        "modified": string,
                                        "status": string,
                                        "name": string,
                                        "google_sheet_url": string
                                    }
                                },
                                "pricing_lookup_cash_collection": {
                                    "id": integer,
                                    "created": string,
                                    "modified": string,
                                    "status": string,
                                    "service_type": string,
                                    "package": {
                                        "id": integer,
                                        "created": string,
                                        "modified": string,
                                        "status": string,
                                        "name": string,
                                        "google_sheet_url": string
                                    }
                                },
                                "act_cod_account": {
                                    "account_number": string,
                                    "created": string,
                                    "modified": string,
                                    "name": string,
                                    "parent_account": {
                                        "account_number": string",
                                        "created": string,
                                        "modified": string,
                                        "name": string,
                                        "parent_account": object,
                                        "type": {
                                            "id": integer,
                                            "name": string
                                        }
                                    },
                                    "type": {
                                        "id": integer,
                                        "name": string
                                    }
                                },
                                "act_shipping_revenue_account": {
                                    "account_number": string,
                                    "created": string,
                                    "modified": string,
                                    "name": string,
                                    "parent_account": {
                                        "account_number": string",
                                        "created": string,
                                        "modified": string,
                                        "name": string,
                                        "parent_account": object,
                                        "type": {
                                            "id": integer,
                                            "name": string
                                        }
                                    },
                                    "type": {
                                        "id": integer,
                                        "name": string
                                    }
                                },
                                "act_discounts_account": {
                                    "account_number": string,
                                    "created": string,
                                    "modified": string,
                                    "name": string,
                                    "parent_account": {
                                        "account_number": string",
                                        "created": string,
                                        "modified": string,
                                        "name": string,
                                        "parent_account": object,
                                        "type": {
                                            "id": integer,
                                            "name": string
                                        }
                                    },
                                    "type": {
                                        "id": integer,
                                        "name": string
                                    }
                                },
                                "act_account_receivable": {
                                    "account_number": string,
                                    "created": string,
                                    "modified": string,
                                    "name": string,
                                    "parent_account": {
                                        "account_number": string",
                                        "created": string,
                                        "modified": string,
                                        "name": string,
                                        "parent_account": object,
                                        "type": {
                                            "id": integer,
                                            "name": string
                                        }
                                    },
                                    "type": {
                                        "id": integer,
                                        "name": string
                                    }
                                },
                                "act_supplies_revenue_account": {
                                    "account_number": string,
                                    "created": string,
                                    "modified": string,
                                    "name": string,
                                    "parent_account": {
                                        "account_number": string",
                                        "created": string,
                                        "modified": string,
                                        "name": string,
                                        "parent_account": object,
                                        "type": {
                                            "id": integer,
                                            "name": string
                                        }
                                    },
                                    "type": {
                                        "id": integer,
                                        "name": string
                                    }
                                },
                                "pickup_days": [{
                                    "id": integer,
                                    "day": string
                                }],
                                "billing_days": [{
                                    "id": integer,
                                    "day": string
                                }]
                            },
                            "customer": {
                                "id": integer,
                                "created": string,
                                "modified": string,
                                "first_name": string,
                                "last_name": string,
                                "email": string,
                                "phone": string,
                                "address": {
                                    "id": integer,
                                    "created": string,
                                    "modified": string,
                                    "nickname": string,
                                    "line_1": string,
                                    "line_2": string,
                                    "line_3": string,
                                    "zip_code": string,
                                    "latitude": number,
                                    "longitude": number,
                                    "google_maps_link": string,
                                    "notes": string,
                                    "zone": {
                                        "id": integer,
                                        "name": string,
                                        "radius": number,
                                        "city": {
                                            "id": integer,
                                            "name": string,
                                            "population": integer,
                                            "is_captial": boolean,
                                            "governorate": {
                                                "id": integer,
                                                "name": string
                                            }
                                        },
                                        "served_by": {
                                            "id": integer,
                                            "name": string,
                                            "code": string,
                                            "capacity": number,
                                            "current_utilization": number,
                                            "size": number,
                                            "latitude": number,
                                            "longitude": number,
                                            "address": string,
                                            "is_virtual": boolean
                                        },
                                        "zone_group": [{
                                            "id": integer,
                                            "created": string,
                                            "modified": string,
                                            "name": string,
                                            "served_by": {
                                                "id": integer,
                                                "name": string,
                                                "code": string,
                                                "capacity": number,
                                                "current_utilization": number,
                                                "size": number,
                                                "latitude": number,
                                                "longitude": number,
                                                "address": string,
                                                "is_virtual": boolean
                                            },
                                        }]
                                    }
                                },
                                "act_cash_account": {
                                    "account_number": string,
                                    "created": string,
                                    "modified": string,
                                    "name": string,
                                    "parent_account": {
                                        "account_number": string",
                                        "created": string,
                                        "modified": string,
                                        "name": string,
                                        "parent_account": object,
                                        "type": {
                                            "id": integer,
                                            "name": string
                                        }
                                    },
                                    "type": {
                                        "id": integer,
                                        "name": string
                                    }
                                }
                            },
                            "service_level": {
                                "id": integer,
                                "name": string,
                                "short_code": string,
                                "description": string
                            },
                            "pickup_point": {
                                "id": integer,
                                "created": string,
                                "modified": string,
                                "is_default": boolean,
                                "merchant": object,
                                "address":object
                            },
                            "order_price": {
                                "id": integer,
                                "created": string,
                                "modified": string,
                                "subtotal": number,
                                "vat": number,
                                "postal_tax": number,
                                "total": number
                            },
                            "current_warehouse": {
                                "id": integer,
                                "name": string,
                                "code": string",
                                "capacity": number,
                                "current_utilization": number,
                                "size": number,
                                "latitude": number,
                                "longitude": number,
                                "address": string,
                                "is_virtual": boolean
                            },
                            "inbound_warehouse": {
                                "id": integer,
                                "name": string,
                                "code": string",
                                "capacity": number,
                                "current_utilization": number,
                                "size": number,
                                "latitude": number,
                                "longitude": number,
                                "address": string,
                                "is_virtual": boolean
                            },
                            "outbound_warehouse": {
                                "id": integer,
                                "name": string,
                                "code": string",
                                "capacity": number,
                                "current_utilization": number,
                                "size": number,
                                "latitude": number,
                                "longitude": number,
                                "address": string,
                                "is_virtual": boolean
                            },
                            "preferred_window": [{
                                "id": integer,
                                "display_name": string
                            }]
                        }
                    ]
                }
           </pre>
           </div>
           </div>
          </div>
       </div>
        This end-point allow you to list all delivery orders.

    2. <div id='accordionExample_2' class='desc post-desc accordion'><span class='request post' >POST</span>/v1/delivery-orders/
          <div style='margin-top: 15px;'>
           <h2 class="accordion-header" id="deliveryHeadingOne_2">
           <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#deliveryCollapseOne_2" aria-expanded="true" aria-controls="collapseOne">
                Request body exampel
           </button>
           </h2>
           <div id="deliveryCollapseOne_2" class="accordion-collapse collapse" aria-labelledby="deliveryHeadingOne_2" data-bs-parent="#accordionExample">
           <div class="accordion-body">
           <pre>
           {
                "customer": {
                    "first_name": string,
                    "last_name": string,
                    "phone": string,
                    "address":{
                        "line_1":string,
                        "line_2":string,
                        "zone": integer
                    }
                },
                "service_level": integer,
                "packages":[
                    {
                        "package_size": integer
                    }
                ]
            }
           </pre>
           </div>
           </div>

           <h2 class="accordion-header" id="deliveryHeadingTwo_2">
           <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#deliveryCollapseTwo_2" aria-expanded="true" aria-controls="collapseOne">
                Response header exampel
           </button>
           </h2>
           <div id="deliveryCollapseTwo_2" class="accordion-collapse collapse" aria-labelledby="deliveryHeadingTwo_2" data-bs-parent="#accordionExample">
           <div class="accordion-body">
           <pre>
            access-control-allow-origin: * 
            allow: GET,POST,HEAD,OPTIONS 
            content-length: 58 
            content-type: application/json 
            date: Sun,15 Aug 2021 12:56:02 GMT 
            referrer-policy: same-origin 
            server: WSGIServer/0.2 CPython/3.9.6 
            vary: Accept,Origin,Cookie 
            www-authenticate: Bearer realm="api" 
            x-content-type-options: nosniff 
            x-frame-options: DENY 
            x-queryinspect-duplicate-sql-queries: 0 
            x-queryinspect-num-sql-queries: 0 
            x-queryinspect-total-request-time: 9 ms 
            x-queryinspect-total-sql-time: 0 ms 
            x-xss-protection: 1; mode=block
           </pre>
           </div>
           </div>

           <h2 class="accordion-header" id="deliveryHeadingThree_2">
           <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#deliveryCollapseThree_2" aria-expanded="true" aria-controls="collapseOne">
                Response body exampel
           </button>
           </h2>
           <div id="deliveryCollapseThree_2" class="accordion-collapse collapse" aria-labelledby="deliveryHeadingThree_2" data-bs-parent="#accordionExample">
           <div class="accordion-body">
           <pre>
           {
                "id": integer,
                "customer": {
                    "id": integer,
                    "address": {
                        "id": integer,
                        "created": string,
                        "modified": string,
                        "nickname": string,
                        "line_1": string,
                        "line_2": string,
                        "line_3": null,
                        "zip_code": null,
                        "latitude": null,
                        "longitude": null,
                        "google_maps_link": null,
                        "notes": null,
                        "zone": integer
                    },
                    "created": string,
                    "modified": string,
                    "first_name": string,
                    "last_name": string,
                    "email": null,
                    "phone": string,
                    "act_cash_account": null
                },
                "created": string,
                "modified": string,
                "tracking_number": string,
                "merchant_order_reference": null,
                "order_notes": null,
                "is_exchange": boolean,
                "is_pudo": boolean,
                "is_counter_dropoff": boolean,
                "cash_processing": boolean,
                "cash_amount": null,
                "preferred_date": null,
                "estimated_date": null,
                "status": string,
                "intermediate_warehouses": [
                    string,
                    ...
                ],
                "dispatch_early": null,
                "dispatch_late": null,
                "merchant": integer,
                "service_level": integer,
                "pickup_point": null,
                "order_price": integer,
                "current_warehouse": null,
                "inbound_warehouse": integer,
                "outbound_warehouse": integer,
                "preferred_window": []
            }
           </pre>
           </div>
          </div>
       </div>
       This end-point allow you to create new delivery order.

    3. <div id='accordionExample_3' class='desc get-desc accordion'>
        <span class='request get'>GET</span>/v1/delivery-orders/{id}/
          <div style='margin-top: 15px;'>
           <h2 class="accordion-header" id="deliveryHeadingOne_3">
           <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#deliveryCollapseOne_3" aria-expanded="true" aria-controls="collapseOne">
                Request body exampel
           </button>
           </h2>
           <div id="deliveryCollapseOne_3" class="accordion-collapse collapse" aria-labelledby="deliveryHeadingOne_3" data-bs-parent="#accordionExample">
           <div class="accordion-body">
           In this end-point no request body needed, but one parameter is required: 
           <code>id</code>
           </div>
           </div>

           <h2 class="accordion-header" id="deliveryHeadingTwo_3">
           <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#deliveryCollapseTwo_3" aria-expanded="true" aria-controls="collapseOne">
                Response header exampel
           </button>
           </h2>
           <div id="deliveryCollapseTwo_3" class="accordion-collapse collapse" aria-labelledby="deliveryHeadingTwo_3" data-bs-parent="#accordionExample">
           <div class="accordion-body">
           <pre>
            allow: GET,PUT,PATCH,DELETE,HEAD,OPTIONS 
            content-length: 58 
            content-type: application/json 
            date: Sun,15 Aug 2021 13:11:17 GMT 
            referrer-policy: same-origin 
            server: WSGIServer/0.2 CPython/3.9.6 
            vary: Accept,Origin,Cookie 
            www-authenticate: Bearer realm="api" 
            x-content-type-options: nosniff 
            x-frame-options: DENY 
            x-queryinspect-duplicate-sql-queries: 0 
            x-queryinspect-num-sql-queries: 0 
            x-queryinspect-total-request-time: 8 ms 
            x-queryinspect-total-sql-time: 0 ms 
            x-xss-protection: 1; mode=block 
           </pre>
           </div>
           </div>

           <h2 class="accordion-header" id="deliveryHeadingThree_3">
           <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#deliveryCollapseThree_3" aria-expanded="true" aria-controls="collapseOne">
                Response body exampel
           </button>
           </h2>
           <div id="deliveryCollapseThree_3" class="accordion-collapse collapse" aria-labelledby="deliveryHeadingThree_3" data-bs-parent="#accordionExample">
           <div class="accordion-body">
           Request body as same as <code>GET: v1/delivery-orders/</code> BUT for specific delivery order id
           </div>
          </div>
       </div>
        This end-point allow you retrieve specific delivery based on his id.  

    4. <div id='accordionExample_4' class='desc put-desc accordion'><span class='request put' >PUT</span>/v1/delivery-orders/{id}/
          <div style='margin-top: 15px;'>
           <h2 class="accordion-header" id="deliveryHeadingOne_4">
           <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#deliveryCollapseOne_4" aria-expanded="true" aria-controls="collapseOne">
                Request body exampel
           </button>
           </h2>
           <div id="deliveryCollapseOne_4" class="accordion-collapse collapse" aria-labelledby="deliveryHeadingOne_4" data-bs-parent="#accordionExample">
           <div class="accordion-body">
           <pre>
           {
                "customer": {
                    "first_name": string,
                    "last_name": string,
                    "phone": string,
                    "address":{
                        "line_1":string,
                        "line_2":string,
                        "zone": integer
                    }
                },
                "service_level": integer,
                "packages":[
                    {
                        "package_size": integer
                    }
                ],
                "tracking_number":string",
                "merchant":integer
            }
           </pre>
           </div>
           </div>

           <h2 class="accordion-header" id="deliveryHeadingTwo_4">
           <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#deliveryCollapseTwo_4" aria-expanded="true" aria-controls="collapseOne">
                Response header exampel
           </button>
           </h2>
           <div id="deliveryCollapseTwo_4" class="accordion-collapse collapse" aria-labelledby="deliveryHeadingTwo_4" data-bs-parent="#accordionExample">
           <div class="accordion-body">
           <pre>
            access-control-allow-origin: * 
            allow: GET,PUT,PATCH,DELETE,HEAD,OPTIONS 
            content-length: 58 
            content-type: application/json 
            date: Sun,15 Aug 2021 13:29:33 GMT 
            referrer-policy: same-origin 
            server: WSGIServer/0.2 CPython/3.9.6 
            vary: Accept,Origin,Cookie 
            www-authenticate: Bearer realm="api" 
            x-content-type-options: nosniff 
            x-frame-options: DENY 
            x-queryinspect-duplicate-sql-queries: 0 
            x-queryinspect-num-sql-queries: 0 
            x-queryinspect-total-request-time: 7 ms 
            x-queryinspect-total-sql-time: 0 ms 
            x-xss-protection: 1; mode=bloc 
           </pre>
           </div>
           </div>

           <h2 class="accordion-header" id="deliveryHeadingThree_4">
           <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#deliveryCollapseThree_4" aria-expanded="true" aria-controls="collapseOne">
                Response body exampel
           </button>
           </h2>
           <div id="deliveryCollapseThree_4" class="accordion-collapse collapse" aria-labelledby="deliveryHeadingThree_4" data-bs-parent="#accordionExample">
           <div class="accordion-body">
           <pre>
           {
                "id": integer,
                "customer": {
                    "id": integer,
                    "address": {
                        "id": integer,
                        "created": string,
                        "modified": string,
                        "nickname": string,
                        "line_1": string,
                        "line_2": "string,
                        "line_3": null,
                        "zip_code": null,
                        "latitude": null,
                        "longitude": null,
                        "google_maps_link": null,
                        "notes": null,
                        "zone": integer
                    },
                    "created": string,
                    "modified": string,
                    "first_name": string,
                    "last_name": string,
                    "email": null,
                    "phone": string,
                    "act_cash_account": null
                },
                "created": "string,
                "modified": string,
                "tracking_number": string,
                "merchant_order_reference": null,
                "order_notes": null,
                "is_exchange": boolean,
                "is_pudo": boolean,
                "is_counter_dropoff": boolean,
                "cash_processing": boolean,
                "cash_amount": null,
                "preferred_date": null,
                "estimated_date": null,
                "status": string",
                "intermediate_warehouses": [
                    string,
                    ...
                ],
                "dispatch_early": null,
                "dispatch_late": null,
                "merchant": integer,
                "service_level": integer,
                "pickup_point": null,
                "order_price": integer,
                "current_warehouse": null,
                "inbound_warehouse": integer,
                "outbound_warehouse": integer,
                "preferred_window": []
            }
           </pre>
           </div>

          </div>
       </div>
        This end-point allow you update specific delivery based on his id.

    5. <div id='accordionExample_5' class='desc patch-desc accordion'><span class='request patch'>PATCH</span>/v1/delivery-orders/{id}/
          <div style='margin-top: 15px;'>
           <h2 class="accordion-header" id="deliveryHeadingOne_5">
           <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#deliveryCollapseOne_5" aria-expanded="true" aria-controls="collapseOne">
                Request body exampel
           </button>
           </h2>
           <div id="deliveryCollapseOne_5" class="accordion-collapse collapse" aria-labelledby="deliveryHeadingOne_5" data-bs-parent="#accordionExample">
           <div class="accordion-body">
           Request body as same as <code>PUT: /v1/delivery-orders/{id}/</code> BUT you can ignore some of keys because it partial update
           </div>
           </div>

           <h2 class="accordion-header" id="deliveryHeadingTwo_5">
           <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#deliveryCollapseTwo_5" aria-expanded="true" aria-controls="collapseOne">
                Response header exampel
           </button>
           </h2>
           <div id="deliveryCollapseTwo_5" class="accordion-collapse collapse" aria-labelledby="deliveryHeadingTwo_5" data-bs-parent="#accordionExample">
           <div class="accordion-body">
           <pre>
            access-control-allow-origin: * 
            allow: GET,PUT,PATCH,DELETE,HEAD,OPTIONS 
            content-length: 58 
            content-type: application/json 
            date: Sun,15 Aug 2021 14:29:17 GMT 
            referrer-policy: same-origin 
            server: WSGIServer/0.2 CPython/3.9.6 
            vary: Accept,Origin,Cookie 
            www-authenticate: Bearer realm="api" 
            x-content-type-options: nosniff 
            x-frame-options: DENY 
            x-queryinspect-duplicate-sql-queries: 0 
            x-queryinspect-num-sql-queries: 0 
            x-queryinspect-total-request-time: 6 ms 
            x-queryinspect-total-sql-time: 0 ms 
            x-xss-protection: 1; mode=block 
           </pre>
           </div>
           </div>

           <h2 class="accordion-header" id="deliveryHeadingThree_5">
           <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#deliveryCollapseThree_5" aria-expanded="true" aria-controls="collapseOne">
                Response body exampel
           </button>
           </h2>
           <div id="deliveryCollapseThree_5" class="accordion-collapse collapse" aria-labelledby="deliveryHeadingThree_5" data-bs-parent="#accordionExample">
           <div class="accordion-body">
            Response body as same as <code>PUT: /v1/delivery-orders/{id}/</code>
           </div>
          </div> 
       </div>
        This end-point allow you partial update delivery based on his id.  

    6. <div id='accordionExample_6' class='desc delete-desc accordion'><span class='request delete' >DELETE</span>/v1/delivery-orders/{id}/
          <div style='margin-top: 15px;'>
           <h2 class="accordion-header" id="deliveryHeadingOne_6">
           <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#deliveryCollapseOne_6" aria-expanded="true" aria-controls="collapseOne">
                Request body exampel
           </button>
           </h2>
           <div id="deliveryCollapseOne_6" class="accordion-collapse collapse" aria-labelledby="deliveryHeadingOne_6" data-bs-parent="#accordionExample">
           <div class="accordion-body">
           In this end-point no request body needed, but one parameter is required:    <code>id</code>
           </div>
           </div>

           <h2 class="accordion-header" id="deliveryHeadingTwo_6">
           <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#deliveryCollapseTwo_6" aria-expanded="true" aria-controls="collapseOne">
                Response header exampel
           </button>
           </h2>
           <div id="deliveryCollapseTwo_6" class="accordion-collapse collapse" aria-labelledby="deliveryHeadingTwo_6" data-bs-parent="#accordionExample">
           <div class="accordion-body">
           <pre>
            access-control-allow-origin: * 
            allow: GET,PUT,PATCH,DELETE,HEAD,OPTIONS 
            content-length: 58 
            content-type: application/json 
            date: Sun,15 Aug 2021 14:39:46 GMT 
            referrer-policy: same-origin 
            server: WSGIServer/0.2 CPython/3.9.6 
            vary: Accept,Origin,Cookie 
            www-authenticate: Bearer realm="api" 
            x-content-type-options: nosniff 
            x-frame-options: DENY 
            x-queryinspect-duplicate-sql-queries: 0 
            x-queryinspect-num-sql-queries: 0 
            x-queryinspect-total-request-time: 6 ms 
            x-queryinspect-total-sql-time: 0 ms 
            x-xss-protection: 1; mode=block
           </pre>
           </div>
           </div>

           <h2 class="accordion-header" id="deliveryHeadingThree_6">
           <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#deliveryCollapseThree_6" aria-expanded="true" aria-controls="collapseOne">
                Response body exampel
           </button>
           </h2>
           <div id="deliveryCollapseThree_6" class="accordion-collapse collapse" aria-labelledby="deliveryHeadingThree_6" data-bs-parent="#accordionExample">
           <div class="accordion-body">
            In this end-point no response body.
           </div>
          </div>

          </div>  
       </div>
        This end-point allow you delete specific delivery based on his id.

    7. <div class='desc get-desc'><span class='request get' >GET</span>/v1/merchants/{merchant_id}/delivery-order/
          <div>

           <p class='request black'>Request body exampel</p>
           <p class='request black'>Response header exampel</p>
           <p class='request black'>Response body exampel</p>
          </div>  
       </div>
        check...       

- [tracking](#) <br />
    1. <div class='desc get-desc'><span class='request get'>GET</span>/v1/delivery-order/{tracking_number}/
          <div>
           <p class='request black'>Request body exampel</p>
           <p class='request black'>Response header exampel</p>
           <p class='request black'>Response body exampel</p>
          </div>
      </div>
       check...

    2. <div class='desc post-desc'><span class='request post' >POST</span>/v1/delivery-order/{tracking_number}/
          <div>
           <p class='request black'>Request body exampel</p>
           <p class='request black'>Response header exampel</p>
           <p class='request black'>Response body exampel</p>
          </div>
       </div>
    check...

- [upload](#)  <br />
    1. <div class='desc get-desc'><span class='request get'>GET</span>/v1/delivery-order-upload/
          <div>
           <p class='request black'>Request body exampel</p>
           <p class='request black'>Response header exampel</p>
           <p class='request black'>Response body exampel</p>
          </div>
       </div>
    check...

    2. <div class='desc post-desc'><span class='request post' >POST</span>/v1/delivery-order-upload/
          <div>
           <p class='request black'>Request body exampel</p>
           <p class='request black'>Response header exampel</p>
           <p class='request black'>Response body exampel</p>
          </div>
       </div>
        check...
- [uncompleted](#)  <br />
    1. <div id='accordionExample_1' class='desc get-desc accordion'><span class='request get'>GET</span>/v1/delivery-orders-uncompleted/
          <div style='margin-top: 15px;'>
           <h2 class="accordion-header" id="deliveryUncompletedHeadingOne_1">
           <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#deliveryUncompletedCollapseOne_1" aria-expanded="true" aria-controls="collapseOne">
                Request body exampel
           </button>
           </h2>
           <div id="deliveryUncompletedCollapseOne_1" class="accordion-collapse collapse" aria-labelledby="deliveryUncompletedHeadingOne_1" data-bs-parent="#accordionExample">
           <div class="accordion-body">
           In this end-point no request body needed.
           </div>
           </div>

           <h2 class="accordion-header" id="deliveryUncompletedHeadingTwo_1">
           <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#deliveryUncompletedCollapseTwo_1" aria-expanded="true" aria-controls="collapseOne">
                Response header exampel
           </button>
           </h2>
           <div id="deliveryUncompletedCollapseTwo_1" class="accordion-collapse collapse" aria-labelledby="deliveryUncompletedHeadingTwo_1" data-bs-parent="#accordionExample">
           <div class="accordion-body">
           <pre>
            allow: GET,HEAD,OPTIONS 
            content-length: 58 
            content-type: application/json 
            date: Sun,15 Aug 2021 15:07:37 GMT 
            referrer-policy: same-origin 
            server: WSGIServer/0.2 CPython/3.9.6 
            vary: Accept,Origin,Cookie 
            www-authenticate: Bearer realm="api" 
            x-content-type-options: nosniff 
            x-frame-options: DENY 
            x-queryinspect-duplicate-sql-queries: 0 
            x-queryinspect-num-sql-queries: 0 
            x-queryinspect-total-request-time: 6 ms 
            x-queryinspect-total-sql-time: 0 ms 
            x-xss-protection: 1; mode=block 
           </pre>
           </div>
           </div>

           <h2 class="accordion-header" id="deliveryUncompletedHeadingThree_1">
           <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#deliveryUncompletedCollapseThree_1" aria-expanded="true" aria-controls="collapseOne">
                Response body exampel
           </button>
           </h2>
           <div id="deliveryUncompletedCollapseThree_1" class="accordion-collapse collapse" aria-labelledby="deliveryUncompletedHeadingThree_1" data-bs-parent="#accordionExample">
           <div class="accordion-body">
           <pre>
           {
                "count": integer,
                "next": null,
                "previous": null,
                "results": [
                    {
                        "id": integer,
                        "packages": [
                            {
                                "id": integer,
                                "supplies_required": boolean,
                                "sms_confirmation_code": null,
                                "package": {
                                    "id": integer,
                                    "created": string,
                                    "modified": string,
                                    "description": null,
                                    "weight": number,
                                    "volume": number,
                                    "fragile": boolean,
                                    "package_size": {
                                        "id": integer,
                                        "name": string,
                                        "short_code": string,
                                        "description": string
                                    }
                                },
                                "package_location": string
                            }
                        ],
                        "delivery_attempts": string,
                        "pickup_date": string,
                        "delivered_date": string,
                        "created": string,
                        "modified": string,
                        "tracking_number": string,
                        "merchant_order_reference": null,
                        "order_notes": null,
                        "is_exchange": boolean,
                        "is_pudo": boolean,
                        "is_counter_dropoff": boolean,
                        "cash_processing": boolean,
                        "cash_amount": null,
                        "preferred_date": null,
                        "estimated_date": null,
                        "status": "created",
                        "intermediate_warehouses": [
                            string,
                            ...
                        ],
                        "dispatch_early": null,
                        "dispatch_late": null,
                        "merchant": {
                            "id": integer,
                            "created": string,
                            "modified": string,
                            "name": string,
                            "store_url": string,
                            "logo": string,
                            "store_phone": string,
                            "store_email": string,
                            "status": string,
                            "api_key": null,
                            "cash_processing_fees": number,
                            "cash_processing_fees_max": number,
                            "cash_processing_percentage": number,
                            "cash_processing_threshold": number,
                            "address": {
                                "id": integer,
                                "created": string,
                                "modified": string,
                                "nickname": string,
                                "line_1": string,
                                "line_2": string,
                                "line_3": null,
                                "zip_code": null,
                                "latitude": null,
                                "longitude": null,
                                "google_maps_link": null,
                                "notes": null,
                                "zone": {
                                    "id": integer,
                                    "name": string,
                                    "radius": number,
                                    "city": {
                                        "id": integer,
                                        "name": string,
                                        "population": integer,
                                        "is_captial": boolean,
                                        "governorate": {
                                            "id": integer,
                                            "name": string
                                        }
                                    },
                                    "served_by": {
                                        "id": integer,
                                        "name": string,
                                        "code": string,
                                        "capacity": number,
                                        "current_utilization": number,
                                        "size": number,
                                        "latitude": number,
                                        "longitude": number,
                                        "address": string,
                                        "is_virtual": boolean
                                    },
                                    "zone_group": []
                                }
                            },
                            "subscription": {
                                "id": integer,
                                "name": string
                            },
                            "pricing_lookup_delivery": null,
                            "pricing_lookup_return": null,
                            "pricing_lookup_exchange": null,
                            "pricing_lookup_cash_collection": null,
                            "act_cod_account": {
                                "account_number": string,
                                "created": string,
                                "modified": string,
                                "name": string,
                                "parent_account": {
                                    "account_number": string",
                                    "created": string,
                                    "modified": string,
                                    "name": string,
                                    "parent_account": object,
                                    "type": {
                                        "id": integer,
                                        "name": string
                                    }
                                },
                                "type": {
                                    "id": integer,
                                    "name": string
                                }
                            },
                            "act_shipping_revenue_account": {
                                "account_number": string,
                                "created": string,
                                "modified": string,
                                "name": string,
                                "parent_account": {
                                    "account_number": string",
                                    "created": string,
                                    "modified": string,
                                    "name": string,
                                    "parent_account": object,
                                    "type": {
                                        "id": integer,
                                        "name": string
                                    }
                                },
                                "type": {
                                    "id": integer,
                                    "name": string
                                }
                            },
                            "act_discounts_account": {
                                "account_number": string,
                                "created": string,
                                "modified": string,
                                "name": string,
                                "parent_account": {
                                    "account_number": string",
                                    "created": string,
                                    "modified": string,
                                    "name": string,
                                    "parent_account": object,
                                    "type": {
                                        "id": integer,
                                        "name": string
                                    }
                                },
                                "type": {
                                    "id": integer,
                                    "name": string
                                }
                            },
                            "act_account_receivable": {
                                "account_number": string,
                                "created": string,
                                "modified": string,
                                "name": string,
                                "parent_account": {
                                    "account_number": string",
                                    "created": string,
                                    "modified": string,
                                    "name": string,
                                    "parent_account": object,
                                    "type": {
                                        "id": integer,
                                        "name": string
                                    }
                                },
                                "type": {
                                    "id": integer,
                                    "name": string
                                }
                            },
                            "act_supplies_revenue_account": {
                                "account_number": string,
                                "created": string,
                                "modified": string,
                                "name": string,
                                "parent_account": {
                                    "account_number": string",
                                    "created": string,
                                    "modified": string,
                                    "name": string,
                                    "parent_account": object,
                                    "type": {
                                        "id": integer,
                                        "name": string
                                    }
                                },
                                "type": {
                                    "id": integer,
                                    "name": string
                                }
                            },
                            "pickup_days": [],
                            "billing_days": []
                        },
                        "customer": {
                            "id": integer,
                            "created": string,
                            "modified": string,
                            "first_name": string,
                            "last_name": string,
                            "email": null,
                            "phone": string,
                            "address": {
                                "id": integer,
                                "created": string,
                                "modified": string,
                                "nickname": string,
                                "line_1": string,
                                "line_2": string,
                                "line_3": null,
                                "zip_code": null,
                                "latitude": null,
                                "longitude": null,
                                "google_maps_link": null,
                                "notes": null,
                                "zone": {
                                    "id": integer,
                                    "name": string,
                                    "radius": number,
                                    "city": {
                                        "id": integer,
                                        "name": string,
                                        "population": integer,
                                        "is_captial": boolean,
                                        "governorate": {
                                            "id": integer,
                                            "name": string
                                        }
                                    },
                                    "served_by": {
                                        "id": 1,
                                        "name": "Downtown Cairo",
                                        "code": "DW",
                                        "capacity": 0.0,
                                        "current_utilization": 0.0,
                                        "size": 0.0,
                                        "latitude": 30.031367,
                                        "longitude": 31.232819,
                                        "address": "شارع كورنيش النيل",
                                        "is_virtual": false
                                    },
                                    "zone_group": []
                                }
                            },
                            "act_cash_account": null
                        },
                        "service_level": {
                            "id": integer,
                            "name": string,
                            "short_code": string,
                            "description": string
                        },
                        "pickup_point": null,
                        "order_price": {
                            "id": integer,
                            "created": string,
                            "modified": string,
                            "subtotal": number,
                            "vat": number,
                            "postal_tax": number,
                            "total": number
                        },
                        "current_warehouse": null,
                        "inbound_warehouse": {
                            "id": integer,
                            "name": string,
                            "code": string,
                            "capacity": number,
                            "current_utilization": number,
                            "size": number,
                            "latitude": number,
                            "longitude": number,
                            "address": string,
                            "is_virtual": boolean
                        },
                        "outbound_warehouse": {
                            "id": integer,
                            "name": string,
                            "code": string,
                            "capacity": number,
                            "current_utilization": number,
                            "size": number,
                            "latitude": number,
                            "longitude": number,
                            "address": string,
                            "is_virtual": boolean
                        },
                        "preferred_window": []
                    },
                    .....
            }
           </pre>
           </div>
          </div>

          </div>  
       </div>
    check...

### Return

- [return order](#) <br />
    1. <div class='desc get-desc'><span class='request get'>GET</span>/v1/returns/
          <div>
           <p class='request black'>Request body exampel</p>
           <p class='request black'>Response header exampel</p>
           <p class='request black'>Response body exampel</p>
          </div>
       </div>
        This end-point allow you to list all return orders.

    2. <div class='desc post-desc'><span class='request post' >POST</span>/v1/returns/
          <div>
           <p class='request black'>Request body exampel</p>
           <p class='request black'>Response header exampel</p>
           <p class='request black'>Response body exampel</p>
          </div>
       </div>
        This end-point allow you to create new return orde

    3. <div class='desc get-desc'>
        <span class='request get'>GET</span>/v1/returns/{id}/
          <div>
           <p class='request black'>Request body exampel</p>
           <p class='request black'>Response header exampel</p>
           <p class='request black'>Response body exampel</p>
          </div>
       </div>
        This end-point allow you retrieve specific return based on his id.  

    4. <div class='desc put-desc'><span class='request put' >PUT</span>/v1/returns/{id}/
          <div>
           <p class='request black'>Request body exampel</p>
           <p class='request black'>Response header exampel</p>
           <p class='request black'>Response body exampel</p>
          </div>
       </div>
        This end-point allow you update specific return based on his id.

    5. <div class='desc patch-desc'><span class='request patch'>PATCH</span>/v1/returns/{id}/
          <div>
           <p class='request black'>Request body exampel</p>
           <p class='request black'>Response header exampel</p>
           <p class='request black'>Response body exampel</p>
          </div> 
       </div>
        This end-point allow you partial update return based on his id.  

    6. <div class='desc delete-desc'><span class='request delete' >DELETE</span>/v1/returns/{id}/
          <div>
           <p class='request black'>Request body exampel</p>
           <p class='request black'>Response header exampel</p>
           <p class='request black'>Response body exampel</p>
          </div>  
       </div>
        This end-point allow you delete specific return based on his id.

- [tracking](#) <br />
    1. <div class='desc get-desc'><span class='request get'>GET</span>/v1/return/{tracking_number}/
          <div>
           <p class='request black'>Request body exampel</p>
           <p class='request black'>Response header exampel</p>
           <p class='request black'>Response body exampel</p>
          </div> 
       </div>
        check...

    2. <div class='desc post-desc'><span class='request post' >POST</span>/v1/return/{tracking_number}/
          <div>
           <p class='request black'>Request body exampel</p>
           <p class='request black'>Response header exampel</p>
           <p class='request black'>Response body exampel</p>
          </div>
       </div>
        check...

- [uncompleted](#) <br />
    1. <div class='desc get-desc'><span class='request get'>GET</span>/v1/return-orders-uncompleted/
          <div>
           <p class='request black'>Request body exampel</p>
           <p class='request black'>Response header exampel</p>
           <p class='request black'>Response body exampel</p>
          </div>
       </div>
        check...

### Exchanges

- [exchange order](#) <br />
    1. <div class='desc get-desc'>
        <span class='request get'>GET</span>/v1/exchanges/
          <div>
           <p class='request black'>Request body exampel</p>
           <p class='request black'>Response header exampel</p>
           <p class='request black'>Response body exampel</p>
          </div> 
    </div>
        This end-point allow you to list all exchange orders.

    2. <div class='desc post-desc'>
        <span class='request post' >POST</span>/v1/exchanges/
          <div>
           <p class='request black'>Request body exampel</p>
           <p class='request black'>Response header exampel</p>
           <p class='request black'>Response body exampel</p>
          </div>
    </div>
        This end-point allow you to create new exchange orders.  

    3. <div class='desc get-desc'>
        <span class='request get'>GET</span>/v1/exchanges/{id}/
          <div>
           <p class='request black'>Request body exampel</p>
           <p class='request black'>Response header exampel</p>
           <p class='request black'>Response body exampel</p>
          </div>
    </div>
        This end-point allow you retrieve specific exchange orders based on his id.  

    4. <div class='desc put-desc'><span class='request put' >PUT</span>/v1/exchanges/{id}/
          <div>
           <p class='request black'>Request body exampel</p>
           <p class='request black'>Response header exampel</p>
           <p class='request black'>Response body exampel</p>
          </div>
       </div>
        This end-point allow you update specific exchange orders based on his id.

    5. <div class='desc patch-desc'><span class='request patch'>PATCH</span>/v1/exchanges/{id}/
          <div>
           <p class='request black'>Request body exampel</p>
           <p class='request black'>Response header exampel</p>
           <p class='request black'>Response body exampel</p>
          </div>
       </div>
        This end-point allow you partial update specific exchange orders based on his id.  

    6. <div class='desc delete-desc'><span class='request delete' >DELETE</span>/v1/exchanges/{id}/
          <div>
           <p class='request black'>Request body exampel</p>
           <p class='request black'>Response header exampel</p>
           <p class='request black'>Response body exampel</p>
          </div>
       </div>
        This end-point allow you delete specific exchange orders based on his id.

### Cash Collection

Collect shipment cost from customer.
- [cash collection](#) 

## Billing Statements

- [invoices](#) <br />
    1. <div class='desc get-desc'>
        <span class='request get'>GET</span>/v1/billing/invoices/
          <div>
           <p class='request black'>Request body exampel</p>
           <p class='request black'>Response header exampel</p>
           <p class='request black'>Response body exampel</p>
          </div>
       </div>
        This end-point allow you to list all invoices.

    2. <div class='desc get-desc'>
        <span class='request get'>GET</span>/v1/billing/invoices/{id}/
           <div>
           <p class='request black'>Request body exampel</p>
           <p class='request black'>Response header exampel</p>
           <p class='request black'>Response body exampel</p>
          </div>
       </div>
        This end-point allow you to retrieve specific invoice based on his id. 

    3. <div class='desc post-desc'>
        <span class='request post' >POST</span>/v1/billing/invoices/order/
          <div>
           <p class='request black'>Request body exampel</p>
           <p class='request black'>Response header exampel</p>
           <p class='request black'>Response body exampel</p>
          </div>
       </div>
        This end-point allow you to create new invoice for orders list.
- [statements](#) 



<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.0/dist/js/bootstrap.bundle.min.js" integrity="sha384-U1DAWAznBHeqEIlVSCgzq+c9gqGAJn5c/t99JyeKa9xxaYpSvHU5awsuZVVFIhvj" crossorigin="anonymous"></script>


