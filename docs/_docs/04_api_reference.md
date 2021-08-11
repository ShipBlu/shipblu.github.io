---
layout: default
title: API Reference
nav_order: 4
description: "Full API Reference"
permalink: /api-reference
---

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
</style>

# API Reference
{: .fs-9 }

TO BE DOCUMENTED 


## Geographic Availability

- [pudos](#) <br />

  We can define pudos as meeting points between customer and CA.<br />

  Now after know what is pudos, let's play with his API end-points.<br />

    1. <div class='desc get-desc'><span class='request get'>GET</span>/v1/pudos/</div>
        This end-point allow you to list all pudos.

    2. <div class='desc post-desc'><span class='request post' >POST</span>/v1/pudos/</div>
        This end-point allow you to create new pudo point.  

    3. <div class='desc get-desc'><span class='request get'>GET</span>/v1/pudos/{id}/</div>
        This end-point allow you retrieve specific pudo based on his id.  

    4. <div class='desc put-desc'><span class='request put' >PUT</span>/v1/pudos/{id}/</div>
        This end-point allow you update specific pudo based on his id.

    5. <div class='desc patch-desc'><span class='request patch'>PATCH</span>/v1/pudos/{id}/</div>
        This end-point allow you partial update specific pudo based on his id.  

    6. <div class='desc delete-desc'><span class='request delete' >DELETE</span>/v1/pudos/{id}/</div>
        This end-point allow you delete specific pudo based on his id.  

    7. <div class='desc get-desc'><span class='request get' >GET</span>/v1/pudo/cities/{city_id}/</div>
        This end-point allow you retrieve pudos in specific city based on city id.     

- [governorates](#) <br />

    1. <div class='desc get-desc'><span class='request get'>GET</span>/v1/governorates/</div>
        This end-point allow you to list all governorates.

    2. <div class='desc post-desc'><span class='request post' >POST</span>/v1/governorates/</div>
        This end-point allow you to create new governorate.

    3. <div class='desc get-desc'><span class='request get'>GET</span>/v1/governorates/{governorate_id}/cities/</div>
        This end-point allow you retrieve all cities in specific governorate based on governorates id.
- [warehouses](#) <br />

    A large building where shipments may be stored before their export or distribution for sale.

    1. <div class='desc get-desc'><span class='request get'>GET</span>/v1/warehouses/</div>
        This end-point allow you to list all warehouses.

    2. <div class='desc get-desc'><span class='request get'>GET</span>/v1/warehouses/{warehouse_code}/zone-groups/</div>
        This end-point allow you to retrieve all zone-groups served by specific warehouse based on warehouse code.

    3. <div class='desc post-desc'><span class='request post'>POST</span>/v1/warehouses/{warehouse_code}/zone-groups/</div>
        This end-point allow you to create new zone-groups served by specific warehouse.

    4. <div class='desc get-desc'><span class='request get'>GET</span>/v1/warehouses/{warehouse_code}/zones/</div>
        This end-point allow you to retrieve all zones served by specific warehouse based on warehouse code.

- [zones](#) <br />

    We can define zones as specific areas in city.<br />

    Now after know what is zones, let's play with his API end-points.<br />

    1. <div class='desc get-desc'><span class='request get'>GET</span>/v1/cities/{city_id}/zones/</div>
        This end-point allow you retrieve zones in specific city based on city id.
 
- [zone groups](#) <br />

    1. <div class='desc get-desc'><span class='request get'>GET</span>/v1/zone-groups/{id}/</div>
        This end-point allow you retrieve specific zone group based on his id.  

    2. <div class='desc put-desc'><span class='request put' >PUT</span>/v1/zone-groups/{id}/</div>
        This end-point allow you update specific zone group based on his id.

    3. <div class='desc patch-desc'><span class='request patch'>PATCH</span>/v1/zone-groups/{id}/</div>
        This end-point allow you partial update specific zone group based on his id.  

    4. <div class='desc delete-desc'><span class='request delete' >DELETE</span>/v1/zone-groups/{id}/</div>
        This end-point allow you delete specific zone group based on his id.

- [cities](#) <br />

    1. <div class='desc get-desc'><span class='request get'>GET</span>/v1/cities/{id}/</div>
        This end-point allow you retrieve specific city based on his id.  

    2. <div class='desc post-desc'><span class='request post'>POST</span>/v1/cities/{id}/</div>
        check...     

    3. <div class='desc put-desc'><span class='request put' >PUT</span>/v1/cities/{id}/</div>
        This end-point allow you update specific city based on his id.

    4. <div class='desc patch-desc'><span class='request patch'>PATCH</span>/v1/cities/{id}/</div>
        This end-point allow you partial update specific city based on his id.  

    5. <div class='desc delete-desc'><span class='request delete' >DELETE</span>/v1/cities/{id}/</div>
        This end-point allow you delete specific city based on his id.

## Service Availability
   To Be Document

## Pickup Points

- [pickup points](#) <br />

   Meeting points between merchant and merchant agent.

    1. <div class='desc get-desc'><span class='request get'>GET</span>/v1/merchants/{merchant_id}/pickup-points/</div>
        This end-point allow you to list all pickup point of specific merchant based on merchant id.

    2. <div class='desc post-desc'><span class='request post' >POST</span>/v1/merchants/{merchant_id}/pickup-points/</div>
        This end-point allow you to create new pickup point to specific merchant based on merchant id.  

    3. <div class='desc get-desc'><span class='request get'>GET</span>/v1/merchants/{merchant_id}/pickup-points/{id}/</div>
        This end-point allow you retrieve specific pickup point based on merchant id and his id.  

    4. <div class='desc put-desc'><span class='request put' >PUT</span>/v1/merchants/{merchant_id}/pickup-points/{id}/</div>
        This end-point allow you update specific pickup point based on merchant id and his id.

    5. <div class='desc patch-desc'><span class='request patch'>PATCH</span>/v1/merchants/{merchant_id}/pickup-points/{id}/</div>
        This end-point allow you partial update pickup point based on merchant id and his id.  

    6. <div class='desc delete-desc'><span class='request delete' >DELETE</span>/v1/merchants/{merchant_id}/pickup-points/{id}/</div>
        This end-point allow you delete specific pickup point based on merchant id and his id.

## Orders

Orders divided on three categoricals
- Delivery
- Return
- Exchanges

### Delivery
- [delivery order](#) <br />
    1. <div class='desc get-desc'><span class='request get'>GET</span>/v1/delivery-orders/</div>
        This end-point allow you to list all delivery orders.

    2. <div class='desc post-desc'><span class='request post' >POST</span>/v1/delivery-orders/</div>
        This end-point allow you to create new delivery order.

- [tracking](#) <br />
    1. <div class='desc get-desc'><span class='request get'>GET</span>/v1/delivery-order/{tracking_number}/</div>
    check...

    2. <div class='desc post-desc'><span class='request post' >POST</span>/v1/delivery-order/{tracking_number}/</div>
    check...

- [upload](#)  <br />
    1. <div class='desc get-desc'><span class='request get'>GET</span>/v1/delivery-order-upload/</div>
    check...

    2. <div class='desc post-desc'><span class='request post' >POST</span>/v1/delivery-order-upload/</div>
        check...
- [uncompleted](#)  <br />
    1. <div class='desc get-desc'><span class='request get'>GET</span>/v1/delivery-orders-uncompleted/</div>
    check...

### Return

- [return order](#) <br />
    1. <div class='desc get-desc'><span class='request get'>GET</span>/v1/returns/</div>
        This end-point allow you to list all return orders.

    2. <div class='desc post-desc'><span class='request post' >POST</span>/v1/returns/</div>
        This end-point allow you to create new return orde

    3. <div class='desc get-desc'>
        <span class='request get'>GET</span>/v1/returns/{id}/
       </div>
        This end-point allow you retrieve specific return based on his id.  

    4. <div class='desc put-desc'><span class='request put' >PUT</span>/v1/returns/{id}/</div>
        This end-point allow you update specific return based on his id.

    5. <div class='desc patch-desc'><span class='request patch'>PATCH</span>/v1/returns/{id}/</div>
        This end-point allow you partial update return pudo based on his id.  

    6. <div class='desc delete-desc'><span class='request delete' >DELETE</span>/v1/returns/{id}/</div>
        This end-point allow you delete specific return based on his id.

- [tracking](#) <br />
    1. <div class='desc get-desc'><span class='request get'>GET</span>/v1/return/{tracking_number}/</div>
        check...

    2. <div class='desc post-desc'><span class='request post' >POST</span>/v1/return/{tracking_number}/</div>
        check...

- [uncompleted](#) <br />
    1. <div class='desc get-desc'><span class='request get'>GET</span>/v1/return-orders-uncompleted/</div>
        check...

### Exchanges

- [exchange order](#) <br />
    1. <div class='desc get-desc'>
        <span class='request get'>GET</span>/v1/exchanges/
    </div>
        This end-point allow you to list all exchange orders.

    2. <div class='desc post-desc'>
        <span class='request post' >POST</span>/v1/exchanges/
    </div>
        This end-point allow you to create new exchange orders.  

    3. <div class='desc get-desc'>
        <span class='request get'>GET</span>/v1/exchanges/{id}/
    </div>
        This end-point allow you retrieve specific exchange orders based on his id.  

    4. <div class='desc put-desc'><span class='request put' >PUT</span>/v1/exchanges/{id}/</div>
        This end-point allow you update specific exchange orders based on his id.

    5. <div class='desc patch-desc'><span class='request patch'>PATCH</span>/v1/exchanges/{id}/</div>
        This end-point allow you partial update specific exchange orders based on his id.  

    6. <div class='desc delete-desc'><span class='request delete' >DELETE</span>/v1/exchanges/{id}/</div>
        This end-point allow you delete specific exchange orders based on his id.

### Cash Collection

Collect shipment cost from customer.
- [cash collection](#) 

## Billing Statements

- [invoices](#) <br />
    1. <div class='desc get-desc'>
        <span class='request get'>GET</span>/v1/billing/invoices/
       </div>
        This end-point allow you to list all invoices.

    2. <div class='desc get-desc'>
        <span class='request get'>GET</span>/v1/billing/invoices/{id}/
       </div>
        This end-point allow you to retrieve specific invoice based on his id. 

    3. <div class='desc post-desc'>
        <span class='request post' >POST</span>/v1/billing/invoices/order/
       </div>
        This end-point allow you to create new invoice for orders list.
- [statements](#) 

