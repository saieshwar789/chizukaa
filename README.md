# Chizukaa - Cloud Kitchen Website

This repository contains the source code for the official website of Chizukaa, a premium cloud kitchen focused on perfecting the art of five signature chicken dishes.

### [View the Live Website](https://saieshwar789.github.io/chizukaa/)

## About Chizukaa

Chizukaa was born from a simple belief: do a few things exceptionally well. We are obsessed with perfecting chicken. Each of our five signature dishes is a masterpiece, the result of countless hours of testing, tasting, and a relentless pursuit of flavor. This isn't just a kitchen; it's our craft, served to you.

## Features

This website is a fully-featured, single-page application that allows customers to browse the menu and place orders directly.

- **Interactive Menu:** A horizontally scrolling menu showcasing all five signature dishes.
- **Dynamic Shopping Cart:**
  - Users can add items to their order directly from the menu.
  - An "Amazon-style" `[ - | 1 | + ]` quantity selector appears on the menu cards for easy adjustments.
  - The main "Your Order" cart is always in sync with the menu controls and displays a running total.
- **Live Price Calculation:** The total order price is calculated and updated in real-time as item quantities change.
- **Smart "Proceed to Order" Button:** A shortcut button appears below the menu as soon as an item is added, allowing for quick navigation.
- **Functional Order Form:**
  - A clean, user-friendly form to collect customer details.
  - Submits the complete order (including item quantities and total price) directly to a designated email address using the free **Web3Forms** service.
- **Personalized Confirmation:** After placing an order, the user receives a personalized thank you message with a unique confirmation number.
- **Fully Responsive Design:** A mobile-first approach ensures a seamless experience on all devices, from desktops to smartphones.
- **SEO Optimized:** Includes all essential meta tags (Title, Description, Keywords, Canonical, Open Graph) for improved search engine visibility and social media sharing.

## Tech Stack

- **HTML5:** For the core structure and content.
- **CSS3:** For all styling, including variables, animations, and a fully responsive layout.
- **JavaScript (Vanilla):** For all interactivity, including the shopping cart logic, dynamic UI updates, and form submission handling.

## Configuration

This project is self-contained in a single `index.html` file. The only configuration is the Web3Forms `access_key` in the form element, which has already been set up.
