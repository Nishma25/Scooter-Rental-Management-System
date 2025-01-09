# Scooter Rental Management System

## Project Overview

This project implements an object-oriented scooter rental management system for a rental shop. The system manages a fleet of scooters, handles customer rentals, and processes payments.

## Features

- Scooter fleet management (Standard and Premium models)
- Multiple rental options (Hourly, Daily, Weekly)
- Automated maintenance tracking
- Discount application for bulk rentals
- Transaction management and history
- Report generation

## System Requirements

### Scooter Management
- Unique ID for each scooter
- Standard and Premium scooter models
- Maintenance required after every 10 rides
- Availability and maintenance status tracking

### Rental Options
- Hourly: $5 per scooter per hour
- Daily: $20 per scooter per day
- Weekly: $50 per scooter per week

### Rental Rules
- Single time period per rental transaction
- No multiple active rentals per customer
- Rental requests limited by available inventory
- 30% discount for renting 3-5 scooters in a single transaction

### Transaction Management
- Rental duration tracking
- Cost calculation based on duration and number of scooters
- Discount application
- Payment processing
- Rental history maintenance
- Receipt generation (in USD)

## Technical Implementation

### Classes
- ScooterRental (main system class)
- Scooter (individual scooter management)
- RentalTransaction (rental tracking)
- RentalPeriod (rental period enumeration)
- IPaymentProcessor and CreditCardPaymentProcessor (payment processing interface)

### Error Handling
- Insufficient scooter inventory
- Invalid rental periods
- Payment processing failures
- Invalid customer operations

### Command-line Interface
- View available scooters
- Rent scooters
- Return scooters
- View system reports

## Testing

Unit tests are implemented to verify system functionality, including:
- Rental calculations
- Discount applications
- Error handling
- Business rule enforcement

## Setup Instructions

1. Clone the repository
2. Install Jupyter Notebook
3. Run the main script to start the system



