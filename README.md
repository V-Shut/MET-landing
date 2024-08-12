# Landing page

- [MET landing design](https://www.figma.com/file/lSR1m42L9YwzQwzzxKwHpw/THE-MET)
- [Preview](https://v-shut.github.io/layout_landing-page/)

Use 'npm' to interact with the application!

# Overview:
- Header: Contains the museum's logo, contact information with phone numbers for two museum locations (The Met Fifth Avenue and The Met Cloisters), and a navigation menu with sections of the site.
- Main Content: Includes a section with information about the museum's hours of operation, as well as blocks featuring ongoing exhibitions and options for virtual tours.
- ooter: Contains contact information and a form for sending messages.


# Structure:
- DOCTYPE: Indicates that the document is HTML5.
- HTML: The main tag that contains all other elements of the page.
- Head: Contains metadata of the page, such as encoding, title, stylesheets, scripts, and fonts from Google Fonts.
- Body: The main part of the page with content, divided into the header, main content, and footer.


# Features:
- Responsive Menu: A checkbox is used to manage the burger menu.
- Interactivity: A script resets the burger menu state when the URL hash changes.
- edia Content: Includes images and links to view exhibitions.
- Contact Form: A form to receive messages from users, which resets after submission (for demonstration purposes).


# Optimization:
- Preconnect: Optimizes the loading speed of fonts using rel="preconnect".
- Defer Scripts: Uses defer for scripts so they do not block the page loading.

# How to use:
Project Interaction Instructions
This project is a React TypeScript starter pack, including setup for ESLint, Prettier, and Bulma for styling.

Cloning the Repository:
1. To get started, clone the repository:
- git clone
- cd react-typescript-starter-pack
  
2. Installing Dependencies
After cloning, install the required dependencies:
- npm install
  
3. Running the Project in Development Mode
To run the project in development mode, use:
- npm start (This will open your project in the default web browser.)
  
4. Building the Project for Production
To build the project for production, run:
- npm run build (This will create an optimized version of your app in the build folder.)
5. Deploying to GitHub Pages
To deploy to GitHub Pages, use the following commands:
- npm run deploy
  
6. Linting and Formatting Code
To check and automatically fix code style issues, use:
- npm run lint
  
7. To format TypeScript files with Prettier, run:
- npm run format
