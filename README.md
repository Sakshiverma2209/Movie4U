## Movie4u: Your One-Stop Shop for Movie Entertainment

Movie4u is a web application built with HTML, CSS, and JavaScript that allows users to search for movies using the OMDb API and save their favorites. It provides a user-friendly interface to explore a vast library of movies, making it your go-to destination for movie discovery and enjoyment.

### Features:

#### HTML:

*   **Structure and Layout:** The website is structured using semantic HTML elements like `header`, `div`, `nav`, `input`, `button`, `img`, `h1`, `h2`, `p`, providing a clear and organized layout.
*   **Forms and Inputs:** The search bar allows users to enter movie titles using a text input field (`<input type="text">`) and initiate a search using a button (`<button>`).
*   **Multimedia Integration:** Movie posters are displayed using the `img` tag, enhancing the visual appeal of the application.

#### CSS:

*   **Styling and Aesthetics:** The website utilizes custom CSS to achieve a visually appealing design, including a dark background, stylized buttons, a responsive layout, and a user-friendly search bar.
*   **Grid Layout:** The movies are displayed in a grid layout using `display: grid`, making it easy for users to browse through the search results.
*   **Responsive Design:** The layout adapts to different screen sizes, ensuring an optimal viewing experience on desktops, tablets, and mobile devices.

#### JavaScript:

*   **API Integration:** The application fetches movie data from the OMDb API using the `fetch` API.
*   **Dynamic Content:** Search results are dynamically displayed on the page, updating in real-time as the user types in the search bar.
*   **Event Handling:** Event listeners are used to handle user interactions, such as button clicks for searching and adding to favorites.
*   **Local Storage:** The application utilizes local storage to store users' favorite movies, ensuring that their preferences are saved even after closing the browser.
*   **DOM Manipulation:** JavaScript is used to create and manipulate DOM elements, allowing for the dynamic display of movie information, buttons, and error messages.

#### API:

*   **OMDb API:** The application utilizes the OMDb API (https://www.omdbapi.com/) to fetch movie data, including titles, posters, release years, and IMDb IDs.

### Functionality:

1.  **Home Page:** The home page features a prominent search bar where users can enter the title of a movie they want to find.
2.  **Search:** Upon entering a movie title and clicking the "Search" button, the application fetches movie data from the OMDb API based on the search term.
3.  **Display Results:** Search results are displayed in a grid format, each movie card showcasing the movie poster, title, and year of release. Clicking on the poster or title redirects the user to the corresponding IMDb page.
4.  **Add to Favorites:** Users can add a movie to their favorites list by clicking the "heart" icon on the movie card. Favorites are stored locally in the browser's storage.
5.  **Favorites Page:** The "Favorites" button on the navigation bar takes users to a dedicated page where they can view all their saved favorite movies.
6.  **Remove from Favorites:** Users can remove a movie from their favorites list by clicking the "Remove" button on the movie card within the Favorites page.

### How to Use:

1.  Clone or download the repository.
2.  Open the `index.html` file in your web browser.
3.  Start searching for your favorite movies.
4.  Click the "heart" icon to add movies to your favorites.
5.  Navigate to the "Favorites" page to view your saved movies.

Movie4u provides a seamless and enjoyable movie browsing experience, allowing users to discover new films and keep track of their favorites. Its intuitive design and robust functionality make it an ideal platform for all movie enthusiasts.
