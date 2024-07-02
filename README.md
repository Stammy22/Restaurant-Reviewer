# Restaurant-Reviewer
Restaurant Review Aggregator and Locator

# Objectives:

- Develop a web application that aggregates restaurant reviews from multiple sources.
- ~~Use web scraping to gather reviews and ratings from websites like Yelp, TripAdvisor, or Google Reviews~~
- Utilize the Yelp Fusion API, Google Places API, and optionally the Foursquare Places API to gather restaurant review data.
- Integrate the Google Maps API to display the locations of these restaurants on a map.
- Provide a user-friendly interface for searching and filtering restaurants based on different criteria.

# Features:

1. **~~Web Scraping:~~**
    - ~~Scrape restaurant data (name, address, reviews, ratings) from different review sites.~~
    - ~~Ensure compliance with the terms of service of the websites you are scraping.~~
2. API Integration:
    - Integrate the Yelp Fusion API to fetch restaurant details, reviews, and ratings.
    - Integrate the Google Places API to fetch additional restaurant details, reviews, and ratings.
    - Optionally, integrate the Foursquare Places API for supplementary restaurant data.
3. **Data Storage:**
    - Store the ~~scraped~~ fetched data in a database (e.g., SQLite, MongoDB).
    - ~~Update the database periodically to keep the reviews up to date.~~
    - Implement mechanisms to update the database periodically to keep the review data current.
4. **Google Maps Integration:**
    - Use the Google Maps API to display restaurant locations.
    - Implement markers for each restaurant on the map.
    - Provide detailed information in an info window when a marker is clicked.
5. **Search and Filter:**
    - Allow users to search for restaurants by name, location, rating, or cuisine.
    - Implement filters to sort the results based on user preferences.
6. **User Interface:**
    - Create a responsive web interface using a front-end framework like React or Vue.js.
    - Display the map and the list of restaurants side by side.
    - Show aggregated reviews and ratings for each restaurant.
