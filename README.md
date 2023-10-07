# YOUTUBE_HARVESTING
YOUTUBE_HARVESTING I developed a YouTube data collection and storage system using the Google API, MongoDB, and SQL. The system allows users to input a YouTube channel ID and retrieve various relevant data for the channel, including the channel name, number of subscribers, total video count, playlist ID, video ID, likes, dislikes, and comments for each video The project consists of the following key features

YouTube Data Retrieval: By providing a YouTube channel ID, the system fetches data from the YouTube API, extracting information such as channel name, subscriber count, total video count, playlist ID, and video details (likes, dislikes, comments) for each video

MongoDB Data Lake: The collected data is stored in a MongoDB database, serving as a data lake. This allows for efficient storage and retrieval of the YouTube channel data. Screenshot (21)

The system allows users to collect data for YouTube channels. By clicking a button, the data for each channel is collected and stored in the MongoDB data lake.

SQL Database Migration: Users have the option to select a specific channel and migrate its data from the MongoDB data lake to a SQL database. The data is structured into tables, providing a more organized and structured format for data analysis and retrieval.
