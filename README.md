<p align="center">
  <img src="assets/images/responsive-screen.png">
</p>

# Astra rental Website

Simone Casoni's first Milestone project:
- [Gitpod](https://simocaso.github.io/ms1.2-astra-rental/)
- [Repl](https://astra-rental-ms1-2--simonecasoni.repl.co/)



# Introduction

"Astra rental" is a motorcycles rental company that aims to offer the opportunity to ride motocross bikes of different engine sizes, and strokes, currently based in Dublin.<br> 

_Please, note that this site portrays a fictitious business, created purely for the purpose of this exercise. This will be my Milestone Project second attempt for the Code Institute Diploma in Full Stack Development._ <br>

Moreover, for this second attempt, I decided to rebuild a new website using a single page structure with multiple sections. I'd also like to apologise for have used the word "inspired" instead of "used" in my previous submission, and thank the assessment team for feedback. 

## UX

### Design
I wanted to create a clean website where users could directly understand its purpose. In order to accomplish that, the home page shows you a carousel comprehensive of our 3 main topics: "WHO AND WHERE", "OUR BIKES", and "REVIEWS".  

### Colour Scheme

- The main colours used are black, grey, white (monochromatic) and yellow. To give the website a clean, serious, and professional.

### Typography

- Lato e Osvald, in order to give you a young and dinamic impression.

### Imagery

- Imagery is important. The large, background image is designed to let you feel involved! Also added many images to let the site be very intuitive.

### Wireframes

- Wireframe - Loving being old fashioned. Below, you can see some scatches using pen and paper:
<p align="center">
  <img src="assets/images/wf-0.jpg">
</p>

## User stories:

### Users:
-   As a user, I'd like to visit a clean and clear website.
-   As a user, I'd like to be able to see the different range and type of bikes.
-   As a user, I'd like to see the location of the business.
-   As a user, I'd like to see reviews by other customers.
-   As a user, I'd like to see the different types of services that the business offers, including full pricing details.
-   As a user, I'd like to be able to click the contact number and email to contact the business straight away if I so wish.

### Astra rental business owner:
- As a business owner, I'd like to let my users have a clear idea of what we are and who we are
- As a business owner, I'd like to clearly show our bikes fleet and prices 
- As a business owner, I'd like to share a bit of who we are and what we want to offer
- As a business owner, I'd like to have a website that looks fresh and professional at the same time


## Features

- Responsive on all device sizes
- Moving carousel, to show immediately every content 
- Interactive buttons in the carousel (if you leave your cursor above them, they will stop the sliding. They also redirect you to the respective section)
- Navbar menu, with the respective sections redirects
- Scrollspy function to help you visualize where you are
- When you pass above the bikes cards, they will expand a bit, to help you focus on them
- Google maps interactive window 


## Technologies Used

### Languages Used

- [HTML5](https://en.wikipedia.org/wiki/HTML5)

- [CSS3](https://en.wikipedia.org/wiki/Cascading_Style_Sheets)

  

### Frameworks, Libraries & Programs Used

1. [Repl:](https://repl.it/)

- fast and useful editor!

2. [Bootstrap 4.4.1:](https://getbootstrap.com/docs/4.4/getting-started/introduction/)

- Bootstrap was used to assist with the responsiveness and styling of the website.

3. [Font Awesome:](https://fontawesome.com/)

- Font Awesome was used on all pages throughout the website to add icons for aesthetic and UX purposes.

4. [Git/Gitpod:](https://git-scm.com/)

- Git was used for version control by utilizing the Gitpod terminal to commit to Git and Push to GitHub.

5. [GitHub:](https://github.com/)

- GitHub is used to store the project's code after being pushed from Git.

6.  [https://tinypng.com/](https://tinypng.com/)
- Let me save almost 61% of spaces occupied by images and speeding up the website loading

<p align="center">
  <img src="assets/images/tinipng.png">
</p>

 ## Deployment

This website has been deployed to GitHub Pages as  [ms1.2-astra-rental](https://github.com/Simocaso/ms1.2-astra-rental)

The process for deployment is documented below:

-   Log into  [GitHub](https://www.github.com/)
    
-   Access the page with the repository for this project
    
-   Click on 'Settings' on the main menu over the file listing
    
-   Navigate down to 'GitHub Pages'
    
-   Select 'Branch: Master' from the menu
    
-   This generates a live link for the website, which is now viewable publicly

## Testing

The W3C Markup Validator and W3C CSS Validator Services were used to validate every page of the project to ensure there were no syntax errors in the project.

- [W3C CSS Validator](https://jigsaw.w3.org/css-validator/#validate_by_input) - passed - No errors

<p align="center">
  <img src="assets/images/w3c-css.png">
</p>

- [W3C Markup Validator](https://jigsaw.w3.org/css-validator/#validate_by_input) : 7 errors shown (but only for the code copied from Embedgooglemap, used for the google maps content)

<p align="center">
  <img src="assets/images/w3c-html.png">
</p>


### Further Testing

- The Website was tested on Google Chrome, Internet Explorer, and Safari browsers.

- The website was viewed on a variety of devices such as Laptop (Apple Macbook pro, Chromebook), iPhone devices ( iPad 10 pro, iPhone 11 pro, iPhone 7, iPhone X, iPhone 8), Android devices (Samsung galaxy s5, Samsung A7, Huawei P20), and Desktop (with 22", 24", 17" monitors).

- A large amount of testing was done to ensure that all pages were linking correctly.

- Friends and family members were asked to review the site and documentation to point out any bugs and/or user experience issues.

- I used Light house, an open-source automated tool, to test the performance of the website. The site performed a good average score of 91:

<p align="center">
  <img src="assets/images/lhp.png">
</p>

### Known Bugs

- No bugs found/left over so far


### Fixed bugs, respective solutions

- navbar bottom could have been confused with the background <br>
  -> added a small border on the bottom
  
- navbar animations don't follow you whenever you scroll the page<br>
  -> added a scrollspy component
  
- section's tops are a bit cropped when you click on the navbar's links<br>
  -> added some padding on the top
  
- couldn't add a background image to carousel's slides<br>
  -> rebuilt the carousel manually and fixed the img paths

- couldn't center the google maps location<br>
  -> fixed it through bootstrap column method and by adjusting the inner div responsiveness 

- Navbar wasn't collapsing after clicking on links<br>
  -> Added " data-target=".navbar-collapse" data-toggle="collapse" " to the Navbar Link's Div

## Credits

### Code

- Took very few things (navbar base, footer base, and some actual contents) from my previous website code on Repl,  https://repl.it/@simonecasoni/motocross-rental-bike
- [Bootstrap4](https://getbootstrap.com/docs/4.4/getting-started/introduction/): Bootstrap Library/templates used throughout the project to make site responsive.
- [Embedgooglemap](https://www.embedgooglemap.net/en/) for the google maps box code

### Media

-  [Font Awesome](https://fontawesome.com/6?next=%2Fstart)  for the icons used on this project.
-  [Am I Responsive](http://ami.responsivedesign.is/)  for the image used in the UX section showing the different screen sizes.
-  [Favicon](https://www.favicon.io/)  for the thumbnail icon on the internet tab header
- [https://tinypng.com/](https://tinypng.com/) for letting me show how much spaced i saved
- [Google](https://www.google.com/), for all the images I've found
 
### Acknowledgements and Thanks

I would like to mention all the different resources and sites that are out there, with their respective communities, which have been a huge help for me. I will list some of them below:
-   Repl
-   Bootstrap
-   Git Hub and Git Pod
-   Font Awesome
-   jQuery developers
-   Stack Overflow
-   Slack
-   coffee (!important)
-   Assessment Team<br>
And lastly, I could not leave out the Code Institute team: Alex who has been so comprehensive and kind, my mentor Felipe Souza Alarcon for his help and advice during this project, his flexibility and availability.