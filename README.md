# NoSql-Challenge: The UK Food Standards Agency Evaluation:

**Overview:**

Within this assignment, I learned how to use MongoDB and Pymongo to one extract data from json file and then run analysis using Pymongo query in understanding UK restaurant data. While conducting these analysis, the following things were focused on:

**<ins> Key Learnings: </ins>**
* **Part 1: Database and Jupyter Notebook Set Up**
  * Establish database and collections within the system
  * Ensure collections and database are validated using find_one() and pprint queries
* **Part 2: Update the Database**
  *  Insert Penang flavors into dataframe
  * Update Penange flavors Business Type by 1) querying what type of business id is needed and 2) updaing database to B-ID: 1
  * Deleting Dover documents
  * Updating Lat & Long to decimal (using update_many),which is used in next section
* **Part 3: Exploratory Analysis**
  * Run queries on multiple questions to understand rating, hygiene and local related questions
  * Use various operators such as regex, eg, greater than or less than and more to filter data
  * Convert data to dataframe for easier pandas analysis
  * Using aggregrate, pipeline and sorting methods to narrow down queries 
