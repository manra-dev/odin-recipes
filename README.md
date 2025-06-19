# 📚 The Recipe Book (Frontend)

✨ **A responsive web-based recipe application built with HTML, CSS, and vanilla JavaScript.** ✨
---

## 📝 Project Description

This project is a practical demonstration of frontend development skills, providing a user-friendly platform to browse, search, and manage a collection of recipes. All recipe data is stored locally within the application, showcasing dynamic content rendering without a backend. It's optimized for various screen sizes, from mobile devices to desktops, ensuring a seamless user experience.

---

## 🌟 Features

- **Homepage:** Displays a welcoming hero section, featured recipes, and an overview of all available recipes.
- **Recipe Display:** Dynamically renders recipe cards for easy Browse.
- **Search Functionality:** Allows users to find recipes by name, ingredients, or description.
- **Category Filtering:** Filters recipes by different categories (e.g., Breakfast, Dinner, Dessert).
- **Recipe Detail Modal:** Displays comprehensive details for each recipe (ingredients, instructions, times) in an interactive modal overlay.
- **Favorites:** Users can "favorite" recipes, with selections persistently stored in `localStorage`.
- **Responsive Design:** Optimized for various screen sizes, from mobile devices to desktop computers.
- **"About Us" Page:** A static page providing information about the project.

---

## 🛠️ Technologies Used

- **HTML5:** For structuring the web content.
- **CSS3:** For styling and layout, including **Flexbox** and **CSS Grid** for responsiveness.
- **Vanilla JavaScript:** For all dynamic content rendering, search, filtering, modal functionality, and `localStorage` interactions.
- **Font Awesome:** For icons (e.g., heart icons for favorites, social media icons).

---

## 🚀 Live Demo

You can view the live deployed version of this project here:
[YOUR_GITHUB_PAGES_LINK_HERE](https://www.google.com/search?q=YOUR_GITHUB_PAGES_LINK_HERE)
_(Remember to replace `YOUR_GITHUB_PAGES_LINK_HERE` with your actual GitHub Pages URL once deployed\!)_

---

## 💻 Installation and Local Setup

To get a local copy of this project up and running on your machine:

1.  **Clone the repository:**

    ```bash
    git clone https://github.com/manra-dev/odin-recipes.git
    ```

2.  **Navigate to the project directory:**

    ```bash
    cd odin-recipes
    ```

3.  **Open `index.html`:**
    Simply open the `index.html` file in your web browser. You can do this by double-clicking the file or by running a simple local web server (e.g., using VS Code's Live Server extension).

---

## 💡 Usage

- **Browse Recipes:** Scroll through the "Featured Delights" and "All Recipes" sections on the homepage.
- **Search:** Use the search bar at the top to filter recipes.
- **Filter:** Select a category from the dropdown to narrow down recipes.
- **View Details:** Click on any recipe card to open a modal with full ingredients and instructions.
- **Favorite:** Click the "Favorite" button on a recipe card or within the detail modal to add/remove it from your local favorites list. Your favorites will persist even if you close the browser.

---

## 📂 File Structure

```
recipe-book-app/
├── index.html            # Main homepage and recipe listings
├── about.html            # Static about page
├── css/                  # Contains stylesheets
│   └── style.css         # Main CSS file for global and component styles
├── js/                   # Contains JavaScript files
│   ├── data.js           # Holds the local array of recipe data
│   └── app.js            # Main application logic for DOM manipulation, search, filter, modal, favorites
└── images/               # Stores project images
    ├── hero-bg.jpg       # Background for the hero section
    ├── placeholder.jpg   # Fallback image for recipes
    ├── about-us.jpg      # Image for the about page
    └── ... (individual recipe images: pancakes.jpg, chicken-curry.jpg, etc.)
```

---

## ✨ Future Enhancements (Ideas)

- **Recipe Submission Form:** Implement a functional form for users to submit new recipes (which would temporarily add to `localStorage`).
- **Favorite Recipes Page:** Create a dedicated page to view all favorited recipes.
- **Sorting Options:** Add options to sort recipes (e.g., by name, prep time).
- **Rating System:** Integrate a simple star-rating system (visual only, or with `localStorage` persistence).
- **Print Recipe:** Add a button to print a clean version of the recipe details.
- **Animations and Transitions:** Further enhance UI/UX with more subtle animations.

---

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](https://www.google.com/search?q=MIT+License) file for details.

---

## 🙏 Acknowledgements

- Inspired by The Odin Project's Foundations curriculum.
- Recipe content adapted from common cooking resources.
- Icons from Font Awesome.

---

Feel free to explore the code, contribute, or adapt it for your own projects\!
