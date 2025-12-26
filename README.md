**Image Resizer – JavaScript DOM Project**

This project is a simple interactive web application that demonstrates dynamic manipulation of the Document Object Model (DOM) using HTML, CSS, and JavaScript. The application allows users to resize an image by increasing or decreasing its width through button interactions, while enforcing defined size limits.

Live Demo ->  https://sreeramyerabati.github.io/Image-resizer/


Project Description:
The Image Resizer project focuses on understanding how JavaScript interacts with HTML elements in real time. Users can control the width of an image using plus and minus buttons. The width changes in fixed steps, and warning messages are displayed when the image reaches its minimum or maximum allowed size.

**Features:**
  • Increase image width using the “+” button
  • Decrease image width using the “–” button
  • Image resizes in steps of 5 pixels
  • Minimum and maximum width limits applied
  • Warning messages shown when limits are reached
  • Current image width displayed dynamically

**Technologies Used:**
  • HTML5 for page structure
  • CSS3 for styling and layout
  • JavaScript for DOM manipulation
  • Bootstrap (CSS only) for responsive layout
  • GitHub Pages for hosting     

**How the Project Works:**

JavaScript selects HTML elements using their IDs and stores them as DOM references. The image width is updated dynamically using inline style properties. Text updates, such as the current width and warning messages, are handled using textContent. Button clicks trigger JavaScript functions that control the resizing logic while ensuring size constraints are respected.

The JavaScript file is loaded using the defer attribute to ensure that the DOM is fully loaded before the script executes.  

**Learning Outcomes:**

  • Understanding how JavaScript manipulates DOM elements
  • Differentiating between modifying styles and modifying text
  • Managing UI state using variables
  • Handling browser caching during deployment
  • Deploying static websites using GitHub Pages

**Hosting Instructions (GitHub Pages)**

  1. Upload all project files to a GitHub repository
  2. Ensure the main HTML file is named index.html
  3. Open repository Settings and navigate to Pages
  4. Select the main branch and root folder
  5. Save and wait for the live site URL to be generated

**License**
This project is intended for learning and educational purposes.
