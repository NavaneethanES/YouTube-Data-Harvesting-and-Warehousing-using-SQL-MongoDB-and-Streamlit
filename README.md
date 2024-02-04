# YouTube Data Harvesting and Warehousing

## Overview
This project extracts data from YouTube channels using the YouTube Data API, stores it in a MongoDB database, and then transforms and loads it into a MySQL database. The data is then queried and displayed in a Streamlit app.

## Flow of the Project
1. **Extract Data from YouTube:**
   - Input the YouTube Channel ID.
   - Extracts channel details, video details, and comments using the YouTube Data API.
   - Data is stored in MongoDB.

2. **Transform Data to SQL:**
   - Select a channel from the MongoDB data.
   - Transform and load data into MySQL database tables.

3. **View Data Insights:**
   - Answer predefined questions about the data using SQL queries.
   - Visualize insights using Plotly in the Streamlit app.

## Libraries Used
- **Python**
- **MongoDB** for data lake storage
- **MySQL** for structured data storage
- **Streamlit** for creating the interactive web app
- **Plotly Express** for data visualization
- **Google API Client** for YouTube Data API
- **Pandas** for data manipulation
- **Pillow (PIL)** for image processing

## Usage
1. Clone the repository.
2. Install required libraries: `pip install -r requirements.txt`
3. Set up MongoDB and MySQL databases.
4. Add your YouTube Data API key.
5. Run the Streamlit app: `streamlit run py_script.py`
