# VinVivant

**Table of contents:**

 - [Introduction](#introduction)
 - [Deployed Site](#deployed-site)
 - [VinVivant Features](#vinvivant-features)
   - [Landing Page](#landing-page)
   - [Blog](#blog)
   - [Contact Us](#contact-us)
   - [Newsletter Sign Up](#newsletter-sign-up)
 - [User Experience](#user-experience)
    - [User Goals](#user-goals)
    - [User Stories](#user-stories)
    - [Design](#design)
    - [Wireframes](#wireframes)
 - [Technologies Used](#technologies-used)
 - [Acknowledgements](#acknowledgements)


<a id=#introduction></a>

## Introduction

VinVivant is a blog about natural wine featuring natural wine reviews, with the option for the user to sign up to a newsletter to receive blog posts via email, and a contact form to enter their contact details and send a message.

It is primarily targeted at those with an interest in wine and natural winemaking, but the informative nature of the site will make it ideal for those without prior knowledge to learn more, with the potential to add blog posts about different grape varietals, winemaking regions, terminology, and styles.

![VinVivant responsiveness mockup](/assets/READMEcontent/ui-responsiveness2.png)

<a id=#deployed-site></a>

## Deployed Site
VinVivant can be accessed [here](https://klchambers.github.io/VinVivant/).

<a id=#vinvivant-features></a>

## VinVivant Features

<a id=#landing-page></a>

### Landing Page

The landing page features a hero image, with image links below this inviting the user to visit the VinVivant Blog and the Newsletter Sign Up sections of the website.

![Landing Page Screenshot](/assets/READMEcontent/landingpage.png)
![Bottom of Landing Page Screenshot](/assets/READMEcontent/landingpagebottom.png)
![Landing Page mobile Screenshot](/assets/READMEcontent/landingpagemobile.png)
Content is partially hidden from the user, to indicate that there is more information below the hero image, and to invite them to scroll down further.

<a id=#blog></a>

### Blog

VinVivant/blog.html displays blog posts in a column on mobile devices, and rows/columns increasing as the screen size gets larger.

![Blog section screenshot](/assets/READMEcontent/blogscreenshot.png)

HTML image elements are clickable links, with take the user to the corresponding page for that blog post.

![Blog post example screenshot](/assets/READMEcontent/blogpostscreenshot.png)

<a id=#contact-us></a>

### Contact Us

<a id=#newsletter-sign-up></a>

### Newsletter Sign Up

<a id=#user-experience>

## User Experience

<a id=#usergoals></a>

### User Goals

* The site should be laid out well and visually appealing
* The site should be structured in a logical manner, with layout and style remaining consistent throughout pages and elements in places where I expect to find them, making navigation simple and intuitive
* Content should be of good quality

<a id=#userstories></a>

### User Stories

* I would like to find high quality content
* I would like this content to be displayed properly, regardless of the device, software, or assistive technology I use to access it
* I would like to be able to use the site, links, and form elements easily with everything working as I exxpect when I click or interact with it
* I would like the site to be informative and for this information to be easy and enjoyable to access

### Site Structure

From the homepage (/index.html), the user can visit the following three pages: blog.html, contactus.html, and signup.html.

The navigation bar holds links to the three aforementioned pages, and collapses down into a hamburger icon on smaller screens to optimise the layout with less screen space.

Clicking the VinVivant logo in the top left, from any page, will take the user back to the home page.

<a id=#design></a>

### Design

#### Colour

The user interface of VinVivant is primarily white and black for legibility and simplicity. In the footer and accents, a muted green (rgba(71, 108, 70) is used. This colour and shade were chosen as green... "provokes feelings of wealth and tradition (particularly darker hues), while on the other it’s strongly associated with environmentalism and nature.", according to [this](https://www.toptal.com/designers/ux/color-in-ux) article by [toptal.com](https://www.toptal.com) about the role of colours in UX design. The intention of this was to draw connotations and parallels between the pages with the environmental focus and ancient traditions of most natural winemakers.

Background images are overlaid with the same muted green (rgba(71, 108, 70, 0.8), with a colour of 'antique white' to maintain legibility of the text over the image, with the opacity of the text box set to 0.8 to allow the user to see the background image.

#### Typography

[Google Fonts](https://fonts.google.com/) was used to import custom fonts into the CSS.

For headings, ['Playfair Display'](https://fonts.google.com/specimen/Playfair+Display?query=playfair) was selected. This neutral serif font is readable, particularly in higher font weights, across all screen sizes and the serif features of it evoke a trustworthy and reputable feeling to the user.

In body text, the sans-serif typeface ['Assistant'](https://fonts.google.com/specimen/Assistant?query=assistant) was used for legibility and adaptability across different font weights and screen sizes.

### Wireframes

During the inception of this project, Balsamiq wireframes was used to create mockups of the responsiveness I wanted to create across device types.

#### [index.html mobile mockup](/assets/READMEcontent/wireframe1.png)
#### [index.html tablet mockup](/assets/READMEcontent/wireframe4.png)
#### [index.html browser mockup](/assets/READMEcontent/wireframe5.png)

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

[Assistant]() typeface designed by Ben Nathan & Adobe Systems Inc.

Code used to create the class "nav-toggle" was adapted from Code Institute's "[Love Running](https://github.com/Code-Institute-Solutions/love-running-v3)" project.