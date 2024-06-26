# Milestone-Project-1

https://seanbrindley17.github.io/milestone-project-1/index.html

---

## Mockup Screenshots

I used the [Am I Responsive]() website to create a mockup of how the site can look on multiple different display sizes.

![mockup screenshot from the am i responsive website](/readme-documentations/screenshots/am%20i%20responsive%20screenshot.jpg)

## UX

### Project Goal

The goal of this project is to create a static portfolio page that I can use as a base to begin to build up a proper portfolio of my work created during this diploma and beyond. I will be creating a **home** page, an **about me** page, a **projects** page and a **contact** page to satisfy the minimum 3 page requirement for this project.

My initial design was created as a series of wireframes for mobile, tablet and desktop. This was then adapted and changed upon feedback from my mentor. 

I wanted a minimalist look to the site, primarily for ease of use and also for my benefit of not needing to correct an unnecessary amount of coding mistakes. 

### User Stories 

#### First Time Visitors

* As a new site user, I would like to know what the site is about so I can understand what the purpose of the site is for.

* As a new site user, I would like to be able to locate the navigation elements to take me to the relevant page quickly and easily. 

* As a new site user, I would like to see a clear and concise website.

#### Returning Visitors 

* As a returning site visitor, I would like to be able to immediately navigate to the page which is most relevant for me.

* As a returning site visitor, I would like to see the programming languages associated with the creator if I feel like I could work with the creator.

---

## Design 

### Wireframes

