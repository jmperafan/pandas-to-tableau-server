# How to publish Pandas DataFrames to Tableau Server
<p>By <a href="https://www.linkedin.com/in/jmperafan/">Juan Manuel Perafan</a></p>

Tableau Server has many data governance features to promote exploration, collaboration, and security. Out of all of them, my favorite by far is the Data Server.

The Data Server is a powerful, but often underutilized, feature that allows you to publish certified data sources directly to Tableau Server. These data sources can be analyzed with Tableau Web Edit or directly in Tableau Desktop. There numerous benefits of using the Data Server:

- **User friendly**: Empowering your business users to use analyze this data Tableau without having to understand how to connect to a database, join tables, or write difficult calculations. 
- **Single Version of the Truth**: It removes the risk of ambiguity for important data versions of your data sources and ensures people use the right calculations and logic. 
- **Security**: It allows you to implement row-level security and allows you to monitor who sees what data.  

In my career, I have prepared a couple dozen datasources in Tableau Desktop for other analysts to explore in Tableau Server. This process might involve a lot of manual work and prone to errors. Additionally, there are some use cases (not many, but some) that might not be possible or extremely tedious in Tableau. Some examples include:

- The IN operator from SQL
- Proper case for strings
- Regex lookup from right to left
- Prediction output from a Machine Learning Model
- Row_number or index without a Table Calculation
- Tokenizing strings
- Removing columns if all of the values are NULL

But what if I told you that you can wrangle your data in Python and publish the output as a hyper extract in your Tableau Server? Follow the instructions if you want to learn how!

<a href="https://www.linkedin.com/feed/hashtag/juanalytics/">#juanalytics</a>

<p><img src="https://www.blastam.com/wp-content/uploads/tableau-python-forecast.png" alt="";></p>
