# Inventory Vendor Management System

A Django REST Framework-based Inventory Vendor Management System with JWT Authentication and Swagger API documentation.

## Features

* JWT Authentication
* Product Management
* Inventory Management
* Purchase Request Management
* Purchase Order Management
* Goods Receipt API

## Tech Stack

* Python
* Django
* Django REST Framework
* PostgreSQL
* Swagger (drf-spectacular)

## API Documentation

After running the project locally or deploying on Render:

* Swagger: `/api/docs/`
* Schema: `/api/schema/`

## Goods Receipt API

**Endpoint:**

`POST /api/v1/purchase-requests/receiving/create/`

**Status:** Successfully tested with **201 Created**.
