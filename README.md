# Gallery-Website

This is an HTML page that displays a gallery of pictures fetched from the Unsplash API based on a user’s
search query. The gallery has a responsive grid layout that adapts to different screen sizes.
The HTML structure includes a header with a title and a search bar, and a div with class “gallery” that
will hold the pictures.
The CSS styles define the layout and appearance of the page, including the header, search bar, gallery,
and individual pictures. The gallery uses a grid layout to display the pictures, with each picture having an
image and a caption with the photographer’s name, a link to their Unsplash profile, and a description.
The JavaScript code fetches the pictures from the Unsplash API using the provided API key, search
query, and category. It then parses the response and creates HTML elements for each picture using the
data provided by the API. Finally, it adds the pictures to the gallery by appending them to the div with
class “gallery”.
The JavaScript code also includes an event listener on the search button that triggers a new search when
the user enters a query and clicks the button. The new search updates the search query and calls the
fetchPictures function again to display the new results.
