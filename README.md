# Heart Helpers

The Heart Helpers website designed to attract prospect volunteers to participate in events that raise money for people suffering with heart disease. It is designed to be responsive so that users of a range of devices can use the website without degredation of experience.

INCLUDE IMAGE HERE
![ALT TEXT](HYPERLINK.PNG)

[View Heart Helpers on Github](https://github.com/Dan-Matthews-23/heart-helpers)

![GitHub last commit](LINK TO GITHUB LAST COMMIT)
![GitHub contributors](LINK TO GITHUB)
![GitHub language count](LINK TO GITHUB)
![GitHub top language](LINK TO GITHUB)
![W3C Validation](LINK TO W3C VALIDATION)

## CONTENTS

- [Heart Helpers](#heart-helpers)
  - [CONTENTS](#contents)
  - [User Experience (UX)](#user-experience-ux)
    - [Background](#background)
      - [Key information for the site](#key-information-for-the-site)
    - [About the user](#about-the-user)
      - [User Goals](#user-goals)
      - [First Time Visitor Goals](#first-time-visitor-goals)
      - [Returning Visitor Goals](#returning-visitor-goals)
      - [Frequent Visitor Goals](#frequent-visitor-goals)
  - [Design](#design)
    - [Wireframes](#wireframes)
    - [Colour](#colour)
    - [Font](#font)
    - [Images](#images)
    - [Features](#features)
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
    - [W3C Validator](#w3c-validator)
    - [Solved Bugs](#solved-bugs)
    - [Known Bugs](#known-bugs)
    - [Testing User Stories](#testing-user-stories)
    - [Full Testing](#full-testing)
  - [Credits](#credits)
    - [Code Used](#code-used)
    - [Content](#content)
    - [Media](#media)
      - [Book Cover Images](#book-cover-images)
      - [Other Images](#other-images)
    - [Acknowledgments](#acknowledgments)

- - -

## User Experience (UX)

### Background

Heart Helpers are a fictional charitiable organisation that aim to generate revenue and attarct volunteers to support in local and national events in the interest of raising money for people affected by heart disease. Heart Helpers have twelve branches across the United Kingsdom. Each branch hosts fundraising activities in their local communities such as sponsered walks, walks and events with their local authority to raise awareness, particularly in schools and community centres. Each branch participates in quarterly national events organised by the central team. This website aims to showcase such events and attract new participents. 

There are two main aims for the website:

- Recruit new and existing volunteers to help with natioanlly-organised events
- Provide contact information about local branches to new and existing volunteers

#### Key information for the site

- Information on the next national event
- Information about previous events
- Testimonies of previous and existing volunteers
- Contact information for the twelve branches across the United Kingdom

### About the user

#### User Goals

- To recieve the same user experience on multiple devices
- To find out about previous and upcoming events easily
- To sign up to volunteer on the next national event
- To allow users to find information on their local branch
- To allow the user to contact someone if they need more information

#### First Time Visitor Goals

- To find information on the next national event, and to sign up to it with ease
- To be presented with clear, factual information
- To be able to connect with a local branch or a central team

#### Returning Visitor Goals

- To sign up to the next event
- To find out how sucessful the previous events have been
- To read volunteer testimonies, or submit one

#### Frequent Visitor Goals

- To find out how sucessful the previous events have been
- To read volunteer testimonies, or submit one

- - -

## Design

### Wireframes

Wireframes were created for desktop, tablet and mobile (1200px, 758px, 476px respectivley).

[Home Page Wireframe in Mobile View](/assets/images/wireframes-index-mobile.png)

[Home Page Wireframe in Tablet View](/assets/images/wireframes-index-tablet.png)

[Home Page Wireframe in Desktop View](/assets/images/wireframes-index-desktop.png)


[About Us Page Wireframe in Mobile View](/assets/images/wireframes-aboutus-mobile.png)

[About Us Page Wireframe in Tablet View](/assets/images/wireframes-aboutus-tablet.png)

[About Us Page Wireframe in Desktop View](/assets/images/wireframes-aboutus-desktop.png)


[Get Involved Page Wireframe in Mobile View](/assets/images/wireframes-getinvolved-mobile.png)

[Get Involved Page Wireframe in Tablet View](/assets/images/wireframes-getinvolved-tablet.png)

[Get Involved Page Wireframe in Desktop View](/assets/images/wireframes-getinvolved-desktop.png)


### Colour

![HEART HELPERS COLOUR PALETTE](/assets/images/colour-palette-final.png)

[Also available as Coolors palette](https://coolors.co/f8f9fa-e9ecef-dee2e6-ced4da-adb5bd-6c757d-495057-343a40-212529)


I have chosen the above colour palette for the Heart Helpers website for several reasons. First, I wanted to use a palette that was easy for the users to see. I did research on what colours would be the most accessible to use. The Office for National Statistics suggest three helpful rules to consider when creating accessible websites:

- “Get it right in black and white”

- “The safest hue is blue”

- “Red and green should never be seen”

Following the advice of fellow students, I decided to use [Coolors](https://coolors.co/) for my palette. I've used this particular palette out of personal choice. I'm partially colourblind myself and have always appreciated a website with an appropiate contrast. 


### Font


The font I have chosen to use for Heart Helpers is one called Poppins, which is part of the Sans Sarif family. It can be found [here](https://fonts.google.com/specimen/Poppins?preview.text=Heart%20Helpers&preview.text_type=custom). I chose the 'Light' weighting as I felt that it would look better against an off-white colour I planned to use as my background colour. 


### Images

Where did your images come from? Did ypu get permission? Did you credit them?



### Features

#### Header

My header will be comprised of the Heart Helpers logo (see above for images) that will also act as a hyperlink that will always bring the user back to the Home page. It will also contain the navigation bar which will change position depending on the user's device.


#### Footer

My footer will contain links to LinkedIn, GitHub, Facebook and Twitter. 


#### Home Page

My Home page will begin with the Next Event with a large image (see Images) and a block of text describing what the event is, with a button just below called 'Sign Up'. If clicked, the button will take the user to the Get Involved page so that they can sign up to this event. 

The next thing the desktop and tablet users will see is an image of the previous event (in this case, the Winter Wonderland Event), showcasing a team of happy volunteers. This image will not be displayed on the mobile view.

Beneath the Winter Wonderland Event image, the user will be shown a series of four written testimonies from previous volunteers. All four will be shown to users regardless of the device they are using, however the way in which they see them will differ (see Wireframes).


#### Get Involved

Get Involved will be where the user can sign up to the next event by using a form that captures (through POST) the user's name, email address and date of birth. There is also a 'Confirm Email' address and a date selection for the date of birth, although neither of them have validation assigned to it (see Future Developments).

There is also a checkbox with a 'I agree with the Terms of Service' label assigned to it. There will be no data validation assigned to this checkbox. The label will carry a hyperlink that will take the user to the Terms of Service page. 


 
 
## Future Developments

There are several improvements I would like to make to Heart Helpers in the future when my knowledge and experience are improved.




|      Page     |   Future Development Ideas  | Reason not added in this release  |
| ------------  | ------------ | ------------ |
|  Get Involved | On:Hover option that explains why DOB is required  |  Limited knowledge of Javascript |
|  Get Involved | Javascript that will idenfity if the user is under 18. If yes, refer to sign-up-on-hold page, await parental consent  | Limited knowledge of Javascript  |
|  Get Involved | Data vadlidation on Confirm Email Address | Limited knowledge of Javascript  |
|  Get Involved | Data validation on Terms of Service checkbox | Limited knowledge of Javascript  |
|  Contact Us   | Data vadlidation on Contact Us form to detect value submission (more than 0, less than 'X') |  Limited knowledge of Javascript  |
|  Contact Us   | Data validation on other input values (email address format, numerical only for telephone) | Limited knowledge of Javascript  |
|  About Us     | Interactivity on central rounded image so that when user clicks, information sections are shown | Limited knowledge of Javascript  |


### Accessibility

I have been mindful during coding to ensure that the website is as accessible friendly as possible. I have achieved this by:

- Using alternative text for all images throughout the Heart Helpers website
- Using an accessible colour palette and contracts suitable for all users
- Using an easy to access navigation bar that clearly highlights which page the user is currently viewing
- Where possible, using screen reading tools where there is no alternative text available and the user is presented with an important feature (e.g. button, icon)
- Using semantic scripts


- - -

## Technologies Used


|      Programme / feature      |   Technology used                                                               | 
| ------------------------      | -------------------                                                             | 
|  Languages                    | HTML and CSS                                                                    |
|  Framework                    | [Bootstrap version 5.3](https://getbootstrap.com/docs/5.3/)                     |
|  Colour Scheme                | [Coolors](https://coolors.co/?home/)                                            |
|  Fonts                        | [Google Fonts](https://fonts.google.com/)                                       |
|  **Images**                   |                                                                                 |
|                               |                                                                                 |
|  *Icons*                      | [Font Awesome](https://fontawesome.com/) and [Favicon](https://favicon.io/)     |
|  *Image Compression tools*    | [Tiny PNG](https://tinypng.com/)                                                |
|  *Image editing*              | [Birme](https://www.birme.net/)                                                 |
|  *Responsiveness testing*     | [Am I Responsive?](http://ami.responsivedesign.is/)                             |
|  *Other icons*                | [Shields.io](https://shields.io/)                                               |
|                               |                                                                                 |                                                                            
|  Version control              | Git                                                                             |
|  IDE / file storing           | [Gitpod](https://gitpod.io/) and [Code Anywhere](https://app.codeanywhere.com/) |
|  Wireframes                   | [Balsamiq](https://balsamiq.com/)                                               |
|  Code Validation              | [W3C Schools](https://validator.w3.org/)                                        |
|  Developer Tools              | Chrome Developer Tools                                                          |


- - -

## Deployment & Local Development

### Deployment

The Heart Helpers website was made live through GitHub. This is how to deploy Heart Helpers again:

1. Log in (or sign up) to Github.
2. Find the repository for this project, Dan-Matthews-23/heart-helpers.
3. Click on the Settings link.
4. Click on the Pages link in the left hand side navigation bar.
5. In the Source section, choose main from the drop down select branch menu. Select Root from the drop down select folder menu.
6. Click Save. Your live Github Pages site is now deployed at the URL shown.

### Local Development

#### How to Fork

To fork the Heart Helpers repository:

1. Log in (or sign up) to Github.
2. Go to the repository for this project, Dan-Matthews-23/heart-helpers.
3. Click the Fork button in the top right corner.

#### How to Clone

To clone the Heart Helpers repository:

1. Log in (or sign up) to GitHub.
2. Go to the repository for this project, Dan-Matthews-23/heart-helpers.
3. Click on the code button, select whether you would like to clone with HTTPS, SSH or GitHub CLI and copy the link shown.
4. Open the terminal in your code editor and change the current working directory to the location you want to use for the cloned directory.
5. Type 'git clone' into the terminal and then paste the link you copied in step 3. Press enter.

- - -

## Testing

The following tests were undertaken using Google Chrome, Firefox, Microsoft Edge and SAfari. I have not tested the features using Internet Explorer as support ended for this browser (on some operating systems in June 2022.


|      Page     |   Browser                 |   Feature (by ID)                 | Result                                 |
| ------------  | ------------              | ------------                      |------------                                    |
|  About Us     | Chrome                    |   email_address                   | Pass                                           |
|  Get Involved | Firefox                   |  Pass                             | Pass                                           |
|  Get Involved | Microsoft Edge            |  Fail                             | Fail                                           |
|  Get Involved | Safari                    |  Fail                             | Pass                                           |
|  Get Involved | Safari                    |  Fail                             | Fail                                           |



### Solved Bugs

|      Page     |   Feature                 | What went wrong and how you resolved it                                    |
| ------------  | ------------              | ------------                                                               |
|  Get Involved | Hover button              |  Resolved issue where submit buttom was not working                        |



### Known Bugs



### Testing User Stories

Refer back to the User Stories under First Time Visitors, Returning Visotirs and the other one. Get feedback from peers

### Full Testing

Which browsers did you test it on? Why?

Did you use developer tools? Which browser? Why?

Index.html
    Hyperlinks
    Images
    Forms
    Responsive Design    
Contact-US
    Hyperlinks
    Images
    Forms
    Responsive Design  
    
Get-InvolvedHyperlinks
    Images
    Forms
    Responsive Design  
    
- - -

## Credits
[The Office of National Statistics](https://style.ons.gov.uk/category/data-visualisation/using-colours/#accessibility-and-colours) for advice on colour palette. 


### Code Used

### Content

Content for the website was written by Dan Matthews.

### Media

#### Other Images

### Acknowledgments

Finally, I want to take the opportunity to thank and acknowledge the following for their support and patience in helping me create my first ever project:

- [Harry Dhillon](https://github.com/Harry-Leepz), who is my mentor at the Code Institute
