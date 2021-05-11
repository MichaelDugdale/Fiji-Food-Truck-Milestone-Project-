# Fiji Food Truck

[FijiFoodTruck](https://michaeldugdale.github.io/Fiji-Food-Truck-Milestone-Project-/index.html)

Create a website for a catering business, with the goal being to  Raise Brand awareness, increasing sales, Boosting customer retention, loyalty, and lifetime value. A catering business out of a food truck can be constantly on the move, we want to be able to provide a constant location of where we are on any given day. To make bookings for catering events easy and user freindly. lastly spread awareness on sustainable sourcing of ethically caught products.

## UX

![ResponsiveDesign](/assets/wireframes/MSPresponsive.png)

### user stories
* as a user i want to be able to book the truck for private hire
* as a user i want to be able to know the location on any given day
* As a user, I want a simple and clean looking website as messy, busy pages with lots of information overwhelms me.
* as a user i want to be able to see what food is avaiable 
* as a user i want to know how the food is sourced so i can make informed decisions
* as a user i want to be able to easily find your social media accounts so i stay up to date  
* as a user i want to be able to find out who background of the foodtruck and owners/chefs
* as a user i want to be able to see pictures of food made by the fiji food truck


### wireframes

![wireframes](/assets/wireframes/MSPIC.png)


### features

#### Existing Features

* responsive design - mobile first application using bootstrap
* header/nav user can easily navigate through the website navbar becomes hamburger button depending on screen res using javascript
* footer allows easy access to social media accounts and information on opening/ closing hours/ location on all pages and the option to subscribe to our newsletter

###### Home page

* Shows what the website is for and provides a brief introduction to the business, with easy to follow links for what you would like to see next.

###### Contact us

* information about hiring process eg costs/what to expect 
* A form to fill in in order for the user to hire the foodtruck 
* a googlemaps picture of the location of the fiji food truck during the week using iframes

###### about us

* information about how the food truck came to be
* information about the current owners and chefs
* information about the ingredents and how they are sourced ethically 

###### Gallery

* assorted pictures of food and staff of the fiji food truck

###### menu

* a simple menu pdf for the user to look at or download

#### Features left to implement

* lightbox feature using js for the gallery, making it more interactive
* a way to update the pdf menu daily so it can show daily specials instead of just the stapels.

### Technologies Used

- [HTML5](https://en.wikipedia.org/wiki/HTML5) - provides the content and structure for my website.
- [CSS3](https://en.wikipedia.org/wiki/Cascading_Style_Sheets) - provides the styling.
- [Bootstrap](https://getbootstrap.com/) - used to create the layout of the project.
- [JavaScript](https://www.javascript.com/) - JS is used for dynamic functionallity
- [JQuery](https://jquery.com) - JQuery is used to simplify DOM manipulation
- [Google Chrome](https://www.google.com/chrome/) - Chrome has been used for browsing and Dev Tools
- [Balsamiq](https://balsamiq.com/) - used to create the project's wireframes.
- [Gitpod](https://gitpod.io/) - used to develop the website.
- [GitHub](https://github.com/) - used to host the project.
- [Google Fonts](https://fonts.google.com/) 
- [Font Awesome](https://fontawesome.com/) - used the font awesome icons to style the information and the links in the footer, and also to make the Reservation section stand out a small bit.
- [Am I Responsive](http://ami.responsivedesign.is) - Testing of the site to make sure it's responsive
- [The W3C Markup Validation Service](https://validator.w3.org/) - For testing of all the HTML and CSS


## Testing

### First Test - Manual testing in Chrome Dev Tools
Using Dev Tools, checking booth responsiveness, navigation and links. One screen size at a time.
- Mobile 
    - Design and responsiveness - Making sure the user experience is good a small screen.
    - Links and Buttons - Making sure links and buttons do what are intended
    - Navigation - Testing the dropdown navigation, making sure it becomes a hamburger button for mobile screens
- Tablet 
    - Design and responsiveness - Making sure the user experience is good on all platforms and is repsonsive at slightly bigger screen.
    - Links and Buttons - Making sure links and buttons take you where they should
    - Navigation - Testing navigation, making sure it's visible and that the dropdown for mobile screens is not visible
- Desktop (Laptop and large screen resolution)
    - Design and responsiveness - Making sure the user experience is good on all platforms and is repsonsive at larger screen.
    - Links and Buttons - Making sure links and buttons take you where they should
    - Navigation - Testing navigation, making sure it's visible and that the dropdown for mobile screens is not visible

### Browser compatibility

- works as intended on chrome, firefox and opera, IE works the same however the wanted google fonts dont come through, however the site is still fine to navigate.

### Second Test - Validation of code using W3C Markup Validation Service
- Testing HTML
    - Pasted the url of each individual page for validation. A few minor errors in the code was discovered and corrected.
- Testing CSS
    - Pasted the complete CSS code in the "Validate by direct input"-section. No problems found

### testing user stories 

* as a user i want to be able to book the truck for private hire
   - User navigates to the contact page easily and fills in the form and sends the email.
* as a user i want to be able to know the location on any given day
   - location is given in the footer on all pages and map is on the contact page.
* As a user, I want a simple and clean looking website as messy, busy pages with lots of information overwhelms me.
  - User views the homepage and sees that the colour scheme and layout is very clean and simple and minimalistic, the images and content is well spaced out. With 4 pages all with the same consistent style, with quality images and brief descriptions throughout so not to overwhelm users with too much information.
* as a user i want to be able to see what food is available.
  - the menu is available as a PDF found in the nav bar on all pages, pictures of food are displayed in the gallery! 
* as a user i want to know how the food is sourced so i can make informed decisions
  - a brief introduction is on the home page and a more indepth account of where the ingredients are sourced can be easily found on the about us page.
* as a user i want to be able to easily find your social media accounts so i stay up to date 
  - all social media links found within the footer as clear icons on all pages. 
* as a user i want to be able to find out who background of the foodtruck and owners/chefs
  - a brief introduction is on the home page and a more indepth account of the staff and owner can be found by clicking a link on the homepage or using the nav bar to go directly to the about us page.
* as a user i want to be able to see pictures of food made by the fiji food truck
  - pictures available on the home page with most of the content available within the gallery page.

  ### bugs

* on smaller devices within the footer a white margin appears on the left, using chrome dev i cant find where this stems from so i am unable to find a way to resolve this.

## Deployment 

### Delopying the project remotely via githubpages:

1. On the menu on the top of the project’s repository on GitHub select Settings.
2. Scroll down to the GitHub Pages section.
3. Inside that section, click on the drop-down menu under Source and select Master Branch.
4. The page refreshes automatically and the website is now deployed.
5. The link to the webpage is just in the GitHub Pages section down below.

i only used one branch for this project

### delopying he code locally 

1. Go to GitHub.com
2. Under the this repository’s name, click Clone or download.
3. Click on the icon that looks like a clipboard on the right side of the URL (this copies URL link)
4. Open repo or create new repo
5. Open terminal
6. Type git clone and paste URL link and press enter.

to open via repl:
 1. follow up to step 4 then:
 2.  Click on ‘Download Zip’
 3. Open IDE Repl.it
 4. Upload folder or files

## Credits

#### media 
 all images taken from The Fiji food truck instagram [Fijifoodtruckinsta](https://www.instagram.com/thefijifoodtruck/?hl=en) 

#### Acknowledgements

Code institue previous projects as well as my mentor Precious Ijege.
https://www.youtube.com/watch?v=wfaDzSL6ll0&list=LL&index=13&t=299s&ab_channel=Keepcoding

