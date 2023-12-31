# GOTHENBURG CYCLING TRIPS

Gothenburg Cycling Trips is a bike tour service in Gothenburg city (Sweden). The reason for creating this site is to promote an environmentally friendly and uncomplicated way to explore Gothenburg city for tourists or anyone enjoying bicycling. Furthermore, the target group could be anyone newly moved to Gothenburg wishing to make new acquaintances and would suit well for team activities.

![landingpage](landingpage_.png)

Link to the site:
[GOTHENBURG CYCLING TRIPS](https://bjornl1.github.io/cycling-gothenburg/)

## CONTENTS

- [GOTHENBURG CYCLING TRIPS](#gothenburg-cycling-trips)
  - [CONTENTS](#contents)
  - [User Experience (UX)](#user-experience-ux)
    - [User Stories](#user-stories)
  - [Design](#design)
    - [Colour Scheme](#colour-scheme)
    - [Typography](#typography)
    - [Imagery](#imagery)
    - [Wireframes](#wireframes)
  - [Features](#features)
    - [Future Implementations](#future-implementations)
    - [Accessibility](#accessibility)
  - [Technologies Used](#technologies-used)
    - [Languages Used](#languages-used)
    - [Frameworks, Libraries \& Programs Used](#frameworks-libraries--programs-used)
  - [Deployment \& Local Development](#deployment--local-development)
    - [Deployment](#deployment)
    - [Local Development](#local-development)
      - [How to Fork](#how-to-fork)
      - [How to Clone](#how-to-clone)
  - [Testing](#testing)
  - [Credits](#credits)
    - [Code Used](#code-used)
    - [Content](#content)
    - [Media](#media)
    - [Acknowledgments](#acknowledgments)

---

## User Experience (UX)

- __Initiation of concept__

Bicycling has become more popular in recent years in Gothenburg, combined with an improved bike lane network, the evolution of e-bikes, and ambitious targets from local authorities to use environmentally friendly transportation solutions, a new market opportunity has been enabled. Gothenburg cycling trips can offer the potential increase for bike trips.

- __Key goals for the site__

  - To offer a bike tour through the city by providing an easily accessible website. 
  - To offer a platform for social events and flexibility to adapt for customer/user input.

### User Stories

- __First time user:__
    I am:
  - Appreciating the website with a first impression of a well-balanced layout for information
  - Understanding the website's purpose and what services it offers.
  - Navigating easily to access the main functions.


- __Returning User:__
    I am:  
  - Establishing personal contact and should be able to give input to improve the site or service.
  - Exploring further options for bike tours.

## Design
### Colour Scheme
The landing page is the primary colour contributor to the website; hence the background is white in order the enhance the dominant colours in the hero image which represents the long Nordic summer sunsets.

One of the main colours used in the hero image (#252621) was re-used for the footer as well, the colour is still clearly making a distinct difference compared to the contact section above it but keeping the theme consistent with the landing page. The colour scheme was created with [coolors](https://coolors.co/). 

![colourscheme](colourscheme.png)

### Typography        
The fonts chosen for the project are Babas Neue and Kanit with sans-serif as backup, the fonts are distinct but still with a soft edge matching the landing page content.
These fonts were imported with Google Fonts [Google Fonts](https://fonts.google.com/)

Kanit: for all content except the header title element (h1)
Babas Neue: for Header (h1)

### Imagery
The imagery is a fundamental aspect of the site, since the service provided is primarily bike tours, various images from the tour were included to let the user be able to properly view the main parts of the route thus improving the experience overall.

Images:
- The landing page and rent a bike section are from pexels.
- The Gothenburg city map is from open street map (see reference in the credits section).
- All other pictures are taken by me.

### Wireframes

<details>
<summary>Desktop wireframe</summary>
<img src="wireframe_desktop.png" width="500">
</details>

<details>
<summary>Mobile wireframe</summary>
<img src="wireframe_mobile.png" width="500">
</details>

## Features

- The website is comprised of 6 sections: 
 - Landing page
   - Navigation bar 
   - Separate link to access the sign up page directly
 - Bike tour content
 - About us
 - Fixed tour
 - Rent a bike
 - Contact


- Landing page
  -  The header and navigation bar are adapted to media queries, once viewed on a smaller device the navbar will be placed under the header and both header and navbar will be centered for promoting consistency in the display of the items and avoiding interference between them.

  - A link to the sign-up form is displayed close to the top center, the purpose of the element is to draw attention to the link since it stands out from the page and leads directly to the link to sign-up form for the users.
![](navbar_tourlink.png)
- Bike tour content
  - In this section, the main content is presented to the user, it follows directly after the main page. The first image displayed is an overview of the Gothenburg city tour, the following content illustrates each tour section in the order following the route. For each image, there is a brief description of the different stops that are included in the tour. For smaller screens, the content is displayed as a row the information text is followed by the image for each tour stop, and by presenting the information in a row the image can be kept with a size making the image content clearly visible.
![](biketour_content_.png)
  - About Us. This section includes a subsection for the sign-up form for fixed tours. The first section is a description of the background of the webpage and what service is provided, after the introduction the subsection follows with the sign-up form.  
  - Fixed tour sign-up form
    - In this form, the user can submit a sign-up form to join the fixed tour, the form also includes the possibility to rent different bikes. The name and email fields are required to be filled in whereas the bike field is optional, however, there is a set quantity between 1 to 5 bikes preventing the user to not adding copious quantities by mistake. Furthermore, there is a link to the rent a bike in the form field allowing the user to quickly check which bikes are available before sending the form.
![](aboutus_tour_.png)    
- Rent a bike
  - This section includes the bikes provided by Gothenburg cycling trips, a table shows the cost of renting a bike. Below the table, a paragraph is placed at the top of each bike image.
 On smaller screens, the bike images are adapted by a media query to display a row instead of a horizontal alignment to fit the content properly.
![](rent_a_bike.png)
- Contact
  - The contact section includes an address field but also phone and mail information, the latter is prepared with a link enabling the user to access a prepared mail link to improve accessibility. 

- A footer that contains social media links to Facebook, Twitter, and YouTube. Using icons in the footer can be kept clean and because they are universally recognizable.
![](contact_footer.png)

### Future Implementations
  - Use JavaScript to add a "to top" button with a solid smooth scroll function.  
  - Use JavaScript to add a confirmation pop-up window to allow the user to confirm the submitted form.
  - Create a database for the bikes in order to easily control the number of bikes available and the repair status. 
  
### Accessibility

- I have been mindful during coding to ensure that the website is as accessible and friendly as possible. I have achieved this by:
- Using semantic HTML.
- Added metadata characteristics for optimizing SEO.
- Using descriptive alt attributes on images on the site.
- Ensuring menus are accessible by underlining the nav links for screen readers.
- Use the "hover" function on the sign-up submit button.

## Technologies Used

### Languages Used
- HTML5
- CSS
### Frameworks, Libraries & Programs Used
- [Balsamiq](https://balsamiq.com/) - Used to create wireframes.
- Git - For version control.
- Github - To save and store the files for the website.

- [Google Fonts](https://fonts.google.com/) - To import the fonts used on the website.

- [Font Awesome](https://fontawesome.com/) - For the iconography on the website.

- [Google Dev Tools](https://developer.chrome.com/docs/devtools/) - To troubleshoot and test features, and solve issues with responsiveness and styling.

- [TinyPNG](https://tinypng.com/) - To compress images.

- [Resize Pexel](https://www.resizepixel.com/) - To resize images and change to webp format.

- [Favicon.io](https://favicon.io/) To create favicon.

- [Am I Responsive](https://ui.dev/amiresponsive) & [Responsinator](http://www.responsinator.com/) - To show the website image on a range of devices.
  
## Deployment & Local Development

The project was deployed using GitHub pages. The steps to deploy using GitHub pages are:

Go to the repository on GitHub.com
Select 'Settings' near the top of the page.
Select 'Pages' from the menu bar on the left of the page.
Under 'Source' select the 'Branch' dropdown menu and select the main branch.
Once selected, click the 'Save'.
Deployment should be confirmed by a message on a green background saying "Your site is published at" followed by the web address.

### Deployment

Include instructions here on how to deploy your project. For your first project, you will most likely be using GitHub Pages.

### Local Development

#### How to Fork

- To fork the repository:

  - Log in (or sign up) to Github.
  - Go to the repository for this project, [cycling-gothenburg](https://github.com/BjornL1/cycling-gothenburg)
  - Click the Fork button in the top right corner.

#### How to Clone
- To clone the repository:

  - Log in (or sign up) to GitHub.
  - Go to the repository for this project,[cycling-gothenburg](https://github.com/BjornL1/cycling-gothenburg)
  - Click on the code button, select whether you would like to clone with HTTPS, SSH or GitHub CLI and copy the link shown.
  - Open the terminal in your code editor and change the current working directory to the location you want to use for the cloned directory.
  - Type 'git clone' into the terminal and then paste the link you copied in step 3. Press enter.

## Testing

### Testing User Stories from (UX) Section
- As a user, I want to be able to understand the business brand at a first look.
  - The welcome area on the homepage looks good on all devices. This is the main introduction to the brand and sets a nice tone for the business brand.

- As a user, I want to be able to see which type of service is provided on the landing page.
  - The link to the bike tour is clearly visible and which days it is scheduled for, also the navbar shows the user that you can rent a bike.

- As a user, I want to be able to access information where I can address questions and how to get in contact with the service provider.
  -  The links for "contact" "and about us" are positioned at the upper right position on the desktop version and centered just above the landing page on smaller screen devices for accessibility reasons.

As a user, I want to be able to be able to find the business location and to understand the scope of the tour.
- The map of the tour is placed directly under the landing page making it easy to be clearly visible, the starting point of the tour is indicated on the map with a big red marker, and the tour direction including stops is presented as numbers (1-7).
####  Validator Testing
- W3C Markup Validator
  - HTML - No errors were returned when passing through the official W3C Markup Validator

- W3C Validator Results
  - CSS - No errors were found when passing through the official W3C CSS Validator
   
- Lighthouse
  - Accessibility/SEO/Best practice
   - The site achieved a score of 100%, see below picture from lighthouse testing.
 
  - *Performance - The performance is 87% from one test run, however, the results can vary between different test runs even with unchanged code according to Google "lighthouse performance scores tend to change due the inherent variability and network technologies, even if there has not been a change to the page" reference in this link:
[DevelopersGoogle](https://developers.google.com/web/tools/lighthouse/variability) In order to achive above 90% in the test, the images would have been needed to be even more compressed and risking to become pixelated which would reduce the important first impression of the site, therefore this balance was judged to be the best compromise between loading page and image quality. If the site would become a real official site, a content device network (CDN) could be the best solution to display images, especially if the number of users would increase.
 
![lighthouse_test](lighthouse_test.png)

####  Further Testing

- Form Testing
  - The form has been tested to ensure it would not submit without the required input fields being filled in (full name and email address).
  - It also checks that the correct quantity is written in the rent-a-bike section of the form.

- Links Testing
  - All navigation links were tested manually to ensure the user is directed to the correct section of the website.

  - Social Media links in the footer of each page were tested manually to ensure they direct the user to the correct page and open in a new tab.

- Browser Testing
  - The Website was tested on Google Chrome, Firefox, Microsoft Edge, and Safari browsers with no issues noted.

- Device Testing
  - The website was viewed on a variety of devices such as Laptop, iPhone 11, and iPad to ensure responsiveness on various screen sizes. The website performed as intended. The responsive design was also checked using Chrome developer tools across multiple devices with structural integrity holding for the various sizes.

I also used the following website to test responsiveness:
- Responsinator
- Am I responsive

- Solved bugs
  - A problem with the footer was detected when trying to fixate it in the bottom of the page. At first it was possible to fixate it but then it covered other content above it. To solve it an instruction on a website had proper advice to on how to solve it by using the "flex-grow" which keeps the footer in the bottom of the page.

- Known Bugs/compromise
  - A "to the top" button with smooth behaviour would have been preferred to include in the site, however since I do not have any experience so far with JavaScript and judging from best practices to implement in a rational way java would be required, this is something I am currently unable to implement but would like to add to the website in a future update.

## Credits
### Code Used 

- Specific coding
  - For handling header and nav elements to make a column and center the website [adiati.com](https://adiati.com/how-to-create-a-responsive-navigation-bar-with-flexbox-and-media-queries) was an important contributor to solve the media query set up for smaller screens. In the section "Make The Navbar Responsive With Media Queries" partly the code shown was used on my website. The code can be found by searching on the class ". header-container" in the css file

 - General coding
   - For inspiration and tips the major sources were:
   - [W3 Schools](https://www.w3schools.com)
   - [Mozilla](https://developer.mozilla.org/en-US/docs/Learn)
  
### Content

The content is done by me, from idea to deployment.

### Media

- Pexels
  - No author - Silhouette-of-person-riding-a-bike-during-sunset [hero image](https://www.pexels.com/photo/silhouette-of-person-riding-a-bike-during-sunset-37836/)
  - Philipp M -  [Standard bike 28”](https://www.pexels.com/photo/black-and-white-hardtail-bike-on-brown-road-between-trees-100582/)
  - Adam Dubec [Standard bike 26”](https://www.pexels.com/photo/red-cruiser-bike-1595476/)
  - Abdulmomen Bsruki [Ebike 28”](https://www.pexels.com/sv-se/foto/gras-cykel-varumarke-produktfotografering-13989110/)
- Unsplash
  - No author  [Ebike 26”](https://unsplash.com/photos/eh64UHZ2m5Y)

- [OpenStreetMap](https://www.openstreetmap.org/copyright) (Gothenburg tour map)
 
### Acknowledgments

- I would like to thank the following:
  - Antonio Rodriguez (mentor) for guidance and support. 
  - Slack community - for quick feedback on various questions
  - My family - for their patience with having me coding sometimes late evenings and nights.  
