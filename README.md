# Salford Squash Centre  
[View website in GitHub Pages](https://conal84.github.io/MS1-salford-squash-centre/)  

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
As a potential new customer I want to access squash centre information relating to
a first time visit to the centre. This includes centre location, parking, court and changing room facilities,
and how to become a member.

As an existing member I want to be able to access the log in area where future functionality could
provide information on squash centre timetable, training sessions
and court bookings easily so I can effortlessly use the court facilities.

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
Website key features will include the following;

* Header Navigation bar - provides webpage navigation options and links
    * Header Logo which also acts as a Home button  
    * Navigation items with links which scroll to related webpage content  
    * Hamburger icon which contains dropdown navigation items at screen sizes smaller than large

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

* Sign In Section - allows existing members to sign in
    * Existing members can sign in here

The site quotation section with information from the squash centre
coaches aims to provide a link between the coaches and potential
new customers. These quotations also give potential new customers a sense
of the professionalism of the squash centre.

### Structure
I want to keep the site as minimalist and clutter free as possible so that it is
easy to use for the wide ranging demographic. Users should be able to sign up easily as such I will adhere to the 3 click rule of thumb.
Information will be provided to users in a concise, straight forward manner. A common navbar and footer
will be used throughout the design.

The mobile first design will arrange information in single full width columns to allow content to be read easily.
On larger tablet and desktop display infromation will be arranged in additional columns using Bootstraps responsive grid design.
On larger displays the facilties section has been arranged in a mosaic type grid to present content in a more interesting, eye catching way.

Information will be grouped in 4 key areas;
* About - providing general squash centre infromation to the user
* Facilities - providing specific squash centre infromation
* Play - providing specific squash playing information
* Sign In - a page where exisintg users can sign in

### Skeleton
[Balsamiq-wireframe-mobile](wireframes/Squash-Centre-wireframe-mobile.pdf)  
[Balsamiq-wireframe-tablet](wireframes/Squash-Centre-wireframe-tablet.pdf)  
[Balsamiq-wireframe-desktop](wireframes/Squash-Centre-wireframe-desktop.pdf)

### Surface
I want the colors used on the site to mimic the colors of a professional squash court which are blue walls.
The color scheme of the site will match the images of professional courts and players.
Additional colors have been chosen by using a palette produced on the coolors.co website.  
[Coolors-palette](wireframes/palette.pdf)

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
3. Bootstrap (4.3.1)
4. Javascript
5. Google Fonts
6. AutoPrefixer
7. W3C HTML & CSS code validators

## Testing
In each of the main sections; Home, Facilities, Play and Login the required information has been provided and is accessible
to the end user. 

The layout of information expands into side by side columns on medium sized screens and above. The font also
increases slightly on medium screens sizes and above to provide easier to read text. At these larger screen sizes 
a jumbotron has been implemented to grab the attention and draw the user in to the sign up button. This has not been 
included on smaller screen sizes to prevent screen clutter. The facilities section has information laid out in single columns
at small screen sizes but on medium screens and above this becomes a mosaic tile design to present information in a more intertesting way.
The functionality of these media queries has been tested across all devices using Chrome Devtools.

The funtionality of Sign Up and Log In buttons has been tested by inputting incorrect and correct information into the required 
fields. The user cannot submit the Sign Up form without a first name, last name, email address in the correct format and a drop down select.
The user also cannot submit the Log In form without a username and a password. In the Get In Touch section the Google Maps link and the mailto link have also been tested. Social media links in the footer
have also been tested to ensure they take the user to the correct website. The naviagtion bar link items have been tested to ensure that when pressed the webpage scrolls to the correct content section.

The responsiveness of the website has been tested across a range of devices (Galaxy S5, Iphone 5/6/7/8/X, IPad, IPad Pro and Desktop PC) using Chrome Dev tools. The responsive design was also physically tested on personal Iphone, IPad, desktop and widescreen monitor devices.

W3C CSS & HTML Validators were used to check the validity and formatting of code.  

Fellow student feedback was also key to the testing procedure where other course participants provided me with some valuable tips.

## Deployment  
This project was developed using the GitPod IDE, version controlled by committing to git and pushing to GitHub via the GitPod IDE.

To deploy this page to GitHub pages from its specific [GitHub repository](https://github.com/Conal84/MS1-salford-squash-centre) the steps followed were;

1. Log into GitHub
2. In the Repositories list select **MS1-salford-squash-centre**
3. From the menu select **Settings**
4. Scroll down to the **GitHub Pages** section
5. Under **Source** select **Master branch**
6. On selecting Master branch the page is automatically refreshed, the website is now delployed
7. The link to the webpage can be found at the top of the **GitHub Pages** section

### How to run this project locally
To clone this project from GitHub:

1. Follow this link to the [Project GitHub repository.](https://github.com/Conal84/MS1-salford-squash-centre)
2. Under the repository name, click "Clone or download".
3. In the Clone with HTTPs section, copy the clone URL for the repository.
4. In your local IDE open Git Bash.
5. Change the current working directory to the location where you want the cloned directory to be made.
6. Type git clone, and then paste the URL you copied in Step 3.
7. Press Enter. Your local clone will be created

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