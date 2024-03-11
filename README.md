Certainly! Here's a more polished version:

# App Scraper Application - User Guide

- [Just want to use the Scraper on Apify?](#docs-for-using-scraper)
- [Want to push data in the database?](#want-to-push-data-in-the-database)

## Overview

This analytics product provides insights for game developers, offering information about the current top games on the market.

## [Using the Scraper](#docs-for-using-scraper)

### 1. Choose Action

- **Action to Perform:**
  - Select the desired action:
    - List Apps
    - List Developer Apps
    - Get Details of an App
    - Get Reviews of an App

### 2. Specify Platform

- **Choose the Platform:**
  - Select the platform to scrape:
    - Google Play
    - App Store

### 3. Provide Details

- **Action-Specific Details:**
  - Depending on the chosen action, provide the necessary details:
    - For "List Apps," specify the category, collection, country, and sorting options.
    - For "List Developer Apps," provide the developer's ID.
    - For "Get Details," provide the app's ID.

### 4. Review Type (When the action chosen is GET_REVIEWS)

- **Type of Reviews :**
  - When fetching reviews, choose between "GOOD" and "BAD" reviews.
  - **Enter the number of reviews:**
    - For fetching reviews from GOOGLE_PLAY, enter a maximum of 3000 reviews.
    - For fetching reviews from APP_STORE, enter a maximum of 10 pages.

### 5. Set Limit

- **Enter the number of results:**
  - Specify the number of results to fetch.

### 6. Run the Application

- **Execute the Application:**
  - Initiate the scraping process by running the application.

### 7. View Results

- **Review the Results:**
  - Once the application completes, review the fetched data.
  - Data may include app details, developer apps, or reviews based on your selected action.

## [Want to push data in the database?](#want-to-push-data-in-the-database)

- **To push data to the database:**
  - Always select the `LIST_APPS` action.
  - For other parameters like choosing the platform, category, collection, country, limit, and sorting, follow the standard procedure.
  
- **Details of the application and reviews will be automatically fetched.**
  - You have control over the number of applications and reviews to be pushed to the database.
