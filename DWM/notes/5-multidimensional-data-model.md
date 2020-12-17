# Multidimensional Data Model

# Content

- [Multidimensional Data Model](#multidimensional-data-model)
- [Content](#content)
  - [Previous Year Questions](#previous-year-questions)
    - [Short](#short)
    - [Long](#long)
  - [Topics](#topics)
    - [Multi-Dimensional Data Model](#multi-dimensional-data-model)
      - [REFERENCES](#references)

## Previous Year Questions

### Short

1. What is multidimensional data? Give two examples.
2. What is Star Schema? `2 times`
3. Briefly discuss the Snowflake schema.

### Long

1. Explain the various schemas for multidimensional data model `3 times`
2. What is multidimensional data model? Discuss the schemas for multidimensional data.
3. Explain Star & Snowflake database schema in detail. Also construct a fact table of star schema. `2 times`
4. Differentiate star and snowflake schemas of warehouse.
5. Write a detailed note on fact constellation, its advantages and related concepts.

## Topics

### Multi-Dimensional Data Model

- views data in the form of a data-cube
- A data cube enables data to be modeled and viewed in multiple dimensions. It is defined by dimensions
  and facts.
- The dimensions are the perspectives or entities which an organization keeps records
- **For example**, a shop may create a sales data warehouse to keep records of the store's sales for
  the dimension time, item, and location.
- These dimensions allow the save to keep track of things, for example, monthly sales of items and
  the locations at which the items were sold.
- Each dimension has a table related to it, called a dimensional table, which describes the
  dimension further. For example, a dimensional table for an item may contain the attributes
  item_name, brand, and type.
- A multidimensional data model is organized around a central theme, for example, sales. This theme
  is represented by a fact table.

#### REFERENCES

- [www.javatpoint.com](https://www.javatpoint.com/data-warehouse-what-is-multi-dimensional-data-model)
