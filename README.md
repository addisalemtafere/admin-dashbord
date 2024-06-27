
# Responsive Admin Dashboard 

![Screenshot of the Dashboard](assets/imgs/Screenshot%202024-06-27%20113049.png)

## Description

This project is a responsive admin dashboard template designed using HTML, CSS, and JavaScript. It features a navigation menu, top bar, statistics cards, recent orders list, and a recent customers list. The design is clean and modern, suitable for various administrative purposes.

## Project Structure

The project structure is organized as follows:

```
/
├── assets/
│   ├── css/
│   │   └── style.css
│   ├── imgs/
│   │   ├── customer01.jpg
│   │   ├── customer02.jpg
│   │   └── Screenshot%202024-06-27%20113049.png
│   └── js/
│       └── main.js
├── index.html
```

## HTML Structure

The `index.html` file is the main entry point of the dashboard. It includes the following sections:

- **Head**: Contains meta tags, title, and link to the CSS file.
- **Body**: Contains the main structure of the dashboard, including navigation, top bar, statistics cards, recent orders, and recent customers.

### Navigation

The navigation section contains a list of menu items, each with an icon and a title. Icons are provided by Ionicons.

### Top Bar

The top bar includes a menu toggle button, a search bar, and a user profile image.

### Main Content

The main content is divided into two primary sections:

1. **Statistics Cards**: Displays key statistics such as daily views, sales, comments, and earnings.
2. **Details**: Contains recent orders and recent customers lists.

### Scripts

The `index.html` file includes links to the main JavaScript file and Ionicons library.

## CSS and JavaScript

- **CSS**: Styles for the dashboard are defined in `assets/css/style.css`. The CSS file is responsible for the layout, colors, fonts, and responsiveness of the dashboard.
- **JavaScript**: Interactive features and functionality are implemented in `assets/js/main.js`. This includes handling the menu toggle and any other dynamic behavior.

## How to Use

1. **Clone the repository**:
   ```bash
   git clone https://github.com/addisalemtafere/admin-dashbord.git
   ```

2. **Navigate to the project directory**:
   ```bash
   cd ADMIN-CSS
   ```

3. **Open `index.html` in a web browser** to view the dashboard.

## Dependencies

- **Ionicons**: Used for the icons in the navigation menu and statistics cards. The Ionicons library is loaded via a CDN.

```html
<script type="module" src="https://unpkg.com/ionicons@5.5.2/dist/ionicons/ionicons.esm.js"></script>
<script nomodule src="https://unpkg.com/ionicons@5.5.2/dist/ionicons/ionicons.js"></script>
```

## Customization

You can customize the dashboard by modifying the CSS and JavaScript files located in the `assets` directory. Update the styles in `style.css` to change the look and feel of the dashboard. Edit `main.js` to add or modify the interactive behavior.

## Contact

For any inquiries or support, please contact [your email].

---

This README provides an overview of the Responsive Admin Dashboard project, its structure, and instructions on how to use and customize it.
