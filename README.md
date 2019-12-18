<h1 align="center">Salford Squash Centre</h1>

This website will meet the squash centre business needs
of attracting more customers by raising awareness and providing an online presence 
for the centre. The website will provide a simple to use 
squash centre infromation and sign up service for new customers.
Existing customers will also benefit from an efficient log in area.

The squash centre user needs will be met by the website providing
key information regarding facilities, membership and fees.
New users will also find helpful information on contact details, location,
parking facilities and opening times which is aimed at making their first 
visit to the centre as smooth as possible.

## UX
### User Stories
As a user I want to access squash centre information relating to a first time visit to the centre.
This includes centre location, parking, court and changing room facilities and how to become a member.  

As a user I would like to see images of the court, changing room and other facilities.  

As a user I want easy access to sign up and log in buttons and I want to be quickly taken to other main page areas 
of facilties, play and back to the home location.  

As a user when I click the Log In or Sign Up buttons I would like to 
be presented with the relevant user entry information in a concise and simple way.

As an existing member I want to be able to access the log in area where future functionality could
provide information on squash centre timetable, training sessions and court bookings easily so I can effortlessly use the court facilities.

### Strategy
The Salford Squash Centre website will serve the business objectives
by attracting new customers to the centre and by supporting the needs of
existing customers. Overall this will increase the squash centre sales.

Website users will have easy access to squash centre information
which will allow them to use the centres facilities in an effortless and smooth way.

This website will be aimed at a range of squash player demographics from
junior amateur players aged 12 to 18, senior amateur players 18 to 50 to 
elite competitive players at both junior and senior age ranges. As a result
of this wide range of users the site must be simple to use and laid out in 
a concise manner.

### Scope
Website key features include the following;

* Header Navigation bar - provides webpage navigation options and links
    * Header Logo which also acts as a Home button  
    * Navigation items with links which scroll to related webpage content  
    * Hamburger icon which contains dropdown navigation items at screen sizes smaller than large
    * Log In and Sign Up buttons leading to modals where the user can enter information

* Home Section - provides general squash centre information
    * Images carousel of squash players  
    * Call to action button for user to sign up
    * Contact information
    * Opening times
    * Location
    * Quotations from staff

* Facilities Section - provides detailed information on squash centre facilities
    * Court information
    * Changing rooms information
    * General facilities information

* Play Section - provides detailed information on booking and playing
    * Membership schemes
    * Fees
    * Training

* Log In / Sign Up Section
    * Existing members can log in here
    * New members can sign up here

The site quotation section with information from the squash centre
coaches aims to provide a link between the coaches and potential
new customers. These quotations also give potential new customers a sense
of the professionalism of the squash centre.

### Structure
I want to keep the site as minimalist and clutter free as possible so that it is easy to use for the wide ranging demographic. 
Users should be able to sign up easily as such I will adhere to the 3 click rule of thumb.
Information will be provided to users in a concise, straight forward manner. 
A common navbar and footer will be used throughout the design.

The mobile first design will arrange information in single full width columns to allow content to be read easily.
On larger tablet and desktop display infromation will be arranged in additional columns using Bootstraps responsive grid design.
On larger displays the facilties section has been arranged in a mosaic type grid to present content in a more interesting, eye catching way.

Information will be grouped in 4 key areas;
* **About** - providing general squash centre infromation to the user
* **Facilities** - providing specific squash centre infromation
* **Play** - providing specific squash playing information
* **Log In / Sign Up** - an area where exisintg users can log in or new members can sign up

### Wireframes
* [Wireframe-mobile](wireframes/Squash-Centre-wireframe-mobile.pdf)  
* [Wireframe-tablet](wireframes/Squash-Centre-wireframe-tablet.pdf)  
* [Wireframe-desktop](wireframes/Squash-Centre-wireframe-desktop.pdf)

### Surface
I want the colors used on the site to mimic the colors of a professional squash court which are blue walls.
The color scheme of the site matches the images of professional courts and players.
Additional colors have been chosen by using a palette produced on the coolors.co website.  
[Coolors-palette](wireframes/palette.pdf)  

During the design process it was found the the red color originally planned for call to action buttons in the wireframes was too dominant and prevalent.
Alternatively a slightly softer orange color proposed by the coolors.co website was used.

I have used Lato font throughout the website as it has a simplistic style. 
I have used Open Sans font for the website buttons as this font looks slightly better on a bright button background.

## Features to implement
Future features will include a functioning existing user Login section which will redirect the user to a page where
they can access a squash court timetable, view available courts and book a court.

Future features will also include a new member sign up page which will allow the new member to select the membership 
scheme they would like and will then process payment and provide a username and password.  

A future training section would allow users to view and select training sessions and contain imbedded short training 
squash tips videos.

