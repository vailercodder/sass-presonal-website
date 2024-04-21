# sass-presonal-website
Introductions
This document provides an overview of my personal website, designed to showcase my skills and projects as a web developer. The website is built using a combination of Bootstrap for responsive design and SASS for advanced styling capabilities.

Key Features
Responsive Design: Utilizes Bootstrap's grid system to ensure the website looks great on all devices, from phones to desktops.
Custom Styling: Enhanced visual appeal with SASS, allowing for complex styles with variables, mixins, and nested rules.
Interactivity: Implements dynamic CSS effects for user interaction, such as hover effects on portfolio cards.
Technologies Used
HTML5: For structuring the content of the website.
CSS3/SASS: Used for styling. SASS enhances CSS with features like variables, nested rules, and mixins that make the CSS more maintainable.
Bootstrap 5: For responsive layouts and components that ensure the website is mobile-friendly and accessible across all devices.
JavaScript: Minimal usage for enhancing interactivity and handling form submissions.
Sections of the Website
Home
The home section provides a brief introduction about myself and a navigational guide to the rest of the website.

About Me
This section includes a detailed biography, a professional photo, and highlights of my skills and interests.

html
Copy code
<section class="about-me">
  <div class="container">
    <h2>About Me</h2>
    <!-- Content -->
  </div>
</section>
Portfolio
Showcases a selection of recent projects, each displayed in a card layout. Each card includes a project image, title, and brief description, along with a link to view more details.

scss
Copy code
.portfolio-card-a {
  background: url("/path/to/image.jpg") no-repeat center;
  background-size: cover;
}
Contact
Contains a contact form that allows visitors to send messages directly through the website, integrated with backend technology for email handling.

Project Structure
Root Directory: Contains index.html and main.scss files.
CSS Directory: Includes the compiled CSS from SASS.
Images Directory: Stores all images used in the website.
JS Directory: Contains JavaScript files for additional functionality.
Compilation
SASS files are compiled to CSS using the command:

bash
Copy code
sass --watch main.scss:main.css
This command watches the SASS file for changes and automatically compiles it to CSS whenever the file is saved.

Version Control
The project is maintained using Git, with regular commits to track changes and updates.

Conclusion
My personal website serves as a comprehensive showcase of my abilities as a web developer. It combines effective design, advanced CSS techniques with SASS, and responsive Bootstrap layouts to create an engaging user experience.
