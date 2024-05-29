# Movie Search App

## Overview
Movie Search App is a web application built using React that allows users to search for movies by their name. It provides an input form where users can type in a movie name, and the app fetches and displays the relevant movie details, including the movie name and poster. The app efficiently manages API calls using a debounce technique to minimize unnecessary requests.

## Features
- **Search Movies**: Users can search for movies by typing the name in the search input form.
- **Debounce Implementation**: The search input uses debounce to ensure that API calls are made only when necessary, improving performance and reducing server load.
- **Movie Details**: Displays movie name and poster based on the search query.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/ChirlaVishnuRupa/movie-website.git
    cd movie-website
    ```

2. Install dependencies:
    ```bash
    npm install
    ```

3. Start the development server:
    ```bash
    npm start
    ```

## Usage

1. Open your web browser and go to `http://localhost:3000`.
2. Use the search input form to type in the name of the movie you want to search for.
3. The app will display the movie name and poster based on the search results.

## Debounce
Debounce is a technique used to limit the rate at which a function gets executed. In this app, debounce is applied to the search input to ensure that the API is called only when the user has stopped typing, thus reducing the number of API requests and improving performance.


Happy movie searching!
