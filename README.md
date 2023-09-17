# YT Channel Statistics Project

This project retrieves and analyzes YouTube channel statistics and video details using the YouTube Data API. The code is written in Python and utilizes various libraries such as pandas, seaborn, and the Google API client library.

## Project Overview

The goal of this project is to fetch statistics for specific YouTube channels and their videos. The project is divided into the following major steps:

1. **Fetching Channel Statistics**: Retrieve statistics for multiple YouTube channels, including the number of subscribers, total views, and total videos uploaded.

2. **Data Processing**: Convert the retrieved data into a structured DataFrame for further analysis. Perform data type conversions and clean the data.

3. **Visualizations**: Create visualizations to better understand the data. This includes bar plots to compare channel statistics and analyze the top-performing videos.

4. **Video Details**: Fetch details for the videos from a specific channel's uploads playlist, including views, likes, comments, and the published date.

5. **Monthly Video Uploads**: Analyze and visualize the number of videos uploaded per month.

6. **Data Export**: Save the video details to a CSV file for future reference and analysis.

## Code Description

The code is written in Python and utilizes the Google API client library for YouTube Data API v3. It performs the following tasks:

- Fetches channel statistics for the specified channel IDs.
- Processes and cleans the channel statistics data.
- Creates bar plots to compare channel statistics.
- Retrieves video IDs from a specified channel's uploads playlist.
- Fetches video details, including views, likes, comments, and publication date.
- Analyzes and visualizes the number of videos uploaded per month.
- Exports the video details to a CSV file for further analysis.

## Dependencies

- Python
- pandas
- seaborn
- Google API client library (youtube-api-python-client)

## Usage

To use this code, you need to:

1. Replace the `api_key` variable with your own YouTube Data API key.
2. Modify the `channel_ids` list to include the YouTube channel IDs you want to analyze.
3. Run the code to fetch and analyze the data.

The code will generate visualizations and save the video details to a CSV file.

## Data Output

The code generates the following outputs:

- Visualizations comparing channel statistics.
- A CSV file named "Video_Details(TechBar).csv" containing details of the videos from the specified channel's uploads playlist.

Feel free to customize and extend this project for your specific needs. Happy coding!
