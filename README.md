# Hike Ireland
Hike Ireland is a responsive website with information and inspiration for hikes in Ireland. It allows users learn about the benefits of hiking and find inspiration for hikes in every province.
- [Link to deployed site here](https://kerrie-jones.github.io/hike-ireland/)\
- Add image from am i responsive here


# User Experience UX
## User Stories
### First Time Visitor Goals
- As a first time visitor I want to be able to view the site ona range of devices
- As a first time visitor I want to be able to easily navigate around the website
- As a first time visitor I want to find their social media profiles 
### Returning Visitor Goals
- As a returning visitor I want some inspiration for hikes by looking at images of beautiful scenery in various hiking locations around Ireland.
- As a returning visitor I want to signup to the newsletter for more information
### Frequent Visitor Goals
- As a frequent user I want some updated images and information on hikes 

# Design
## Colour Scheme
I used Adobe color wheel to extract themes from the hero image.\
<img src="assets/images/AdobeColor-color theme_connemara_national_park (1).jpeg" height="300px">
<img src="assets/images/AdobeColor-color theme_connemara_national_park (2).jpeg" height="300px">


## Typography
I used [Googlefonts](https://fonts.google.com/) and decided to pair Playfair display, a serif font, with Raleway a sans serif font.\
<img src="assets/images/playfair_display.png" height="200pxpx">
<img src="assets/images/raleway.png" height="200px">

## Imagery
All images on the site were sourced from [Unsplash.com](https://unsplash.com/)\
I used images of Irish mountain scenery and wildlife to inspire potential hikers.


# Features
## Current Features
### Navigation Bar
<img src="assets/images/nav_bar_screenshot.png" width="800px">

- Navigation bar is found on all four pages and it is identical on all to allow easy navigation without using the back button. 
- Current page is underlined so user can clearly see which page they are on.
- Links open in new tab


### Landing Page Image
<img src="assets/images/hero_image_section.png" width="800px">

- The landing page image has an eyecatching image of beautiful scenery to grab the users attention.
- There is a covertext on the image to make clear what the website is about.


### Benefits of Hiking Section
<img src="assets/images/benefits_section_screenshot.png" width="800px">

- The benefits of hiking section goes through some of the benefits of hiking.
- The user will see the positive impact of hiking and be inspred and encouraged to get out and enjoy Ireland's scenery

### Top Hikes in Ireland Section
<img src="assets/images/tophikes_screenshot.png" width="800px">

- This section contains the top hikes in Ireland by province. We have chosen to show the top 6 for each.
- There is a clickable link in this section which brings the user to the Hikes Gallery page. It will open in a new tab 


### Signup Section
<img src="assets/images/signup_section_screenshot.png" width="800px">

- In the signup section there is a form which the user can fill out to signup to the monthly newsletter
- The signup section contains a cover text with information about the monthly newsletter.
- when the user completes the form they will be brought to a thankyou page thanking them for subscribing.


### The footer
<img src="assets/images/footer_screenshot.pngA" width="800px">

- The footer holds links to social media 
- It also has a copyright notice
- When the user clicks on social media links they will open in a new tab


### The Gallery Page
<img src="assets/images/gallery_screenshot.png" width="800px">

- The gallery page contain inspiring images of the irish great outdoors. 
- This page will encourage users to try hikes in different parts of the country.
- It will also help them decide which hikes they would like to try out.


### The Signup Page
<img src="assets/images/signup_page_screenshot.png" width="800px">

- This page will allow the user to get signed up for the monthly newsletter and get information about meetups. 
- There is a form which the user can fill out to signup to the monthly newsletter.
- The user will be asked to submit their first name, last name and email address.
- There is a covertext with an irish proverb and english translation. 


### The Thankyou Page
<img src="assets/images/thankyou_page_screenshot.png" width="800px">

- the thankyou page thanks users for subscribing. 
- It opens in a new tab

## Features Left to Implement
- Make the top hikes section have clickable links to each hike with more inforamtion and images of each individual hike

# Testing
- I have tested tested the website on various different screen sizes in dev tools. 
- Lighthouse showed I had poor performance due to image size so I resized images with Mac Preview which improved performance\
index.html\
<img src="assets/images/index_lighthouse_final_mobile.png" width="400px">
<img src="assets/images/index_final_lighthouse_desktop.png" width="400px">\
gallery.html\
<img src="assets/images/gallery_final_lighthouse_mobile.png" width="400px">
<img src="assets/images/gallery_lighthouse_final_desktop.png" width="400px">\
signup.html
<img src="assets/images/signup_page_final_lighthouse_mobile.png" width="300px">
<img src="assets/images/signup_page_final_desktop_lighthouse.png" width="300px">
thankyou.html
<img src="" width="400px">
<img src="" width="400px">

- Bug in benefits of hiking section in firefox and safari where image is covering end of text when screen is less than 600 px. I fixed issue by increasing padding above image and decreasing max-width of image container in media query for screen sizes 600px and below
- In safari the text was spilling out of container slightly fixed by changing provinces div to fit content.

## Validator Testing
### HTML
- index.html  No errors were returned when passing through the official [W3C validator](https://validator.w3.org/nu/#textarea)
- gallery.html  No errors were returned when passing through the official [W3C validator](https://validator.w3.org/nu/#textarea)
- signup.html  No errors were returned when passing through the official [W3C validator](https://validator.w3.org/nu/#textarea)
- thankyou.html  No errors were returned when passing through the official [W3C validator](https://validator.w3.org)
### CSS
- style.css No errors were found when passing through the official [Jigsaw validator](https://jigsaw.w3.org/css-validator/validator)

## Unfixed Bugs
- Too much space below image in benefits section in chrome but when I correct this the image covers some of the text in safari and firefox.

# Deployment
The site was deployed to GitHub pages.\

The steps to deploy are as follows:
- In the GitHub repository, navigate to the Settings tab
- Select pages from the left column
- Select main branch and save
- Site now deployed but may take a few minutes

# Technologies Used 
## Languages used
- HTML
- CSS
## Frameworks, Libraries & Programs Used
- Google Fonts - Fonts Raleway and Playfair Display were imported for use throughout the project
- Font Awesome - Icons for the benefits of hiking section, top hikes section and footer were used from this site
- GIT - used for version control
- GITHub - code pushed from GIT and stored in GITHub
- GITPod - workspace used in gitpod to work on project then push to github
- Dev Tools - were used to check how project looked on different screen sizes and also to troubleshoot errors and try out changes
- Unsplash - stock image site used for images on the website
- Mac Preview - used to resize large images

# Credits
CI 

## Content
-
-
## Media
-
-
-
-
-

