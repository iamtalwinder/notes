# Topic

# Content

- [Topic](#topic)
- [Content](#content)
  - [Previous Year Questions](#previous-year-questions)
    - [Short](#short)
    - [Long](#long)
  - [Topics](#topics)
    - [Data pre-processing](#data-pre-processing)
    - [Steps Involved in Data Preprocessing](#steps-involved-in-data-preprocessing)
      - [Data Cleaning](#data-cleaning)
      - [Data Integration](#data-integration)
      - [Data reduction](#data-reduction)
      - [Data transformation](#data-transformation)
      - [REFERENCES](#references)

## Previous Year Questions

### Short

1. What is data summarization?
2. Why data summarization and Data cleaning is done?
3. What is data cleaning? Why is it important
4. Why Data Transformation is done?

### Long

1. What do you mean by data pre-processing? Explain the various stages in the
   process of data pre-processing.
2. What are the various designs Consideration of a Data Warehouse? Why data summarization and
   Data cleaning is done?
3. What do you mean by cleaning of data? Explain the important types of data cleaning.

## Topics

### Data pre-processing

- It is a data mining technique that transforms raw data into an understandable format.
- Real-world data is often incomplete, inconsistent, lacking in certain behaviors or trends,
  and is likely to contain many errors.
- **For example** out-of-range values (e.g. Income: −100), impossible data combinations
  (e.g. Sex: Male, Pregnant: Yes), and missing values.
- Data preprocessing is a proven method of resolving such issues. Data preprocessing prepares
  raw data for further processing.
- Data preprocessing is used in database-driven applications such as customer relationship
  management and rule-based applications (like neural networks).
- In Machine Learning (ML) processes, data preprocessing is critical to encode the dataset
  in a form that could be interpreted and parsed by the algorithm.

### Steps Involved in Data Preprocessing

#### Data Cleaning

The data can have many irrelevant and missing parts. To handle this part, data cleaning is done.
It involves handling of missing data, noisy data etc.

1.  **Missing Data:**
    This situation arises when some data is missing in the data. It can be handled in various ways.
    Some of them are:

    - **Ignore the tuples:**
      This approach is suitable only when the dataset we have is quite large and multiple values are
      missing within a tuple.
    - **Fill the Missing values:**
      There are various ways to do this task. You can choose to fill the missing values manually,
      by attribute mean or the most probable value.

2.  **Noisy Data:**
    Noisy data is a meaningless data that can’t be interpreted by machines. It can be generated due
    to faulty data collection, data entry errors etc. It can be handled in following ways:

    - **Binning Method:**
      This method works on sorted data in order to smooth it. The whole data is divided into segments of equal size and then various methods are performed to complete the task. Each segmented is handled separately. One can replace all data in a segment by its mean or boundary values can be used to complete the task.
    - **Regression:**
      Here data can be made smooth by fitting it to a regression function.The regression used may be linear (having one independent variable) or multiple (having multiple independent variables).
    - **Clustering:**
      This approach groups the similar data in a cluster. The outliers may be undetected or it will fall outside the clusters.

#### Data Integration

Since data is being collected from multiple sources, data integration has become a vital part of the process. This may lead to redundant and inconsistent data, which could result in poor accuracy and speed of data model. To deal with these issues and maintain the data integrity, approaches such as tuple duplication detection and data conflict detection are sought after. The most common approaches to integrate data are explained below.

1. **Data consolidation:** The data is physically bought together to one data store. This usually involves Data Warehousing.
2. **Data propagation:** Copying data from one location to another using applications is called data propagation. It can be synchronous or asynchronous and is event-driven.
3. **Data virtualization:** An interface is used to provide a real-time and unified view of data from multiple sources. The data can be viewed from a single point of access.

#### Data reduction

The purpose of data reduction is to have a condensed representation of the data set which is smaller in volume, while maintaining the integrity of original. This results in efficient yet similar results. A few methods to reduce the volume of data are:

1. **Missing values ratio:** Attributes that have more missing values than a threshold are removed.
2. **Low variance filter:** Normalized attributes that have variance (distribution) less than a threshold are also removed, since little changes in data means less information.
3. **High correlation filter:** Normalized attributes that have correlation coefficient more than a threshold are also removed, since similar trends means similar information is carried. Correlation coefficient is usually calculates using statistical methods such as Pearson’s chi-square value etc.

#### Data transformation

The final step of data preprocessing is transforming the data into form appropriate for Data Modeling. Strategies that enable data transformation include:

1. **Attribute/feature construction:** New attributes are constructed from the given set of attributes.
2. **Aggregation:** Summary and Aggregation operations are applied on the given set of attributes to come up with new attributes.
3. **Normalization:** The data in each attribute is scaled between a smaller range e.g. 0 to 1 or -1 to 1.
4. **Discretization:** Raw values of the numeric attributes are replaced by discrete or conceptual intervals, which can in return be further organized into higher level intervals.
5. **Concept hierarchy generation for nominal data:** Values for nominal data are generalized to higher order concepts.

#### REFERENCES

- [www.techopedia.com](https://www.techopedia.com/definition/14650/data-preprocessing)
- [www.developer.ibm.com](https://developer.ibm.com/technologies/data-science/articles/data-preprocessing-in-detail/)
- [www.wikipedia.org](https://en.wikipedia.org/wiki/Data_pre-processing)
