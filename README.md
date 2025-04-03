# HackathonPortfolio

Project Name: Sandra Jepichii Wandera Hackathon Portfolio

version 1.1.1
Author: Sandra Jepichii Wandera
Last Update: 3rd April, 2025
https://sandrawandera.netlify.app/



# INTRODUCTION
A responsove portfolio website showcasing skills, projects and services as a Web Developer, Data Administrator and Records Manager. 

Features include: 
    1. Smooth-scrolling single page design.
    2. Mobile- optimized layout ( smaller screens)
    3. Google forms intergrated - contact form.
    4. Interactives section (About , Services, Projects, Contact)

# TECHNOLOGIES USED
Languages: HTML5 , CSS , JAVASCRIPT
Hosting: Github & Netlify ( netlifylink : )
Icons: Font Awesome
Fonts: Poppins (google fonts)
Form handling: Google Apps Script ( contact form)


# PROJECT STRUCTURE
HackathonPortfolio/ 
                    README.md ------Documentation
                    index.html -----HTML contents & Javascript
                    styles. --------Styles for the whole page
                    images ----------Contains all images & pdf


# KEY FEATURES
SECTIONS:
Home: Hero section with background image and intro text.
About: Grid layout for skills, education and interests.
Services: Card-based showcase of offered services.
Projects: Hoverable project cards with overlay details.
Contact: Form linked to Google Sheets + social media links.

Interactive Elements
Hover Effects: Underline animations, card lifts, project layer reveals.
Mobile-Friendly: Adjusted layouts for screens (MAX width 768px.)


# SET UP & DEPLOYMENT
Local Development
   1.Clone the repository:
        git clone https://github.com/Sandra858/HackathonPortfolio.git 
   2.Open index.html in a browser.

Deployment
    GitHub Pages:
        Push to main branch → Enable GitHub Pages in repo settings.
    Netlify:
        Drag-and-drop the folder or connect GitHub repo

# CUTSTOMIZATION 
UPDATE CONTENT
Text/Images: Modify index.html and replace files in /images/.
Colors: Edit CSS variables in styles.css (e.g., #3E2723 for background).
Projects: Add/remove cards in the projectlist div.

CONTACT FORM
Replace the Google Apps Script URL in script.js:
\
    const scriptURL = 'YOUR_NEW_SCRIPT_URL';
Follow this guide to set up a new Google Sheet

# TROUBLESHOOTING
    Issue	                                     Solution
Form not submitting	          -Check Google Script URL and CORS settings.
Images not loading	          -Verify file paths in HTML/CSS.
Mobile layout breaks	      -Ensure meta viewport tag is present.


# LICENSE & CREDITS
License: MIT (Free to use with attribution).
Credits:
        Icons: Font Awesome.
        Fonts: Google Fonts (Poppins).
        Form Handler: Google Apps Script.