Wireframes were created on [balsamiq](https://balsamiq.com/wireframes) for mobile, tablet and desktop displays.

![homepage wireframe](/readme-documentations/wireframes/homepage%20v2.png)

![about me page wireframe](/readme-documentations/wireframes/about%20me%20v3.png)

![contact me page wireframe](/readme-documentations/wireframes/contact%20v2.png)

### Colours/Background 

I wanted a metallic silvery background colour. Initially I used a gradient from (link to credit here), but after having issues with the gradient background I decided to use a background image. The image I used was downloaded from [Pixabay](https://pixabay.com/illustrations/circular-slabs-metal-iron-837510).

![background image](/assets/images/circular-837510_640.jpg)

The submit button on my contact form was adapted from the gradient code I initially used for the background to create a gold colour gradient.

```css
background: linear-gradient(
        45deg,
        #d4af37 5%,
        #debc5b 10%,
        #e7c97c 30%,
        #efd69d 50%,
        #e7c97c 70%,
        #debc5b 80%,
        #d4af37 95%
        );
```

On my about me page, I noticed that the black text could appear a little washed out against the background when written in a paragraph. To compromise, I used an opaque background:
```css
background-color: rgba (0, 0, 0, 0.5);
```
Combined with using white text, this made the paragraph much more legible.
This opaque background is also used in my contact form input fields. 

### Fonts

For my title and nav buttons I used "[Vast Shadow](https://fonts.google.com/specimen/Vast+Shadow)". The bulk of my text was written in "[Arvo](https://fonts.google.com/specimen/Arvo)", with a smaller amount of text on the home page using "[GFS Neohellenic](https://fonts.google.com/specimen/GFS+Neohellenic)". All of these fonts were sourced from google fonts.

* `#000`, - Main font colour used as this contrasted quite nicely with the background especially with larger text.

* `#fafafa` - Ssed as the font colour for the call to action button and the body content of the about me page.

* `rgba(216, 194, 194, 0.5)` - Used for the placeholder text on the contact form.

The HTML, CSS and Javascript icons on the home page were from [Font Awesome](https://fontawesome.com). 

### Technology Used

#### Coding Languages Used

* HTML - For site content.  

* CSS - For site design and layout

#### Software and Programs Used

* [VSCode](https://code.visualstudio.com/) - IDE used to create website and style.
    * [Google Fonts](https://fonts.google.com/) - Location of fonts used.
    * [Font Awesome](https://fontawesome.com/) - Location of icons used.
    * [Bootstrap](https://getbootstrap.com/) - Framework used to assist in building the site.

* [Git](https://git-scm.com/) - Version control.

* [Github](https://github.com/) - For secure code storage.

* [Github Pages](https://pages.github.com/) - To host the deployed site.

* [W3 Schools](https://www.w3schools.com/) - For extra help with remembering how to use bits of code correctly.

* [balsamiq](https://balsamiq.com/) - Used to create wireframes.

* [Snipping Tool](https://support.microsoft.com/en-us/windows/use-snipping-tool-to-capture-screenshots-00246869-1843-655f-f220-97299b865f6b) - To get relevant screenshots as required.

* [MS Paint](https://www.microsoft.com/en-us/windows/paint) - To do basic cropping, resizing and to save the screenshots from the Snipping Tool.

## Features 

### Existing Features

| Feature | Description | Screenshot |
| :---: | :---: | :---: |
| **Page Title** | The title is a link that takes the user back to the home page from any other page | ![screenshot](/readme-documentations/features/heading.jpg) |
| **Navigation** | Takes a user to each particular part of the site. Includes information about the creator, their portfolio and how to contact them. | ![screenshot](/readme-documentations/features/navbutton.jpg) |
| **Call To Action** | This button takes users to the Contact Me page. | ![screenshot](/readme-documentations/features/calltoaction.jpg) | 
| **About Me** | Contains information about the site creator. | ![screenshot](/readme-documentations/features/aboutme.jpg)|
| **Projects** | Displays projects by the creator. | ![screenshot](/readme-documentations/features/projects.jpg) |
| **Contact Form** | Allows a user to contact the creator. | ![screenshot](/readme-documentations/features/contactform.jpg) |
| **Submission Confirmation** | Shows confirmation to the user of the query being sent successfully. Also has a link back to the home page. | ![screenshot](/readme-documentations/screenshots/confirmation.jpg)
| **Footer** | Footer contains link to creator's Github profile on the the Github icon. | ![screenshot](/readme-documentations/features/footer.jpg)

### Future Features 

* When the amount of projects displayed requires it, a filter feature based on the type of project to make searching easier. 

* Potentially some more user interactivity with the learning of Javascript.

## Testing

All testing was documented on the [TESTING.md](TESTING.md) file.

## Deployment 

The site was deployed on Github Pages. 

The steps of deployment as as follows:

* Go to the Github repository for the site [here](https://github.com/seanbrindley17/milestone-project-1).
* Navigate to Settings.
* Navigate to Pages.
* From the Source dropdown, select Deploy from a branch.
* From the Branch dropdown, select main and then click on the Save button.
* A box at the top of the page will say Your site is live as shown here: 
![screenshot of deployment](/readme-documentations/screenshots/github%20pages%20deployed%20v2.jpg)

### Local Deployment

To create a local copy of the site, you can clone or fork this repository.

#### Cloning 

To clone the repository:

* Go to the Github repository for the site [here](https://github.com/seanbrindley17/milestone-project-1).
* Click on the green Code button above the files. ![screenshot of code button](/readme-documentations/screenshots/github%20code%20button.jpg)
* Select which remote repository URL you'd like to use from HTTPS, SSH or Github CLI, then click the copy url button.
* Open the Terminal in your code editor and change the current working directory to the location you want the cloned repository to go.
* In the Terminal, type git clone followed by the link you copied earlier from the repository.
* Press enter.

#### Forking 

Forking allows us to make a copy of the original repository on our Github account to view and/or edit without actually affecting the original repository.
To fork my repository for this project:

* Log into your Github account and go to the Github repository for the site [here](https://github.com/seanbrindley17/seanb.dev).
* Locate the Fork button near the top of the page and click it. ![screenshot of fork button](/readme-documentations/screenshots/github%20fork%20button%20v2.jpg)
* On the next page, you can change the name to distinguish it from the original. Once done, click Create Fork to create a copy of the repository to your Github account. 


## Credits 

### Code Used From Outside Sources

* Initially, I had a silvery gradient background that was taken from [this page](https://www.julienthibeaut.xyz/blog/creating-metallic-effect-with-css) by Julien Thibeaut. I ended up not using it as a background, but this code was adapted to style the submit button.

* To make the hover effect for the nav buttons, I used code from [hover.css (line 1247)](https://github.com/IanLunn/Hover/blob/master/css/hover.css) by Ian Lunn.

* To make the hover effect for the submit button on the Contact page I used code from [hover.css (line 2427)](https://github.com/IanLunn/Hover/blob/master/css/hover.css) by Ian Lunn.

* To make the hover effect for the icon on the button that returns the user to the home page from the submission confirmation form, I used code from [hover.css (line 3284)](https://github.com/IanLunn/Hover/blob/master/css/hover.css) by Ian Lunn.

* To style my background image and make it sit central I used code from [CSS Tricks](https://css-tricks.com/perfect-full-page-background-image/).

* To make my footer stay sat at the bottom of the page instead of having it float in the middle of pages that have less content i.e. the projects page, I used code from [30 Seconds Of Code](https://www.30secondsofcode.org/css/s/footer-at-the-bottom/).

* To centre the box that appears upon submitting a query on the contact page, I used a solution from [StackOverflow](https://stackoverflow.com/questions/356809/best-way-to-center-a-div-on-a-page-vertically-and-horizontally).