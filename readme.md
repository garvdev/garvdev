
# T1A2 - Portfolio

### Coder Academy<br>Sydney Fast-Track Bootcamp 2021

##### Garvey Chan

<hr>

Website Link - https://garvdev.com

Github Link - https://github.com/garvdev/garvdev

<hr>

### Description / Purpose

This website was developed over Week 3 of the Coder Academy Fast-Track Bootcamp in 2021 for Term 1 - Assignment 2 to showcase basic HTML/CSS abilities and serve as a practical learning experience for the theory covered in the program thus far. While finished with respect to the requirements of the assignment, it is a perpetual work-in-progress as my skills and knowledge continue to develop.

Since the initial draft was presented halfway through Week 3, there have been several design changes to what was outlined in the slides, including but not limited to:
- Colour palette simplification;
- Element positioning tweaks;
- Removal/Addition/Modification of several components.

These change decisions were made due to time restrictions during implementation, diminishing returns on effort, and further UI/UX considerations. Forgoing JavaScript for this assignment was a self-imposed rule in order to force myself to seek out and explore the full potential of HTML/CSS to entrench my understanding of its capabilities.

There is also plenty of scope for **code refactoring**. This is because a bulk of the website was planned and built before I fully understood the complexities of responsive design elements and the interactions between box models and flexboxes. A large number of the final design tweaks have been applied as 'band-aid solutions' rather than through refinement of the underlying styling roots. Given more time, I would rebuild the website from the ground up using **Grids**, develop better **cascading hierarchies** to align with more **structured and distinct HTML components**, implement better **naming conventions** and aim for a more modern 'flat' **aesthetic**.

### Functionality / Features

The website contains several key components styled around a common theme and utilised throughout each page.

##### Navigation Bar (Desktop)

- The navigation bar is a consistent element across each page on the website. 
- The links will change depending on what page the user is currently on.
- It has been designed as a fixed flexbox with several components:
    - Logo (top left) - This takes the user back to the homepage.
    - Navigation Buttons (center) - Links to each page on the website. The button of the current page takes the user back to the top. Hovering over these buttons highlights them.
    - *Buffers* - Invisible elements with different flex properties separating the edge and middle buttons. These grow/shrink at different rates to the rest of the navigation bar.
    - Contact Button (top right) - This takes the user to the contact page.
- The header has been set to stand out with a *box-shadow* and a *z-index* of 10 to keep it above all the other content.

![Desktop Navigation Bar](./docs/feature-screenshots/nav-bar.png)

##### Navigation Bar (Mobile)

- When switching to mobile view, the navigation bar collapses and undergoes the following changes:
    - Center navigation buttons are hidden.
    - Logo shifted into the center and takes user back to the top when clicked.
    - Menu dropdown becomes available on the top left. When clicked, all pages on the website are shown.
    - Contact button switched from text to icon.

![Mobile Navigation Bar](./docs/feature-screenshots/nav-bar-mobile.png)

##### Main Sections

*Articles/Figures - Image & Text*
- The main sections are comprised of either text, images or a combination of both.
- Variations of these sections exist throughout the website.
- They are usually flexboxes with either row or column flow depending on the style requirements of their content.

![Image-Text](./docs/feature-screenshots/image-text.png)
![Article](./docs/feature-screenshots/article.png)

- A notable variation of the sections described above is the gallery.
- This section is comprised of images with minimal text, designed to quickly display graphical content. However, they can have special hover functions which provide more context for each image.

*Gallery*
![Gallery 1](./docs/feature-screenshots/project-gallery.png)
![Gallery 2](./docs/feature-screenshots/blog-gallery.png)

##### Footer

- The footer is a simple component set to reside after all the other sections on every page in the website.
- It contains attributions and social media links.
- When switched to mobile, the content is stacked on top of one another.

![Footer](./docs/feature-screenshots/footer.png)


### Sitemap

![Sitemap](./docs/sitemap.png)

### Screenshots

![Index-1](./docs/site-screenshots/index-1.png)
![Index-2](./docs/site-screenshots/index-2.png)
![Index-3](./docs/site-screenshots/index-3.png)
![Resume](./docs/site-screenshots/resume.png)
![Projects-1](./docs/site-screenshots/projects-1.png)
![Projects-2](./docs/site-screenshots/projects-2.png)
![Blog](./docs/site-screenshots/blog.png)
![Contact](./docs/site-screenshots/contact.png)

|![Mobile Dropdown](./docs/site-screenshots/mobile-dropdown.png)|![Mobile Index](./docs/site-screenshots/mobile-index.png)|![Mobile Resume](./docs/site-screenshots/mobile-resume.png)|
|:---:|:---:|:---:|
|![Mobile Projects](./docs/site-screenshots/mobile-projects.png)|![Mobile Blog](./docs/site-screenshots/mobile-blog.png)|![Mobile Contact](./docs/site-screenshots/mobile-contact.png)|

### Target Audience

The target audience of this website is comprised of the wonderful educators at Coder Academy. Future iterations will serve to display my work, knowledge, and experience for potential recruiters. This repository will then be archived for historical and humorous purposes.

### Tech Stack

This website was written using HTML and CSS with the help of development tools including VSCode, Chrome Developer Tools, Github Version Control, and Trello. This website has been deployed via Github Pages with a custom domain from Namecheap.

![Trello](./docs/dev-screenshots/trello.png)
![VSCode](./docs/dev-screenshots/vscode.png)
![VSCode Extensions](./docs/dev-screenshots/vscode-ext.png)
![Git](./docs/dev-screenshots/git-diff.png)
![Chrome Developer Tools](./docs/dev-screenshots/chrome-dev.png)
![Chrome Developer Tools - Mobile](./docs/dev-screenshots/chrome-dev-mobile.png)
![W3C Markup Validator](./docs/dev-screenshots/w3c-markup.png)