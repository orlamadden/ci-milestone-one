# [Milestone Project One - Matt's Café](https://orlamadden.github.io/ci-milestone-one/)

## Code Institute / User-Centric Frontend Development Milestone Project

Tasked to create a static website combining knowledge from the first three modules in the Full Stack Web Development course with the Code Institute. 

I decided to build a fictional café website called Matt’s Café. This website allows customers and potential customers of the café to view the menu, opening hours and location before visiting.

## UX

The goal of this website for customers and potential customers is to:
- Provide menu option listings.
- Show the café location.
- Display opening hours.

The business owner goals of this website are to:
- Build brand awareness.
- Attract more visitors and increase sales.

#### User Stories

1.	As a potential customer (and returning customer), I want to check the opening hours of Matt’s Café so I know it is open when I arrive.
2.	As a potential customer, I want to check the location of Matt’s Café as I have never been there before and want to know where it is.
3.	As a potential customer (and returning customer), I want to read the menu before I decide to eat here.
4.	As a potential customer I want to see if Matt’s Café has social media presence so I can see what other people on Facebook are saying about them.
5.	As a potential customer I want to be able to check Matt’s Café on my mobile device as I do not own a laptop or desktop.
6.	As a potential customer I want to see images of what Matt’s Café has on offer.
7.	As a potential customer I want to be able to contact Matt’s Café if the website does not answer all my questions.
8.	As a potential customer with dietary requirements, I want to contact Matt to see if they can offer a Vegetarian/Vegan alternative to their current menu.

#### Wireframes

I used Adobe Illustrator to complete my wireframes, as I was already familiar with the software. Wireframing my website was extremely beneficial as it allowed me to visualise my website prior to coding and made development a lot easier. I made changes throughout the development stage so my website looks slightly different than the wireframes, but the core concept is still there.

