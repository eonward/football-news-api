# Football News API

A Football News API that scrapes news data from various football websites using Cheerio and provides endpoints for users to fetch the latest football news. The API supports CORS and is built using Node.js, Cheerio, Axios, and Express.

## Table of Contents

- [Endpoints](#endpoints)
- [Usage](#usage)
- [Getting Started](#getting-started)
- [Contributing](#contributing)
- [License](#license)

## Endpoints

The API provides the following endpoints:

- `/news`: Get the list of websites from where news is coming.
- `/news/onefootball`: Get the latest football news from OneFootball.
- `/news/espn`: Get the latest football news from ESPN.
- `/news/90mins`: Get the latest football news from 90mins.
- `/news/goal`: Get the latest football news from Goal.

## Usage

Users can fetch the latest football news from multiple sources using the provided endpoints. The data is scraped in real-time from popular football news websites.

Here's an example of how to use the API using cURL:

```bash
# Get the list of websites
curl https://your-api-url/news

# Get the latest football news from OneFootball
curl https://your-api-url/news/onefootball

# Get the latest football news from ESPN
curl https://your-api-url/news/espn

# Get the latest football news from 90mins
curl https://your-api-url/news/90mins

# Get the latest football news from Goal
curl https://your-api-url/news/goal
