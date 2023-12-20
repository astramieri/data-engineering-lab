# Data Pipelines Pocket Reference

- Title: Data Pipelines Pocket Reference
- Subtitle: Moving and Processing Data for Analytics
- Author: James Densmore
- Edition: O'Reilly 2021

## Notes

### Chapter 1 - Introduction to Data Pipelines

[Page 1] The famous phrase “data is the new oil” has proven true. Just like oil, the value of data is in its potential after it’s refined and delivered to the consumer. Also like oil, it takes efficient pipelines to deliver data through each stage of its value chain.

[Page 2] **Data pipelines are sets of processes that move and transform
data from various sources to a destination where new value can be derived**. They are the foundation of analytics, reporting, and
machine learning capabilities. [..] Data engineers specialize in building and maintaining the data pipelines that underpin the analytics ecosystem.

### Chapter 2 - A Modern Data Infrastructure

[Page 14] Three things transformed the landscape of analytics and data
warehousing over the last 10 years: [..] The **ease of building** and deploying data pipelines, data lakes, warehouses, and analytics processing in the cloud. [..] Continued **drop-in storage costs** in the cloud. [..] The emergence of **highly scalable columnar databases**.

[Page 14] A **Data Warehouse** is a database where data from different systems
is stored and modeled to support analysis. [..] Data in a data warehouse
is structured and optimized for reporting and analysis queries.

[Page 14] A **Data Lake** is where data is stored, but without the structure or query optimization of a data warehouse. It will likely contain a
high volume of data as well as a variety of data types.

[Page 18] Pipeline steps are always directed, meaning they start with a general task or multiple tasks and end with a specific task or tasks. [..] Pipeline graphs must also be acyclic, meaning that a task cannot
point back to a previously completed task. In other words, it cannot cycle back. [..] With these two constraints in mind, orchestration pipelines produce graphs called **Directed Acyclic Graphs (DAGs)**.