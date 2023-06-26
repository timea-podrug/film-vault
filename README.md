# Film Vault


![film-vault_screenshot](https://github.com/timea-podrug/film-vault/assets/108535463/277cbcfd-644a-4774-8c15-1cc0df79d733)


Film Vault is a React-based application that utilizes the OMDb API to provide users with the ability to search for movies, view their details, add ratings, and create a personalized watched list. This README file will guide you through the installation process and provide an overview of the application's features.

## Installation

To run Film Vault locally on your machine, follow these steps:

1. Clone the repository to your local machine using the following command:

   ```
   git clone https://github.com/timea-podrug/film-vault
   ```

2. Navigate to the project directory:

   ```
   cd film-vault
   ```

3. Install the required dependencies using your preferred package manager. For example, with npm:

   ```
   npm install
   ```

4. Create an account on the [OMDb API website](http://www.omdbapi.com/) and obtain an API key.

5. Go to the App.js file and replace the existing key with your actual API key:

   ```
   export const KEY = "<YOUR_API_KEY>";
   ```

6. Start the development server:

   ```
   npm start
   ```

7. Open your web browser and navigate to `http://localhost:3000` to access Film Vault.

## Features

Film Vault offers the following features:

- **Movie Search**: Users can search for movies by title using the search bar. The application retrieves data from the OMDb API and displays a list of matching movies.

- **Movie Details**: Clicking on a movie from the search results displays detailed information about the selected movie, including its title, release year, runtime, genre, director, actors, plot, and poster.

- **Rating**: Users can rate the movies they have watched by selecting a rating from 1 to 5 stars. The ratings are stored locally and associated with the respective movies.

- **Watched List**: Users can add movies to their watched list by clicking the "Add to Watched" button on the movie details page. The watched list displays all the movies that users have marked as watched, along with their ratings.


## Technologies Used

Film Vault is built with the following technologies:

- React: A JavaScript library for building user interfaces.
- OMDb API: An API that provides access to a vast collection of movie data.
- HTML5: The latest version of the Hypertext Markup Language.
- CSS3: The latest version of Cascading Style Sheets.
- JavaScript: A high-level programming language.

## Contact

If you have any questions or inquiries, please feel free to contact me at [timeapodrug@gmail.com](mailto:timeapodrug@gmail.com). Thank you for using Film Vault!
