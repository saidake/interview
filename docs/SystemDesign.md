<!-----------------------------------------------------------
Author:  Craig Brown
Version: 1.0.0
Source:  https://github.com/saidake/simi-interview
------------------------------------------------------------->
# Table of Contents
[Back to Main Project README](../README.md)
- [Table of Contents](#table-of-contents)
  - [1. Shopping Cart](#1-shopping-cart)
    - [Purpose](#purpose)
    - [Basic Functions](#basic-functions)
    - [Cache Data Storage](#cache-data-storage)
    - [Core Data Storage](#core-data-storage)
      - [MYSQL or Other SQL Databases](#mysql-or-other-sql-databases)
      - [Redis or Other NoSQL Databases (Optimal)](#redis-or-other-nosql-databases-optimal)

## 1. Shopping Cart
### Purpose
A shopping cart temporarily stores selected items before purchase.
### Basic Functions
* Add items to Cart.
  * If the user is not logged in, save items to the **browser cache**.
  * If the user logs in, merge cached items with **server-side user data**.
  * If the user logs out, **sync cart items** across all platforms (browser, mobile, etc.).
* Display cart items
* Checkout selected items.


### Cache Data Storage
Cookie or LocalStorage Storage: 
* Cookie: for small data (< 4KB).
* LocalStorage: for larger data.

Data Structure:
* Cart *(list)*
  * Item
     * sku_id *(product ID)*
     * quantity 
     * timestamp *(added time)*
     * selected *(true/false)*
     
Example:
```json
{
    "cart":[
        {
            "sku_id": 123,
            "quantity": 2,
            "selected": true,
            "timestamp": 1578772233
        }
    ]
}
```
### Core Data Storage
#### MYSQL or Other SQL Databases
Store persistent cart data in a database table.

Data Structure:
* Cart *(table)*
    * id
    * user_id
    * sku_id
    * quantity
    * selected
    * timestamp

#### Redis or Other NoSQL Databases (Optimal)
Use Redis to store temporary cart data per user.

Data Structure:
* KEY *(user id)*
* VALUE *(list)*
  * Item
     * skuId  *(product ID)*
     * quantity
     * timestamp
     * selected 

Example:
```json
{
    "KEY": 567,
    "VALUE":[
        {
          "skuId": 123,
          "quantity": 2,
          "selected": true,
          "timestamp": 1578772233
        }
    ]
}
```