# YouTube Data Harvesting and Warehousing

This project aims to harvest data from YouTube using the YouTube Data API, process it using Pandas, store it in a SQL database, and visualize it using Streamlit.

## Overview

YouTube is one of the largest platforms for sharing video content. This project allows users to collect data about YouTube videos, such as video metadata, statistics, and comments, and store it in a structured SQL database. The data can then be analyzed and visualized using Streamlit, providing insights into trends, popular content, and user engagement on the platform.

## Features

- Harvest YouTube data including video metadata, statistics, and comments.
- Clean and process the harvested data using Pandas.
- Store the processed data in a SQL database for easy retrieval and analysis.
- Visualize the data using Streamlit to gain insights and explore trends.
- Interactive dashboard for exploring YouTube video analytics.

## Installation

1. Clone the repository:

    ```
    git clone https://github.com/NaveenRoy5800/Youtube-data-harvesting-and-warehousing-using-SQL.git
    ```

2. Install dependencies:

    ```
    pip install -r requirements.txt
    ```

3. Set up YouTube Data API credentials by following the instructions in [YouTube Data API documentation](https://developers.google.com/youtube/v3/getting-started).

4. Set up a SQL database (e.g., MySQL, PostgreSQL) and configure the connection.

5. Run the Streamlit app:

    ```
    streamlit run youtube_analysis.py
    ```

6. Access the Streamlit app in your browser at `http://localhost:8501`.

## Usage

1. Launch the Streamlit app by running `youtube.py`.
2. Use the app interface to specify parameters for data harvesting and analysis.
3. Explore the visualizations and insights provided by the app.

## Contributing

Contributions are welcome! If you would like to contribute to this project, please fork the repository and submit a pull request with your changes.
