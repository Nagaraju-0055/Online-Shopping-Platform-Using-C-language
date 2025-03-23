### Online-Shopping-Platform-Using-C-language

# Online Shopping Platform

A console-based e-commerce application that simulates the complete shopping experience from user authentication to purchase confirmation. This C program demonstrates fundamental programming concepts including data structures, user management, and transaction processing.

## Project Overview

This application was developed as a course project to apply programming concepts in a real-world scenario. The platform allows users to create accounts, browse products, add items to their cart, and complete purchases in a secure environment.

## Features

### User Authentication
- Secure registration system with data validation
- Password complexity requirements (uppercase, lowercase, numbers, special characters)
- User login with email and password verification
- Account validation to prevent duplicate registrations

### Shopping Experience
- Two navigation paths: shop-based browsing and item-based browsing
- Multiple stores with varied product catalogs
- Dynamic product display with pricing information
- Quantity selection for each product

### Cart Management
- Add multiple items from different stores
- Calculate total purchase amount
- Option to proceed with purchase or cancel order
- Order confirmation system

## Technical Implementation

### Data Structures
- User information stored in structured arrays
- Product information organized by store and item categories
- Shopping cart implementation for item tracking

### Input Validation
- Email format validation (requires '@' and '.' characters)
- Password strength verification
- Mobile number validation for numeric input and proper length
- Age verification

### Program Structure
- Modular design with separate functions for each feature
- Clean interface with intuitive navigation
- Error handling for invalid inputs

## User Flow

1. Start the application
2. Create a new account or login with existing credentials
3. Browse products by shop or item category
4. Select items and specify quantities
5. Review cart contents and total cost
6. Confirm or cancel order
7. Continue shopping or exit

## Code Structure

- `main()`: Entry point with main menu
- `signup()`: Handle user registration
- `validate()`: Validate user input during registration
- `account_validate()`: Check for existing accounts
- `login()`: Authenticate existing users
- `shop_initialize()`: Initialize store product data
- `shop()`: Display shops and handle shop selection
- `Shop()`: Display products in selected shop
- `items()`: Display all available items
- `item_order()`: Process item selection
- `cart()`: Manage shopping cart and checkout

## Future Enhancements

- Database integration for persistent storage
- Admin panel for inventory management
- Payment gateway integration
- User profile management
- Order history tracking

## Contributions

This project was developed as a team effort by:
- B. Nagaraju
- P. Rahul
- M. Sahith
- Ch. Rusikar

Under the guidance of K. Chandhar, Assistant Professor at SR University.

## License

This project is available for educational purposes. Please provide appropriate attribution when using or modifying the code.
