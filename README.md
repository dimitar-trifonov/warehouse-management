#A Demo Laravel App

A web app to demonstrate CRUD operations in Laravel 8.x.

There are two Models
* Warehouse
* Item

Every Warehouse has two properties
* name
* location

The Warehouse should be unique for a specific location.

Items are stored in a warehouse.
Every item should exist only in one warehouse.

Item properties are:
* its name 
* a barcode

The barcode should be unique thrhough all items.
