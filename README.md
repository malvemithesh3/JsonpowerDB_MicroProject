# Shipment Management Form with JsonPowerDB

## Title of the Project

## Shipment Management Form with JsonPowerDB

## Description

The Shipment Management Form is a web application designed to streamline the management of shipment details, including adding, editing, and viewing records. This implementation leverages JsonPowerDB (JPDB), a high-performance NoSQL database, for rapid and efficient data handling.

JsonPowerDB is ideal for this project due to its lightweight structure, built-in REST API support, and minimal configuration setup.


## Benefits of Using JsonPowerDB

Simplified Integration: Direct JSON format compatibility eliminates the need for complex data transformations.

High Performance: JPDB provides ultra-fast data retrieval and storage.

Built-in REST API: Easily interact with the database via APIs without additional backend logic.

Low Configuration: No need for complicated schema design or installations.

Secure and Reliable: In-built security measures and a reliable transactional system.

Ease of Use: Minimal code for CRUD operations, reducing development time significantly.


## Release History

Version 1.0.0 (2024-11-25): Initial release of the Shipment Management Form, integrated with JsonPowerDB for managing shipment details.


## Scope of Functionalities

Add Shipment Records: Users can add new shipment details, including shipment number, description, source, destination, shipping date, and expected delivery date.

Edit Records: Update existing shipment information with ease.

View Shipment Details: Access all records in an organized table format.

Real-time Database Operations: Utilize JsonPowerDB for fast and secure database management.

Data Validation: Ensures that all required fields are entered before submission.

Scalable Architecture: Ready to accommodate additional features like search and filters.


## Examples of Use


### Add a Shipment Record

### Input:

{
  "shipmentNo": "34",
  "description": "Electronics shipment for holiday season",
  "source": "San Francisco",
  "destination": "New York",
  "shippingDate": "2024-11-30",
  "expectedDeliveryDate": "2024-12-05"
}

![Screenshot 2024-11-25 154651](https://github.com/user-attachments/assets/0acfdaac-2b36-446b-a72c-5cb03831a93d)


### Response:


{
  "status": "success",
  "message": "Shipment record added successfully"
}

![Screenshot 2024-11-25 164541](https://github.com/user-attachments/assets/7a50e603-5f89-40ca-8ea9-7b8c3e666e68)


### Edit a Shipment Record

### Input:


{
  "shipmentNo": "34",
  "description": "Updated description: Electronics shipment for Black Friday sale",
  "source": "San Francisco",
  "destination": "Chicago",
  "shippingDate": "2024-11-30",
  "expectedDeliveryDate": "2024-12-05"
}


### Response:

{
  "status": "success",
  "message": "Shipment record updated successfully"
}

### Project Status: Done


## Illustrations

Below are illustrations of the web app in action:


### Homepage

A clean and simple form interface for adding and managing shipment records.


### Shipment Table

View all shipment details in an easy-to-read table format.

![Screenshot 2024-11-25 155102](https://github.com/user-attachments/assets/4ee61cc4-3bdb-48dd-b225-86f521c1f877)


## Sources

Introduction to JsonPowerDB - V2.0: Course Link

JsonPowerDB Documentation: JPDB Docs


## Other Information

Step-by-Step Setup for JsonPowerDB

Creating a Developer Account and Generating Connection Token:

Visit: JsonPowerDB API

Register and follow the email instructions to set up your account.

Change your password after the first login.

Navigate to Tools > Token > Connection Token > Generate to generate your database token.

Example Token: 90934410|-31949230557262165|90957309


## Installing Talend API Tester:

Install Talend API Tester extension via the Chrome Web Store to test API requests.


## Understanding JsonPowerDB:

JsonPowerDB is nimble, schema-free, and easy to maintain.

It supports real-time in-memory operations and is cost-efficient.

JsonPowerDB Use Cases and Benefits:

Suitable for all RDBMS, document, and key-value DB use cases.

Ideal for real-time applications, analytics, and live reporting.


## Working with Commands:

PUT: Insert new records.

GET: Retrieve records by key or criteria.

UPDATE: Update existing records or add new columns.

REMOVE: Delete records from the database.



