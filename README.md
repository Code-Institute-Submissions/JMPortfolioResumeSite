# *Portfolio|Resume Project*
## MilestoneProject1 - UserCentricFrontendDevelopment

## Table Of Contents
1. [Description](#Description)
2. [UX](#UX)
3. [UserStories](#UserStories)
4. [Wireframes](#Wireframes)
5. [Features](#Features)
6. [FutureFeatures](#FutureFeatures)
7. [Fonts](#Fonts)
8. [Pages](#Pages)
9. [Testing](#Testing)
10. [Deployment](#Deployment)
11. [Technologies](#Technologies)
12. [ViewProject](#ViewProject)
13. [Acknowledgements](#Acknowledgements)

## Description

This website will attempt to present my skills, experience and ongoing project work through the Code Institute program. 
Potential employers and collaborators will be able to view skill updates, career updates and ongoing projects I have been involved with aswell as being able to contact me directly through the Contact Form or Social Media sites.
The website will also give the user an insight into my past, what has driven me to pursue software development and hopefully many reasons to hire/collaborate with me on future projects.

## UX

The site has been designed to immediately capture the eye of users by purposely going against the current status quo of minimalistic designs by introducing bursts of abstract geometric colouring throughout and breaking these colours with linear gradient margins and grey scaled images. 
The User experience does not suffer as a result of adding this creativity and usability has been kept clean, concise with the website broken into easily identifiable sections. 

## UserStories

* Potential Employers, User to have the ability to read insights about my career to date and my future vision.
* Potential Employers & Collaborators, I want to showcase the skills I have in an interesting/captivating way.
* Potential Employers, Collaborators, Customers, I want to showcase my projects to date to attract opportunies to anyone visiting my site.
* Everyone, I want everyone to have the ability to contact me for any queries or requests they may have as a result of viewing my content.
* Everyone, I want everyone to have the ability to follow me on social media for interesting updates and project/product releases.

## Wireframes

All wireframes for this website were created using Balsamiq Mock up tool.

1. [DesktopWireFrame](libraries/desktopmockup.png)
2. [MobileWireFrame](libraries/mobilemockup.png)

## Features

* Hamburger Nav Bar on Desktop and Mobile to focus attention on landing screen.
* Animated headings to showcase skillset.
* Overall Responsive Design (hover on desktop / touch on mobile).
* Social Media Links.
* Contact Form.
* Resume/CV external link included.
* All links open in new tab.
* Linear multi-coloured gradient margin lines to seperate sections.

## FutureFeatures

In the future I would like to add the following features;
* A Light/Dark Version of the Website (color would turn to greyscale).
* A professional photo to the about section.
* Javascript to allow smooth scrolling on Mobile Devices.
* The ability for the contact form to email me directly.
* Animations to the skills section.
* Further interesting projects I will be working on in future.
* More skills and links within circles to relevant information.
* Link real life work related social media sites to promote myself.


## Fonts

* GoogleFonts.


## Pages

1. about.html - will give users insights into who I am and what I want to achieve.
2. skills.html - will allow users to view my skill set/abilities in a captivating way.
3. projects.html - will allow users to view my current projects and upcoming projects ideas they may wish to collaborate on.
4. contact.html - will allow everyone who visits the site to contact me directly with any queries or requests.
5. resumé.html - gives potential employers/recruiters the opportunity to view and download my CV.

## Testing

Test | Outcome
------------ | -------------
W3C validation for HTML | Failed on 'Display: Max Content' - investigated and decided to leave in my project as it sizes my content appropriately & appears to be a newer feature which may not have a test built into the HTML Validator yet. 
W3C validation for CSS | Passed
Chrome developer tools (debugging and responsiveness testing) | Passed
Samsung A50 | When using the site on this type of mobile the bodys linear gradient background colors took over the entire screen and covered 60% of my content, after some debugging, I solved the issue by removing the Media Blend function from my css.
Iphone 7 | Image wasn't rendering correctly on this type of mobile, after some investigation and debugging, I figured out the problem was caused by the Background Attachment: fixed function which has been discontinued on mobile. I solved this issue while still implementing the same functionality by using media queries for mobile and standardizing the img {} attachment as position:fixed. 
Iphone X | Image rendered perfectly when vertical but rendered incorrectly when hotizontal - solved with media queries
Friends & Family Testing | Issue seeing some details on skills and projects section parts of the background images - solved by darkening the background colour of the content and scaling up the image on hover
Friends & Family Testing | Nav bar was being interfered with when collapsed by the H1 span - solved by reducing passing between Hyperlink list and Nav Toggle Button
External Links | External links didn't open in a new tab - Solved by adding _Blank function
Overflow Content CSS | Body colours were overflowing due to width set at 100% (plus padding) - Solved by replacing 100vw and 100% widths as I also had padding which was increasing the width to over 100% screen size
Screen 100%+ | Horizontal scroll bar causing a jump when loading due to width set at 100% (plus padding) Solved by replacing 100vw and 100% widths as I also had padding which was increasing the width to over 100% screen size


Browser Test | Outcome
------------ | -------------
 Chrome | Passed
 Edge/IE | Passed
 Firefox | Passed
 Opera | Passed
 Safari | Passed


 On Screen Tests | Outcome
------------ | -------------
 Nav Bar | Passed
 Nav Bar HyperLink Menu | Passed
 HyperLink to Resume | Passed
 Landing Page Animation | Passed
 About Content UX | Passed
 Skills Content UX | Passed
 Project Content UX | Passed
 Project Content Links | Passed
 Contact Form UX | Passed 
 Contact Form Button | Passed
 Footer UX | Passed
 Footer Links | Passed
 Responsive Display | Passed
 Responsive Design | Passed


## Deployment

I decided to commit and push my work to my master branch regularly so when travelling to and from work I could access my site and test features on the most up to date version aswell as share with family and friends for constructive feedback.
Coming to the end of my project I deployed my website to GitHub Pages using information found here [GitHub](https://pages.github.com/).
By deploying my site on Github pages it will allow me to continuously update my site/upgrade my site in the background and submit changes by creating releases/creating pulls from gh pages.
This will allow me to initiate tests on further upgrades/enhancements to my site before deploying to my live version and not disrupt the user experience/inhibit the accessibility for my users. 


## Technologies
* HTML
* CSS
* Bootstrap
* Google Fonts
* FontAwesome
* Git
* GitHub
* Balsamiq


## ViewProject

* The code can be viewed using GitHub pages: https://Murphj99.github.io/milestone-project-1/


## Acknowledgements
* I got the idea to create my own portfolio website from [Code Institute](https://www.codeinstitute.net)
