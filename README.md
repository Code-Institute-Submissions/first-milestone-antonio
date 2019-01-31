# Augello Photoword- First Mileston Project

This Website was developed for Code Institute's User Centic Front End Development Project 1 and is an advertising website of myself as photographer to promote my photography services. It's a five pages responsive website, each area is build to made easily the navigation trough the contents and give all the info needed to the customers interested to have photography services.

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

## Basic Structure

The basic structure of each page is the same, this to allow the user a simple navigation.

The structure is as follow:

* Navbar: a simple navigation bar with a burger bar inside of same to divide the various services category of my website and socials icons.
* Image background
* Jumbotron: inspired by the Whiskey project of Code Institute's User Centic Front End Development Module, this Bootstrap based Jumbotron contain a Bootstrap sign up form with validators value, always inspired by the Whiskey Project, that allows the users to sign up and receive a discount code.
* Footer: A responsive footer in which is implemented the use of Font Awesome and [Ianlunn`s](http://ianlunn.github.io/Hover/)
 Hover.css.

## _Home Page_

This is the original section were my idea started. The basic idea was to give a brief introduction of myself and of my best works.

In this page we can find:

* Presentation Section: Build following the responsive grid it contains a brief presentation of me as phoographer.
* Customers Review: A bootstrap carousel inspired form with customers review, this is important for the users to see what the people think about my services.
* Body Sections: A section with the example of the best services offered build with a responsive grid.


## _Photobook_

This webpage was build to give to the user a better idea of the work I do as photographer.
The structure is simply and easy for the user. There is a bootstrap grid system of 3x6, three column and 6 raws for each column above the widht 1200px. 

Following the principle of the Mobile First the page was build for small screen devices in first and it is possible to see how below a widht of 768px there is only one column full width gallery.
Following the same principle between a width of 768px and 1200px there are 2 column and 6 rows, the third column is hidden to give to the user the best UX experience.

For this section I had inspiration from the CSS Gallery on [freefrontend.com](https://freefrontend.com/css-gallery/), the name of the gallery is "Image gallery with zoom" made by wunnle.

The css transitions and effects used are not displayed on small screens, this to give a better UX experience and because the image won't be larger than the full width that the image already have.


## _Serviced and Prices_

This webpage was build with the purpose to give to the customers all the info they need about all the sevices I provide and the relatives price.
In this page there is the implementation of Bootstrap`s table to allow the customers find all the the info in an in an orderly manner.

The page is full responsive and includes a inpage anchors for the special packages offered, this is to improve the users experience when they are using a smartphone to navigate through the website.

Try it on a small screen resolution and see how tapping one of the special packages you will be able to go directly to the interested package.

## _Delivery & Payment Info_

This web page was build with the purpose to give to the potential customers all the info needed about the delivery and the payment methods.
Like the previous webpage this one implements Bootstrap`s table and it is easy to navigate.

## _Contact Us_

This is the last webpage, I preferred to made a contact webpage to improve the user experience and made easily the navigation trought the website.

The section was build following the responsive mobile first idea and implements a responsive contact info and a Bootstrap form with validators value. 

Let's try and see how you can't proceed with the submission of the same if you don't fill it. 

In addition it's implemented a Bootstrap's select menu with multiple attributes that allow the customer to select easly a service and a printing size and allow me to know for what service the customer is contacting me for.


### Features Left to Implement

- Animated Gallery with the use of javascript
- Thank you notice after the submission of the contact form
- Thank you notice after the submission of the sign up form

## Technologies Used

For this project I used:

- [HTML5]( https://en.wikipedia.org/wiki/HTML5)
    - The project uses **HTML5** to structure the content in line with modern semantic html5.

- [CSS3](https://en.wikipedia.org/wiki/Cascading_Style_Sheets#CSS_3)
    - The project uses **CSS3** to style the html content.

- [Bootstrap3](https://getbootstrap.com/docs/3.3/)
    - The project uses **Bootstrap3** to Layout the html content on different screen sizes.

- [FontAwesome](https://fontawesome.com/)
    - The project uses **FontAwesome** to add icons for social media and contact forms.

- [Hover.css](http://ianlunn.github.io/Hover/)
    - The project uses **Hover.css** to add animations.

- [GoogleFonts](https://fonts.google.com/)
    - The project uses **GoogleFonts** to add the following fonts: Permanent Marker, Roboto, Exo, Indie Flower.

- [JQuery](https://jquery.com)
    - The project uses **JQuery** to control scrolling and toggle features.





## Testing

In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your user stories from the UX section and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

Whenever it is feasible, prefer to automate your tests, and if you've done so, provide a brief explanation of your approach, link to the test file(s) and explain how to run them.

For any scenarios that have not been automated, test the user stories manually and provide as much detail as is relevant. A particularly useful form for describing your testing process is via scenarios, such as:

1. Contact form:
    1. Go to the "Contact Us" page
    2. Try to submit the empty form and verify that an error message about the required fields appears
    3. Try to submit the form with an invalid email address and verify that a relevant error message appears
    4. Try to submit the form with all inputs valid and verify that a success message appears.

In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

If this section grows too long, you may want to split it off into a separate file and link to it from here.

## Deployment

This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub Pages or Heroku).

In particular, you should provide all details of the differences between the deployed version and the development version, if any, including:
- Different values for environment variables (Heroku Config Vars)?
- Different configuration files?
- Separate git branch?

In addition, if it is not obvious, you should also describe how to run your code locally.


## Credits

### Content
- The text for section Y was copied from the [Wikipedia article Z](https://en.wikipedia.org/wiki/Z)

### Media
- The photos used in this site were obtained from ...

### Acknowledgements

- I received inspiration for this project from X
