# Website Name
The History of Egypt


## Introduction

This is a website devoted to the amazing history of ancient Egypt. Its purpose is to create a club of people who would like to learn more about Egypt, travel with others for this purpose and contribute with their photos if they want.

![Project-1_Screeshots_of_Resolutions](https://github.com/user-attachments/assets/3918ffa8-461e-43f9-a74b-9908364165be)

## Overview

This is a simple website project with the following key pages:
- **Homepage**: Provides information about the site.
- **Gallery**: Displays images.
- **Signup Page**: Allows users to sign up and create an account.
- **Newsletter Page**: allows users to subscribe to regular updates and newsletters.

## Table of Contents
- [Technologies Used](#technologies-used)
- [Features](#features)
- [Testing](#testing)
- [Bugs](#bugs)
- [Validator Testing](#validator-testing)
- [Unfixed Bugs](#unfixed-bugs)
- [Deployment](#deployment)
- [Credits](#credits)

## Technologies Used
- HTML5
- CSS
- Backend: Node.js / PHP / Python (depending on your stack)

## Features
- **Navigation** :
 Placed at the top of the page, the navigation shows the group name in the left corner: The History of Egypt which links to the homepage, everytime you wish to come back there. In the right corner of the page you will find the links to the rest of the pages of the website (Gallery, Sign Up and Contact). As well as find a "Home" Button that leads back to the homepage, for the people who are not so familiar with the internet.
- **Homepage**: A user-friendly landing page introducing the site.
  The header gives the names of museums, or places the club visits (they are customisable to fit the clients' needs).
  Above the Footer two buttons, one for Gallery and another for Newsletter, are added. Their purpose is to guide the users to see the exciting things they will miss unless they join and also a shortcut for the Newsletter for those who are already informed about the club.
- **Gallery**: Showcases a collection of images.
- **Signup**: A form for users to register an account. All the fields apart from the "Username" are required. Once a user signs up, they will be led to a success page.
- **Newsletter**: Subscription form for users to receive periodic emails. All the fields are required. Once a user subscribes, they will be led to a success page.

## Testing

- I tested that this page works in Google browser.
- I confirm that the navigation, header, gallery, sign up and newsletter text are readable and easy to understand.
- I have confirmed that the forms work: require almost all fields, will only acceot an email in the email and submit buttons work.

## Bugs

**Solved Bugs**
When I deployed mz project to GitHub Pages I discovered that not all the links were working, some pictures weren't in the right place and the webpage wasn't responsive for larger screens.
- Regarding the links (Gallery and Newsletter buttons) I discovered that I had to change the page links to the links used in the index.html. Then they were working.
- Regarding the responsive behavior of the pictures I had to change the padding and margins and use Flex-box properties. Now they are responsive.

## Validator Testing

1. HTML
   No errors were returned when passing through the official W3C validator
2. CSS
   No errors were returned when passing through the official W3C validator
3. Accessibility
   I confirmed that the colors and fonts chosen are easy to read and accessible


## File Structure
yourproject/
│
├── index.html            # Homepage
├── gallery.html          # Gallery page
├── signup.html           # Signup page
├── newsletter.html       # Newsletter page
├── css/
│   └── styles.css        # Styling file for Home and the main style of the full webpage
│   └── gallery.css       # Styling file created to apply specific styling on Gallery so, that it does affect the other pages or the website
│   └── newsletter.css    # Styling file created to apply specific styling on Newsletter so, that it does affect the other pages or the website
│   └── signup.css        # Styling file created to apply specific styling on Signup so, that it does affect the other pages or the website
│   └── success.css       # Styling file created to apply specific styling on Signup Success so, that it does affect the other pages or the website
│   └── newsletter-success.css   # Styling file created to apply specific styling on Newsletter Success so, that it does affect the other pages or the website
├── images/               # Folder for images used in the gallery, and homepage. Relative paths of this folder have been used on the Homepage and Gallery
│   └── ...
├── README.md             # Project documentation

## Unfixed Bugs

No unfixed Bugs

## Deployment
 
The Webpage was deployed ro GitHub pages. The steps to deploy are as follows:
1. In the GitHub repository, navigate to the Settings tab
2. From the source section drop-down menu select Master Branch
3. Once the master branch has been selected, the page provides the link to the completed website

## Credits

**Content**
The code to make the social media links was taken from online free resources.

**Media**
The image in the header was taken from Freepik.

This `README.md` file serves as a guide for anyone working on or using the website, detailing its structure, usage, and contribution guidelines. You can customize it based on the specifics of your project.

Thank you!
