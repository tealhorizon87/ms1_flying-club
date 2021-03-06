# Flying Club

Flying club is a PPL (Private Pilot's Licence) flying club, with a selection of aircraft to rent and a full calendar of events. A link to the active page is [here](https://tealhorizon87.github.io/ms1_flying-club/).
![mockup image](assets/readme_img/mockup.png)

## Table of Contents
1. [UX](#ux)
    - [User Stories](#user-stories)
    - [Design](#design)
    - [Wireframes](#wireframes)
2. [Features](#features)
3. [Technologies Used](#technologies-used)
4. [Testing](#testing)
5. [Deployment](#deployment)
6. [Credits](#credits)
    - [Content](#content)
    - [Media](#media)
    - [Acknowledgements](#acknowledgements)
    - [Disclaimer](#disclaimer)

## UX
This is the main website for Flying Club, a general aviation flying club that organises air-shows and 'fly-in' events, allows pilots to rent aircraft, and offers experience flights to new users.

### User Stories
#### Common user stories (pilots and first-timers)
- As a user, I expect -
    - to be able to easily navigate around the site.
    - to be able to view the site from any device size.
- As a user, I want
    - to be able to see the cost of service without barriers.
    - to be able to see the location of the service.
    - to be able to  easily understand what the website does.

#### Pilot user stories
- As a user, I want
    - to see what aircraft variety there is available.
    - to see a calendar of upcoming events.

#### First-timers user stories
- As a new user, I expect to feel welcome and not intimidated by lots of technical language.
- As a new user, I want to know that the events are run by professionals.

### Design

The site is designed with four pages - index, about, fleet and events. There are links provided throughout each page to connect to other sections of the project. Each page is fully responsive, and features rearranged for smaller sized screens.

The font families used for the project are Oswald for all headings, and Lato for the main body text.

Within aviation display logic, cyan is used to display information, and magenta is an 'action' colour. The colour palette used to generate all colours in the project was generated by [coolors](https://coolors.co/).
![colour palette image](assets/readme_img/color-palette.png)

### Wireframes
Below are the wireframes that I created using [Balsamiq](https://balsamiq.com/)
#### Home
![wireframe for index.html](assets/readme_img/home.jpeg)
#### About
![wireframe for about.html](assets/readme_img/about.jpeg)
#### The Fleet
![wireframe for fleet.html](assets/readme_img/fleet.jpeg)
#### Events
![wireframe for events.html](assets/readme_img/events.jpeg)

## Features
- The site is fully responsive by using the [Bootstrap](https://getbootstrap.com/) framework.
- The site is easy to navigate by using the navbar in the header if each page, and by making the headings in the about section links to the relevant page.
- The location of the services is added by inserting [Google Maps](https://www.google.com/maps) into a frame element.
- A table is used to display upcoming events in the events page.

### Future Features
- Add a members page with more specific information targeted at a regular user.
- Add a login/sign up modal to access the members section.
- Add an interactive booking system that shows the availability of the aircraft.

## Technologies Used
### Languages:
  - [HTML5](https://en.wikipedia.org/wiki/HTML5)
      - This is the main mark-up language for the project.
  - [CSS3](https://en.wikipedia.org/wiki/CSS)
      - Used for personalised styling over and above the Bootstrap framework.

### Libraries and Frameworks:
  - [Bootstrap 4.6](https://getbootstrap.com/docs/4.6/getting-started/introduction/)
      - Used to provide the framework and facilitating responsiveness.
  - [Google Fonts](https://fonts.google.com/)
      - Used as the source for the font databases used in this site.
  - [Font Awesome 5.15.3](https://fontawesome.com/)
      - Used as the source for the icons used, including the social media links in the footer.

### Tools:
  - [Atom](https://atom.io/) with [GitHub Desktop](https://desktop.github.com/)
      - Atom is my preferred text editor, linked with GitHub Desktop in order to push the code to GitHub.
  - [Git](https://git-scm.com/)
      - Used for version control.
  - [GitHub](https://github.com/)
      - Used to store, host and publish the project files.
  - [Balsamiq](https://balsamiq.com/)
      - A wireframe program used to create the mock-ups.

## Testing

### Code Validation
My first step after publishing the page was to ask a few friends and family to go through the site and make sure all the links work and all the layouts are effective. After that was done (and minor fixes were made), I ran the code through a validator.

- An error was found with the 'Take-off' button, and was corrected:
  ![home page check](assets/readme_img/index-check.png)

- A number of errors were found in the about page, and were corrected:
  ![about page check](assets/readme_img/about-check.png)

- Both the fleet and events pages were clean:
  ![fleet and events check](assets/readme_img/fleet_events-check.png)

- The CSS stylesheet was cleared as well (only when style.css was uploaded as text. There are 2 errors and many warnings associated with the bootstrap library, and several warnings relating to the project URL regarding the custom properties. The image for this form is available [here](assets/readme_img/css-check_url.png)):
  ![CSS check](assets/readme_img/css-check.png)

### Performance
Lighthouse was used in Chrome developer tools to test the performance of the page. This was done for both mobile (top) and desktop (bottom), and for all pages. Below is the report for the home page; all other pages have similar reports.
   ![performance check mobile](assets/readme_img/lh-mobile.png)
   ![performance check desktop](assets/readme_img/lh-desktop.png)

### User Stories Evaluation
To ensure that the project fulfils the goals set out in the user stories:

Common user stories (pilots and first-timers)
- As a user, I expect -
    - to be able to easily navigate around the site.
      - __Bootstrap navbar and other clickable links around the page__
    - to be able to view the site from any device size.
      - __Bootstrap grid systems allows the site to be fully responsive__
- As a user, I want
    - to be able to see the cost of service without barriers.
      - __Service costs are 'on page' rather than 'on request'__
    - to be able to see the location of the service.
      - __A map link is provided with an iframe window and all written addresses link to external google maps site__
    - to be able to  easily understand what the website does.
      - __A bold hero image of an aircraft and an obvious name should accomplish this__

Pilot user stories
- As a user, I want
    - to see what aircraft variety there is available.
      - __All aircraft fleet types are available from the fleet page__
    - to see a calendar of upcoming events.
      - __A tabulated events list is available on the events page__

First-timers user stories
- As a new user, I expect to feel welcome and not intimidated by lots of technical language.
  - __- Any technical language has been limited to those sections that would be of interest to qualified pilots__
- As a new user, I want to know that the events are run by professionals.
  - __- This is difficult to convey, but by emphasising the use of instructors and state of the art equipment should help__

## Deployment
Deployment for this project is via GitHub Pages.
1. From the repository home page, select the 'settings' tab
2. Scroll down the menu on the left and select 'pages'
3. From the dropdown menu under 'source', select the branch that you wish to publish (usually master or main)
![pages screenshot](assets/readme_img/pages-screenshot.png)

4. Make sure that the root folder is selected and click save
![pages screenshot](assets/readme_img/pages-screenshot2.png)
5. A URL will then be displayed for the project that you can copy into other locations, or just follow to the live page.

Bear in mind that it takes up to 10 minutes for the build process so the page may not be available straight away.


## Credits
This project has been designed as part of an educational program hosted by Code Institute. This is a proof of ability page only, and as such, Flying Club and all of the events listed are not representative of any real group or event.

### Media
  - The hero image on the home page was taken from [picjumbo](https://picjumbo.com/cessna-airplane-propeller-closeup/)
  - All other images and videos are public domain and sourced from one of the following:
    - [Pixabay](https://pixabay.com/)
    - [Wikimedia](https://commons.wikimedia.org/wiki/Main_Page)

### Acknowledgements
As this is my first attempt at building a webpage from scratch, special thanks go to so many for the help and advice needed to complete this project. They include, but are not limited to:
  - [w3schools](https://www.w3schools.com/default.asp) - an essential source of support for the novice coder.
  - [Stack Overflow](https://stackoverflow.com/) - much like w3schools, an essential source of guidance...there is always someone who has had the same problem, and the answer is likely here.
  - [Code Institute](https://codeinstitute.net/) - from inspiration through all the walkthrough projects to the tools needed to complete.
  - My mentor for providing help, support and feedback.
