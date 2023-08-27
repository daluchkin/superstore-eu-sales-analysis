# Sales data analysis - Superstore EU

![alt text](https://github.com/daluchkin/sales-superstore-eu/blob/main/Dashboard.png?raw=true)

## Requirements

* Activated Microsoft Power Pivot for Excel COM Add-in.
* Microsoft Excel for OS Windows.
* Dashboard does not work in Excel on MacOS as it does not have Power Pivot COM Add-in.


## Process of analysis

Was implemented the following steps:

1. Identify business questions.
1. Collect and store data.
1. Clean and prepare data. 
1. Analyze data.
1. Visualize and communicate data.


## Dataset

Dataset of Superstore EU contains the following tables:


### Table "Orders"

| Variable name | Data type | Description |
|---|---|---|
| Row ID | `Integer` | Unique ID for each row. |
| Order ID | `String` | Unique Order ID for each Customer. |
| Order Date | `Date` | Order Date of the product. |	
| Ship Date | `Date` | Shipping Date of the Product. |
| Ship Mode | `String` | Shipping Mode specified by the Customer. |
| Customer ID | `String` | Unique ID to identify each Customer. |
| Customer Name	| `String` |  Name of the Customer.|
| Segment | `String` |  The segment where the Customer belongs. |
| City | `String` | City of residence of of the Customer. |
| State/Province | `String` | State of residence of the Customer. |
| Country/Region | `String` | Country of residence of the Customer. |	
| Region | `String` | Region where the Customer belong. |
| Product ID | `String` | Unique ID of the Product. |
| Category | `String` | Category of the product ordered. |
| Sub-Category | `String` | Sub-Category of the product ordered. |
| Product Name | `String` | Name of the Product |
| Sales | `Decimal` | Sales of the Product. |
| Quantity | `Integer` | Quantity of the Product. |
| Discount | `Decimal` | Discount provided. |
| Profit | `Decimal` | Profit/Loss incurred. |


### Table "Returns"

| Variable name | Data type | Description |
| --- | --- | --- |
| Order ID | `String` | Unique Order ID for each Customer. |
| Returned | `Bool` | The flag, indicates that the order was returned. |


### Table "People"

| Variable name | Data type | Description |
| --- | --- | --- |
| Region | `String` | Region where the Customer belong. |
| People | `String` | The name of sales manager. |



