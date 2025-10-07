================================================================================
                    IDLEMASTER WEBSITE - README
================================================================================

Thank you for using the IdleMaster website template! This is a professional, 
modern, and fully responsive multi-page website built with HTML, CSS, and 
JavaScript.

================================================================================
                        TABLE OF CONTENTS
================================================================================

1. File Structure
2. How to Run the Site Locally
3. Customization Guide
   - Changing Colors
   - Updating Links
   - Modifying Content
   - Replacing Google Form
   - Updating GitHub Link
   - Changing Download Link
4. Responsive Design
5. Browser Compatibility
6. SEO Optimization
7. Support & Credits

================================================================================
                        1. FILE STRUCTURE
================================================================================

The website consists of the following files:

├── index.html          - Home page with hero section and features
├── about.html          - About page with mission and vision
├── contact.html        - Contact page with Google Form button
├── download.html       - Download page with download button
├── style.css           - All styling and responsive design
├── script.js           - Interactive JavaScript functionality
└── README.txt          - This file (instructions and documentation)

================================================================================
                    2. HOW TO RUN THE SITE LOCALLY
================================================================================

OPTION 1: Direct Method
------------------------
1. Extract all files to a folder on your computer
2. Double-click on "index.html" to open it in your default web browser
3. Navigate between pages using the navigation menu

OPTION 2: Local Server (Recommended for Development)
-----------------------------------------------------
If you have Python installed:
1. Open Command Prompt or Terminal in the website folder
2. Run: python -m http.server 8000
3. Open browser and go to: http://localhost:8000

If you have Node.js installed:
1. Install live-server: npm install -g live-server
2. Open Command Prompt in the website folder
3. Run: live-server
4. Browser will open automatically

OPTION 3: Using VS Code
------------------------
1. Open the folder in Visual Studio Code
2. Install "Live Server" extension
3. Right-click on index.html and select "Open with Live Server"

================================================================================
                        3. CUSTOMIZATION GUIDE
================================================================================

A. CHANGING COLORS
------------------
All colors are defined in style.css at the top using CSS variables.
Open style.css and find the :root section (around line 10):

    :root {
        --primary-color: #D10000;      /* Main brand color (red) */
        --secondary-color: #EFEFEF;    /* Light gray background */
        --white: #FFFFFF;              /* White color */
        --text-dark: #2C2C2C;          /* Dark text color */
        --text-light: #666666;         /* Light text color */
    }

