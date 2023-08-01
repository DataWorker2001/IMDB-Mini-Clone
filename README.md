# IMDB-Mini-Clone
##  Smaller clone of the IMDB built using OMDB-API built purely using HTML, CSS and Vanilla JS in seperate html, css and js code files.
### Contributed by: Mr. Arpan Choudhury.
![image](https://github.com/DataWorker2001/IMDB-Mini-Clone/assets/123379937/f6aa64c6-6c42-4e98-ae65-da31c04acf6a)


## Folder Structure:-<br/>

Imdb-Mini-Clone/<br/>
├── public/                # Public directory containing static assets<br/>
│   ├── bg1.jpg            # Background image<br/>
│   ├── favorites.js       # JavaScript file for handling favorites functionality<br/>
│   ├── favourites.html    # HTML file for displaying user's favorite movies<br/>
│   ├── index.html         # Main HTML file for the app's homepage<br/>
│   ├── movie.html         # HTML file for displaying movie details<br/>
│   ├── movie.js           # JavaScript file for fetching and displaying movie details<br/>
│   ├── script.js          # Main JavaScript file for the app<br/>
│   └── styles.css         # CSS file for styling the app<br/>
├── .gitattributes         # Git attributes file (for Git version control)<br/>
├── LICENSE                # License file for the app's code<br/>
└── README.md              # Project documentation and information<br/>

## Features of this webapp:-
1) Home Page: On this page, Users can search for any movie using the OMDB API.
As the user types in the search box, real-time search suggestions are displayed, similar to Google.
Each search result will have a "Favourite" button, allowing users to add the movie to their "My Favourite Movies" list.
Clicking on a particular search result will open a new page with more information about the selected movie.

2) Home Page:
Through this page, Users can search for any movie using the OMDB API.
As the user types in the search box, real-time search suggestions are displayed, similar to Google.
Each search result will have a "Favourite" button, allowing users to add the movie to their "My Favourite Movies" list.
Clicking on a particular search result will open a new page with more information about the selected movie.

3) My Favourite Movies Page:
By means of this page users can get UI to access and manipulate their favourite movies. Users can view a list of all their favourite movies on this page.
The list of favourite movies will be made persistent, meaning it will be retained even after closing or refreshing the browser.
Each movie in the favourites list will have a "Remove from favourites" button, allowing users to remove a movie from the list.

## Short description of this App:
The app has been implemented using vanilla JavaScript, and it will interact with the OMDB API to fetch movie data. The user interface will be designed using CSS, and it uses a CSS framework like Bootstrap to assist with styling as desired. The app's data, including the list of favourite movies, will be stored in the browser's local storage to make it persistent across sessions.

## Introduction and stepwise guide to start & complete this project:
Creating a mini IMDB clone app as described in the problem statement of the Frontend Development skill test of Coding Ninjas using vanilla JavaScript and the OMDB API requires a step-by-step approach. 
Below is a guide on how you can proceed with the project using the following steps:

### 1: Set Up the Project
Create a new directory for your project and set up the necessary files (HTML, CSS, and JavaScript).
Obtain an API key from the OMDB API website: https://www.omdbapi.com/ by registering on their website and activating the api key using the email id activation link containing message they send you.
### Step 2: HTML Structure
Create the HTML structure for the Home Page, Movie Page, and My Favourite Movies Page.
Add the necessary input fields, buttons, and containers for displaying search results and favourite movies.
### Step 3: CSS Styling
Apply styling to make the app visually appealing. You can use a CSS framework like Bootstrap for this purpose.
### Step 4: JavaScript Implementation
Implement the functionality for searching movies using the OMDB API and with your provided api-key.
As the user types in the search box, fetch and display search results in real-time (like Google suggestions).
Add a "Favourite" button to each search result, and upon clicking, add the movie to the "My Favourite Movies" list.
Create a separate movie page that displays detailed information about a selected movie.
Implement the functionality to display the list of favourite movies on the "My Favourite Movies" page.
Make the list of favourite movies persistent by storing it in local storage.
Implement the functionality to remove movies from the favourites list when the "Remove from favourites" button is clicked.
### Step 5: Comments and Code Structuring
Add comments to your JavaScript code to explain the functionality of different parts of the code.
Structure your code in a modular and organized way to improve readability and maintainability.
### Step 6: Create a Readme.md
Prepare a detailed Readme.md file that explains the purpose of the project, how to set it up, and how to use the app.
Include screenshots or gifs to demonstrate the app's features.
Add any other relevant information, such as credits, acknowledgments, or additional features.
### Step 7: Host the Project on Github
Create a repository on Github for your project.
Push your code to the Github repository.
Make sure to include the Readme.md and any other necessary files.
### Step 9: Deploy the Project on render:
Using Render go to static website section after syncing render to github and then deploy this webapp using this github repo link and required settings.
### Step 8: Record an Explanation Video
Record a video explaining your project's features, functionality, and any creative additions you have made.
Walk through the app's usage and demonstrate its capabilities.
### Step 9: Submit the Project
Submit your project by sharing the Render Hosting link, Github repository link and the video explanation.
Keep in mind that this is a general guide, and you can add more features or improvements to showcase your creativity and skills. Good luck with this mini IMDB clone app!

If anyone wants to do this directly using my repository then just download this repository, or clone this project using git clone repo-name command by typing the command given below in the command prompt within a folder or the terminal section of your visual-stuio-code or other advanced code editor within a folder:-<br/>
git clone https://github.com/DataWorker2001/IMDB-Mini-Clone.git<br/>
and deploy this directly with the changes included like changing the API-Key and designs and also the other CSS, HTML, JS codes for extra features and changed , updated latest seperate unique layouts.

## License: 
This project is licensed under GNU General Public License-4.

## Contributions:
Any contributions are openly welcomed and I am looking forward for those. Anyone can contribute to this repository by forking this repo, I will be very happy and grateful to the contributors. 





