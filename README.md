# Coffee Analytics Project

## Description

This project aims to analyze a coffee orders dataset to gain insights into customer preferences, popular items, and sales trends in the coffee industry.

## Dataset

The dataset used in this project contains information about coffee orders, including customer details, order items, and products.

## Data Attribute

### Orders Sheet

The Orders sheet contains information about coffee orders, including populated and unpopulated data attributes:

**Populated Data Attributes:**
| Attribute | Data Type | Description |
|-------------|-----------|------------------------------------------|
| Order ID | String | Identifier for each order. |
| Order Date | Date | Date when the order was placed. |
| Customer ID | String | Identifier for each customer. |
| Product ID | String | Identifier for each product in the order.|
| Quantity | Numeric (Float) | Quantity of the product ordered. |

**Unpopulated Data Attributes:**
| Attribute | Data Type | Description |
|---------------|-----------|----------------------------------------------|
| Customer Name | String | Name of the customer associated with the order.|
| Email | String | Email address of the customer. |
| Country | String | Country associated with the order. |
| Coffee Type | String | Type of coffee ordered. |
| Roast Type | String | Roast type of the coffee. |
| Size | Numeric (Float) | Size or portion of the coffee ordered. |
| Unit Price | Numeric (Float) | Price of a single unit of the product. |
| Sales | Numeric | Total sales amount for the order. |

### Customers Sheet

The Customers sheet contains information about customers:

| Attribute      | Data Type | Description                               |
| -------------- | --------- | ----------------------------------------- |
| Customer ID    | String    | Identifier for each customer.             |
| Customer Name  | String    | Name of the customer.                     |
| Email          | String    | Email address of the customer.            |
| Phone Number   | String    | Phone number of the customer.             |
| Address Line 1 | String    | Address line 1 of the customer.           |
| City           | String    | City of the customer.                     |
| Country        | String    | Country associated with the customer.     |
| Postcode       | String    | Postcode or ZIP code of the customer.     |
| Loyalty Card   | Boolean   | Loyalty card information of the customer. |

### Products Sheet

The Products sheet contains information about coffee products:

| Attribute      | Data Type       | Description                            |
| -------------- | --------------- | -------------------------------------- |
| Product ID     | String          | Identifier for each product.           |
| Coffee Type    | String          | Type of coffee.                        |
| Roast Type     | String          | Roast type of the coffee.              |
| Size           | Numeric (Float) | Size or portion of the coffee.         |
| Unit Price     | Numeric (Float) | Price of a single unit of the product. |
| Price per 100g | Numeric (Float) | Price per 100 grams of the product.    |
| Profit         | Numeric (Float) | Profit generated from the product.     |

## Technologies Used

- Microsoft Excel

## Getting Started

To get started with this project, clone the repository and follow the instructions in the project documentation.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.