To change colors:
1. Replace the hex color codes (e.g., #D10000) with your preferred colors
2. Save the file
3. Refresh your browser to see changes

Example: To change the primary red to blue:
    --primary-color: #0066CC;


B. UPDATING LINKS
-----------------

Google Form Link (Contact Page):
1. Open contact.html
2. Find this line (around line 59):
   href="https://docs.google.com/forms/d/e/1FAIpQLSf..."
3. Replace the URL with your new Google Form URL
4. Save the file

GitHub Repository Link:
1. Open any HTML file
2. Find: href="https://github.com/subtitle-edit/Idle-Master"
3. Replace with your GitHub repository URL
4. Update in ALL HTML files (index.html, about.html, contact.html, download.html)

Download Link:
1. Open download.html
2. Find: href="https://idlemaster.net/download/"
3. Replace with your download URL
4. Save the file

Official Website Link:
1. Open index.html
2. Find: href="https://idlemaster.net/"
3. Replace with your official site URL
4. Also update in footer sections of all pages


C. MODIFYING CONTENT
--------------------

To change text content:
1. Open the relevant HTML file
2. Find the section you want to modify
3. Edit the text inside the HTML tags
4. Keep the HTML tags intact, only change the text
5. Save and refresh browser

Example:
To change the hero title in index.html:
<h1 class="hero-title">Welcome to IdleMaster</h1>
Change "Welcome to IdleMaster" to your desired text.


D. CHANGING KEYWORDS
--------------------

The website uses "idlemaster" as a focus keyword in index.html.
To update or add keywords:

1. Open index.html
2. Find the keyword link (around line 67):
   <a href="https://idlemaster.net/">idlemaster</a>
3. Replace "idlemaster" with your keyword
4. Replace the URL with your target URL

Note: Keep keyword usage natural and contextually relevant.


E. UPDATING SITE NAME AND BRANDING
----------------------------------

To change "IdleMaster" to your own brand name:
1. Use Find & Replace in your text editor
2. Find: IdleMaster
3. Replace with: Your Brand Name
4. Do this for ALL HTML files
5. Also update in style.css comments if needed


F. MODIFYING NAVIGATION MENU
----------------------------

To add/remove navigation items:
1. Open any HTML file
2. Find the <ul class="nav-menu"> section
3. Add or remove <li> items
4. Example to add a new link:
   <li><a href="newpage.html" class="nav-link">New Page</a></li>
5. Update navigation in ALL HTML files for consistency


G. CHANGING FONTS
-----------------

The site uses "Poppins" font from Google Fonts.
To change the font:

1. Visit: https://fonts.google.com
2. Select your desired font
3. Copy the font link
4. Open each HTML file
5. Replace this line in the <head> section:
   <link href="https://fonts.googleapis.com/css2?family=Poppins..." rel="stylesheet">
6. Open style.css
7. Find: font-family: 'Poppins', ...
8. Replace 'Poppins' with your new font name

================================================================================
                        4. RESPONSIVE DESIGN
================================================================================

The website is fully responsive and works on:
- Desktop computers (1200px and above)
- Tablets (768px - 1199px)
- Mobile phones (below 768px)

The responsive breakpoints are defined in style.css:
- @media (max-width: 768px) - Tablets and mobile
- @media (max-width: 480px) - Small mobile phones

You can adjust these breakpoints in style.css if needed.

================================================================================
                        5. BROWSER COMPATIBILITY
================================================================================

The website is compatible with:
✓ Google Chrome (latest)
✓ Mozilla Firefox (latest)
✓ Microsoft Edge (latest)
✓ Safari (latest)
✓ Opera (latest)

Minimum browser versions:
- Chrome 60+
- Firefox 60+
- Edge 79+
- Safari 12+

================================================================================
                        6. SEO OPTIMIZATION
================================================================================

The website includes basic SEO optimizations:

1. Meta Tags: Each page has title and description meta tags
2. Semantic HTML: Uses proper HTML5 semantic elements
3. Alt Text: Add alt attributes to images when you add them
4. Internal Linking: Pages are linked together
5. Mobile-Friendly: Fully responsive design
6. Fast Loading: Minimal external dependencies

To improve SEO further:
1. Add alt text to any images you include
2. Create a sitemap.xml file
3. Add robots.txt file
4. Optimize images for web (compress them)
5. Add structured data (JSON-LD)
6. Submit to Google Search Console

================================================================================
                        7. SUPPORT & CREDITS
================================================================================

This website template was created with:
- HTML5 for structure
- CSS3 for styling and animations
- Vanilla JavaScript for interactivity
- Google Fonts for typography

Features included:
✓ Responsive navigation with mobile menu
✓ Smooth scroll animations
✓ Hover effects and transitions
✓ Page transition effects
✓ Scroll animations for elements
✓ Dynamic copyright year
✓ Ripple button effects
✓ Modern gradient backgrounds
✓ Clean and professional design

Design inspired by: https://idlemaster.net/
Color palette: #EFEFEF, #FFFFFF, #D10000

Designed & Developed by: Professional Web Solutions

================================================================================
                        ADDITIONAL TIPS
================================================================================

1. Always backup your files before making changes
2. Test changes in multiple browsers
3. Optimize images before adding them to the site
4. Keep file names lowercase and use hyphens instead of spaces
5. Validate HTML: https://validator.w3.org/
6. Validate CSS: https://jigsaw.w3.org/css-validator/
7. Test mobile responsiveness: Use browser dev tools
8. Compress CSS and JS for production deployment
9. Use HTTPS when hosting the site online
10. Keep content fresh and updated regularly

================================================================================
                        HOSTING THE WEBSITE
================================================================================

To make your website live on the internet:

1. Choose a hosting provider (e.g., Netlify, Vercel, GitHub Pages, HostGator)
2. Upload all files to the hosting server
3. Configure your domain name
4. Enable HTTPS/SSL certificate
5. Test all pages and links

Free hosting options:
- GitHub Pages: https://pages.github.com/
- Netlify: https://www.netlify.com/
- Vercel: https://vercel.com/
- Cloudflare Pages: https://pages.cloudflare.com/

================================================================================
                        TROUBLESHOOTING
================================================================================

Problem: Navigation menu not working on mobile
Solution: Ensure script.js is properly linked and loaded

Problem: Colors not appearing correctly
Solution: Clear browser cache or hard refresh (Ctrl+F5)

Problem: Links not working
Solution: Check that all href attributes have correct URLs

Problem: Page not loading properly
Solution: Ensure all files are in the same directory

Problem: Fonts not loading
Solution: Check internet connection (fonts load from Google)

================================================================================

For questions or support, please contact through the contact page.

Thank you for using the IdleMaster website template!

Last Updated: 2024
Version: 1.0

================================================================================
