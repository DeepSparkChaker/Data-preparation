# Data-preparation
The process of preparing data for a machine learning algorithm has the following phases:

 •Data selection
 
 •Data preprocessing
 
     Steps overview
     1.Data cleaning: Complete missing values, smooth noisy data, identify or remove outliers, and resolve inconsistencies.
     2.Data integration: Using multiple databases, other data sources, or files.
     3.Data sampling: Faster for exploring and prototyping.
     4.Data dimensionality reduction: Reducing the volume but producing the same or similar analytical results.
     5.Data formatting: The data that you selected might not be in a format that is suitable for you to use.
 •Data transformation
 
     Steps overview
     Data transformation (also called feature engineering) is a set of actions that covers transformation of the processed data.
     Engineering features from your data can use some time, but they can enhance the machine learning performance. 
     There are three common data transformations:
     •Scaling: The pre-processed data may contain attributes with a mixture of scales for various quantities, such as meters,
     grams, and dollars. The features should have the same scale, for example, 0 (smallest value) to 1 (largest value).
     •Aggregation: There may be features that can be aggregated into a single feature, which is more meaningful to the problem
     that you are trying to solve.
     •Decomposition: There may be complex features where it is more useful to split into parts. For example, a feature
     representing a date and time stamp in a long format can be split out further into only the hour of the day. 
     Think about what your problem really needs.
 
==>Data preparation is one of the most important and often time-consuming aspects of data mining. In fact, it is estimated that data preparation usually takes 50-70% of a project's time and effort. Devoting adequate energy to the earlier business understanding and data understanding phases can minimize this overhead, but you still need to expend a good amount of effort preparing and packaging the data for mining.

Depending on your organization and its goals, data preparation typically involves the following tasks:

• Merging data sets and/or records

• Selecting a sample subset of data

• Aggregating records

• Deriving new attributes

• Sorting the data for modeling

• Removing or replacing blank or missing values

• Splitting into training and test data sets


==>Machine learning algorithms depend highly on the quality and quantity of data. It is important that you provide these algorithms the correct data. Data preparation is a large subject that can involve many iterations, exploration, and analysis. Becoming proficient at data preparation will make you a master at machine learning.
In this section, we cover basics tasks of the data preparation process: data selection, data preprocessing, and data transformation.
