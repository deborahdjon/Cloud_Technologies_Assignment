# YouTube Video Popularity Analysis Web Application

This web application was created as a group assignment by a team of 6 members.

**Link to Demo Video**: [Watch the Demo](https://www.youtube.com/embed/woDV2NUmlX8)

## General Description

This web application serves as a valuable reference for content creators and investors interested in analyzing YouTube video popularity. It provides users with the ability to browse video titles and categories using interactive data visualizations, including features such as world maps, date selection, and scatterplots for effective data filtering.

## Goals

The primary objectives of this web application are to answer critical questions related to YouTube video popularity, such as:

- What are the most popular videos by region that can be used for advertising?
- Which categories of YouTube videos are the most popular in a specific region?
- What are the categories of YouTube videos that users comment on the most?
- How do metrics like like count, dislike count, and comment count of a YouTube video relate to its overall popularity?

## Motivations

The application is designed with the aim of empowering both content creators and investors to make informed decisions. Here's how it can benefit these stakeholders:

- Content creators can use the insights gained from the application as a reference to focus on the right aspects when creating their videos.
- Investors can identify the best regions and content creators to invest in, enhancing their decision-making process.

## Dataset

The web application relies on a dataset sourced from Kaggle. This dataset contains historical data of trending YouTube videos and is available in both CSV and JSON formats.

## Technologies Used

The development and functionality of this web application are powered by various technologies:

- **Bash**: Regular automated data extraction
- **Python, PySpark, and Jupyter Notebooks**: Used in Google Cloud Dataproc Clusters for data cleaning and pre-processing
- **Google Cloud Storage**: To store the cleaned dataset
- **Google BigQuery**: Creating a connection between Data Studio and the final dataset
- **Google Data Studio**: For the creation of interactive and informative dashboards
- **Flask**: Development of the web application's user interface
- **Heroku**: Deployment of the web application for public access

## How to Use

To access the web application, simply visit [Application Link] and start exploring the exciting world of YouTube video popularity analysis!

---

Feel free to customize this README to include additional details, such as installation instructions, usage guidelines, and any additional features of your web application. This README will provide a clear overview of your project to visitors on your GitHub repository.

[)

To run the website application, follow the next steps:

1. Install neccesary dependencies: pip install -r requiremetns
2. Run script run.py: python run.py
