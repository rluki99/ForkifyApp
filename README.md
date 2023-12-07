# Forkify App

Forkify is a recipe browsing and management application. It allows users to search for recipes, view their details, change serving sizes, add recipes to favorites, and share their own recipes. The application utilizes an API interface to fetch recipe data.

## LIVE https://forkify-app-kohl.vercel.app/

![obraz](https://github.com/rluki99/ForkifyApp/assets/120097849/12ffda38-403c-48ef-a8a7-833a9d3a57a8)


## Project Structure

The project is organized into modules, each responsible for a specific part of the functionality. The main modules include:

1. **config.js:** Contains configuration settings for the application.
2. **controller.js:** Implements the controller logic, connecting the model and views.
3. **helpers.js:** Includes utility functions used throughout the application.
4. **model.js:** Contains the business logic and global state.
5. **views:**
   - **addRecipeView.js:** Handles the view for adding a new recipe.
   - **bookmarksView.js:** Renders the favorites view.
   - **paginationView.js:** Manages the pagination view.
   - **previewView.js:** Handles the preview of recipes.
   - **resultsView.js:** Renders the search results view.
   - **searchView.js:** Manages the search view.
   - **View.js:** Provides a base class for other view modules.

The project follows the Model-View-Controller (MVC) architecture, providing a clear separation of concerns.

## Features

### 1. Browsing Recipes

- Users can view details of a selected recipe.
- The application automatically updates search results and favorite recipes.

### 2. Recipe Search

- Users can enter queries to search for recipes.
- The application supports pagination of search results.

### 3. Changing Serving Sizes

- Users can adjust the number of servings in a recipe.
- Ingredients are automatically adjusted based on the new serving size.

### 4. Adding to Favorites

- Users can add recipes to their favorites.
- Favorite recipes are stored locally - localStorage.

### 5. Managing Favorites

- Users can browse, add, and remove recipes from the favorites list.

### 6. Adding Own Recipes

- Users can add their own recipes.
- The application validates the entered ingredients.
