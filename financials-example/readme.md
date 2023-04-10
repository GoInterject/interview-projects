# USA Economic Data
All data for this test comes from the SEC and can be researched and reviewed on their site: https://www.sec.gov/dera/data/financial-statement-data-sets.

<br>
<br>

Why is this data in this test? At Interject we work with clients across many industries building reports with datasets we have not directly encountered before. This requires us to be able to explore their data, reporting use cases and design an engineered solution that meets their goals and applies to "their world". This test aims to simulate that experience in an isolated project. SEC data is public, widely impactful and researchable with many tools and documentation making it a more ideal version of interject client projects.

Use the data, docs and tools provided in this folder to work with the data and get valuable insights and usable reports from it! That IS our world; Good Luck! 😊


<br>
<br>

# The Data
- Download the SEC data from HERE: https://www.sec.gov/dera/data/financial-statement-data-sets. Pick a year and quarter and unzip the dataset.
  - Alternatively use the pre-cached dataset from the SEC for 2022Q4 HERE: https://drive.google.com/file/d/1On4mrbcEl_GkQ9zveRYyXZmaNye_kH4E/view?usp=share_link
- The follow the goals and todos listed below. attempt to complete as many of the bullets as you can. no one right answer exists


<br>
<br>
<br>


# Goals and Todos
- research the data! use the readme.htm file to get an idea of what the data means
- write a sql\python script to create tables for the csv files in a SQL database (ie SQlite, DuckDB, SQL Server, etc...). also write code to ingest the csv data into those tables
- **Queries & Analysis Questions**
  - **FILTERING**: write sql or python to get the top 10 most recent submission registrants who had a name change (ie see the "Former" column in Subs) 
  - **SQL JOIN**: pick a security (submission) and write a SQL statement to join the security on all its financial statement line items (ie from the NUM dataset).
  - **SQL AGGREGATION**: create a sql query that aggregates all submissions (ie accession numbers) by the sum of the line item values to show the total of their financial statement. generally positive values are good and negative ones indicate a submitter is losing money.
  - **CLUSTERING**: are registrants distributed or do some geographic locations contain significantly higher amounts of registrants?
  - what other insights from the data can you find?
- **Reporting**
  - create a simple Streamlit app (https://streamlit.io/) to display some of your analysis queries in a table format that could be presented to a client as a report\dashboard. be creative and think about data presentation that would make sense to a non-technical person. there is no right answer here.
- Write a brief markdown or text file explaining your approach and findings from the project. if you used specific Ai tools, IDE extensions, python frameworks or notable SQL functions that helped you in this project please mention them and how they helped you! that can help our team learn and grow too! 


<br>
<br>

# Guide
- review the data's readme file. It explains the 4 csv file datasets and can help understanding of what the data means. This is similar to clients who sometimes give us docs about their datasets or environment which help us prepare a solution for them.