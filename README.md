# pokemon_js
This is an HTML code for a Pokedex guide webpage.

It includes a title, a search bar with a search button, and a container for the Pokedex.

The page also includes links to external stylesheets and scripts.

To make the webpage functional, you would need to write the necessary JavaScript code in the "main.js" file and the CSS styling in the "style.css" file.

Additionally, you would need to link those files to the HTML using the appropriate file paths.

 # pokemongift
 ![pokemon](https://github.com/zafer414108/pokemon_js/assets/147662873/9c860c1d-692c-4300-86d6-295296232d7a)

This code creates a Pokedex web application using HTML, CSS, and JavaScript.

Here is a summary of what the code does:

It selects the necessary elements from the HTML using the document.querySelector method and assigns them to variables for further use.
It defines the number of pokemon to be displayed in the Pokedex using the pokemon_count variable. In this case, it is set to 151.
It defines background colors for different pokemon types using the bg_color object.
It adds event listeners to the search button and input field to toggle the visibility of the search bar and filter the pokemon cards based on the search input.
It fetches the pokemon data from the PokeAPI using the fetch function and the specified URL for each pokemon ID from 1 to pokemon_count.
It creates a pokemon card for each fetched pokemon by generating the necessary HTML elements dynamically and adding them to the poke_container element.
The fetched pokemon data is used to set the image, ID, name, base experience, weight, and type of each pokemon card. The background color of each card is also dynamically set based on the pokemon type using the bg_color object.
Overall, this code fetches pokemon data from an API and creates a Pokedex web application to display and search for pokemon.
