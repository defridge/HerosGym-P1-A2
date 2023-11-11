# Heros Gym

The Heros Gym website is designed to give potential members an overview of the gym and what we are all about! Heros Gym offers “big gym” state of the art equipment and classes but with a “small gym” welcoming and encouraging atmosphere.

Using this website you will be able to find all relevant information about the gym including opening and closing times, the class timetable and descriptions of the classes we teach and a gallery showcasing the gym layout and equipment available. There is also a form section where potential members can register their interest and will be sent membership pricing.


![Responsive Mockup](assets/images/mockup.webp)

## Features

### Navigation Bar & Header Section

- Located at the top of the page, the navigation bar & header section shows the gym company logo on the left hand side and the other navigation links to the right.
- The Navigation links are, HOME, TIMETABLE, GALLERY, and SIGNUP
- When displayed on desktop, laptop or tablet screens all navigation links are visible but when displayed on a phone screen the links are hidden behind a Nav button which shows all these links in a dropdown menu.
- This section allows all users to navigate the website without the use of the back button.

![Navigation Bar](assets/images/NavBar-min.png)

### Footer

- Located at the bottom of all pages on the website is the footer which is styled in red with white social media icons which link to Facebook, Youtube, and Instagram.
- All social media icons when clicked or touched will open in a new tab to the correct site.

![Footer](assets/images/footer-min.png)

### Home Page

- The home page, and all other pages are styled using the same colours that are used in the company logo which are white/grey, black and red.
- The top of the page contains a heading of the gym name "Hero's Gym" and the gym tagline of "Are you ready to become your own Hero?"
- Underneath this we have the main image on this page of the gym owner posing on the ground floor of the gym and some text outlining the gyms three step approach to ensure its members make progress.
- This allows any visitor of the website to get the company ethos right away.
- Below this section we have added the gym opening and closing times and the address and contact info.
- The last feature on this page just above the footer section is a Google Map showing the gym location.

![Home Page](assets/images/homepage-min.png)

### Timetable Page

- The Timetable page is the second Nav link in the Nav bar.
- This page has a main image of a gym class in progress at the top of the page with a page heading placed in the center of the image.
- Below the image and the heading we have the full weekly gym class timetable which is coded as a table styled in red, white and grey which shows the name of the gym classes, the times they start, how long they run for and the days in which the classes take place.
- When viewing this page on a mobile screen the table is set to side scroll so it does not distort the layout of the page.
- Below the timetable is a detailed description of all the classes which allows the user of the website to get an idea of how the class is taught.

![Timetable](assets/images/timetable.webp)

### Gallery Page

- The gallery page allows the website user to see how the gym is layed out, the overall size of the ground floor and first floor, and pictures of the equipment in the gym.
- A picture speaks a 1000 words so other than the heading on this page there is no other text.
- Depending on screen size the images will arrange themselves into 1, 2, or 4 columns.

![Gallery](assets/images/gallery.png)

### Signup Page

- The last page on the website is the signup page. Here users are asked to enter some basic contact info and to choose which membership option they are interested in and submit a request to join the gym.

![Signup](assets/images/signup.png)

### Thank You Page

- When a user of the site completes the form on the sign up page and hits submit they will be redirected to the thank you page which confirms the form submission has been succesful and after 10 secounds they will be automatically taken back to the webiste homepage.

![Thankyou](assets/images/thankyou.webp)

### 404 Error Page

- A custome 404 page will be implemented and will display if a user navigates to a broken link.
- The 404 page will allow the webiste user to navigate back to the homepage if they end up on a broken link / missing page, without the need of the browsers back button.

![404](assets/images/404.webp)

## Technologies

- HTML
  - The webpage structure was created using HTML as the main language.
- CSS
  - The styling of the webiste was done using custom CSS saved in an external file.
- IDE
  - The website was developed using Codeanywhere IDE.
- Github
  - The source code is hosted on Github and deployed using Git Pages.
- Git
  - Git was used to commit and push code during the project.
