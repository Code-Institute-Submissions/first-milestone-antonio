# User Centric Front-End Development Milestone Project

# [Augello Photoworld](https://gello94.github.io/first-milestone-antonio)


This Website was developed for Code Institute's User Centic Front End Development Project 1 and is an advertising website of myself as photographer to promote my photography services. It's a five pages responsive website, each area is build to made easily the navigation trough the contents and to give all the info needed to the customers interested to have photography services.


## UX
 
This Project is to demonstrate lessons learned in this section HTML and CSS User-Centric Front End Development.

The website was build following the principle Mobile First and the UX is designed following the Bootstrap Grid system. 

The idea was to build a website designed for customers that are looking for photography services and to give them a brief demonstration of my works as photographer. 

I decided to divide the website into five different sections:

* Home Page
* Photobook
* Services and Prices
* Delivery & Payment Info
* Contact Us


### Scenarios

##### User looking for a Photobook:

A user that may need a photography for a competition or for personal pleasure or to share on the socials. This user will look for the indoor and ourdoor portrait jobs and info.
They will be interested in book the service asking for a special printing size and asking for some request about.

##### Real Estate Agency:

As Real Estate Agency I need to attract the customer's attention on the properties I am advertising and to do this the best way is to show detailed and good quality pictures of same.
A Real Estate Agency will visit the site to see my works, to read other clients review, to look the prices and all the services that I can offer. It can be interested to contact me for further info.

##### Family on special events:

A family that would like to have photos for their family book during a special event. The client will go to the site to look the works and all the services offered with relative prices having a look on the review of the other clients. 
They will look for special offers to have more than one single shot during more hours of the day and to have more picture printed. They will be also interested to know about the payment methods and the delivery options.

##### Couple in Holiday:

A couple in holiday looking for a professional photography service. They will be interested to look the works and other clients review. They will be interested also in look about the delivery options and costs.


## Feature

The basic structure of each page is the same, this to allow the user a simple navigation.

The structure is as follow:

