# 🍽️ Project: Simple API 2 - Restaurant

### Goal: Build a simple front-end app that displays data returned from an api that would be beneficial to someone working at or managing a restaurant. 

### How to submit your code for review:

- Fork and clone this repo
- Create a new branch called answer
- Checkout answer branch
- Push to your fork
- Issue a pull request
- Your pull request description should contain the following:
  - (1 to 5 no 3) I completed the challenge
  - (1 to 5 no 3) I feel good about my code
  - Anything specific on which you want feedback!

Example:
```
I completed the challenge: 5
I feel good about my code: 4
I'm not sure if my constructors are setup cleanly...
```
# Vegan Dish Generator

A simple web application that fetches recipe ideas based on user input and displays a random recipe suggestion using the Spoonacular API.

---

## Features

- **Recipe Search:** Searches for recipes based on the user's selected cuisine or keyword.
- **Random Selection:** Randomly shuffles matching results and picks one featured recipe to display.
- **Visual Presentation:** Displays the recipe title along with its official thumbnail image.

---

## API Used

- **Spoonacular Recipe API:** `https://api.spoonacular.com/recipes/complexSearch`

---

## How It Works

1. The user selects an option from the menu and clicks the search button.
2. The application sends a query to the Spoonacular `complexSearch` endpoint using the selected value.
3. The returned array of recipes is shuffled at random.
4. One recipe is selected from the list, and its image and title are rendered dynamically inside the `.placeHere` container.

---

<img width="2846" height="1556" alt="image" src="https://github.com/user-attachments/assets/72d8ba32-37ff-433e-893c-71e46377f64a" />
