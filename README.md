# 3D Academy

3D Academy is an online school for people who want to learn how to create amazing 3D Models for Games or VFX. This website will be useful for people with different levels of 3D modeling knowledge, either people who are completely new, or people who are looking to extend their knowledge. 

This website will provide the information about the school and mentor, who will be running the program, and different types of courses this school offers. This website also provides a gallery with mentor's work and a sign-up form for people who want to join the school or get more informattion about the courses.

![Responsive Check Screenshot](assets/images/website-responsivnes.JPG)

## Features

This section is describing all the existing features available on the website

* **Navigation bar**

-Navigation bar features the links to different sections of the website, such as Home, About, Courses, Gallery, and Contact Form. It is fully responsive, fixed to the top of the page, and it also contains the logo of "3D Academy". Navigation by navbar offers a smooth scrolling through the website for better user experience.

-This section will allow user to easily navigate through the website without scrolling or need to use "Back" button of the browser.

![Navbar Screenshot](assets/images/navbar-feature.JPG)

* **The Hero Image and Intro text**

-The Hero Image includes a collage of mentor's personal work and it overlayed with a short description of the school. Hero Image features Parallax Scrolling.

-This section will introduce the user to the school and will give a first impression about the mentor experience.

![Hero Image Screenshot](assets/images/hero-image-feature.JPG)

* **About Section**

-About section consists of the background image from one of the projects that mentor has worked on previously and it features Parallax Scrolling effect. It overlayed with mentor's profile, which consists of profile image on top, and short bio at the bottom.

-This section will provide users with information about the mentor, his experience and the reason why he created this school. People will feel more confident joining the school if they know who their mentor is and what expereince he's got.

![About Screenshot](assets/images/about-feature.JPG)

* **Courses**

-Courses section consists of two Cards with details about the courses. It has the background image on top, showing a 3D model related to the course, and at the bottom description of the course providing the information what course it is, what level of knowledge required and what software students will use. This section is responsive and on the smaller screens cards will allign vertically, on top of each other, instead of being two in the row.

-This section will introduce users to the courses that school is offering, giving them the option of two different courses - one is for begginers who want to learn hard surface modeling, and another course at intermidiate level students teaching how to create a character for a video game.

![Courses Screenshot](assets/images/courses-feature.JPG)

* **Gallery**

-The gallery contains the 3D artwork from mentor's portolio, showcasing the variety of experience and knowledge. 

-This section is important as having a great portfolio showcase can inspire and persuade users to sign up to the program.

![Gallery Screenshot](assets/images/gallery-feature.JPG)

* **Sign-up Form**

-Sign-up is a simple form that allows user to enter their first name, last name, and email address. There are also radio buttons which allow user to select what course they are interested in, either Hard Surface, Character Modeling, or both. All fields are mandatory and user won't be able to submit the form without filling up all the fields and selection one option from the radio buttons.

-This section is important as it allows user to show the interest in joining the school and for the mentor to follow up and provide all the details about the course for the user. 

![Form Screenshot](assets/images/signup-form-feature.JPG)

* **Footer**

-Footer is located at the bottom of the page and it contains the links to social medias, such as Instagram, Facebook, Twitter, and Youtube.

-User can use this section to quickly access social medie profiles related to this school or mentor, learn more, or maybe leave a feedback or chat. Because footer is fixed it will always stay at the bottom part of the screen and user doesn't have to scroll all the way down to access the links.

![Footer Screenshot](assets/images/footer-feature.JPG)

* **Sign-up Page**

-Once user completes and submits the sign-up form user will be taken to the new webpage with "Thank you" message. This page consists of Navigation bar, Footer, and a message in the middle. The structure is almost identical to the main page, but with only one difference - Navigation Bar got button only to Home section, which will take the user back to the main page.

-It is important as this section will provide the user with confirmation that form has been submitted and mentor will get in touch soon, and Home button on Navigaton bar will allow user to return back to the main page without using the Back button on their browser.

![Signup Page Screenshot](assets/images/signup-page.JPG)

## Testing

In this section I did some of the automated and manual tests in order to ensure that project is functioning correctly.

### Validator Testing

* **HTML**

-After using W3C Validator I have recieved one warning about my HTML code that suggests using headings for "section" elements:

![HTML Warning message](assets/images/w3c-validator.JPG)

-In this situation, instead of adding headers directly inside the section, I have created separate section inside of my HTML code that contains a header element for each of the section. I found this way to be easier to align the elements and apply different style to them.

