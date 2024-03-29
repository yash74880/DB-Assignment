## Answers


1.  The relationship between the "Product" and "Product_Category" entities is likely a one-to-many relationship, where one product can belong to only one category, but a category can have multiple products. This relationship is established through the "category_id" attribute in the "Product" table, which likely serves as a foreign key referencing the primary key "id" in the "Product_Category" table.
2.  To ensure that each product in the "Product" table has a valid category assigned to it, we can enforce referential integrity by setting up a foreign key constraint between the "category_id" column in the "Product" table and the primary key "id" column in the "Product_Category" table. This constraint will ensure that every value in the "category_id" column of the "Product" table must exist in the "id" column of the "Product_Category" table, preventing the insertion of invalid category IDs.
    
