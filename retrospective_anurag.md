### Project Retrospective - P3
Provide answers to the following questions and submit a PDF via Canvas. Be sure to answer the questions completely and explain your logic.

#### You’ve now had the chance to work with both MapReduce and Spark. In your opinion, what are the pros and cons of both?
MapReduce is more akin to key-value pair, and can sole queries and operation that work on rows.
On the other hand, Spark is based on RDD, and is suited to queries and operation that work on columns.

As such, MapReduce is good for fine grained queries. And spark is good for coarse queries and operations.
Spark keeps dataset in memory, so it can perform operations better.

#### Was there something that you thought would be easy to implement in Spark but it turned out that it wasn’t?
Yes looping over all cells of a column was a bit tricky. 

#### Were there any confusing or surprising aspects of working with Spark? Did you come across some functionality that made your life easier or the computations run faster?
Taking smaller (as much as required) subsets of full data.

#### Give a rough estimate of how long you spent completing this assignment. What part of the assignment took the most time?
I spent approx 40 hours to finish this project.
#### What went well?
Writing queries to get insight from data is a wonderful feeling. Learnt how to use regression. Charting library was easy to use once we got the hang of it.
#### What didn’t go well?
Implementing K-mean cluster in Spark, was hard. Also, had trouble with one hot encoding.

Team Questions
If you worked in a team, answer the following:

#### How did you decide to divide up the workload and coordinate with your team?
We had completed questions together.

#### Describe the questions or deliverables completed by each team member:
We focused to completing questions one by one and both were sitting on the same system.