- Favicon.io
  - Favicon files were created at [favicon.io](https://favicon.io/favicon-converter/)


## Testing

### Responsiveness

- All pages were tested on various screen sizes from Galaxy Fold 280px upwards and all pages are responsive and functions as intended.
- To test this webpage was loaded in browser and using Google Dev Tools each page was opened was changed to 280px and then the responsive window was dragged to max size.
- All pages responsed as intended and no images were stretched or pixelated.
- The timetable was given CSS code overflow to allow for screenscrolling on mobile phones screen sizes as reducing font size to fit made the content unreadable.
- Some devices website was tested on outside of Dev Tools were: Iphone 11, Samsung A6, Macbook Air, HP M27fw FHD monitor.

### Accessibility

- [Wave Accessibility](https://wave.webaim.org/) was used to test accessibility on final deployed website.
- All pages tested an no Errors were found.
- Color contrasts meet a minimum ratio.
- Heading levels are present and not skipped to ensure importance of content.
- All labels or aria-labels are in placed so that is read outload on a screen reader.
- All images have alt labels that will display if image does not load.

### Lighthouse Testing

- Home Page[Home](assets/images/lighthouseHome.png)
- Timetable[Timetable](assets/images/lighthouseTimetable.png)
- Gallery[Gallery](assets/images/lighthouseGallery.png)
- Sign Up[Signup](assets/images/lighthouseSignup.png)

### Functional Testing

- Nav Links
  - Testing was performed to make sure all navigation links opened the correct pages.
    - HOME - index.html
    - TIMETABLE - timetable.html
    - GALLERY - gallery.html
    - SIGN UP - signup.html

- Form Tests
  - The form on the sign up page was tested to make sure it worked as intended.
  - Steps Taken:
    - Test 1: First Name, Last Name, Email Address entered. 1 of the 2 radio buttons ticked. Submit button clicked. User is taken to a "thank you" page confirming form submission and then automatically redirected back to the home screen after 10 secounds.
    - Test 2: If any one of the First Name, Last Name, Email Address sections are left blank when submit button is clicked a "please fill in this field" messaged is displayed on missing info section.
    - Test 3: If a none-email address is entered in the Email Address field a "please include an @ in the email address" messaged is displayed ensuring the error is fixed befor submiting.
    - Form worked as intended.

- Social Media Icons
  - All social media icons located in the footer of the webpage, when clicked open in a new tab to the correct social media website.
  - All links work as intended.

- Contact Infomation Links
  - When the user clicks on the Gym contact number on a mobile device they are promted to call using the devices phone app.
  - When the user clicks on the Gym contact number on a laptop/PC/tablet they are promted to call using the devices phone app such as Facetime.
  - When the user clicks on the Gym email address on any device the email application of said device opens in a new email tab.
  - All contact links work as intended.

### Validator Testing

- HTML: No errros were returned when passing through the offical [W3C Validator](https://validator.w3.org)




### Bugs

- When using validation tools I discovered that the image file paths had blank spaces which needed to be filled with "%20".

### Validator Testing

- HTML: No errors were returned when passing through the official [W3C Validator](https://validator.w3.org/nu/#textarea)
- CSS: No errors were returned when passing through the official [Jigsaw Validator](https://jigsaw.w3.org/css-validator/validator)
- Accessibility: I confirmed that the colours and fonts chosen are easy to read and accessible by running it through lighthouse in Dev Tools.

## Deployment

- The site was deployed to GitHub pages.
- In the GitHub repository, navigate to the Settings tab.
- From the source section drop-down menu, select the Master Branch.
- Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment.

The link to the live site can be found here: [Heros Gym](https://defridge.github.io/HerosGym-P1-A2/)

## Credits

### Content

- The code for the footer section using the social media icons were taken from the CI Love Running project.
- The code to style the table for the Timetable page was taken from [w3schools](https://www.w3schools.com/css/css_table.asp)

### Images

- All images used for the website were taken by myself.