# INSIGHT DAILY

Welcome to INSIGHT DAILY! This web application provides up-to-date news articles from around the world. Users can search for news by categories or specific topics. 

## Usage
1. Load the application to see the latest news about India.
2. Use the navigation bar to filter news by categories.
3. Use the search bar to find news by keywords.

## Features
- Displays latest news on load.
- Filters news by categories.
- Search functionality for specific topics.
- Responsive design.

## Technologies Used
- HTML
- CSS
- JavaScript
- [News API](https://newsapi.org/)

## Instructions to Add API Key
1. Get an API key from [News API](https://newsapi.org/).
2. Open the `script.js` file in the `client` directory.
3. Add your API key at the beginning of the `script.js` file like this:
    ```javascript
    const API_KEY = 'your_news_api_key_here';
    const url = `https://newsapi.org/v2/everything?apiKey=${API_KEY}&q=`;
    ```
 
Thank you for checking out INSIGHT DAILY! If you have any questions or suggestions, feel free to open an issue.
