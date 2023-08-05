#Recipe APP

This is a simple Recipe App that allows users to search for their favorite recipes. The app fetches recipe data from the MealDB API and displays the recipes along with their images, names, areas, and categories. Users can click on the "View Recipe" button to see detailed information about a specific recipe, including its name, ingredients, and instructions.

Features:

Search for Recipes: Users can search for recipes by entering the name of the meal they want to find in the search box and clicking the "Search" button.

Recipe Display: The app displays the search results in a grid layout, each recipe represented by a card with its image, name, area, and category. Hovering over a recipe card slightly enlarges it for visual feedback.

View Recipe Details: Clicking on the "View Recipe" button within a recipe card opens a pop-up displaying the detailed information of the selected recipe, including its name, list of ingredients with measurements, and cooking instructions.

Responsive Design: The app has a responsive design to provide a good user experience on various screen sizes, with a mobile-friendly layout for screens smaller than 600px wide.

How to Use:

Open the "index.html" file in a web browser to access the Recipe App.

In the search box, type the name of the meal you want to find recipes for.

Click the "Search" button or press Enter to fetch recipes related to the entered meal.

Recipe cards will be displayed with the meal's image, name, area, and category.

Click on the "View Recipe" button on a card to see detailed information about the selected recipe.

The pop-up will show the recipe name, list of ingredients, and cooking instructions.

To close the recipe details pop-up, click the "X" button on the top right corner.

Note: The app uses the MealDB API to fetch recipe data, so an active internet connection is required for it to work correctly.

Styling:
The app's styling is defined in the "style.css" file, providing an attractive and user-friendly interface. The use of grid layout and flexbox ensures responsive and organized content presentation.

Scripting:
The app's interactivity and functionality are implemented using JavaScript. The "script.js" file contains functions to handle API calls, populate the recipe cards, and display recipe details in the pop-up.

Dependencies:
The app uses Font Awesome icons and the MealDB API (https://www.themealdb.com/api/json/v1/1/search.php?s=${query}) to fetch recipe data.
