![OH_header](https://64.media.tumblr.com/a9932fd5e5508fce2c67b5b4d133583c/ededd5d66eb91b7b-e5/s1280x1920/b930aed5e286f3903788ad4334c44c9581191655.jpg)
# MP-1 Olivia Hird Professional Portfolio

This project will endeavour to present and reflect the work, ethos and acumen of Olivia Hird, a filmmaker, production manager, researcher, cameraperson and writer for documentary film and festivals. 
This website will provide a platform for her to demonstrate previous and current work in a style that reflects her methodologies and aesthetic inclination.
This in turn will enable Olivia to direct prospective employers towards her work and allow those she works with a comprehensive frame of reference.

* It will include:
    * examples of previous work in video, image and essay formats
    * statement of intent and interests
    * details on her previous experience
    * social links
    * contact details

* It will serve to: 
    * direct traffic to articles already hosted around the web and articles not yet hosted elsewhere
    * showcase directorial and editorial capability within production and the edit respectively
    * detail organisational strengths accrued through festival work

## Demo
_______

Deployed here - https://charliehawley.github.io/MP1-OH/

Repository here - https://github.com/charliehawley/MP1-OH

### Wireframes

![Index wireframe](https://i.imgur.com/dk1WVoC.jpg)

![About wireframe](https://i.imgur.com/4Aj6BKf.jpg)

![Portfolio wireframe](https://i.imgur.com/Oq5I2cY.jpg)

![Writing wireframe](https://i.imgur.com/onIDxyy.jpg)

### Reactive demo

![Reactive capabilities evidenced here](https://i.imgur.com/zxu8Olb.jpg)

## UX
___

#### User stories

- As the producer of a film festival, I wish to gain an understanding of Olivia's past experience and potential in order to properly consider her for the role of production manager/programmer/preselector.

- As the producer of a film festival, I would like to verify whether Olivia's previous film reviews and essays are of the correct standard to grant Olivia a press pass to our festival.

- As a producer for a feature documentary, I would like to see a list of Olivia's previous experience in order to consider her for a role as researcher on my upcoming project.

- As a documentary filmmaker, I would like to see examples of Olivia's previous work to better understand her aesthetic and compositional strength in camera work.

- As the editor of an online film journal, I would like to verify that Olivia's writing is of the correct standard and quality to grant her request to write for us.
___
### Strategy

The fundamental goal of this website is to make Olivia's details available and her experience apparent as well as showcasing her acumen and drive as an individual through her personal work.
___
### Scope

The minimum viable product for this project necessitates:

- embedded videos (hosted remotely) which populate a portfolio

- contact details and a form to further facilitate correspondence

- links to essays and reviews (hosted remotely and locally) as well as links to social profiles

Animations are implemented on the Writing cards that show excerpts of the written work on hover.

#### Future features

I would also like to add a feature to allow users to switch between Factual and Personal work channels on the landing page video but this.
___
### Structure

Each webpage features a navigation bar fixed to the left, a header fixed to the top and a footer, also fixed to the bottom to create a windowed effect and standardize the experience across all facets of the site. 

___
### Skeleton

The user can navigate between four pages:
- a landing page (Home) 
- an About page with contact details and a form 
- a Portfolio page with a video and short description for each project
- a Writing page which will contain links to reviews and essays

All pages can always be accessed from the fixed nav bar.

Most common paths:
- Home > About > Portfolio
- Home > About > Writing
- Home > Socials

Contact details are included on every page so that a user never needs to interrupt the content they might be watching/reading to open a correspondence.

___
### Surface

The site employs a minimal windowed layout where many elements employ shadows to give the impression of 'floating' just off the background. 

The video on the Index page, the form on the About page and the iframes on the Portfolio page in particular, are formatted with a box shadow arrangement that characterises Neumorphism which nurtures a sense of style within minimalism (links to articles used to inform the use of Neumorphism in [Credits](#credits) below).

All anchor elements on the website (with the exception of the logo) react to mouse hover to demonstrate their interactivity and encourage engagement. 
- All nav elements italicize on hover as do links to production house sites and imdb profiles. 
- All review/writing cards transform through the y axis on hover. 
- All social icons gain a drop shadow on hover.

___
## Technologies Included

- HTML
- CSS
- Google Fonts
- Adobe Fonts
- Youtube embed
- Vimeo embed
___
## Testing

The W3C Markup Validator tool and W3C CSS Validation Service were both used to test the validity of all html and css files in the project. All files passed with no errors found.

The Web AIM Contrast Checker tool was used to develop the colour scheme for the website and helped to ensure that all text, graphics and objects passed a contrast check.

All links in the website were manually tested to ensure they opened the correct desination and those that led to external sources opened in a new tab using the target="_blank" attribute.

The form includes three required fields and will not submit without correctly formatted inputs.

An email field is included which will fail if the input is not correctly formatted.

All successful form submissions were tested using https://formdump.codeinstitute.net/ and all fields were recorded with accurate name attributes.

The site was tested across many responsive scenarios using Google's dev tools (F12) and performed well in the following emulated environments:

- iPhone X
- iPhone 6/7/8
- iPhone 5/SE
- iPad
- 3200 x 1700
- 1920 x 1080
___
## Deployment

The site was created using a versioning system integrated with GitHub via Gitpod.

The site is hosted on GitHub pages at the link above and will adapt whenever changes are made to the main branch.

You can run this respository locally by running ```git clone https://github.com/charliehawley/MP1-OH.git``` in your terminal.

___
## Known Bugs

> BUG - nav bar appeared with no background revealing content scrolled behind.

FIX - background color applied to element

> BUG - on screens wider than 1700px, Early Morning, Early March iframe at the bottom of the Portfolio.html is partially obscured by footer.

> BUG - on iPad mini and iPad pro, the body is wider than the viewport. Have combed for an element or margin wider than the viewport to no avail.

> BUG - site does not adjust well to resolutions above 4K.
___
## Credits

### Content

All copy for the About page was written by Olivia Hird.

All reviews and essays referenced on the writing page were written by Olivia Hird.

### Media

The video and image on the landing page (index.html) were created by Olivia Hird.

All content on the Portfolio and Writing pages is intended for educational use and as such falls under fair use policy. All creators, producers and directors are credited and referenced appropriately.

### Acknowledgements

Neumorphism article - https://uxdesign.cc/neumorphism-in-user-interfaces-b47cef3bf3a6

and generator - https://neumorphism.io/

I consulted W3 Schools, MDN and Stack Overflow many times during the course of this project to inform the creation of cards, fixed elements, media queries and positional arguments/attributes.

### Note
Should switch hosting from cpanel to hostinger for value