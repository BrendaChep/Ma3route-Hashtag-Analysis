# Ma3route-Hashtag-Analysis

This project aims to analyze Twitter data related to the Ma3Route hashtag, which is used by users in Kenya to report traffic and accidents in real-time. The project uses Twitter API, Python, Spark, Nomatim API, and Mongodb to process and store the data.

The project begins with collecting data from Twitter using the Twitter API and filtering it based on the Ma3Route hashtag. The filtered tweets are then cleaned and processed using Spark, which performs various transformations to extract relevant information, such as location data and user information.

To enrich the location data, the project uses the Nomatim API to query the latitude and longitude coordinates of the reported incidents. The location data is then used to create a map visualization of the reported incidents on the front-end.

The processed data is then stored in a MongoDB database for easy retrieval and scalability. The data is served to the back-end, which is responsible for serving the data to the front-end via an API. 

The front-end displays the data in a user-friendly way, providing insights into traffic patterns, accidents and road conditions in real-time.

In addition to providing real-time information, the project also maintains a history file of the processed data in a CSV format, which can be used for further analysis and reporting.

Overall, this project showcases the power of using Python, Spark, Nomatim API, and MongoDB for processing and storing real-time data, providing valuable insights into traffic patterns and road conditions in Kenya.
