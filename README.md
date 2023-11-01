# MyPortfolio

# Project Overview:

# HTML (index.html):
This file represents the structure and content of my web page.
It contains the basic layout and elements that users will interact with.

# CSS (styles.css):
This file contains the styles (e.g., colors, fonts, layout) that define the visual appearance of my web page.
It helps in making the HTML content look aesthetically pleasing.

JavaScript (script.js):
This file contains the scripting logic for interactivity on my web page.
It handles events like button clicks and updates the DOM (Document Object Model) accordingly.

# Features:

# HTML (index.html):
The HTML file contains the basic structure of the web page, which includes:
Header section with a title.
A container for buttons (with class "controls").
A container for displaying content associated with the buttons (with class "content").
A button for toggling between light and dark themes (with class "theme-btn").

# CSS (styles.css):
It provides styling information for various elements on the page.
It likely defines things like fonts, colors, margins, and padding.

# JavaScript (script.js):
It adds functionality to the web page. Specifically:
It adds event listeners to all elements with the class "control" (presumably buttons).
When a button with class "control" is clicked, it:
Removes the "active-btn" class from any previously active button.
Adds the "active-btn" class to the clicked button.
Hides any previously active content and shows the content associated with the clicked button.
It adds an event listener to the element with class "theme-btn". When clicked, it toggles the "light-mode" class on the body, potentially changing the theme of the page.
