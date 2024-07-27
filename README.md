YouTube Data Harvesting


Overview
This project involves retrieving data from YouTube channels using the Google API, storing it in MongoDB as a data lake, migrating and transforming the data into a SQLite database, and then querying and displaying the data using a Streamlit app.

Technologies Used:

Python
MongoDB
YouTube Data API
SQLite
Streamlit

Project Structure:

Youtube_15.py: Main script for the Streamlit app.
Youtube_logo.png: YouTube logo used for the app icon.
title.png: Title image for the home page.

Features:

Home: Displays project overview and technologies used.
Extract & Transform: Allows users to input a YouTube Channel ID, extract data, upload it to MongoDB, and transform it to SQLite.
View: Provides insights and answers to predefined questions based on the data in the SQLite database.

Setup Instructions:

Prerequisites
Python 3.x
MongoDB
SQLite
Installation

Clone the repository:

bash
Copy code
git clone https://github.com/yourusername/youtube-data-harvesting.git
cd youtube-data-harvesting

Install the required Python packages:

bash
Copy code
pip install -r requirements.txt
Set up MongoDB:

Ensure MongoDB is running on localhost:27017.

Create a new database named Youtube_Data_Sam.
Update the YouTube API Key:

Replace the api_key variable in the Youtube_15.py file with your YouTube API key.
Running the Application
Run the Streamlit app:

bash

Copy code
streamlit run Youtube_15.py

Usage
Home Page: Displays an overview of the project.

Extract & Transform:
Enter YouTube Channel ID(s) and click "Extract Data" to fetch channel details.

Click "Upload to MongoDB" to store the data in MongoDB.

Click "Submit" to transform and load the data into SQLite.

View Page: Select from predefined questions to get insights from the SQLite database.

Screenshots

Home Page
![image](https://github.com/user-attachments/assets/01770c27-8400-4e97-b226-19c0e9cba97b)

Extract & Transform Page
![image](https://github.com/user-attachments/assets/3827e4f1-ccb0-4b56-84c0-7314e263c0d6)


View Page
![image](https://github.com/user-attachments/assets/e2404091-cd14-491d-9295-e0a71f96832c)


Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

License
This project is licensed under the MIT License.

Acknowledgements
Google YouTube Data API
Streamlit
MongoDB
SQLite
