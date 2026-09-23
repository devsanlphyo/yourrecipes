Share not only recipes but also loves. Made with ❤️ by San Linn Phyo.

### Overview

- About
- How It Is Structured
- Features
- Process Flows

### About

YourRecipes (YR) is a recipe sharing website. It has a lot of recipes that you would like and you can share your favorite recipes too. Browse, save and share.

### How It Is Structured

NextJs is used to built Frontend while powering backend by ASP.NET Core Web API.

```bash
YourRecipes/
|----------- YourRecipes.Database
|----------- YourRecipes.Domain
|----------- YourRecipes.WebAPI
|----------- YourRecipes.Website
```

### Features

- **Recipe Sharing**
Users can create and share their favorite recipes with the community.
- **Recipe Browsing**
Browse recipes by categories, ingredients, cooking time, and other useful filters.
- **Save Favorite Recipes**
Save recipes you love and easily access them later.
- **Recipe Details**
View ingredients, instructions, preparation time, cooking time, servings, and other recipe information.
- **User Accounts**
Users can create an account and manage their own recipes and saved recipes.

### Process Flows

- Browse

```bash
start -> user -> recipesPage -> recipeDetail -> end
```

- Save

```bash
start -> user -> recipesPage -> recipeDetail -> saveRecipe -> isLoggedIn -> loginPage -> end
																														 |
																														 V
																														save
																														 |
																														 V
																														end
```

- Share

```bash
start -> user -> recipesPage -> recipeDetail -> shareRecipe -> isLoggedIn -> loginPage -> end
																														 |
																														 V
																														share
																														 |
																														 V
																														end
```

> Made with ❤️ by San Linn Phyo…
>