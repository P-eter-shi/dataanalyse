E-commerce Database Design

### 1. Ecommerce ERD

* Clearly define all entities (tables) and their attributes
* Identified relationships between tables
* Specified primary keys, foreign keys, and constraints
* Used:
  * draw.io

### 2. Plan of  the Data Flow

* Data flows between entities , connected through keys
* Design with scalability and clarity in mind



---

## Database Tables

E-commerce platform tables:

* **Product_image**
  Stores product image URLs or file references

* **Color**
  Manages available color options

* **Product_category**
  Classifies products into categories (e.g., clothing, electronics)

* **Product**
  Stores general product details such as name, brand, and base price

* **Product_item**
  Represents purchasable items with specific variations

* **Brand**
  Stores brand-related information

* **Product_variation**
  Links a product to its variations (e.g., size, color)

* **Size_category**
  Groups sizes into categories (e.g., clothing sizes, shoe sizes)

* **Size_option**
  Lists specific sizes (e.g., S, M, L, 42)

* **Product_attribute**
  Stores custom product attributes (e.g., material, weight)

* **Attribute_category**
  Groups attributes into categories (e.g., physical, technical)

* **Attribute_type**
  Defines attribute data types (e.g., text, number, boolean)

## Relationships and directionality
  - **one-to-many**: Single
  - **one-to-one**: Biderectional
  - **Multiple fact tables are present**
       

 