- Home page
  * [Mobile](https://github.com/orlamadden/ci-milestone-one/blob/master/wireframes/mobile/mockup-mobile-home.jpg)
  * [Tablet](https://github.com/orlamadden/ci-milestone-one/blob/master/wireframes/tablet/mockup-tablet-home.jpg)
  * [Desktop](https://github.com/orlamadden/ci-milestone-one/blob/master/wireframes/desktop/mockup-desktop-home.jpg)
- Menu page
  * [Mobile](https://github.com/orlamadden/ci-milestone-one/blob/master/wireframes/mobile/mockup-mobile-menu.jpg)
  * [Tablet](https://github.com/orlamadden/ci-milestone-one/blob/master/wireframes/tablet/mockup-tablet-menu.jpg)
  * [Desktop](https://github.com/orlamadden/ci-milestone-one/blob/master/wireframes/desktop/mockup-desktop-menu.jpg)
- Contact page
  * [Mobile](https://github.com/orlamadden/ci-milestone-one/blob/master/wireframes/mobile/mockup-mobile-contact.jpg)
  * [Tablet](https://github.com/orlamadden/ci-milestone-one/blob/master/wireframes/tablet/mockup-tablet-contact.jpg)
  *  [Desktop](https://github.com/orlamadden/ci-milestone-one/blob/master/wireframes/desktop/mockup-desktop-contact.jpg)


---

## Features

The following is a summary of the features already in place and those that could perhaps be implemented in the future.
#### Navbar
The main aim of the navbar is to navigate the website The navbar is featured on all pages. 
- The café logo is featured on the left side of the navigation bar which links back to the home page when clicked.
- The page item links are on the right side of the navigation bar, featuring:
   * Home
   * Menu
   * Contact
- The navbar collapses into a burger menu when resized to tablet and mobile view.
#### Footer
- The footer is featured on all pages. It contains:
   * Location
   * Opening hours
   * Newsletter signup

- The secondary footer contains social media links for Matt’s Café and copyright information.

#### Video
- The inclusion of a video on the home page was for educational purposes only. As Matt’s Café is fictional, this video does not promote my website but would be a compliment to the website.

#### Carousel
- The homepage features a carousel which displays some of the latest customer images from Instagram.

#### Newsletter Signup form
- The footer provides a very basic signup form for users to enter if they want to receive a monthly newsletter from Matt’s Café.

#### Contact us form
- The contact page features a form so visitors can contact Matt’s Café looking for more information that may not have been addressed on the website.

#### Menu list
- The menu list on the menu page gives visitors a complete overview of what Matt’s Café offers, along with menu item description and menu item pricing.

#### FUTURE IMPLEMENTATIONS
- I would create a small section above the header that would feature the current day and the opening hours associated with that day.
- I would create a section that would display daily offers associated with the current day of website visitation.

---

## Technology

#### HTML
- For building the foundation of my website.

#### CSS
- For custom styling on my website
#### Bootstrap 4.3.1
- The framework behind my website’s structure and layout, which prioritises mobile first design.
#### Font Awesome
- For icon elements in the footer.
#### Google Fonts
- For choosing fonts that I thought worked well on my website.
#### Gitpod
- My IDE of choice for developing my website.
#### Git 
- For version control.
#### Github
- For storing and managing my code in a remote location.

---

## Testing

- [W3C Mark-up Validation](https://validator.w3.org/) and [W3C CSS Validation](https://jigsaw.w3.org/css-validator/) was used to check the validity of the website. Errors were spotted and fixed.

- Chrome Devtools was used throughout the duration of the project for testing responsiveness of the website and bug fixes.

- [Responsinator](https://www.responsinator.com/) was recommended by my mentor and was used to check the responsiveness of my website across many devices at the same time. This pointed out the burger menu expansion issue which I outline below.

- During testing, the navbar did not display properly on mobile. I gave the navbar a custom height which affected the styling of the burger menu on mobile when it was expanded. I removed the custom styling.

- This site was tested across multiple browsers (Chrome, Safari, Microsoft Edge FireFox) and on multiple mobile devices (iPhone X, Huawei P30 Pro, iPad Pro and Samsung Galaxy S7) to ensure compatibility and responsiveness.

#### User Story Testing

1. As a potential customer (and returning customer), I want to check the opening hours of Matt’s Café so I know it is open when I arrive.
   1. At the bottom of each page, the opening hours of the café are clearly labelled.
2. As a potential customer, I want to check the location of Matt’s Café as I have never been there before and want to know where it is.
   1. At the bottom of the home page, the location of Matt’s Café is clearly labelled.
3. As a potential customer (and returning customer), I want to read the menu before I decide to eat here.
   1. A clearly labelled menu page is visible on each page.
The menu page contains all the food and beverages available to purchase at Matt’s Café.
4. As a potential customer I want to see if Matt’s Café has social media presence so I can see what other people on Facebook are saying about them.
   1. At the bottom of each page, social media icons (including Facebook) is available. 
5. As a potential customer I want to be able to check Matt’s Café on my mobile device as I do not own a laptop or desktop.
   1. The website is mobile responsive and works on mobile devices.
6. As a potential customer I want to see images of what Matt’s Café has on offer.
   1. As the user scrolls through the homepage, there is a carousel gallery labelled ‘top picks from our Instagram’ which features curated content from visitors to the café.
   2. The user can click on the view more button to be take to Matt’s Café’s Instagram feed to view images.
7. As a potential customer I want to be able to contact Matt’s Café if the website does not answer all my questions (like bank holiday opening hours and table reservations for a small party).
   1. A clearly labelled contact page is visible on each page.
   2. The contact page contains a contact form that the user can input their details and query to send to Matt’s Café. 
8. As a potential customer with dietary requirements, I want to contact Matt to see if they can offer a Vegetarian/Vegan alternative to their current menu.
   1. Once the user has scanned the menu, they are met with an asterisk followed by a note detailing that if the user has any dietary requirements, to get in touch via the contact form (there is an inline link that highlights this).
   2. Alternatively, there is a contact form clearly labelled in the navigation bar on each page. 


---

## Deployment

This project was developed using the GitHub IDE, committed to git and pushed to GitHub.
To deploy my website to GitHub Pages, the following steps were taken:
1.	Log into GitHub.
2.	Selected repository from GitHub dashboard.
3.	Select ‘Settings’ at the top of the chosen repository.
4.	Scroll down to GitHub Pages section.
5.	Under ‘Source’ click the drop-down menu and select ‘Master Branch’.
6.	Once selected, the page auto refreshed, and the website was deployed.

***NOTE***

**After deployment I realised my images were not displaying correctly. The history of my style.css file might be a little confusing as it looks like it has very little commits made. There is a reason for this which I outline below.**

Upon deploying my website to Github, I realised that my images were not displaying. I found the solution through Slack – I needed to point to a relative path, and not an absolute path. Upon figuring this out, I changed the code accordingly from ‘/assets/images/cafe-background.jpg/’ to ‘.. /images/cafe-background.jpg’. This commit can be found on Nov. 21st 2019.

This change was still not giving me the solution I was looking for. I realised that in the assets folder, I did not have a CSS folder to contain my style.css - I only had an images folder and for this my images were not being picked up. 

[May need a graphic here to visually explain this]

I created a CSS folder and moved my style.css into it. My images were finally being picked up and now working correctly.

Unfortunately, all my style.css commits are contained in the assets folder history, not the CSS folder.

---

## Credits

#### Content
- The text copy for the home page was written by me.
- The text copy for the menu was written by me but with a little inspiration from the following websites:
  * [The Abbey Tavern](https://www.abbeytavern.ie/menus/food)
  * [Judge Roy Beans](https://www.judgeroybeans.ie/our-menu/)
  * [Insomnia](https://www.insomnia.ie/menu)

#### Media
- The video was obtained from [Youtube](https://www.youtube.com/watch?v=ZDQn-9cdx9Q)
- All images were obtained from [Pexels](https://www.pexels.com/), with the exception of one image from [Pixabay](https://pixabay.com/). It is worth noting that an opacity filter is applied to the hero images on the home page, menu page and contact page.

#### Code
- Assistance with centering my buttons on the page are from this Stackoverflow post -https://stackoverflow.com/questions/22578853/how-to-center-buttons-in-twitter-bootstrap-3

---

This README.md document is a work in progress.