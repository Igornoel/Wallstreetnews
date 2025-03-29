# Wall Street News Website
A comprehensive financial news platform that aggregates and displays the latest market updates and financial analysis using the NewsAPI. This project was developed as part of the "News API Integration" assignment.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [API Integration](#api-integration)
- [Deployment](#deployment)
- [Challenges and Solutions](#challenges-and-solutions)
- [Demo](#demo)
- [Credits](#credits)

## Overview
This application serves as a one-stop destination for financial news, providing users with the latest Wall Street updates, market news, and financial insights. The platform aggregates news from various trusted financial sources through NewsAPI, creating a centralized hub for anyone interested in staying updated with financial developments.

## Features
- **Financial News Feed**: Displays the latest market news from trusted financial sources
- **Category Filtering**: Filter news by categories (stocks, markets, economy, cryptocurrencies)
- **Source Selection**: Choose specific news sources to customize your feed
- **Article Search**: Search for specific financial topics or companies
- **Saved Articles**: Bookmark important news for later reading
- **Responsive Design**: Works seamlessly across desktop and mobile devices
- **Dark Mode**: Provides an alternative viewing experience for extended reading sessions
- **Social Sharing**: Easily share financial news via social media platforms
- **Error Handling**: Provides helpful feedback when API errors occur or internet connection is lost

## Technologies Used
- HTML5
- CSS3
- JavaScript (ES6+)
- Fetch API for asynchronous requests
- LocalStorage for saving user preferences and bookmarked articles
- NewsAPI for all financial news content

## API Integration
This project exclusively utilizes the [NewsAPI](https://newsapi.org/), a comprehensive news data service that provides:
- Breaking news headlines from trusted sources
- Full-text search with keyword filtering
- Date range filtering
- Source filtering
- Category-based news aggregation

The application makes multiple endpoint calls to gather financial news, filter by relevance, and present the most important stories to users. The API responses are processed and displayed in a user-friendly format with proper attribution to original sources.

## Deployment
The application has been deployed to two web servers (Web01 and Web02) with a load balancer (Lb01) distributing traffic between them, similar to the Weather App deployment architecture.

## Challenges and Solutions
### Challenge 1: API Rate Limiting
**Solution:** Implemented client-side caching to store news data temporarily, reducing the number of API calls for frequently viewed categories.

### Challenge 2: News Content Relevance
**Solution:** Created a custom relevance algorithm that prioritizes financial news based on keywords, publication time, and source reliability.

### Challenge 3: Secure API Key Management
**Solution:** Implemented environment variables on the server side to securely store the NewsAPI key, preventing exposure in client-side code.

## Demo
A short demonstration video showing the application's functionality and deployment can be found here: [Demo Video Link]()

The video covers:
- How to browse and filter financial news
- Searching for specific companies or financial topics
- Saving articles for later reading
- Sharing content to social media
- Accessing the application through the load balancer
- Verification of load balancing functionality

## Credits
- News content provided by [NewsAPI](https://newsapi.org/)
- Original article content from various financial news sources
- HTML/CSS/JavaScript implementation by Igornoel
- A help of AI to formalize code and optimize API requests

---
*This project was created as an assignment for News API Integration. For questions or feedback, please contact n.ishimwe4@alustudent.com.*
