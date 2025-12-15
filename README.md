# Postman & JMeter Test Plan for Simple Books API

This repository contains a JMeter test plan for interacting with the [Simple Books API](https://simple-books-api.glitch.me).

## Files Included

- `simple-books-test-plan.jmx` - JMeter test plan with the following steps:
  - Generate auth token
  - Create an order
  - Extract orderId
  - Get the order
  - Update the order
  - Delete the order
  - Confirm deletion with GET
  - Read data from CSV and create orders

- `order-data.csv` - Contains bookId and customerName pairs for POST request data

## Setup Instructions

1. Open `simple-books-test-plan.jmx` in Apache JMeter.
2. Place `order-data.csv` in the same directory as the JMX file.
3. Update the Thread Group if you want to run multiple users or loops.
4. Run the test plan and observe the results using View Results Tree and Summary Report.
