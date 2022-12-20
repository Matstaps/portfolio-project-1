# Project 1 - Raz Bakes

## Overview

A link to the live website is provided [here](https://matstaps.github.io/portfolio-project-1/).

Raz bakes is a website dedicated to showcase the bakery products of Raz Yacobi, a hobby baker. The website is intended to offer a visual representation of the various cakes and baked goods that she produces, by means of a gallery. The website provides a brief introduction of the subject's rationale and influences for baking, within the 'about me' section. This website provides information on a selection of as yet fictional baking classes in a 'baking classes' section and a means by which users can register their interest for these classes using a 'contact me' form. The footer section provides contains a fictional address, email and social links.

This website intends to allow the subject a means to showcase their future bakes, and provide a potential should they wish to expand their baking activities in the future by giving classes or adding a social media presence. 

This site was written using HTML and CSS. Additional text styling was provided using [Google Fonts](https://fonts.google.com/about) and [Font Awesome](https://fontawesome.com/).

![amiresponsive image](readme_images/amiresponsiveimage1.png)

## User Experience

### User Stories
 
* First Time users
            
    * To inform users of the bakers rationale and products
    * To be able to easily navigate the page and find the relavant sections simply
    * To easily see a selection of products            
    * To easily find contact details of the subject
            
* Returning users
    
    * To gain further interest in baking through the products highlighted
    * To be informed of further baking classes on offer
    
* Frequent users
    
    * To be regularly updated on new products and classes offered
            
## Features

### Existing Features

### Navigation

* The navigation bar sits within the header on the top-right of the page, alongside the Website name to the left.
* The 'Raz Bakes' Logo sits to the left. It is designed to immediately inform the user of the page's name.
* The navigation links; 'Home', 'About me', 'My Bakes', 'Class Times' and 'Contact Me' all link to the respective sections of the same page.
* The navigation font is consitent with the website, and the colour palette contrasts with the background colour.
* This section is responsive, the navigation bar moves below the logo and stacks vertically upon smaller viewports.


![Navigation bar image](readme_images/navbarimage1.jpg)

### Hero Image

* The hero image displays three background images of the subject's baking.
* The images are intended to immediately highlight a suggestion of the products offered for the user.
* The images contain baked products and highlight their natural colours and textures. The images' content sets the thematic tone of the website, and the colour palette therein visually compliments the website's aesthetic and colour palette.


![Hero image image](readme_images/heroimageimage.jpg)

### About Me

* The about me section introduces the subject's reasons for baking, baking background, and expresses their wish to teach others who are interested in baking. 
* It contains a background image of an example of a baked bread to compliment the aesthetic of this webpage.
* This section is presented in three columns, with text to the left and right, and an image in the centre. It is responsive, with the columns stacking upon each other on smaller screens.


![About me image](readme_images/aboutmeimage1.jpg)

### A Selection of my bakes

* This section presents a gallery which shows a selection of images of the subject's baking.
* It is intended to inform the user of the variety of bakes produced by the subject, giving the user an idea of the products they could learn to bake.
* The section is responsive, moving from four, to two, to a single column as the viewport reduces.


![Gallery of bakes image](readme_images/gallerygrab1.jpg)

### Baking Classes

* This section informs users of the baking classes offered by the subject.
* It provides information on the themes that each class focusses on, and the days of the month that these classes are delivered on.
* The section features three classes, each display white text on a background from the colour palette, so as to be easily readable.
* This section is responsive, the boxes stack upon each other on smaller viewports.


![Baking class information image](readme_images/classesscreengrab1.jpg)

### Contact Me

* This section allows users to register their interest in the classes offered using an HTML form.
* The user is required to provide their first name, last name, email address, and specify which baking class they are interested in.
* The form contains white text and input boxes on a background colour from the colour palette so as to be easily readable.
* The form has been tested to submit correctly.


![Contact form image](readme_images/contactformscreengrab.jpg)

### Footer

* This section provides contact information for the subject.
* It features an address, an email and social media links.
* Each of the social media icons and email address are target linked. (NB: the email presented does not currently exist, nor do the social media icons link to active accounts, but act as placeholders for furure links).
* The section places white text upon a background colour from the colour palette so as to be easily readable. The icons for social media are sourced from Font Awesome.

![Footer image](readme_images/footerscreengrab.jpg)

### Supporting the user experience

* The features intend to satisfy the aims mentioeds in the user stories. This single page site is designed to be easily navigable, with links to each section. It is clearly themed with a consitent design throughout the page, and the textual elements are concise.

### Potential Future Features

#### Embedded video content

* A future section could be added to the website to embed short video elements to highlight baking techniques.

#### Recipe section

* A future section could be added to showcase recipes and provide users with a walkthrough on baking.

## Design

### Website Style

* A single page format was chosen to this website, the intention being that it is easy for the user to navigate to each section or to scroll through the page.

### Imagery

* All images used are those of the subject's baking. The images intend to provide a broad selection of the subject's baking styles. The images are considered key to this website as they visually convey the subject's products. These images are largely beiges and browns in appearance.

### Colour Scheme

* The colour scheme is intended to be easily seen by the user and provide clear text. The scheme chosen was informed the colour tones of the images. The brown/orange colour palette is intended to be sympathetic to the image colours. The background is white so as to allow the sections to stand out.

### Typography

* The Roboto and Lato fonts were imported from Google Font. They are intended to present the website text with a simple, clean and modern feel. These two fonts compliment one another well.

## Technologies used

### Languages

* HTML5
* CSS3


### Further Technologies

* Fonts were imported using Google Fonts.
* Icons were imported from Font Awesome.
* The code was written on Gitpod workspace, to commit and push to Github.
* Github was used as a repository for the code once pushed from Gitpod.


## Testing

### Browser Testing

* I tested this site in different browsers: Chrome, Edge and Safari.
* I confirmed that this website was responsive across different devices using the Google Chrome devtools device toolbar.
* I confirm that the sections, navigation, hero image, About me, A Selection of my bakes, baking classes, contact and footer are readable, understandable and responsive.
* I performed some manual testing on various devices, including Windows Desktop, iPhone SE, iPad

#### Nav Bar Testing

* I confirmed that each link; Home, About Me, My Bakes, Class Times, and Contact me, correctly link to the relevant sections.

#### Contact Me Testing

* I confirmed that the form element works correctly. With all input fields and radio button completed it will submit correctly. If any of inputs is blank, it provides a prompt to complete missing information before submission is allowed.
* The Submit button hover cursor worked correctly.


#### Footer Testing

* I confirmed that the Facebook and Instagram icons correctly link to their respective social media sites.
* I confirmed the the linked email correctly links to a new mail link.</li>


### Bugs

* I can confirm that no bugs were detected upon deployment.

### Validator Testing

* HTML 

Upon validation using [W3C HTML Validation Service](https://validator.w3.org/#validate_by_input), a warning advised that the hero-image was missing a header. This was resolved by adding a header and setting the CSS to display:none. Repeating the validation then confirmed there were no errors.

![W3C HTML Validation results](readme_images/htmlvalidator.jpg)

* CSS

No errors were found when passing through the [Jigsaw CSS Validation Service](https://jigsaw.w3.org/css-validator/#validate_by_input).

![Jigsaw CSS Validation results](readme_images/cssvalidator.jpg)

* Accessibility

The colour scheme chosen was passed through the [Color Tool](https://m2.material.io/resources/color/#!/?view.left=1&view.right=0&primary.color=E65100&secondary.color=FFEB3B) website to check the color palette against accessibility.
I confirmed that color and fonts are accessible and easy to read by passing the website through Lighthouse in devtools.

*Lighthouse desktop results:

![Lighthouse desktop results](readme_images/lighthousedesktop.jpg)

*Lighthouse mobile results: 

![Lighthouse mobile results](readme_images/lighthousemobile.jpg)

## Deployment

The site was deployed to Github, the steps as follows: 

1. In the github repository, navigate to the settings tab and choose Pages
2. From the Source section drop-down, select Master Branch and save
3. Once the page then refreshes, a link is provided to the live website
4. Further changes pushed to the main branch will update the live site


## Credits

### Content

Stylings of the Navigation Bar and About Me section were informed by CSS stylings used within the  [Love Running](https://code-institute-org.github.io/love-running-2.0/index.html) website.
Icons were sourced from the [Font Awesome](https://fontawesome.com/) website.
General HTML and CSS coding techniques were learned from the [Code Institute](https://codeinstitute.net/) tutorials and the [W3 Schools](https://www.w3schools.com/) website.

### Media

All images were provided by the subject.

### Acknowledgements

* Thank you to my mentor Akshat Garg for help and direction to useful resources.
* Thank you to the tutors and staff at Code Institute for continued support.


