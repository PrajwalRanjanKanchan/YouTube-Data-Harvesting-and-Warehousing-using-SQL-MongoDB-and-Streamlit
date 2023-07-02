# YouTube-Data-Harvesting-and-Warehousing-using-SQL-MongoDB-and-Streamlit

To solve the given problem statement, you can follow the steps outlined below using Python and the required libraries:

Install the necessary packages:

Install streamlit for creating the web application.
Install pymongo for interacting with MongoDB.
Install google-api-python-client for accessing the YouTube API.
Install mysql-connector-python for connecting to MySQL.
Obtain API credentials:

Go to the Google Developers Console and create a new project.
Enable the YouTube Data API for your project and generate API credentials (API key).
Note down the API key for later use.
Set up the Streamlit application:

Import the required libraries (streamlit, pymongo, googleapiclient).
Create the Streamlit app using streamlit library.
Set up the necessary Streamlit UI components like input fields, buttons, and tables.
Retrieve data from the YouTube API:

Use the googleapiclient library to authenticate and create a YouTube API client.
Implement a function to fetch data from the YouTube API based on the provided channel ID.
Fetch data such as channel details, video details, likes, dislikes, and comments.
Store data in MongoDB:

Create a connection to MongoDB using pymongo.
Implement a function to store the retrieved data in a MongoDB collection.
Migrate data to SQL database:

Create a connection to the MySQL database using mysql.connector.
Implement a function to migrate data from the MongoDB collection to SQL tables.
Query data from the SQL database:

Implement functions to execute SQL queries on the MySQL database and retrieve the required data.
Display data in the Streamlit app:

Implement the necessary Streamlit components to display the retrieved data from SQL.
