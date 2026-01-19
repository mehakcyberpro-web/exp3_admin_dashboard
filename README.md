# Admin Dashboard with CSS Grid and Dynamic Theme Switching

## 1. Personal Information

- **Name:** mehakpreet kaur____________
- **UID:** 24bcy70046______________________
- **Group:**a ______________________


## 2. Title of the Experiment

**Develop an Admin Dashboard with CSS Grid Layout and Dynamic Theme Switching**


## 3. Defined Approach

The objective of this experiment is to design and implement a responsive admin dashboard interface using modern web technologies such as HTML, CSS, and JavaScript.

First, the overall structure of the dashboard is created using **HTML**. The layout consists of a sidebar, header, and main content area. Semantic elements are used to improve readability and structure.

Next, **CSS Grid Layout** is used to arrange the dashboard components efficiently. Grid template areas are defined to position the sidebar, header, and main section. CSS variables are declared in the `:root` selector to manage theme-related properties such as background color, text color, and primary color. This makes theme switching easy and maintainable.

For implementing **dark and light mode**, a separate CSS class is defined for the dark theme. When this class is applied to the body element, the CSS variables automatically update the UI colors.

Using **JavaScript**, a toggle button is implemented to switch between light and dark themes. JavaScript dynamically adds or removes the dark theme class from the body element. To ensure that the selected theme persists even after refreshing the browser, **localStorage** is used to save and retrieve the user’s theme preference.

This approach demonstrates effective use of CSS Grid, CSS variables, JavaScript DOM manipulation, and browser storage to build a modern, responsive, and user-friendly admin dashboard.


## Result

A responsive admin dashboard was successfully created using CSS Grid. Dark and light theme switching was implemented, and the selected theme persists using localStorage even after page reload.
