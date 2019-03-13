# The efficient rota
[(site available here)](https://sarosim.github.io/CUBE-Rota/index.html)

Preparing the optimal coverage of hourly paid staff for any events, shifts, projects or particular tasks is a combination of 
best assumptions for the amount of workload and the scheduling of workforce with the appropriate knowledge and experience.

Therefore technology assisting this process can:
 - deliver better sales or results otherwise by avoiding understaffing
 - deliver cost savings by eliminating overstaffing
 - improve outcome by making sure proper knowledge is always present
 - save time for managers planning their rota and preparing their staff schedule
 - streamline communications of schedules and minimize misinformation, miscommunication and misunderstandings
 - reduce administration costs and time spent on payroll and time & attendance reporting
 - evaluate, follow up and further optimize efficiency
 - provide benchmarking

Most online tools that aim to help managers in this area focus on the scheduling part, while only a few include solution for the planning part.

On the other hand, potential users either prepare rotas manually or use some sort of tools, but mostly spreadsheets with or without planning and evaluation features.

The aim of CUBE Rota is to fill this gap and provide an easy-to-use planning **and** scheduling tool for stand-alone stores/coffee shops/restaurants/caterers 
or multi-unit operators either in retail or hospitality.

## UX

This website is for **operations managers** of retail networks, hotels or catering companies as well as for **store/restaurant managers**, recruitment **agencies** and **caterers**.

- As a Retail Operations Manager of a network of 100 stores I'd like to reduce my labour costs while maintaining or improving sales results and customer satisfaction. 
- As the manager of an artesian coffee shop, I want to schedule enough people for the morning peak periods while keeping my labour costs under control.
- As a manager at a recruitment agency, I want to reduce the time needed to prepare all the schedules as well as switch the administration from paper to electronic and eliminate manual work.
- As a caterer, I want to use a single platform to allocate proper labour force for my functions and communicate the shift details to staff in a documented way, 
making sure all of them are aware of and confirm the details of their shifts.

As part of the design process I created mock-ups using the trial version of Balsamiq Cloud:
- [The main page](https://github.com/Sarosim/CUBE-Rota/blob/master/assets/Documents/Mockups/Home.png)
- [Industries page](https://github.com/Sarosim/CUBE-Rota/blob/master/assets/Documents/Mockups/Industries.png)
- [Features page](https://github.com/Sarosim/CUBE-Rota/blob/master/assets/Documents/Mockups/Features.png)
- [Pricing page](https://github.com/Sarosim/CUBE-Rota/blob/master/assets/Documents/Mockups/Pricing.png)
- [Login page](https://github.com/Sarosim/CUBE-Rota/blob/master/assets/Documents/Mockups/LogIn.png)
- [Sign up form page](https://github.com/Sarosim/CUBE-Rota/blob/master/assets/Documents/Mockups/Signup.png)
- [Booking a demo page](https://github.com/Sarosim/CUBE-Rota/blob/master/assets/Documents/Mockups/BookaDemo.png)

_The mock-ups contain a message indicator in the navbar, although I later decided not to include it in the production, because that is a feature for users already logged in._

I used mobile first approach as these pages can serve as landing pages for future advertisements, most of the features (to be developed later) will need desktop first approach,
as they are too complex to use on mobile and the users are office based.

As a landing page, the most important goals are to convey the message why this is good for the operations manager, the store manager, the caterer 
or the manager of an agency **and** to be eye-catching, visually appealing.

Pictures are telling 1000 words, so I choose a [picture](https://github.com/Sarosim/CUBE-Rota/blob/master/assets/agenda-2295709_1920.jpg) with a diary, a desk, a pen and a phone to generate the impression of **office work**, **scheduling** and **communication**. 
It is from Pixabay, where it is available *Free for commercial use No attribution required.*

The headline message tells:
- "Cost effective" - so you can save money
- "Plan your rota and Schedule your staff" - clearly states what it does.

Further indications of 'what', 'why' and 'for whom' are included on the home page, supported by showing the logos of and quoting existing happy users.<br> 
Links to more detailed explanations of the features, benefits and industry specifics are organized on separate pages, with links from the main page.<br>
At any given point, the user exactly knows how they can learn more and what actions can be taken (how they can start using the system or contact someone). 

In order to visually differentiate sections, the font colour of the jumbotron is used as background colour for the section right underneath it, 
while using its complementary colour to create maximum visibility and harmony. The font colour and the background colour are alternated for the 
following sections to clearly differentiate them. 

The background image of the index page is used for the login, sign in and demo requesting pages to keep consistency and minimise file size, although the 
forms are placed on a less transparent background to make them pop up.

The primary market for the site is London - where the proportion of staff with English as a second language is relatively high in retail and hospitality - therefore providing 
language options for the potential users is essential. It also serves the future aim of opening for overseas businesses.

I inserted a video and an audio file in order to satisfy the project brief, but these were not part of the original UX. 
I may decide to keep the idea of the embedded media, if so, media quality needs improvement.

## Features

### Existing Features

#### Explanation of industry specific advantages

Industry specific advantages are explained on a dedicated page, with short descriptions and links to them on the home page.

#### Explanation of site features

Similarly to the industry specific advantages, key features of the solution are explained on its dedicated page, with short descriptions and links to them on the home page.

#### User Stories 

User stories are shown in quotes, as well as in a linked video and an audio file. 
There are also logos of *current subscribers* (fake at the moment obviously) to the service shown at the bottom of the home page. 

#### Pricing packages

There are three levels the service can be used. The basic features are offered for free, more advanced features are offered for £1 per user per month and the full, 
customised version is to be negotiated. These packages are clearly demonstrated on the pricing page.

#### Booking a demo

Potential users can fill in a form to get someone demonstrating and explaining how to use the system and what it does.

#### Signing up for the service

At any given point on the site, users may decide to start using the service, they can jump to the sign up form with one click.

#### LogIn

A page for existing users to log in. There are two main types of users:
- managers preparing the rota and the schedules and
- staff receiving the info about their rota,

therefore users have to pre-select which group they belong to - using radio buttons on the top of the log in form.

### Features left to implement

#### Language selection

The feature is indicated in the navbar by its icon and dropdown list of languages, but only English is available for now, the rest of the list is disabled.

#### Social media and other footer links

As there are no social media accounts set up for the currently fictional company, nor legal documents or detailed company info 
available, the links point to the home page (social links open in a new browser window - as it is more appropriate for them).

#### Form submission

The scope of the current project is to create the user interface with the appropriate design as per the UX, without backend support the forms can not yet be submitted.

## Technologies used

### Bootstrap 4, Bootswatch 

I used Bootstrap 4.2.1 framework and applied the Litera theme of Bootswatch. 

### Adobe Photoshop CS5

The CUBE logo and the CUBE Solutions Ltd. (fictional) company logo were created in Photoshop.

![Cube logo](assets/cube.png)

![CubeSolutions logo](assets/CubeSolutions_logo_small.png)

### Google fonts 

The extra look of the 'CUBE Rota' text in the brand section of the navbar is achieved by using Fredericka the Great font from Google fonts.

### Font Awesome

Icons used throughout the pages are from Font Awesome Free Version 5.7.2

## Testing

As it is not possible to automate any testing in HTML or CSS, I performed manual tests on available devices 
(Android 6.0.1 and 8.1, iPhone 4S, SE and 6, Google Chrome 72.0.3626.109 both on laptop and desktop) and asked family members to do the same by checking 
each section, picture, logo, link and feature.

First results showed some pages overlapping the footer on smaller devices and some internal links pointing to improper parts of the site. 
All pictures were showing correctly on each device. I fixed the links in the html files and the overlap in the css. 

I wasn't happy with the display of the pricing cards on mobile or tablet size, therefore modified the flexbox of the pricing page.

Checking the forms I found that the job title field of the *Book a Demo* form was defined as e-mail and one of the e-mail fields was defined as text field, 
corrected and also solved the form validation for the password field for the sign up by adding input pattern to it.

Trying to test other browsers I've found CrossBrowserTesting Chrome extension and I tested the following browsers with it:
- Microsoft Edge 18
- Firefox 65 (64 bit)
- Opera 58
- Safari 10.13
- Internet Explorer 11

The outcome of the test was that the CSS Shapes solution for floating the text in a circular shape around the logos didn't work on Edge and IE, 
text flow around the logos showed up square. I expected this, as the tutorial stated that "Shapes do not have IE support, and are under consideration for Microsoft Edge". 
Showing in a square is an okay fallback solution, so this can be treated as a feature rather than a bug :) 

The headline text was rendered in the middle 10% of the page on Internet Explorer. I made a decision to ignore this issue and do not spend time and effort 
to support an obsolete browser, especially because of the very limited likelihood of businesses still using it. 
Those who do, may not be the target audience of the solution I plan to offer, anyway.

Finally I validated each html as well as the css codes with the validator on the W3C website. I corrected the errors or in case of the css, the validator 
treated the *shape-outside: circle();* as error, but I left it unchanged.

## Deployment

I deployed the site on GitHub Pages from the master branch. Any future changes committed to the master branch will automatically update the deployed site.
By default on GitHub, the landing page must be named index.html, therefore it may not be renamed.

## Credits

### Media

As mention earlier, the background image is obtained from Pixabay. Likewise, the 'fake' logos for the *happy customers* section are from Pixabay, by [ptra]("https://pixabay.com/users/ptra-359668/").

The profile pictures at the Quotes section is my wife and myself, names and the hotel are fictional.

The audio and the video is my own recording, the video is directed by and featuring Sofia Sarosi - my daughter.

### Acknowledgement

I'd like to thank to **Rick Gallegos** - my mentor - for the encouragement to choose my own idea for the project as well as for the support throughout.

##### Codrops

Positioning the floating paragraphs around Font Awesome logos in a circular shape is achieved by implementing the idea of Tania Rascia 
following her ["An Introduction to CSS Shapes"](https://tympanus.net/codrops/2018/11/29/an-introduction-to-css-shapes/) tutorial on Codrops.

##### Convertico.com

The browser tab icon (favicon) was converted from png by using the Convertico.com site.

##### Stack Overflow

I searched Stack Overflow to fix some bugs or figure out solutions that I couldn't solve otherwise.

##### W3Schools.com 

Beside revisiting the modules and checking my notes, explanations and examples at W3Schools.com helped me properly shape my code.

##### CSSmatic

I used CSSmatic to generate the box-shadow that I liked the most.

##### W3C Validator

I validated both the html and the css codes with W3C's validator.