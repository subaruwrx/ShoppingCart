# Shopping cart System Domain Model

## Introduction
Shopping can be tiring walking from one store to another, the Shopping cart system allows customers to shop online

without tiring themselves standing in long lines for minutes.

## Class Diagram of the Domain Model

Below is the domain Domain of the  Shopping cart System that I want to develop.
![Domain Model](/model.png)
 ## Description of the Domain Model and its Invariants

one offer can be offerd for many products ,an order can have one to many orderDetails and orderDetails

can have one to many products. An order can only have one address assigned to it.A user can have one to 

many addresses for example postal address or home address, a user can only have one userAccount under 

they name. UserAccount has only one role in the system.eg user,admin,guest and an order can have only 

one status. one wishList can have one to many products on it or consist and one product can belong to

many brand names. One brand can have many products eg..produced goods-one to many . One product can 

have one to many ratings.A product can only belong to one category and a shopping cart can have zero

to many products on it. A product can have one to many atrributes a product can belong to one productType


Customer on the system can browse or search items, view specific item, add it to shopping cart, view and update shopping cart,

checkout. User can view shopping cart at any time. Checkout is assumed to include user registration and login.Customer may search or

browse items, add or remove items from shopping cart, do checkout.

## Type of Users and Fuctions they allowed to do

##Administrator
The Admin can login the System, Admin can create categories, Admin can create subcategories, Admin can upload products and Admin can upload product features

##Buyer
The customer can login the System, The customer  can search for a particular productand  The customer  can order a product
