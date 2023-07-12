# Class11 Read Database and Schemas

- ## what is the Schema

    - Database Schema is defined as a how the data orginized withing a realtion in the database. inlcusive of logical constriant such as table names and firleds and data types and the relationship between these entities.

    - commonly it use a visual representaions to communicate the architecture of the database .

   - A database schema is considered the “blueprint” of a database which describes how the data may relate to other tables or other data models. However, the schema does not actually contain data.

   -  It can be categorized into three parts (Physical Schema, Logical Schema, View Schema)

- ## Why do we use them 
    
    - Access and security: Database schema design helps organize data into separate entities, making it easier to share a single schema within another database. 
    Administrators can also control access through database permissions, adding another layer of security for more proprietary data

    - Organization and communication: Documentation of database schemas allow for more organization and better communication among internal stakeholders. 

    - Integrity: This organization and communication also helps to ensure data validity. For example, it can help administrators manage normalization processes to avoid data duplication.

- ## How it looks like 

    ``` 
    - Table: Customers

    | customer_id | first_name | last_name | email             |
    |-------------|------------|-----------|-------------------|
    | 1           | John       | Doe       | example@email.com |
    | 2           | Jane       | Smith     | ex.ample@email.com |

    - Table: Orders

    | order_id | customer_id | order_date |
    |----------|-------------|------------|
    | 1        | 1           | 2023-07-01 |
    | 2        | 2           | 2023-07-05 |

    ```

- ## What is a Primary Key?

    - A primary key is a column or group of columns in a database table that uniquely identifies each row in a table. The primary key must contain a unique values for each row in the table, which means it cannot have a two rows have the same value in the same table.
     in the table above the customer_id in table customers it can be as a primary key.


    - A Foreign key : is a column or a group of columns in a database table that references the primary key of another table. Foreign keys are used to establish relationships between tables and to ensure the referential integrity of data.
     in the table above the customer_id in table orders it can be as a foreign key.

    - What is a Composite Key: is a group of columns that together uniquely identify each row in a table. Composite keys are often used when the primary key of a table is not a single column, but rather a combination of columns. For example, a table of customers might have a composite key consisting of the customer's first name, last name, and address. This would ensure that each customer is uniquely identified, even if there are two customers with the same first and last name.
     in the table above the customer_id in table customers the email can be a composite key while the customer_id is the primary key this means there is only one customer with this email here. 


    - Primary keys, foreign keys, and composite keys are all important concepts in database design. Primary keys are used to uniquely identify each row in a table, foreign keys are used to establish relationships between tables, and composite keys are used when the primary key of a table is a combination of columns.

- ## What are Relationships in a relational database?

    - A relationship in a relational databas is a conncetion between two or more tables. the tables are connected by a common field which is  a foriegn key.

    - A 1:1 : is a relationship between two tabels where each row in one row is related to exactly one row on the other table.

    - A Many:Many : is a relationship between two tables where each row in multiple rows is related to more than one (multiple) row in the other table and vice versa.
    
    - A 1:Many : is a relationship between two tables where each row in multiple rows is related to a multiple row in the other table, but each row in other table can be related to exaclty one row from the first table. 

     - A Many:1 : is a relationship between two tables where each row in multiple rows is related to at most one record (row) of another table. but each row in the other table can be related to multiple rows in the first table. 
