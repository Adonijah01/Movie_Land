Overview
This Movie App is a simple React application that allows users to search for movies using the Open Movie Database (OMDb) API. Users can enter a movie title in the search bar, and the app will display a list of movies matching the search term. Each movie card includes information such as the movie's title, year of release, type, and poster image.

Features
Search for movies by title.
Display a list of movies matching the search term.
Show movie details including title, year, type, and poster image.
Handle cases where no movies are found.
Stylish and responsive design.
Load additional pages of search results.
Error handling for invalid search queries and API requests.
Installation
To run this Movie App locally, follow these steps:

Clone the repository to your local machine:
https://github.com/Adonijah01/Movie_Land.git
bash
Copy code
Navigate to the project directory:

bash
Copy code
cd movie-app
Install the dependencies:

bash
Copy code
npm install
Get an API key from the OMDb API (free tier available).

Create a .env file in the project root directory and add your API key as follows:

env
Copy code
REACT_APP_API_KEY=your_api_key_here
Start the development server:

bash
Copy code
npm start
Open your browser and go to http://localhost:3000 to view the Movie App.

Usage
Enter a movie title in the search bar and press "Enter" or click the search icon.
The app will display a list of movies matching the search term.
Click on a movie card to view more details.
Use the "Load More" button at the bottom to fetch additional pages of search results.
Troubleshooting
If you encounter issues with the app, you can refer to the GitHub repository for discussions and solutions: Movie App GitHub Repository.

Contributing
Contributions are welcome! If you'd like to contribute to the project, please fork the repository and create a pull request with your changes.

License
This Movie App is open-source and available under the MIT License.

