# 🍽️ Chef's Menu Manager

## Project Overview

Chef's Menu Manager is a mobile application developed using React Native and Expo. The application is designed to help restaurant owners and chefs manage their restaurant menus digitally instead of relying on paper records.

The app allows users to add, view, update, delete, search and filter menu items. It also displays useful statistics to help the restaurant owner understand the menu.

This project was developed as part of a Mobile Application Development Portfolio of Evidence (POE).

## Features

### 1. Manage Menu Items
- Add new dishes to the menu.
- View all available menu items.
- Edit existing dish information.
- Delete menu items.
- Enter a dish name, description, course and price.

### 2. Search and Filter
- Search for dishes by name.
- Search using dish descriptions.
- Search using course categories.
- Filter menu items by Starter, Main Course or Dessert.
- View all menu items using the All filter.

### 3. Menu Statistics
The application automatically calculates and displays:
- Total number of menu items.
- Average menu price.
- Lowest menu price.
- Highest menu price.
- Number of starters.
- Number of main courses.
- Number of desserts.

### 4. Sample Menu

The application includes 30 example dishes divided into three categories.

| Category | Number of dishes |
|---|---:|
| Starters | 10 |
| Main Courses | 10 |
| Desserts | 10 |
| **Total** | **30** |

All sample prices are displayed in South African Rand (ZAR).

### 5. User Interface
- Simple and beginner-friendly interface.
- Navy blue and yellow colour scheme.
- Food emojis to identify menu categories.
- Clear buttons and input fields.
- Validation messages to help prevent incorrect information.
- Confirmation message before deleting a dish.

## Technologies Used

- **React Native** – Used to develop the mobile application.
- **JavaScript** – Used to implement the application functionality.
- **Expo Snack** – Used to develop and run the application.
- **React Hooks** – Used to manage application state.
- **Material Community Icons** – Used for application icons.

## Getting Started

### Requirements

To run this project, you need:

- An internet connection.
- A web browser.
- Access to Expo Snack.

### Running the Application Using Expo Snack

1. Visit [Expo Snack](https://snack.expo.dev/).
2. Open the project.
3. Open the `App.js` file.
4. Copy the application code into the file.
5. Run the application using the available preview.

### Running the Project Locally

If you want to run the project on your computer:

1. Install Node.js.
2. Install Expo CLI or use the current Expo project setup instructions.
3. Create an Expo React Native project.
4. Add the application code to `App.js`.
5. Install any dependencies that are not already included.
6. Start the development server using:

```bash
npx expo start
```

## How to Use the Application

1. Open the application to view the restaurant menu.
2. Browse the available starters, main courses and desserts.
3. Use the search bar to find a particular dish.
4. Use the course filters to display a specific category.
5. Select **Add Menu Item** to add a new dish.
6. Enter the dish name, description, course and price.
7. Select **Save Menu Item**.
8. Select the pencil icon to edit an existing dish.
9. Select the bin icon to delete a dish.
10. Open the statistics section to view menu information.

## Project Structure

```text
Chefs-Menu-Manager/
│
├── App.js
│   └── Main React Native application
│
└── README.md
    └── Project documentation
```

## Learning Outcomes

Through developing this application, I practised:

- Building mobile user interfaces using React Native.
- Using JavaScript functions and variables.
- Managing application data using `useState`.
- Displaying lists using `FlatList`.
- Handling user input using `TextInput`.
- Creating reusable components.
- Implementing add, edit and delete functionality.
- Searching and filtering menu information.
- Calculating and displaying statistics.
- Using conditional rendering.
- Applying basic input validation.

## Future Improvements

Possible improvements for future versions include:

- Adding real food images.
- Saving menu information permanently using a database.
- Adding user authentication.
- Allowing menu items to be sorted by price.
- Adding more menu categories.
- Creating a restaurant dashboard.

## Important Note

The application currently uses sample menu data and React state to manage menu items. Menu changes are not permanently stored in a database, so they may reset when the application reloads.

The listed dish prices are examples and can be changed by the restaurant owner.

## Author

**Developer:** [David Kambay-Bumba]

**Project:** Chef's Menu Manager

**Technology:** React Native and JavaScript

**Platform:** Expo Snack

---

*This project was developed for educational purposes as part of a  school project.*
## Youtube video link

## References
# REFERENCES

Expo (n.d.) *Expo Documentation*. Available at: https://docs.expo.dev/ (Accessed: 5 November 2026).

GitHub (n.d.) *GitHub Documentation*. Available at: https://docs.github.com/ (Accessed: 6 October 2026).

Meta Platforms, Inc. (n.d.) *React Documentation*. Available at: https://react.dev/ (Accessed: 3 November 2026).

Meta Platforms, Inc. (n.d.) *React Native Documentation*. Available at: https://reactnative.dev/ (Accessed: 1 November 2026).

Mozilla (n.d.) *JavaScript Guide*. MDN Web Docs. Available at: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide (Accessed: 2 November 2026).

University College London (n.d.) *Harvard referencing: Web page*. Available at: https://library-guides.ucl.ac.uk/harvard/web-page (Accessed: 6 November 2026).
