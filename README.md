# BIM-Dance-Studio
Website for a dance studio based in Edinburgh

[View the live website here](http://)

## TABLE OF CONTENTS
1. [INTRODUCTION](#1-introduction)
2. [USER EXPERIENCE DESIGN](#2-user-experience-design)
    - [User persona & their goals/needs](#user-persona--their-goalsneeds)
    - [Business goals](#business-goals)
    - [Wireframes](#wireframes)
    - [Design](#design)
        - [Colors](#colors)
        - [Icons](#icons)
        - [Typography](#typography)
        - [Images](#images)
        - [Mockups](#mockups)
3. [FEATURES](#3-features) 
    - [Existing features](#existing-features)
        - [Header](#header)
        - [Hero Section](#hero-section)
        - [Classes Section](#classes-section)
        - [Instructors Section](#meet-the-team-section)
4. [TESTING](#4-testing)
5. [CREDITS](#5-credits)
6. [DEPLOYMENT](#6-deployment)

## 1. INTRODUCTION

This site has been created as a business website for __a fictional Dance Studio, called BIM (Bodies in Motion) based in Edinburgh__. The studio offers adults dance classes, from beginner to advanced levels, in Ballet, Jazz, Contemporary and Afro dance.

I've created this static front-end website to showcase my knowledge of HTML and CSS, accessibility, responsitivity and UX Design. 
The design is clean, modern and elegant to reassure users about the dance studio professionality and reliability. 

## 2. USER EXPERIENCE DESIGN

### USER PERSONA & THEIR GOALS/NEEDS

Users are adults based in Edinburgh who want to:

- learn how to dance/improve their dancing skills
- be taught by qualified and trustworthy professionals
- be able to see a class timetable to decide if it would work around their schedule
- have clear pricing information
- have the chance to contact and locate easily the dance studio
- easily book a class with just a couple of clicks using their devices

### BUSINESS GOALS

- increase the amount of class participants and consequently the business revenue
- promote the dance studio online presence

### WIREFRAMES

All wireframes were created with [Figma](https://www.figma.com/) while keeping in mind the user needs and business goals, so that the result focuses on prioritizing the right content in a clear and concise way. 

[See wireframes here](docs/wireframes)

### DESIGN

- #### COLORS

I've used [Coolors](https://coolors.co/) website to generate a colour palette for the website. The palette was generated from the homepage __hero image__ and then adjusted to my personal preferences. The result is a palette that fits well with the whole design and images chosen.
I wanted to keep a good contrast between text and background, so that most of the website has been styled using a white background and the dark grey color (#2a282c) for paragraphs.
#2C343C (dark-blue color) has been mostly used for the nav bar, hero section (homepage, with a white text color for contrast), footer background and some buttons background colors. 
#c5c0b9 (creamy color) has been mainly used as a background color for some sections, buttons and headings.

![Color palette](docs/docs-images/palette.png)
- #### ICONS
Icons were needed for the social media links and have been taken from [FontAwesome](https://fontawesome.com/).

- #### TYPOGRAPHY
The chosen fonts fo the website are:
1. __Lora__, which is 
> a well-balanced contemporary serif with roots in calligraphy.

It's a modern and artistic font, mostly used for headings and buttons. It reverts to serif if not available.
2. __Nunito__ , a simple and easily readable sans serif, mainly used for the paragraphs, that pairs well with Lora.
Sans-serif is the font fallback.
- #### IMAGES
All images have been selected and taken from [Pexels](https://www.pexels.com) and then compressed and optimized using [TinyPNG](https://tinypng.com/).

- #### MOCKUPS
After all of the design details were decided and the website content composed, I've used [Figma](https://www.figma.com/) to create mockups for all of the website pages and different screen sizes so that I'd have a high-fidelity website simulation to follow as a coding guide: the result is an aesthetically pleasing design that helps satisfying the website goals.

[See mockups here](docs/mockups)

## 3. FEATURES
### EXISTING FEATURES
- #### HEADER

The header appears at the top of all of the website pages and stays consistent and responsive across all of them.
It features an absolute positioning so that it stands on top of the hero sections and has a transparent background for the hero images to come trough.
It is a flex container and flexbox properties have been used to achieve the different displays based on screen size.

![Desktop header](docs/docs-images/header.png)

On large screen sizes the logo is positioned on the left of the header, while the navigation bar is on the right.
![Tablet header](docs/docs-images/tablet-header.png)

On tablets views the header is displayed in two different rows, with the logo at the top and the nav bar below it (flex direction changed to column).

![Smartphone header](docs/docs-images/smartphone-header.png) ![Smartphone header active](docs/docs-images/smartphone-header-active.png)

In smaller screen sizes the header goes back to display the logo on the left, with the difference that now the navigation bar has been replaced by an hamburger menu.

- #### HERO SECTION

The hero section showcases the dance studio flair: with a catchy background image overlayed by a captivating intro about the website objective, it also contains an immediate call to action for users to book a class.

![Hero section](docs/docs-images/hero-image-section.png)

- #### CLASSES SECTION

After a brief introduction, the classes section under the hero displays a grid of the dance genres taught in the studio (paired with an image) and a button that links to the "Classes & Prices" page. It's a further aid for navigation purposes and encourages users to discover more and feel more engaged with the brand.

![Classes section](docs/docs-images/classes-section.png)

- #### MEET THE TEAM SECTION

This section of the homepage reassures the user about the studio reliability. It also provides a link to the "Instructors" page of the website.

![Instructors section](docs/docs-images/meet-the-team.png)

## 4. TESTING

## 5. CREDITS

## 6. DEPLOYMENT
