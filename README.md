# Parallax Scrolling Website

## Overview
This project is a parallax scrolling website that creates an engaging visual experience using various layers that move at different speeds when the user scrolls. The website is built using HTML, CSS, and JavaScript.

## Features
- **Parallax Scrolling Effect:** Multiple layers move at different speeds to create a depth effect.
- **Responsive Design:** The layout is responsive and works well on different screen sizes.
- **Smooth Navigation:** The website includes smooth scrolling navigation links.

## Technologies Used
- **HTML**
- **CSS**
- **JavaScript**

## Setup Instructions
1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/parallax-website.git
   cd parallax-website
   open index.html
HTML Structure
Header: Contains the navigation menu with links to different sections.
Section: The main section with parallax effect elements and introductory content.
div.sec: A secondary section with additional content and a sample story.
CSS Styles
The CSS file styles.css includes styles for:

General layout and positioning.
Parallax layers.
Responsive design adjustments.
JavaScript Functionality
The JavaScript code in index.html manages the parallax effect:

Event Listener: Listens for the scroll event.
Scroll Effect: Adjusts the position of various elements based on the scroll position.

Certainly! Here's a sample README.md file for your parallax scrolling website project, with clear labeling and a structured format:

markdown
Copy code
# Parallax Scrolling Website

## Overview
This project is a parallax scrolling website that creates an engaging visual experience using various layers that move at different speeds when the user scrolls. The website is built using HTML, CSS, and JavaScript.

## Features
- **Parallax Scrolling Effect:** Multiple layers move at different speeds to create a depth effect.
- **Responsive Design:** The layout is responsive and works well on different screen sizes.
- **Smooth Navigation:** The website includes smooth scrolling navigation links.

## Technologies Used
- **HTML**
- **CSS**
- **JavaScript**

## Setup Instructions
1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/parallax-website.git
Navigate to the project directory:
bash
Copy code
cd parallax-website
Open index.html in your preferred web browser:
bash
Copy code
open index.html
File Structure
index.html: Main HTML file containing the structure of the website.
styles.css: CSS file for styling the website.
images/: Directory containing image assets used in the website.
stars.png
moon.png
mountains_behind.png
mountains_front.png
scripts/: Directory containing JavaScript files.
script.js
HTML Structure
Header: Contains the navigation menu with links to different sections.
Section: The main section with parallax effect elements and introductory content.
div.sec: A secondary section with additional content and a sample story.
CSS Styles
The CSS file styles.css includes styles for:

General layout and positioning.
Parallax layers.
Responsive design adjustments.
JavaScript Functionality
The JavaScript code in index.html manages the parallax effect:

Event Listener: Listens for the scroll event.
Scroll Effect: Adjusts the position of various elements based on the scroll position.
javascript
Copy code
let stars = document.getElementById('stars');
let moon = document.getElementById('moon');
let mountains_behind = document.getElementById('mountains_behind');
let mountains_front = document.getElementById('mountains_front');
let text = document.getElementById('text');
let btn = document.getElementById('btn');

window.addEventListener('scroll', function(){
    let value = window.scrollY;
    stars.style.left = value * 0.25 + 'px';
    moon.style.top = value * 1.05 + 'px';
    mountains_behind.style.top = value * 0.5 + 'px';
    mountains_front.style.top = value * 0 + 'px';
    text.style.marginRight = value * 4 + 'px';
    text.style.marginTop = value * 1.5 + 'px';
    btn.style.marginTop = value * 1.5 + 'px';
    header.style.marginTop = value * 0.5 + 'px';
});
Future Improvements
Additional Layers: Adding more layers for a more complex parallax effect.
Animations: Incorporating CSS animations for enhanced visual appeal.
Content Expansion: Adding more sections and content to the website.
Contributors
Your Name

Certainly! Here's a sample README.md file for your parallax scrolling website project, with clear labeling and a structured format:

markdown
Copy code
# Parallax Scrolling Website

## Overview
This project is a parallax scrolling website that creates an engaging visual experience using various layers that move at different speeds when the user scrolls. The website is built using HTML, CSS, and JavaScript.

## Features
- **Parallax Scrolling Effect:** Multiple layers move at different speeds to create a depth effect.
- **Responsive Design:** The layout is responsive and works well on different screen sizes.
- **Smooth Navigation:** The website includes smooth scrolling navigation links.

## Technologies Used
- **HTML**
- **CSS**
- **JavaScript**

## Setup Instructions
1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/parallax-website.git
   Navigate to the project directory:
bash
cd parallax-website
Open index.html in your preferred web browser:
bash
open index.html

## File Structure

index.html: Main HTML file containing the structure of the website.
styles.css: CSS file for styling the website.
images/: Directory containing image assets used in the website.
stars.png
moon.png
mountains_behind.png
mountains_front.png
scripts/: Directory containing JavaScript files.
script.js

HTML Structure
Header: Contains the navigation menu with links to different sections.
Section: The main section with parallax effect elements and introductory content.
div.sec: A secondary section with additional content and a sample story.
CSS Styles
The CSS file styles.css includes styles for:

General layout and positioning.
Parallax layers.
Responsive design adjustments.
JavaScript Functionality
The JavaScript code in index.html manages the parallax effect:

Event Listener: Listens for the scroll event.
Scroll Effect: Adjusts the position of various elements based on the scroll position.


## Future Improvements
Additional Layers: Adding more layers for a more complex parallax effect.
Animations: Incorporating CSS animations for enhanced visual appeal.
Content Expansion: Adding more sections and content to the website.

## Contributors: [Kanchana Karunarathna]

Feel free to customize the content and structure according to your specific project details and preferences!
