## Introduction
This repository aims to be a portfolio of my work during the 'Applied Data Science With Python' specialization held by the University of Michigan on Coursera. It also serves me as a quick reminder of some awesome tricks that I have used for data cleaning and analysis.

A big thank you to Professor Cristopher Brooks of the University of Michigan. Thanks for creating a data science specialization that guides the student to find his own tools for solving real data science problems!

The specialization consists of the following courses:
* Introduction to Data Science in Python
* Applied Plotting, Charting & Data Representation in Python
* Applied Machine Learning in Python
* Applied Text Mining in Python
* Applied Social Network Analysis in Python

For each course in part, I have condensed all the assignments in one major notebook for easier visualization.


### Course 1: Introduction to Data Science in Python
This course showed me how to take tabular data, clean it,  manipulate it, and run inferential statistical analyses on it. I had to complete three different assignments during this course. They were really awesome as it required a lot of individual learning which makes the learning more memorable for future tasks. Here is a basic description of each assignment completed:
* **Data Processing with Pandas and Numpy**

This assignment introduced data manipulation and cleaning techniques using the popular python pandas data science library and introduced the abstraction of the DataFrame as the central data structure for data analysis.
* **Advanced Pandas usage**

In this assignment I was asked to use pandas to answer more difficult questions. I definitely feel that I have learned a lot on this assignment as I had to search and investigate a lot of issues on StackOverflow. This made my knowledge of this library stronger as I had spent quite a few time analysing its different functions.
* **Statistical analysis in Python - hypothesis testing**

In this assignment I was asked to conduct a hypothesis testing using three different datasets. It gave me a glimpse on how I could run inferential statistical analyses.

### Course 2: Applied Plotting, Charting & Data Representation in Python
This course introduced me to information visualization basics, with a focus on reporting and charting using the matplotlib library. The course started with a design and information literacy perspective, touching on what makes a good and bad visualization, and what statistical measures translate into in terms of visualizations. It also introduced me to the best practices when creating new charts and how to realize design decisions in the framework.

To pass this course, I had to complete 3 assignments. Here is a short description of each assignment in part:
* **Plotting Weather Patterns**

In this assignment, I worked with real world CSV weather data. I had to manipulate the data to display the minimum and maximum temperature for a range of dates and demonstrate that I know how to create a line graph using matplotlib. Additionally, I overlayed a scatter plot of record breaking data for a particular year.

* **Building a custom visualization**

For this assignment I had to implement a visualization of sample data as described in Ferreria et al. (2014). I had implemented the bar coloring as described in the paper, where the color of the bar is actually based on the amount of data covered (a gradient ranging from dark blue for the distribution being certainly below this y-axis, to white if the value is certainly contained, to dark red if the value is certainly not contained as the distribution is above the axis). I chose the 'Even Harder' option in which I had to make the plot interactive, allowing the user to click on the y axis to set the value of interest. The bar colors change with respect to what value the user has selected.

* **Becoming an independent data scientist**

This assignment required to identify at least two publicly accessible datasets that are consistent across a meaningful dimension. I had to state a research question that can be answered using these datasets and then create a visual using matplotlib that addresses the stated research question. I also had to justify how the visual addresses my research question. As this assignment was for the whole course, I had to incorporate and defend the principles discussed in the first week and align with Cairo’s principles of truth, beauty, function, and insight.

### Course 3: Applied Machine Learning in Python
This course focused on the fundamentals of machine learning. It has taught me how to identify which machine learning algorithm is more suitable for a particular dataset and how to engineer features and write Python code to build, train and test ML models.

Here is a short description of the assignments that I had during this course:
* **Introduction to machine learning**

In this assignment I've used the Breast Cancer Wisconsin Database to create a classifier that can help diagnose patients.

* **Supervised machine learning**

This assignment was split into parts: regression and classification. In the first part I've fitted the data using Linear Regression and Lasso Regression. For the second part I've worked with the UCI Mushroom Data Set to train a model to predict whether or not a mushroom is poisonous.

* **Evaluation**

In this assignment I have trained several models and evaluated how effectively they predict instances of fraud, using Support Vector Machines and Logistic Regression.

* **Understanding and predicting property maintenance fines**

For this assignment, my task was to predict whether a given blight ticket will be paid on time. I have obtained an AUC score of 0.809 on the test dataset, using Gradient Boosted Trees.

### Course 4: Applied Text Mining in Python
In this course I've learned how to use regular expressions to search for text and how to clean and prepare it for use by machine learning algorithms.
I've also learned how to apply basic natural language processing methods to text, and demonstrate how text classification is accomplished. The final week of the course focused on exploring more advanced techniques such as detecting topics in documents and topic modelling.

To pass this course, I had to complete 4 assignments. Here is a short description of each assignment in part:
* **Cleaning messy medical data**

In this assignment, I had to use *Pandas* and *regex* to clean and extract relevant information from medical notes. The final objective was to correctly identify all of the different date variants encoded in this dataset and to properly normalize and sort the dates.

* **Introduction to NLTK**

This assignment was structured in two parts. In the first part of this assignment I've explored the Herman Melville novel Moby Dick with *nltk*. In the second part of the assignment, I have created a spelling recommender function that uses *nltk* to find words similar to the misspelling.

* **Spam classifier**

In this assignment, I've created a model to predict if a text message is spam or not. This assignment required  knowledge on both text mining as well as machine learning.

* **Document similarity & topic modelling**

This assignment was split in two parts. In the first part of the assignment, I've created two functions *doc_to_synsets* and *similarity_score* to find the path similarity between two documents. In the second part of the assignment, I've used Gensim's LDA (Latent Dirichlet Allocation) model to model topics in text data.

### Course 5: Applied Social Network Analysis in Python
During this course I've learned the principles of network analysis through tutorials using the NetworkX library. I've also learned about more advanced topics such as network generation and link prediction.

I have finished the following assignments during the practical sessions of this course:
* **Creating and manipulating graphs**

In this assignment, I've acquired experience in creating bipartite graphs, how to add node attributes and how to find a weighted projection of the graph.

* **Network Connectivity**

For this assignment I've analyzed the internal email communication network between employees of a mid-sized manufacturing company.

* **Influence Measures and Network Centralization**

In this part of the assignment I've computed various measures of centrality on two networks: *a friendship network in Part 1*, and a *blog network in Part 2*.

* **Network Evolution**

This assignment was split in two parts. In the first part of the assignment I've analyzed randomly generated graphs and determined which algorithm created them. For the second part of this assignment I've worked with a company's email network to predict salaries and new connections.

Overall, I am very grateful for finishing this specialization as I believe it made me a better data scientist. And of course, I will be forever grateful for the amazing platform Coursera on which this specialization takes place. 
