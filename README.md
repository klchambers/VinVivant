# VinVivant

**Table of contents:**

 - [Introduction](#introduction)
 - [Deployed Site](#deployed-site)
  - [User Experience](#user-experience)
    - [User Goals](#user-goals)
    - [User Stories](#user-stories)
    - [Site Structure](#site-structure)
    - [Design](#design)
    - [Wireframes](#wireframes)
 - [VinVivant Features](#vinvivant-features)
   - [Landing Page](#landing-page)
   - [Blog](#blog)
   - [Contact Us](#contact-us)
   - [Newsletter Sign Up](#newsletter-sign-up)
 - [Testing and Validation](#testing-and-validation)
    - [Testing Methodology](#testing-methodology)
    - [Testing](#testing)
    - [Jigsaw CSS Validator](#jigsaw-css-validator)
    - [W3C HTML Validator](#w3c-html-validator)
    - [Lighthouse Accessibility & Performance](#lighthouse-accessibility-&-performance)
 - [Development and Deployment](#development-and-deployment)
    - [Development](#development)
    - [Contributing to VinVivant](#contributing-to-vinvivant)
    - [Deployment](#deployment)
 - [Technologies Used](#technologies-used)
 - [Acknowledgements](#acknowledgements)


<a id=#introduction></a>

## Introduction

VinVivant is a blog about natural wine featuring natural wine reviews, with the option for the user to sign up to a newsletter to receive blog posts via email, and a contact form to enter their contact details and send a message.

It is primarily targeted at those with an interest in wine and natural winemaking, but the informative nature of the site will make it ideal for those without prior knowledge to learn more, with the potential to add blog posts about different grape varietals, winemaking regions, terminology, and styles.

![VinVivant responsiveness mockup](/assets/docs/ui-responsiveness.png)

<a id=#deployed-site></a>

## Deployed Site
VinVivant can be accessed [here](https://klchambers.github.io/VinVivant/).

<a id=#user-experience>

## User Experience

<a id=#user-goals></a>

### User Goals

* The site should be laid out well and visually appealing
* The site should be structured in a logical manner, with layout and style remaining consistent throughout pages and elements in places where I expect to find them, making navigation simple and intuitive
* Content should be of good quality

<a id=#user-stories></a>

### User Stories

* I would like to find high quality content
* I would like this content to be displayed properly, regardless of the device, software, or assistive technology I use to access it
* I would like to be able to use the site, links, and form elements easily with everything working as I exxpect when I click or interact with it
* I would like the site to be informative and for this information to be easy and enjoyable to access

<a id=#site-structure></a>

### Site Structure

From the homepage (/index.html), the user can visit the following three pages: blog.html, contactus.html, and signup.html.

The navigation bar holds links to the three aforementioned pages, and collapses down into a hamburger icon on smaller screens to optimise the layout with less screen space.

Clicking the VinVivant logo in the top left, from any page, will take the user back to the home page.

<a id=#design></a>

### Design

#### Colour

The user interface of VinVivant is primarily white and black for legibility and simplicity. In the footer and accents, a muted green (`rgb(71, 108, 70)`, or Hex `#476c46`) (https://placehold.co/15/476c46/png) is used. This colour and shade were chosen as green... "provokes feelings of wealth and tradition (particularly darker hues), while on the other it’s strongly associated with environmentalism and nature.", according to [this](https://www.toptal.com/designers/ux/color-in-ux) article by [toptal.com](https://www.toptal.com) about the role of colours in UX design. The intention of this was to draw connotations and parallels between the pages with the environmental focus and ancient traditions of many natural winemakers.

Background images are overlaid with the same muted green (rgba(71, 108, 70, 0.8), with a colour of 'antique white' to maintain legibility of the text over the image, with the opacity of the text box set to 0.8 to allow the user to see the background image.

#### Typography

[Google Fonts](https://fonts.google.com/) was used to import custom fonts into the CSS.

For headings, ['Playfair Display'](https://fonts.google.com/specimen/Playfair+Display?query=playfair) was selected. This neutral serif font is readable, particularly in higher font weights, across all screen sizes and the serif features of it evoke a trustworthy and reputable feeling to the user.

In body text, the sans-serif typeface ['Assistant'](https://fonts.google.com/specimen/Assistant?query=assistant) was used for legibility and adaptability across different font weights and screen sizes.

### Wireframes

During the inception of this project, Balsamiq Wireframes was used to create mockups of the responsiveness I wanted to create across device types.

#### [index.html mobile mockup](/assets/docs/wireframe1.png)
#### [index.html tablet mockup](/assets/docs/wireframe4.png)
#### [index.html browser mockup](/assets/docs/wireframe5.png)

<a id=#vinvivant-features></a>

## VinVivant Features

<a id=#landing-page></a>

### Landing Page

![Landing Page responsiveness screenshot](/assets/docs/landing-page-responsiveness.png)

The landing page features a hero image, with image links below this inviting the user to visit the VinVivant Blog and the Newsletter Sign Up sections of the website.

![Landing Page Screenshot](/assets/docs/landingpage.png)

Content is partially hidden from the user, to indicate that there is more information below the hero image, and to invite them to scroll down further.

![Bottom of Landing Page Screenshot](/assets/docs/landingpagebottom.png)

<a id=#blog></a>

### Blog

VinVivant/blog.html displays blog posts in a column on mobile devices, and rows/columns increasing as the screen size gets larger.

![Blog section screenshot](/assets/docs/blogscreenshot.png)

HTML image elements are clickable links, with take the user to the corresponding page for that blog post.

![Blog post example screenshot](/assets/docs/blogpostscreenshot.png)

<a id=#contact-us></a>

### Contact Us

![Screen cap of contactus.html](/assets/docs/contact-form-screencap.png)

From the Contact Us page, the user can fill out a contact form, which requires every field to be filled before it can be submitted. Data is validated, and the user is prompted to check that the form has been filled correctly if needed. The form action is linked to the Code Institute's Formdump link to verify when data is correctly submitted.

<a id=#newsletter-sign-up></a>

### Newsletter Sign Up

On the sign up page is a form for the user to fill out their details and set preferences regarding their newsletter subscription. Text fields are required and the user is prompted to check the data they have entered if it does not meet the requirements.

![Newsletter Sign Up page screenshot](/assets/docs/signup-screeencap.png)

At present, the submit button takes the user to ./thankyou.html, the data is not submitted anywhere yet but this can be implemented in future.

![Screencap of Newsletter Signup](/assets/docs/signupformcomplete-screenshot.png)

<a id=#testing-and-validation></a>

## Testing and Validation

<a id=#testing-methodology></a>

### Testing Methodology

When testing, the following outcomes should be met:
* Content displays properly on all device screeen sizes in both portrait and landscape orientation by checking on different devices, or using Responsive Design Mode in your browser's Developer Tools.

* Appropriate breakpoints are set, and creates responsiveness of all pages across device types, by checking media queries in CSS or using the CSS Breakpoints selector in Google Chrome's Developer Tools.

* All internal and external links direct the user to the expected destination, with external links opening in a new tab when clicked.

* HTML returns no errors or warnings when checked through the [W3C HTML Validation Service](https://validator.w3.org/).

* CSS returns no errors or warnings when checked through the [W3C Jigsaw CSS Validation Service](https://jigsaw.w3.org/css-validator/).

<a id=#testing></a>

### Testing

A number of tests have been carried out to ensure that the site works as intended. These tests include:
* Checking all internal and external links to ensure that they lead the user to the expected page or site.
* Checking that all images and content display correctly across screen sizes and orientations, without being distorted or obscured.
* Testing that form validation is in place, and submissionbutton inputs work as expected.
* Testing filepaths and ensuring CSS selectors target the expected element, class, or ID.

<a id=#jigsaw-css-validator></a>

### Jigsaw CSS Validator

The Jigsaw CSS validator was used and returned no errors or warnings. The Jigsaw validator results can be viewed [here](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fklchambers.github.io%2FVinVivant%2F&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en#css).

<a id=#w3c-html-validator></a>

### W3C HTML Validator

All page URLs were entered into the W3C HTML Validator and returned no errors or warnings. Results listed below:
* [Homepage HTML validator results](https://validator.w3.org/nu/?doc=https%3A%2F%2Fklchambers.github.io%2FVinVivant%2F)

* [Blog page HTML validator results](https://validator.w3.org/nu/?doc=https%3A%2F%2Fklchambers.github.io%2FVinVivant%2Fblog.html)

* [Blog post 1 HTML validator results](https://validator.w3.org/nu/?doc=https%3A%2F%2Fklchambers.github.io%2FVinVivant%2Fblogpost1.html)

* [Blog post 2 HTML validator results](https://validator.w3.org/nu/?doc=https%3A%2F%2Fklchambers.github.io%2FVinVivant%2Fblogpost2.html)

* [Blog post 3 HTML validator results](https://validator.w3.org/nu/?doc=https%3A%2F%2Fklchambers.github.io%2FVinVivant%2Fblogpost3.html)

* [Blog post 4 HTML validator results](https://validator.w3.org/nu/?doc=https%3A%2F%2Fklchambers.github.io%2FVinVivant%2Fblogpost4.html)

* [Contact Us HTML validator results](https://validator.w3.org/nu/?doc=https%3A%2F%2Fklchambers.github.io%2FVinVivant%2Fcontactus.html)
* [Signup page HTML validator results](https://validator.w3.org/nu/?doc=https%3A%2F%2Fklchambers.github.io%2FVinVivant%2Fsignup.html)
* [thankyou.html HTML validator results](https://validator.w3.org/nu/?doc=https%3A%2F%2Fklchambers.github.io%2FVinVivant%2Fthankyou.html%3Fsignupname%3D1%26signupemail%3D1%2540e.com%26freqpref%3Dmonthly%26news%3Don)

<a id=#lighthouse-accessibility-&-performance></a>

### Lighthouse Accessibility & Performance

![Lighthouse Report Summary](/assets/docs/lighthouse-report.png)

VinVivant performed well across the Lighthouse test. The full report summary can be viewed [here](/assets/docs/lighthouse-report.pdf).

<a id=#development-and-deployment></a>

## Development and Deployment

<a id=#development></a>

### Development

Development was started by cloning Code Institute's project template (available [here](https://github.com/Code-Institute-Org/ci-full-template)), and HTML and CSS was written in VSCode with changes pushed to GitHub.

<a id=#contributing-to-vinvivant></a>

### Contributing to VinVivant

To contribute, make a pull request from the [project repository](https://github.com/klchambers/VinVivant). When merged, any changes will automatically be reflected in the live deployment on Github Pages.

<a id=#Deployment></a>

### Deployment

VinVivant has been deployed to GitHub Pages, a cloud-based hosting platform.

In order to deploy a cloned copy or fork of the project to GitHub Pages, follow the steps below:
1. From the GitHub repository, select '**Settings**'
2. In the left-hand menu, under the 'Code and automation' section, select '**Pages**'
3. Ensure *Sources* is set to '**Deploy from a branch**', and that *Branch* is set to '**Main**'
4. Click **Save**, the repository will now be available at https://*yourGitHubusername*.github.io/*yourprojectname*/ (for example: https://klchambers.github.io/VinVivant/)

<a id=#technologies-used></a>

## Technologies Used

* VSCode: Writing and editing HTML and CSS files
* GitHub: Source control
* GitHub Pages: Live deployment of site
* Balsamiq Wireframes: Creating initial webpage layout mockups during project inception

<a id=#acknowledgements></a>

## Acknowledgements

Blog image photos by Stephanie Martínez.

Blog text in blogpost1.html by Len Ahern.

Blog text in blogpost3.html by Le Caveau Wine Merchants, Kilkenny.

Hero image photo by [Johny Goerend](https://unsplash.com/@johnygoerend?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash) on [Unsplash](https://unsplash.com/photos/green-grass-field-during-daytime-pnigODapPek?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash).

Blog photo by [Polina Tankilevitch](https://www.pexels.com/photo/spilled-red-wine-from-a-glass-4110404/).

Contact Us background image by [Max Tutak](https://unsplash.com/@maxtutakphotography?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash) on [Unsplash](https://unsplash.com/photos/red-wine-in-clear-wine-glass--NOXMXHchEo?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash).

Background photo for signup.html by [Jep Gambardella](https://www.pexels.com/photo/hands-toasting-wine-glasses-with-red-wine-5086617/).
  

Favicons created using [favicon.io](https://favicon.io/).

Icon fonts from [Font Awesome](https://fontawesome.com/).

Fonts imported into style.css from [Google Fonts]().

[Playfair Display](https://fonts.google.com/specimen/Playfair+Display?query=playfair) typeface designed by Claus Eggers Sørensen.

[Assistant](https://fonts.google.com/specimen/Assistant) typeface designed by Ben Nathan & Adobe Systems Inc.

Code used to create the class "nav-toggle" was adapted from Code Institute's "[Love Running](https://github.com/Code-Institute-Solutions/love-running-v3)" project.