# Landing Page

- **[Design Reference](https://www.figma.com/file/lSR1m42L9YwzQwzzxKwHpw/THE-MET)**
- **[Preview](https://v-shut.github.io/layout_landing-page/)**

Use `npm` to interact with the application!

## Overview

- **Header:** Features the museum's logo, contact information for The Met Fifth Avenue and The Met Cloisters, and a navigation menu.
- **Main Content:** Displays the museum's hours of operation, ongoing exhibitions, and options for virtual tours.
- **Footer:** Contains contact details and a message submission form.

## Structure

- **DOCTYPE:** Specifies HTML5.
- **HTML:** The root element that contains all other elements.
- **Head:** Includes metadata such as encoding, title, stylesheets, scripts, and fonts from Google Fonts.
- **Body:** Contains the main content, organized into header, main content, and footer.

## Features

- **Responsive Menu:** Managed by a checkbox for the burger menu.
- **Interactivity:** Script to reset the burger menu state when the URL hash changes.
- **Media Content:** Images and links showcasing exhibitions.
- **Contact Form:** Form to receive user messages, with a reset function post-submission for demonstration purposes.

## Optimization

- **Preconnect:** Enhances font loading speed using `rel="preconnect"`.
- **Defer Scripts:** Scripts are deferred to avoid blocking page loading.

## How to Use

### Project Interaction Instructions

This project is a React TypeScript starter pack with ESLint, Prettier, and Bulma for styling.

1. **Cloning the Repository:**
   ```bash
   git clone <YOUR-REPOSITORY-URL>
   cd react-typescript-starter-pack
  
2. Installing Dependencies
After cloning, install the required dependencies:
   ```bash
   npm install
  
3. Running the Project in Development Mode
To run the project in development mode, use:
   ```bash
   npm start
  
4. Building the Project for Production
To build the project for production, run:
   ```bash
   npm run build
5. Deploying to GitHub Pages
To deploy to GitHub Pages, use the following commands:
   ```bash
   npm run deploy
  
6. Linting and Formatting Code
To check and automatically fix code style issues, use:
   ```bash
   npm run lint
  
7. To format TypeScript files with Prettier, run:
      ```bash
   npm run format
