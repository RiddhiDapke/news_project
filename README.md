## News App

A simple news website that fetches and displays news articles using the NewsAPI. This project is built using HTML, CSS, and JavaScript.

## Features
- Fetches and displays news articles based on categories and search queries.
- Categories include IPL, Finance, and Politics, Technology.
- Responsive design suitable for various screen sizes.

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/news-app.git
    cd news-app
    ```

2. Open `index.html` in your browser to view the app.

## Usage

1. **Navigation**: Click on the category names (IPL, Finance, Politics) in the navigation bar to view news articles related to that category.

2. **Search**: Enter a search term in the search bar and click the search button to view news articles related to that search term.

## APIs Used
This project uses the [NewsAPI](https://newsapi.org/) to fetch news articles. 

To use this project, you need to get an API key from NewsAPI:

1. Go to [NewsAPI](https://newsapi.org/) and sign up for an account.
2. Get your API key.
3. Replace `'YOUR_API_KEY'` in `script.js` with your actual API key.

```javascript
const API_KEY = 'YOUR_API_KEY';  // Replace with your actual API key
