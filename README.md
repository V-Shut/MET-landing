# Landing page

- [MET landing design](https://www.figma.com/file/lSR1m42L9YwzQwzzxKwHpw/THE-MET)
- [Preview](https://v-shut.github.io/layout_landing-page/)

Use 'npm' to interact with the application!

Overview:
- Header: Contains the museum's logo, contact information with phone numbers for two museum locations (The Met Fifth Avenue and The Met Cloisters), and a navigation menu with sections of the site.
- Main Content: Includes a section with information about the museum's hours of operation, as well as blocks featuring ongoing exhibitions and options for virtual tours.
- ooter: Contains contact information and a form for sending messages.


Structure:
- DOCTYPE: Indicates that the document is HTML5.
- HTML: The main tag that contains all other elements of the page.
- Head: Contains metadata of the page, such as encoding, title, stylesheets, scripts, and fonts from Google Fonts.
- Body: The main part of the page with content, divided into the header, main content, and footer.


Features:
- Responsive Menu: A checkbox is used to manage the burger menu.
- Interactivity: A script resets the burger menu state when the URL hash changes.
- edia Content: Includes images and links to view exhibitions.
- Contact Form: A form to receive messages from users, which resets after submission (for demonstration purposes).


Optimization:
- Preconnect: Optimizes the loading speed of fonts using rel="preconnect".
- Defer Scripts: Uses defer for scripts so they do not block the page loading.
