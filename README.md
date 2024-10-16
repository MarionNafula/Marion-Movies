# VideoFive

A web application that displays a list of videos with their posters and titles. The user can search for a specific video by typing in the search bar and can also navigate through the list of videos using the pagination buttons.

## Technologies Used

* HTML
* CSS
* JavaScript

## Code Explanation

The code is divided into three main parts: the HTML, CSS and JavaScript files.

### HTML

The HTML file contains the structure of the web page. It includes a header with a search bar, a main section for the video list and a footer with pagination buttons.

### CSS

The CSS file contains the styles for the HTML elements. It includes styles for the header, main section, footer and the video elements.

### JavaScript

The JavaScript file contains the code that handles the functionality of the web page. It includes the following functions:

* `loadVideos()`: This function loads the video data from the `db.json` file and displays it on the web page.
* `searchVideos()`: This function handles the search functionality. It takes the search query from the search bar and filters the video list based on the query.
* `paginateVideos()`: This function handles the pagination functionality. It takes the current page number and the number of videos per page as parameters and displays the correct videos on the web page.

The JavaScript file also includes event listeners for the search bar and pagination buttons. When the user types in the search bar, the `searchVideos()` function is called. When the user clicks on a pagination button, the `paginateVideos()` function is called.

## db.json

The `db.json` file contains the video data. It is a JSON file that contains an array of objects, each representing a video. Each object has the following properties:

* `id`: The id of the video.
* `title`: The title of the video.
* `description`: The description of the video.
* `poster`: The URL of the video poster image.
* `video`: The URL of the video file.

## How to Use

To use the web application, simply open the `index.html` file in a web browser. The video list will be displayed and the user can search for a specific video by typing in the search bar. The user can also navigate through the list of videos using the pagination buttons.
