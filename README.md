# YouTube Video Scrapper
A simple YouTube video recommender system that leverages web scraping and the YouTube Data API to build a graph of video recommendations and generate a list of similar videos based on user input.

## Installation
To run the project, you will need Python 3.x, as well as several libraries which can be installed via pip. To install these dependencies, simply run:

pip install -r requirements.txt
You will also need a Google Cloud Platform (GCP) account with the YouTube Data API enabled, as well as a Chrome driver to run the web scraper. Once you have these set up, you can run the script:

python youtube_recommender.py
Usage
The program will ask for a YouTube video ID, which can be found in the URL of a YouTube video. Once you enter an ID, the program will generate a graph of recommended videos and display the top 10 most similar videos.

You can adjust the depth of the search by changing the depth parameter in the get_video_recommendations function. The default depth is 2, meaning the program will search for recommended videos and their recommended videos.

## Contributions
Contributions are welcome and encouraged! If you would like to contribute to the project, please submit a pull request with your changes.

## License

