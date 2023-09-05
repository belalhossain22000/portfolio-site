Documentation for the HTML and CSS Code:

Title: Portfolio

**HTML Structure:**
1. `<!DOCTYPE html>`: This declaration defines the document type and version of HTML used in the document.
2. `<html lang="en">`: The root element of the HTML document, specifying the language as English.
3. `<head>`: Contains metadata about the HTML document, including character set and viewport settings.
   - `<meta charset="UTF-8">`: Sets the character encoding to UTF-8.
   - `<meta name="viewport" content="width=device-width, initial-scale=1.0">`: Configures the viewport for responsive design.
   - `<title>portfolio</title>`: Sets the title of the webpage.
   - Bootstrap CSS and a custom CSS file are linked in this section.

**Body:**
1. `<body class="container mt-5">`: The main content of the webpage is contained within the body element. It uses the Bootstrap container class for layout and adds a top margin of 5 units.

**Header Section:**
1. `<header class="d-flex align-items-center justify-content-center flex-column">`: Defines the header section of the page, which includes the site title and category tabs.
   - `<h1>Portfolio</h1>`: Displays the main title of the portfolio.
   - `<ul>`: A list of category tabs using Bootstrap's nav components.
     - `<li>`: List items for each category tab.
     - `<button>`: Buttons serve as category tabs with specific attributes and data attributes to toggle content.

**Main Section:**
1. `<main class="mt-5">`: Contains the main content of the page.
2. `<section class="tab-content" id="pills-tabContent">`: Defines the content section that corresponds to the selected category tab.
   - Three category content sections are defined, one for each category (React/Next, Webflow, Shopify).

**Category Tabs and Content:**
1. **React/Next Tab Content:**
   - `<div class="tab-pane fade show active" id="pills-home">`: Contains content related to the React/Next.js category.
   - Multiple card components are displayed, each representing a project.
   - Each card includes an image, title, description, and a button to visit the project site.

2. **Webflow Tab Content:**
   - `<div class="tab-pane fade" id="pills-profile">`: Contains content related to the Webflow category.
   - Similar to the React/Next section, it displays cards for various Webflow projects.

3. **Shopify Tab Content:**
   - `<div class="tab-pane fade" id="pills-contact">`: Contains content related to the Shopify category.
   - Displays cards for Shopify projects.

**JavaScript:**
1. `<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js" ...>`: Includes the Bootstrap JavaScript library for interactive features.

**Custom CSS:**
1. A custom CSS file (`styles.css`) is linked to the HTML document to define additional styling and layout rules.

**Overall Purpose:**
This HTML document represents a portfolio website with three categories: React/Next.js, Webflow, and Shopify. It uses Bootstrap for responsive layout and includes cards for showcasing various web projects within each category. The user can switch between categories using the tabs in the header section. Each project card contains an image, project title, description, and a button to visit the project's website. The design is responsive, ensuring it looks good on various screen sizes. JavaScript is included to enable Bootstrap functionality, and custom styling is applied through CSS.

# live site: https://guileless-jalebi-bde2ae.netlify.app/