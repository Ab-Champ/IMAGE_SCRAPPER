# Image Scraper Flask App

This project is a simple web-based Image Scraper application built using Flask. It allows users to search and download images from Google based on a keyword. The scraped images are saved locally in a designated directory.

## Project Description

The Image Scraper Flask App is designed to take a search query from the user, send it to Google Images, extract the image URLs using BeautifulSoup, and download them into a local folder. The interface is minimal and intuitive, offering users a straightforward way to collect visual content for research, prototyping, or personal use.

## Features
- Simple and user-friendly interface.

- Scrapes images directly from Google Image search results.

- Stores all scraped images in a local Scrapped_images folder.

- Uses a fake User-Agent to mimic browser requests and avoid getting blocked.

- Logs errors and events for better debugging and tracking.

## How It Works

User enters a search keyword on the homepage.

The app sends a request to Google Images using the keyword.

The server parses the HTML response to extract image sources.

Each image is downloaded and saved with a relevant filename.

Images can be accessed in the Scrapped_images directory.

## Requirements

Python 3.x

Flask

BeautifulSoup4

requests

urllib

## Folder Structure

app.py: Main Flask application.

templates/index.html: The frontend HTML template.

Scrapped_images/: Folder where scraped images are saved.

scrapper.log: Log file capturing backend operations and errors.

## Usage

Clone the repository to your local machine.

Install required dependencies using pip.

Run the Flask app.

Open the browser and go to http://localhost:8000/.

Enter your search term and let the app download images for you.

## Notes
The scraper works best for generic queries. Some specific queries may return fewer or no results.

Make sure you are connected to the internet while using the app.

It is advised to use this tool responsibly and comply with Google's Terms of Service.

## Disclaimer
This tool is intended for educational and research purposes only. The developer is not responsible for any misuse of the application. Please respect copyright laws and avoid scraping copyrighted images for commercial use.

