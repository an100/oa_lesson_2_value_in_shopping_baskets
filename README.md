Value in Shopping Baskets
==============================
Datasets and example code for Lesson 2 in Oracle Academy's Data Science Bootcamp.  Sample shopping baskets are stored as XML in **new_market_basket_sample.xml**.  All commands (include HiveQL statements) are in **market_basket_commands.txt**.  The pairwise UDF is contained in **pairwise.jar**, with the source and build script in the **pairwise** directory.  The **olh** directory contains scripts and loader maps for using *Oracle Loader for Hadoop* to load basket data in to Oracle Database for use with Oracle Data Mining.

For this lesson, the sequence of events is:

1. Copy the data in **new_market_basket_sample.xml** to HDFS
2. Use the commands in **market_basket_commands.txt** and the **pairwise.jar** to expose frequently used pairs and explore the XML data.
3. Optional: examine and modify the source of *pairwise* to provide a UDF for handle item triples.
4. Optional: use OLH and Oracle Data Mining to load transactions into Oracle Database and run the *a priori* algorithm.