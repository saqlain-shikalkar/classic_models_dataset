# classic_models_dataset
Power BI Project – Classic Models Sales Analysis

Built an interactive Power BI dashboard using SQL-based Classic Models dataset

Created DAX measures for sales, revenue, and performance tracking

Designed multi-page dashboards with filters and drill-downs

Analyzed customer behavior, product performance, and regional sales

The Classic Models Dataset is a sample business dataset commonly used for data analysis, and Power BI projects.
It represents a fictional company that sells classic model vehicles and contains detailed information about customers, orders, products, employees, and payments.

This dataset is ideal for:
##Data analysis & visualization##
##Power BI / Tableau dashboards##

📊 Table Descriptions
🧾 customers

Contains customer information and assigned sales representatives.

Key Columns:

customerNumber (PK)

customerName

contactFirstName

contactLastName

phone

city, country

salesRepEmployeeNumber

creditLimit

📦 orders

Stores order-level information.

Key Columns:

orderNumber (PK)

orderDate

requiredDate

shippedDate

status

customerNumber (FK)

🧾 order_details

Contains line-level order details.

Key Columns:

orderNumber (FK)

productCode (FK)

quantityOrdered

priceEach

orderLineNumber

🛒 products

Product catalog data.

Key Columns:

productCode (PK)

productName

productLine

productScale

productVendor

quantityInStock

buyPrice

MSRP

🧩 productlines

Product category information.

Key Columns:

productLine (PK)

textDescription

htmlDescription

image

💳 payments

Customer payment records.

Key Columns:

customerNumber (FK)

checkNumber

paymentDate

amount

🧑‍💼 employees

Employee and sales representative data.

Key Columns:

employeeNumber (PK)

firstName

lastName

email

officeCode

reportsTo

jobTitle

🏢 offices

Office location information.

Key Columns:

officeCode (PK)

city

country

phone

territory
