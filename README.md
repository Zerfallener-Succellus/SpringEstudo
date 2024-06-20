# Simple CRUD in Spring

 This is a simple CRUD that I created to review my Java Spring knowledge. ⌨️

## Table of Contents😎

 - Installation
 - Config
 - Endpoints
 - Database
 - Example of endpoint uses

## Installation💻
1. Clone

     git clone https://github.com/Zerfallener-Succellus/SpringEstudo

2. Install Maven dependencies

## Config⚙️
1. Start Application
2. The API will be accessible at  [http://localhost:8080](http://localhost:8080/)

## Endpoints👨🏻‍💻

    GET/ - Retrieve a list of all products in tables
    POST/ - Register a new product in the tables
    PUT/ - Modify a product
    DELETE/ - Delete a product

## Database🗒️
The project utilizes PostgresSQL as the database.  The necessary database migrations are managed using Flyway.
Install PostgresSQL👉🏻 ([https://www.postgresql.org/download/](https://www.postgresql.org/download/)) 

## Example of endpoint uses🤓👆🏻

    POST/
    {
	    "name": "cinto",
	    "price_in_cents": 400
	}
	
	DELETE/
	{
		"id": "7dff78a2-6005-4d0c-975c-ead8c96bbbc9",
		"name": "cinto",
		"price_in_cents": 400
	}
	
	PUT/
	{
		"id": "e89dcc7c-87e7-4cde-a06d-f3d7d53b2064",
		"name": "camiseta",
		"price_in_cents": 8000
	}


	

