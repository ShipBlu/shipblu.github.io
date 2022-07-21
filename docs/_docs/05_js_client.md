---
layout: default
title: JS Client
nav_order: 5
description: "JS Client Library"
permalink: /js-client
---
# ShipBlu JS Client Library

The client library used in our frontend to communiate with ShipBlu API.


### Installation

#### With npm
```
npm install shipblu
```

### Usage

#### In your `main.js`:

```js
import * as ShipBlu from 'shipblu'
const options = {
  key: '', //your API-Key or token
  type: '', // Api-Key or Bearer
  enviroment: '' // staging or production
}
ShipBlu.ShipbluClient.getInstance(options)
```

#### In your component file:
```js
import * as ShipBlu from 'shipblu'
const order = new ShipBlu.DeliveryOrder() //or ShipBlu.ReturnOrder()
```
##### To get all orders
```js
async getOrders () {
  const data = await order.get(10, 0) //(limit, offset)
}
```
##### To retrieve order

```js
async getOrder () {
  const data = await order.retrieve(10) //(orderID)
}
```
##### To create order

```js
async createOrder () {
  // PACKAGES
  const packages = new ShipBlu.Package()
  const packagesArr = [
    {
      package_size: id, // 1: Small, 2: Medium, 3: Large or 4: Extra Large 
      description: '',
      fragile: false
    }
  ]
  packages.set(packagesArr)  // add packages
  const orderPackages = packages.get() // get packages to send it to order creation 

  // CUSTOMER
  const customer = new ShipBlu.Customer()
  customer.create(
    fullName,       // fullName: string
    phone,          // phone: string
    line1,          // line1: string
    line2,          // line2: string
    zoneID,         // zoneID: number
    email,          // email?: string
    secondaryPhone  // secondaryPhone?: string
  )
  const orderCustomer = Customer.get() // get packages to send it to order creation 

  const data = await 
    order.create(
      orderCustomer,   // customer: {}
      orderPackages,   // packages:[], 
      cashAmount,      // cashAmount: number
      orderReference,  // orderReference?: string
      notes,           // notes?: string
      openPackages     // openPackages?: Boolean
    )
}
```
##### To update order

```js
async updateOrder () {
  const body = {}
  const data = await order.update(9775, body) //(orderID, body obj)
},
```