# OLAP & OLTP & OLAM

# Content

- [OLAP & OLTP & OLAM](#olap--oltp--olam)
- [Content](#content)
  - [Previous Year Questions](#previous-year-questions)
    - [Short](#short)
    - [Long](#long)
  - [Topics](#topics)
    - [Online Analytical Processing (OLAP)](#online-analytical-processing-olap)
      - [REFERENCES](#references)
    - [Purpose of OLAP](#purpose-of-olap)
      - [REFERENCES](#references-1)
    - [How OLAP works?](#how-olap-works)
      - [REFERENCES](#references-2)
    - [OLAP Application](#olap-application)
      - [Finance and accounting:](#finance-and-accounting)
      - [Sales and Marketing](#sales-and-marketing)
      - [Production](#production)
      - [REFERENCES](#references-3)
    - [OLAP Operation `important`](#olap-operation-important)
      - [Roll up](#roll-up)
      - [Roll down](#roll-down)
      - [Slice](#slice)
      - [Dice](#dice)
      - [Pivot](#pivot)
      - [REFERENCES](#references-4)

## Previous Year Questions

### Short

1. What is OLAP data warehouse?
2. What is Indexing & Querying in OLAP? `2 times`
3. Differentiate OLAP & OLTP
4. What are the storage models of OLAP?
5. What is OLAM? How is it different from OLAP?
6. What are OLAP & OLTP?

### Long

1. What is OLAP? Discuss the architecture of OLAP in detail.
2. What is OLAP and OLTP? Differentiate OLAP and OLTP. `important`
3. Define and compare OLAP and OLTP. Discuss the various OLAP operations with
   examples. `2 times` `important`
4. Explain the following with proper examples :
   1. Hyper cubes
   2. ROLAP and MOLAP

## Topics

### Online Analytical Processing (OLAP)

- approach to answer multi-dimensional analytical (MDA) queries swiftly in computing
- aid in trends analysis, financial reporting, sales forecasting, budgeting and other
  planning purposes.

#### REFERENCES

- [www.wikipedia.org](https://en.wikipedia.org/wiki/Online_analytical_processing)
- [www.searchdatamanagement.techtarget.com](https://searchdatamanagement.techtarget.com/definition/OLAP)

### Purpose of OLAP

- provide business users with a data model more intuitive to them than a
  tabular model. This model is called a Dimensional Model.
- enable fast query response that is usually difficult to achieve using
  tabular models.

#### REFERENCES

- [www.javatpoint.com](https://www.javatpoint.com/what-is-olap)

### How OLAP works?

- It pre-calculates most of the queries that are typically very hard to execute over
  tabular databases, namely aggregation, joining, and grouping.
- This process is usually called 'building' or 'processing' of the OLAP cube.
- This process happens overnight, and by the time end users get to work - data will have been
  updated.

#### REFERENCES

- [www.javatpoint.com](https://www.javatpoint.com/what-is-olap)

### OLAP Application

#### Finance and accounting:

- Budgeting
- Activity-based costing
- Financial performance analysis
- And financial modeling

#### Sales and Marketing

- Sales analysis and forecasting
- Market research analysis
- Promotion analysis
- Customer analysis
- Market and customer segmentation

#### Production

- Production planning
- Defect analysis

#### REFERENCES

- [www.javatpoint.com](https://www.javatpoint.com/what-is-olap)

### OLAP Operation `important`

#### Roll up

- Also known as consolidation, or drill-up, this operation summarizes the data along the
  dimension.
- Performs aggregation on a data cube, by climbing up concept hierarchies, i.e., dimension
  reduction.
- It is like zooming-out on the data cubes.
- Example:
  <br />
  <p align="center">
    <img src="./imgs/roll-up.png" alt="roll-up">
  </p>

#### Roll down

- is a technique that allows users to navigate through the details.
- it navigates from less detailed record to more detailed data
- can be performed by either stepping down a concept hierarchy for a dimension or adding
  additional dimensions.
- Example:
  <br />
  <p align="center">
    <img src="./imgs/roll-down.png" alt="roll-down">
  </p>

#### Slice

- This enables an analyst to take one level of information for display
- A slice is a subset of the cubes corresponding to a single value for one or more members
  of the dimension.
- Example:
  <br />
  <p align="center">
    <img src="./imgs/slice.png" alt="slice">
  </p>

#### Dice

- describes a subcube by operating a selection on two or more dimension.
- Example:
  <br />
  <p align="center">
    <img src="./imgs/dice.png" alt="dice">
  </p>

#### Pivot

- also called a rotation
- visualization operations which rotates the data axes in view to provide an
  alternative presentation of the data.
- It may contain swapping the rows and columns or moving one of the row-dimensions
  into the column dimensions.
- Example:
  <br />
  <p align="center">
    <img src="./imgs/pivot.png" alt="pivot">
  </p>

#### REFERENCES

- [www.javatpoint.com](https://www.javatpoint.com/olap-operations)
- [www.searchdatamanagement.techtarget.com](https://searchdatamanagement.techtarget.com/definition/OLAP)
- [www.wikipedia.org](https://en.wikipedia.org/wiki/Online_analytical_processing)