## Technologies used
1. HTML
2. CSS
3. Javascript
4. [Bootstrap](https://getbootstrap.com/)
5. [Google Fonts](https://fonts.google.com/)
6. [AutoPrefixer](https://autoprefixer.github.io/)
7. [Font awesome](https://fontawesome.com/)
8. [jQuery](https://jquery.com/)
9. [Popper.js](https://popper.js.org/)

## Testing
Testing involved viewing the website myself on a range of devices both in Chrome Dev tools and on physical Iphone, tablet and desktop devices.
As part of the testing procedure my peers reviewed the website and provided constructive comments.

In each of the main sections; Home, Facilities, Play, Login and SignUp the required information has been provided and is accessible
to the end user. The layout of information expands into side by side columns on medium sized screens and above. The font also
increases slightly on medium screens sizes and above to provide easier to read text. At these larger screen sizes 
a jumbotron has been implemented to grab the attention and draw the user in to the sign up button. This has not been 
included on smaller screen sizes to prevent screen clutter. The facilities section has information laid out in single columns
at small screen sizes but on medium screens and above this becomes a mosaic tile design to present information in a more intertesting way.
The functionality of these media queries has been tested across all devices using Chrome Devtools.

The funtionality of Sign Up and Log In buttons has been tested by inputting incorrect and correct information into the required 
fields. The user cannot submit the Sign Up form without a first name, last name, email address in the correct format and a drop down select.
The user also cannot submit the Log In form without a username and a password. In the Get In Touch section the Google Maps link, the mailto link and the telephone link have also been tested. Social media links in the footer
have also been tested to ensure they take the user to the correct website. The naviagtion bar link items have been tested to ensure that when pressed the webpage scrolls to the correct content section.

The responsiveness of the website has been tested across a range of devices (Galaxy S5, Iphone 5/6/7/8/X, IPad, IPad Pro and Desktop PC) using Chrome Dev tools. The responsive design was also physically tested on personal Iphone, IPad, desktop and widescreen monitor devices.

W3C CSS & HTML Validators were used to check the validity and formatting of code.  

Fellow student feedback was also key to the testing procedure where other course participants provided me with some valuable tips.
This advice included the fact that at larger screen sizes the mosaic tile images in the facilties section appeared slightly wider than the other text
based tiles. Also during a user review I was informed that the image height was too large as it skewed the image on smaller devices, this was rectified by setting a smaller value for this variable.

### Responsiveness
* Plan: The website needed to respond to different device sizes and to device orientation. 
* Implementation: Bootstrap was employed to undertake a mobile first design with grid elements which change orientation based on screen width.
The facilities section mosaic was designed with a Bootstrap grid system which used the Bootstrap order class to change the position of mosaic tiles at larger screen sizes.
This means that the mosaic can be used at larger screen sizes but on smaller devices the mosaic would not be shown as it would cause too much clutter and would not look good at the smaller size.
I also created my own media queries to changed the color of text, icons and backgrounds for the mosaic tiles at different screen sizes.
* Result: On small devices and medium to large devices the website responds well and the images and text can be easily viewed. The mosaic tiles and their content change colors as planned.
* Verdict: This test has passed and the site is reponsive.

### Design
* Plan: The design of the site needs to be eye catching and high energy as it is to appeal to an energetic squash player user.
In this way I wanted to use bold colors which mimic squash court colors to some degree. The design also needs to have many call to action buttons to attract new users.
* Implementation: Bold blue and orange colors were used as the bold matches the professional squash court colors and with the orange provides a good contrast.
Two triangle opaque shapes are used at large screen sizes on the carousel images to give an effect of players moving at an angle around the court. Call to action buttons
are also provided at multiple locations throughout the website. The image carousel also provides a high energy feel by showing squash players at different emotional states.
* Result: The website catches the eye without overwhelming the user and provides a high energy, intensity to the user.
* Verdict: This test has passed as the colors are bold and the website stands out with being overpowering.

### Carousel
* Plan: I wanted to use an image carousel to show squash players in different states and to provide the user with a high energy feel and the intensity of playing a game of squash while on the site.
* Implementation: I used Bootstrap carousel to create the image carousel within a Bootstrap grid system.
* Result: The sliding carousel works well a provides the user with an energetic website feel.
* Verdict: This test has passed.

### Contact information
* Plan: I wanted to display the contact infromation in a simple easy to access way which would increase the chances of a user visiting the physical squash courts.
* Implementation: Using the Bootstrap grid system the information was presented in a minimal but informative manner. Links to google maps location, email address and telephone number are also easily accessible.
* Result: The information is easily viewed and links are easy to access and work well.
* Verdict: This test has passed as the user can access this information easily.

### Quotations
* Plan: To include quotations from squash centre staff which speak about the faciltiies and enhance the professional feel of the site while providing useful information to the user.
* Implementation: Staff quotations have been included in the Bootstrap grid
* Result: The quotation section can be easily read at all screen sizes and provide useful information and a professional squash centre feel.
* Verdict: The test has passed

### Facilities
* Plan: Provide the user with images and general information about the squash centre in an interesting way
* Implementation: At smaller screen sizes the Bootstrap grid is used to present images and information to the user but at larger screen sizes
I designed a mosaic tile pattern by ordering the tiles in different arrangements and then using media queries to target and style the text and background of the tiles.
* Result: At large screen the infromation is provided in a mosaic tiled pattern which makes viewing and reading about the facilities a more interesting and eye catching experience as 
often reading about these aspects can be more mundane for the user.
* Verdict: This section ahs passed the test.

### Forms
* Plan: Provide users log in and sign up information in a easy to use, clutter free manner
* Implementation: Originally only the Sign Up section was in a button and modal format and the log in section was at the bottom of the web page but after some user feedback this was changed
to have both the log in and sign up features in button modal formats to improve the user experience.
* Result: Both Log In and Sign Up buttons are available to the user on the navigation bar and at the bottom of the web page. The Sign up button is also
included in the jumbotron at larger screen sizes for an added call to action.
* Verdict: This works well for the users and provides them with many opportunities to use the call to action buttons.

### Social media
* Plan: Include social media links for the squash court to improve the user experience and to make this infromation easily available.
This also increases the professional sense of the squash centre.
* Implementation: Social media links have been added to the footer of the site
* Result: The links stand out on the footer and change color when the user hovers over them.
* Verdict: This element of the website has passed this test.

## Bugs  
### During development
* Bug: The html scroll to the facilties and the play sections would always scroll too far down the page leaving the navigation bar directly above
the facilities and play section headings.
* Fix: I have added a span to each of these sections which are positioned absolute and moved towards the top of the web page by 50px.
* Verdict: The scroll to facilities and play sections now allows some space above the headings and looks much better.

* Bug: A user provided testing feedback that the facilities mosaic tile images appeared slightly too wide at larger screen sizes.
* Fix: The overflow of the image was set to hidden, the height was set to auto and the display was flexed and centered.
* Verdict: Images now appear the correct width on all screen sizes.

### Known bugs
* Bug: At large screen sizes the carousel images appear slightly pixelated. This is due to there being no squash player stock images available and all
images on google images at large wallpaper size are of slightly lower quality compared with standard wallpaper size images 1920 x 1080.

## Deployment  
This project was developed using the GitPod IDE, version controlled by committing to git and pushing to GitHub via the GitPod IDE.

To deploy this page to GitHub pages from its specific [GitHub repository](https://github.com/Conal84/MS1-salford-squash-centre) the steps followed were;

1. Scroll to the top of this GitHub page
2. In the Repositories list select **MS1-salford-squash-centre**
3. From the menu select **Settings**
4. Scroll down to the **GitHub Pages** section
5. Under **Source** select **Master branch**
6. On selecting Master branch the page is automatically refreshed, the website is now delployed
7. The link to the webpage can be found at the top of the **GitHub Pages** section

### How to run this project locally
To clone this project from GitHub:

1. Follow this link to the [Project GitHub repository.](https://github.com/Conal84/MS1-salford-squash-centre)
2. Under the repository name, click **"Clone or download"**
3. In the **Clone with HTTPs** section, **copy the clone URL** for the repository
4. In your local IDE open the terminal
5. Change the current working directory to the location where you want the cloned directory to be made
6. **Type git clone**, and then **paste the URL** you copied in Step 3
7. Press **Enter**. Your local clone will be created

## Credits

Due to the difficulty in finding large good quality squash images on stock photo websites the images for the site were found 
by google searches at the links below.

[carousel image 1](https://www.gq-magazine.co.uk/article/how-to-play-a-killer-squash-serve)  
[carousel image 2](https://www.axios.com/newsletters/axios-sports-71a2fe22-8b3f-449a-9fc5-dfaf10ff3574.html)  
[carousel image 3](https://www.axios.com/newsletters/axios-sports-de0e0ae1-e235-4424-a5e8-ddd4b5065f9f.html)  
[carousel image 4](https://www.elmogaz.com/node/572311)  
[carousel image 5](https://www.squashsource.com/asics-gel-blade-4/)  
[carousel image 6](https://twitter.com/PSAWorldTour/status/956709294862426112)  
[headshot images](https://www.vosjcc.org/personal-training/)  
[facilities images](https://www.washingtonian.com/2017/05/16/take-a-first-look-inside-dcs-luxe-new-squash-gym/)

## Acknowledgements

The javascript to close the navbar menu once a selection has been made was found at this [site](https://mdbootstrap.com/support/general/auto-close-navbar-when-click-on-link-responsive-mode/).

**This is for educational use.**