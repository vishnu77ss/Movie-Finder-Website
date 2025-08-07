# Movie Finder Website

A responsive and dynamic movie search application built with vanilla JavaScript that allows users to search for movies using the OMDB (Open Movie Database) API.

![Project Screenshot or GIF]
<img width="1840" height="959" alt="Image" src="https://github.com/user-attachments/assets/afc80606-38f1-48c9-9b3a-9b64b83b8998" />

## Description

This project showcases the ability to connect to a public API, handle user input, and display the fetched data in a clean, user-friendly grid. Users can search for any movie, and the application will return a list of matching results with their posters, titles, and release years. The project emphasizes good practices like error handling and providing user feedback.

## Key Features

* **External API Consumption:** Fetches data from the public OMDB API based on user search queries.
* **Dynamic Results Grid:** Dynamically generates and displays movie cards in a responsive grid layout for an optimal viewing experience.
* **Asynchronous Data Fetching:** Uses `async/await` to handle API calls, ensuring the UI remains responsive while data is being fetched.
* **Error Handling & Loading States:** Provides feedback to the user with a "Searching..." message during API calls and displays a clear error message if no movies are found or if the API call fails.

## Technologies Used

* HTML5
* CSS3
* JavaScript (ES6+)
* OMDB API

## How to Run Locally

1.  Clone the repository: `git clone https://github.com/vishnu77ss/movie-finder.git`
2.  Open the `index.html` file in your browser.