![Gallery code snipet](assets/images/gallery-section-code.JPG)

Here you can see how it looks in the browser:
![Gallery with heading](assets/images/gallery-with-heading.JPG)

* **CSS**

-After using W3C CSS validator I got an error message saying that on line 278 of my CSS code I used the wrong value for "transform" property:

![CSS Validator error message](assets/images/css-validation-error-message.JPG)

And here is the code snipet. This code is responsible for increasing the size of the image in gallery once the user hovers the mouse over it:

![CSS Code error](assets/images/css-error.JPG)

-Even though the functionality wasn't affected, I still had to fix my code to ensure that all the values are set correctly and my code meets the standards:

![Fixed CCS code](assets/images/css-validator-fix.JPG)

-After this changes I used W3C validator again and my code was approved:

![CSS Validator Approved](assets/images/css-validation-pass.JPG)


### Manual Testing

In this section I did some manual testing, using various mobile devices, to ensure that website is responsive and adapts to different screen sizes.

* **Samsung S8+ Tablet**

-Here I used my Samsung S8+ tablet, medium size device, to ensure that website behaves correctly. Tablet operates on Android 13 and uses Chrome browser:

<img src="assets/images/tabs8-about-section.jpg" alt="Tab S8+ About section vertical view" width=50% height=50%>

<img src="assets/images/tabs8-courses-section.jpg" alt="Tab S8+ Courses section vertical view" width=50% height=50%>

I also did tests using a landscape orientation of the screen:

<img src="assets/images/tabs8-courses-horizontal-test.jpg" alt="Tab S8+ Courses section horizontal view" width=50% height=50%>

<img src="assets/images/tabs8-horizontal-form-test.jpg" alt="Tab S8+ Form section horizontal view" width=50% height=50%>


* **Sony mobile phone**

-I used my Sony Xperia 1ii mobile phone in order to test my website on a smaller screen. Phone operates on Adroid 12 and uses Chrome browser:

<img src="assets/images/sony-phone-home-section.png" alt="Sony phone Home section" width=50% height=50%>

Due to the smaller screens originally not all the text could fit within the "About" section, so I had to implement a scrollbar in order to allow user to scroll and read through the profile: 

<img src="assets/images/sony-phone-about-section.png" alt="Sony phone About section" width=50% height=50%>

* **Iphone mobile phone**

-For this test I use Iphone 13 Pro to test the responsivnes of the website. Phone operates iOS 16.3.1 and uses Safari browser:

<img src="assets/images/iphone-courses.jpg" alt="Iphone courses section" width=50% height=50%>

<img src="assets/images/iphone-signup-page.jpg" alt="Iphone Sign-up page section" width=50% height=50%>

### Unfixed bugs
Here are listed some of the known bugs that currently are not fixed:

* **Gallery images get cropped at the edge of the screen**

-One of the unfixed bugs in the Gallery section. When user hovers a mouse over an image in the gallery, position at the edge of the screen, the images scales up and a part of the image goes outside of the borders of the screen, resulting of that part being cropped:

<img src="assets/images/gallery-bug.png" alt="Gallery bug" width=50% height=50%>

* **Hero image doesn't dislay correctly on iPhone**

-When testing this website on iPhone device I've noticed that the hero image is not displayed correctly. This issue has never appeard on any other devices, including the PC:

<img src="assets/images/iphone-heroimage-bug.jpg" alt="Iphone hero image bug" width=50% height=50%>


## Deployment

The site was deployed to GitHub pages. The steps to deploy are as follows: 
  - In the GitHub repository, navigate to the Settings tab 
  - From the source section drop-down menu, select the Master Branch
  - Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment. 

The live link can be found here - https://amozaya.github.io/portfolio-1-project/


## Credits

**Content**

* For inspiration and guidance whilst working on this project I used "Love Running" project
* Instructions on how to implement Parral Scrolling were taken from <a href="https://www.w3schools.com/howto/howto_css_parallax.asp">W3School - Parralax Scrolling</a>
* Instructions on how to implement Cards for Courses section were taken from <a href="https://www.w3schools.com/howto/howto_css_cards.asp">W3School - Cards</a>

**Media**
* About section background was taken from the project I've been working on called <a href="https://www.oncelostgames.com/the-wayward-realms"> Wayward Realms </a>
* All the other background or gallery images are my personal work and you can find some of them on my portfolio website - <a href="https://www.artstation.com/amozaya"> Artstation </a>






