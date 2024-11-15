# Mindful Waters Foundation

![Mindful Waters Foundation - Project Banner](/documentation/images/banner.png)


<p align="center">
| <a href="https://a-sousarodrigues.github.io/mindful-waters-foundation/" target="_blank">Live Project</a> |
</p>

## Introduction 

"Calm Waters Foundation" is my first assessed portfolio project, developed as part of the Code Institute Full Stack Software Developer Bootcamp. This project showcases my skills in HTML5, CSS3, and Bootstrap to create a responsive, accessible website dedicated to mental health awareness. The site is designed to provide users with essential mental health information, stress management tips, and resources for support. Through a clean, calming layout and structured content, Calm Waters Foundation aims to create an inclusive, supportive environment for all visitors while fulfilling the requirements of the provided brief focused on accessible, user-centered design

The live project can be found here: <a href="https://a-sousarodrigues.github.io/mindful-waters-foundation/" target="_blank">Mindful Waters Foundation</a>

<h2 align="center" id="TOC">Table of Contents</h2>

* [Mindful Waters Foundation](#mindful-waters-foundation)
  - [Introduction](#introduction)
  - [Table of Contents](#TOC)
  - [Project Ouline](#project-outline)
* [Project Planning](#project-planning)
  - [UX Design](#ux-design)
    - [User Stories](#user-stories)
    - [Colors](#colors)
    - [Fonts](#fonts)
    - [Imagery](#imagery)
    - [Wireframes](#wireframes)
* [Features](#features)
  - [General Features](#general-features)
    - [Navigation and Hero Section](#navigation-and-hero-section)
    - [Bootstrap Cards](#bootstrap-cards)
    - [Policies Section](#policies-section)
    - [Footer](#footer)
    - [Links and Buttons](#links-and-buttons)
  - [Resnposive Design](#responsive-design)
* [Built With](#built-with)
  - [Technology and Languages](#technologies-and-languages)
  - [Libraries and Frameworks](#libraries-and-frameworks)
  - [Tools & Programs](#tools-and-programs)
* [Development](#deployment)
* [Testing](#testing)
* [Credits](#credits)
  - [Code](#code)
  - [Content Research](#content-research)
  - [Media](#media)
  - [Acknowledgements](#acknowledgements)


<p align="right"><a href="#mindful-waters-foundation">Back To Top</a></p>

## Project Outline

### External User’s Goal: 
The user seeks accessible, beginner-friendly information on mental health, including how to recognize common issues and manage stress, presented in a supportive and organised layout.

### Site Owner’s Goal: 
The site owner wants to create a welcoming webpage that provides basic mental health information using a clean and supportive design. The focus is on using HTML and CSS with Bootstrap to create a calming and well-organised user experience.


### Key Objectives

- Design and implement an interactive front-end web application using HTML and CSS based on user experience design principles, accessibility, and responsiveness.
- Test and validate the web application through the development, implementation, and deployment stages.
- Deploy the one-page web application to a cloud platform.
- Maximise future maintainability through documentation, code structure, and organisation.
- Leverage AI tools to orchestrate the software development process.


## Project Planning

### UX Design

### User Stories 

- I am the site owner who wants to create a supportive environment. I want the page to have a welcoming hero section with positive messaging so that users feel encouraged to learn more about mental health and seek help if needed.

- I am a user interested in learning about common mental health issues. I want clear, concise information presented in a structured way so that I can understand the basics without needing to dig through too much text.

- As a user concerned about privacy, I want reassurance that my information is protected so that I feel safe interacting with the website, especially if I log or track anything personal.

- I am someone looking for ways to manage stress. I want quick tips and helpful advice organized in an easy-to-read format so that I can apply them to my life right away.

- I am a site owner aiming for a responsive design. I want the page to adjust seamlessly on any screen size so that users on different devices can access the content without issues.

- I am a visitor seeking basic mental health information. I want a simple, calming layout so that I can easily find the information without feeling overwhelmed.

- I am a user interested in uplifting messages. I want to read positive affirmations so that I can feel encouraged and motivated while browsing the site.

- I am a person who may need additional resources for mental health support. I want a list of reputable links to mental health organizations so that I can access further information and support if needed.

- As a teacher seeking to support my students, I want educational materials or activities that I can use in my classroom so that I can promote mental wellness among students.

- As a user interested in mental health events, I want a calendar or list of upcoming webinars and workshops so that I can participate in live learning opportunities.


<hr>
<p align="right"><a href="#mindful-waters-foundation">Back To Top</a></p>

## Colors



### Main Palette

The colour scheme should create a calm environment and have easy readability in order to reduce cognitive load for the user. The following colours are what I landed on:

- Title and subtitles: '#4D4D4D'
- Body text: '#2C3E50'
- Header and footer: '#b9ccb';
- Background: '#F9FAFB'
- Primary button: '#B39DDB'
- Secondary button: '#D4A5A5'
- Links: '#5E548E'

![Color Palette](/documentation/images/pallete.png)
<hr>
<p align="right"><a href="#mindful-waters-foundation">Back To Top</a></p>

## Fonts

Similar to colour, the font should be easy to read. Three differnt fonts were needed; titles, body, and quotes. These were implemnted through [Google Fonts](https://fonts.google.com) using a direct import code within the style.css file.

[Lato](https://fonts.google.com/specimen/Lato) was used for headings.

[Roboto](https://fonts.google.com/specimen/Roboto) was used for body text.

[Caveat](https://fonts.google.com/specimen/Caveat) was used for quotes to add some flourish.


<hr>
<p align="right"><a href="#mindful-waters-foundation">Back To Top</a></p>

### Wireframes

 

**Mobile Wireframe**

![Mobile Wireframe](/documentation/images/wireframe-mobile.png)

**Tablet Wireframe**

![Tablet Wireframe](/documentation/images/wireframe-tablet.png)

**Desktop Wireframes**

![Desktop Wireframe 1](/documentation/images/wireframe-web.png)

<hr>
<p align="right"><a href="#mindful-waters-foundation">Back To Top</a></p>

## Imagery

I wanted the hero image to be light and relaxing, to ease the user into the website. Therfore opted for an AI generated image. For the background images on cards I decided to use royalty free photos relating to the specific card as overuse of AI images can look tacky and unapealing. 

<hr>
<p align="right"><a href="#mindful-waters-foundation">Back To Top</a></p>

## Features

### General Features

#### Navigation and Hero Section

I decided to make a calm and relaxing hero section, using an ai image for the background. This section features a CTA button that opens a modal form to reach out for help.

The navigation bar is a Bootstrap component that allows for easy navigation around the site using a familiar method for a positive user experience.

![Header](/documentation/images/header.png)

#### Bootstrap Cards

Bootsrap cards were used for the stress tips section, to layout quick actionable tips. Each card has a learn more button should link to the specific section on the additional resources page.

![Bootstrap Cards](/documentation/images/card.png)

#### Bootsrap accordian

The bootstrap accordian was used for the common mental health issues page so that the user wouldn't be bombarded with text. It allows the user to seek the specific topic they wouldlike to read more about and access the content for that topic step by step.

![Bootstrap Accordians](/documentation/images/accordian.png)

#### Bootstrap Carousel

I used a bootstrap carousel to display motivational quotes. A background image was added to make it more visually appealing. Furthermore, auto-slide was turned off to reduce cognitive load, allowing the user to go through the quotes at their own pace.

![Bootstrap Carousel](/documentation/images/carousel.png)

#### Privacy agreement

I created an additional web page designated for the privacy agreement so that users can feelsafe about the processing and holding of their data.

![Privacy Page](/documentation/images/privacy.png)

#### Footer

For the footer I used bootsrap utilities so that it sticks to the bottom of the page. The footer includes contact information as well as links to social media platforms and the privacy agreement.

![Footer](/documentation/images/footer.png)

#### Links and Buttons

Buttons were customised to their specific role and page layout. This is so that they stand out from their backgrounds and provide uniform function based on design. This was implemnted by customising the btn-primary and btn-secondary bootsrap classes.

#### Future development

With more time I would create the additional resources page and link it to the appropriate buttons. This page would go into more details about how to manage stress, with embeded videos to provide user interaction.

<hr>
<p align="right"><a href="#mindful-waters-foundation">Back To Top</a></p>

### Responsive Design

This project was made responsive by utilising bootstrap's grid system as well as a couplemedia queeries.

![Responsive Design](/documentation/images/responsive.png)

<hr>
<p align="right"><a href="#mindful-waters-foundation">Back To Top</a></p>


## Built With

### Technologies and Languages

- HTML5
- CSS3
- GitHub
- Gitpod

### Libraries and Frameworks

- Bootstrap 5.3.3
- Font Awesome
- Google Fonts

### Tools and Programs

- Balsamiq
- Squoosh
- ChatGPT
- MS CoPilot
- GitHub CoPilot
- Microsoft Designer

<hr>
<p align="right"><a href="#mindful-waters-foundation">Back To Top</a></p>

## Deployment

This [GitHub](https://github.com/) project was created using the [Code Institute Template](https://github.com/Code-Institute-Org/ci-full-template) ensuring all necessary dependencies were included when opening within the designated workspace on the [Gitopod IDE](https://www.gitpod.io/).

Setup a repo using this method and template:
1. Login to your GitHub profile.
2. Navigate to the Code Institute Full Template
3. Click the dropdown for 'Use this template' and select "Create a new repository"
4. Generate the necessary name and description for your repo and click 'Create repository from template'
5. Navigate to the new repo and click the green 'Open' button with the Gitpod logo<br>
**IMPORTANT - This button should only be clicked once to generate the new IDE workspace**
6. You can now work on your repository within the Code Institute Gitpod IDE workspace

Once the project repo is created, an early deployment for the live project should performed.<br>
This allows for early and continuous testing using a variety of devices, as well as the Dev Tools available within browsers.

Additional information on the deployment process can be found on the official [GitHub Docs](https://docs.github.com/en/pages/quickstart)


<hr>
<p align="right"><a href="#mindful-waters-foundation">Back To Top</a></p>

## Testing

### Validation

#### CSS

No errors found. 3 warnings arisen from importing google fonts which are outside of the scope of this project.

![CSS Validation](/documentation/images/css-validation.png)

#### HTML

No errors found.

![HTML Validation](/documentation/images/html-validation.png)

### Lighthouse

A Lighthouse audit was conducted using the tool on Chrome Devtools of each web page.

Home page:

![Home Page](/documentation/images/lighthouse-home-web.png)

Mental Health Basics page:

![HMental Health Basics Page](/documentation/images/lighthouse-mental-web.png)

Stress Tips page:

![tress Tips Page](/documentation/images/lighthouse-stress-web.png)

Privacy page:

![Privacy Page](/documentation/images/lighthouse-privacy-web.png)

<hr>
<p align="right"><a href="#mindful-waters-foundation">Back To Top</a></p>

## Credits

### Code

Project and primary learning supplied by [Code Institute](https://codeinstitute.net/ie/)<br>
Learning and parts of code supplied by Github Copilot.

### Media

All photos aquired from [Unsplash](https://unsplash.com/).
Hero image and favicon made by Microsoft Copilot.

<hr>
<p align="right"><a href="#mindful-waters-foundation">Back To Top</a></p>