* **Navbar**: a simple responsive navigation bar with a dopdown menu inside of same to divide the various services category of my website and with socials icons. The navigation bar will be showed as "Hamburger Menu" on width < 768px.
* **Background Image** 
* **Jumbotron**: inspired by the Whiskey project of Code Institute's User Centic Front End Development Module, this Bootstrap based Jumbotron contain a Bootstrap sign up form with validators value, always inspired by the Whiskey Project, that allows the users to sign up and receive a discount code.
* **Footer**: A responsive footer in which is implemented the use of Font Awesome and [Ianlunn`s](http://ianlunn.github.io/Hover/)
 Hover.css.

In addiction, to the web pages, except for the Home Page, was added a script to allow the auto scroll-down of the page, this to improve the quality of the navigation and to prevent users from thinking that the page has not changed, due to the same structure.
This Javascript code was found on [Stackoverflow](https://stackoverflow.com) community.

#### _Home Page_

This is the original section were my idea started. The basic idea was to give a brief introduction of myself and of my best works.

In this page we can find:

* Presentation Section: Build following the responsive grid it contains a brief presentation of me as phoographer.
* Customers Review: A Bootstrap Carousel inspired form with customers review, this is important for the users to see what the people think about my services.
* Body Sections: A section with the example of the best services offered build with a responsive grid.

Link to the [Home Page](https://gello94.github.io/first-milestone-antonio/).


#### _Photobook_

This webpage was build to give to the user a better idea of the work I do as photographer.
The structure is simply and easy for the user. There is a bootstrap grid system of 3x6, three column and 6 raws for each column above the widht 1200px. 

Following the principle of the Mobile First the page was build for small screen devices in first and it is possible to see how below a widht of 768px there is only one column full width gallery.
Following the same principle between a width of 768px and 1200px there are 2 column and 6 rows, the third column is hidden to give to the user the best UX experience.

For this section I had inspiration from the CSS Gallery on [freefrontend.com](https://freefrontend.com/css-gallery/), the name of the gallery is "Image gallery with zoom" made by wunnle.

The Gallery feature are not displayed on small screens, this to give a better UX experience and because the image won't be larger than the full width that the image already have.

Link to the [Photobook](https://gello94.github.io/first-milestone-antonio/gallery.html) page.


#### _Services and Prices_

This webpage was build with the purpose to give to the customers all the info they need about all the sevices I provide and the relatives price.
In this page there is the implementation of Bootstrap`s table to allow the customers find all the the info in an in an orderly manner.

The page is full responsive and includes a inpage anchors for the special packages offered, this is to improve the users experience when they are using a smartphone to navigate through the website.

Try it on a small screen resolution and see how tapping one of the special packages you will be able to go directly to the interested package.

Link to the [Services and Prices](https://gello94.github.io/first-milestone-antonio/services.html) page.


#### _Delivery & Payment Info_

This web page was build with the purpose to give to the potential customers all the info needed about the delivery and the payment methods.
Like the previous webpage this one implements Bootstrap`s table and it is easy to navigate.

Link to the [Delivery & Payment Info](https://gello94.github.io/first-milestone-antonio/delivery.html) page.


#### _Contact Us_

This is the last webpage, I preferred to made a contact webpage to improve the user experience and made easily the navigation trought the website.

The section was build following the responsive mobile first idea and implements a full responsive contact info and a Bootstrap contact form with validators value. 

In addition I implemented a Bootstrap's select menu with multiple attributes that allow the customer to select easly a service and a printing size and allow me to know for what service the customer is contacting me for.

Link to the [Contact Us](https://gello94.github.io/first-milestone-antonio/contact.html) page.



### Features Left to Implement

- Implement Social Networks Link on the Social Icons
- Thank you windows after the submission of the contact form
- Thank you windows after the submission of the sign up form
- A Purchase Form to allow the user to buy a service directly by the website
- An ordered Gallery / Photography Portfolio divided in different section to show the skills for the services offered 


## Technologies Used

For this project I used:

- [HTML5]( https://en.wikipedia.org/wiki/HTML5)
    - The project uses **HTML5** to structure the content in line with modern semantic html5.

- [CSS3](https://en.wikipedia.org/wiki/Cascading_Style_Sheets#CSS_3)
    - The project uses **CSS3** to style the html content.

- [Bootstrap 3.3.7](https://getbootstrap.com/docs/3.3/)
    - The project uses **Bootstrap 3.3.7** to Layout the html content on different screen sizes.

- [FontAwesome](https://fontawesome.com/)
    - The project uses **FontAwesome** to add icons for social media and contact forms.

- [Hover.css](http://ianlunn.github.io/Hover/)
    - The project uses **Hover.css** to add animations.

- [GoogleFonts](https://fonts.google.com/)
    - The project uses **GoogleFonts** to add the following fonts: Permanent Marker, Roboto, Exo, Indie Flower.

- [Google Images](https://www.google.com/imghp?hl=en)
    - I used **Google Images** to find the icons for my user`s review.

- [JQuery](https://jquery.com)
    - The project uses **JQuery** to control scrolling and toggle features.

- [ResizeImage](https://resizeimage.net/)
    - For the project i used the free online tool **ResizeImage** to resize and compress the images to speed up the charging of the site.

- [Freefrontend](https://freefrontend.com)
    - For the project i used **Freefrontend** resource to find an animated Gallery.

- [Stackoverflow](https://stackoverflow.com)
    - For the project i used **stackoverflow** community to find a scroll down script for my project.
 

## Testing

To test this project I used various browsers and devices.

#### Mobile Browsers
* Chrome
* Safari
* Internet Samsung 

#### Desktop Browsers
* Chrome
* Firefox
* Edge

#### Devices
* Hp Laptop
* Asus Laptop
* Acer Laptop
* Samsung S8
* Iphone X

During testing i used Chrome Developer tools to test the responsive design on different size and the features of the page on different width.

The site was developed following the Bootstrap Grid System and the same was tested to ensure that all the elements are responsive on the following resolutions on each page:

- Width ≥1200px 
- Width between 1200px and 768px
- Width ≤ 768px 


### Forms and Gallery Testing

1. Sign Up form:
    1. Go to one of the page and click on the Sign Up button
    2. Try to submit the empty form and verify that an error message about the required fields appears
    3. Try to submit the form with an invalid email address and verify that a relevant error message appears
    4. Try to submit the form with all inputs valid.

2. Contact form:
    1. Go to the ["Contact Us"](https://gello94.github.io/first-milestone-antonio/contact.html) page
    2. Try to submit the empty form and verify that an error message about the required fields appears
    3. Try to submit the form with an invalid email address and verify that a relevant error message appears
    4. Try to submit the form with all inputs valid.

3. Animated Gallery 
    1. Go to the ["Photobook"](https://gello94.github.io/first-milestone-antonio/gallery.html)
    2. Try to move your indicator on the images and see the css transitions working.
    3. Try to click on one of the images and see how the image will be displayed full screen in the same page with a transition effect.
    4. Click again to go back on the gallery.
    5. Now try to set the display on a resolution of 768px or less and click on one of the images and see how the transition is not displayed.


### Validation Testings

For HTML validation testing I used ["W3 Validator"](https://validator.w3.org/nu/?doc=https%3A%2F%2Fgello94.github.io%2Ffirst-milestone-antonio%2F) which shows the html documents to be valid.

For CSS validation testing I used ["W3 CSS Validator"](http://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fgello94.github.io%2Ffirst-milestone-antonio%2F&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=it) which shows the stylesheet to be valid CSS3.

## Deployment

This page has been deployed to ["Github Pages"](https://gello94.github.io/first-milestone-antonio/).

GitHub is used to host the code and publish the pages.

A new repository was created in GitHub called: first-milestone-antonio

After a final Git Add and Git commit

`$git add .`

`$git commit -m "Final commit"`

The pages were pushed to the GitHub repository

`$ git push -u origin master`

`$Username`

`$Password`

Under the Settings – GitHub Pages of the new repository, the master branch of the code is published to the url:
https://gello94.github.io/first-milestone-antonio/

## Credits

For this project I had ispiration by the Whiskey project of Code Institute's User Centic Front End Development Module.

### Media

- The icons used for the user review in the Home Page are taken from ["Google Images"](https://www.google.com/imghp?hl=en), found using the filter "re-use rights".
- The photos used in this site are all mine, except for the images used as User Icon as mentioned above. 

