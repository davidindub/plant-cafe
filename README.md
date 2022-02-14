# Plant Cafe

<img alt="The project displayed on a phone, tablet, laptop and desktop computer." src="https://user-images.githubusercontent.com/69420622/153647576-32cab957-ec42-4734-901e-5e8ecb1dcc6a.jpg">
![alt-text](url)


The project is to make a simple website for a Cafe and Houseplant Shop in Dublin City.

The shop serves specialty coffee and plant-based food, sells houseplants in store and frequently hosts events about growing plants.

The plants are not sold online, but the website will include some tips on keeping houseplants, as well as a signup form for a newsletter on upcoming events.

The main target of the website are people looking for quick information such as the food & drinks menu, or the location and opening hours of the shop and it is expected most of these visitors will be checking the website quickly on a mobile device. Delivering this information quickly and clearly is the main aim of the project, and the language used is friendly and welcoming.


## User Stories

- As a tourist, I want to find out when the café is open, and if it has WiFi and where it is so I can visit and use my laptop.

- As a plant enthusiast, I want to find out about upcoming events.

- As a vegan, I want to find out if there is many options for me to eat at the cafe so I can meet my friend for lunch.

- As a wheelchair user, I want to find out if the cafe has accessible facilities so I can plan my visit.

- As a parent, I want to know if the cafe is child friendly so I can bring my baby with me to meet a friend for coffee.

## UX  
  I wanted the project to look soft and earthy. I knew I wanted to use green to fit the theme of plants, and I found gorgeous soft-focus photographs on Unsplash that achieved this feeling.

### Colour Scheme
  ![Color palette used in the project](documentation/images/colors.png)

  I was inspired by [Tanim Khan](https://dribbble.com/shots/14147142-Plant-Shop-Landing-Page)'s mockup for a cactus shop on Dribble for the color scheme of dark green and light grey, I used ColorSlurp to find the colors in the image.

### Typography (explain any fonts and icon libraries used, like font-awesome and google fonts)

### Wireframes
  I sketched my wireframes on paper and on an iPad using Concepts.

  ![](documentation/images/wireframes/wireframe-initial-sketch.jpg)
  ![](documentation/images/wireframes/wireframe-menu-desktop.jpg)
  ![](documentation/images/wireframes/wireframe-menu-mobile.jpg)

## Features 

In this section, you should go over the different parts of your project, and describe each in a sentence or so. You will need to explain what value each of the features provides for the user, focusing on who this website is for, what it is that they want to achieve and how your project is the best way to help them achieve these things.

### Existing Features

- __Navigation Bar__

![Navigation Bar listing Home, Menu, Find Us and Events.](documentation/images/screenshots/screenshot-navbar.png)


  - All pages feature the same responsive navigation bar with links to the Landing Page, Food Menu, Location & Contact Form, and Events page. This allows the user to easily navigate the site.

  - The page the user is currently on is marked with a subtle underline to aide navigation.

  - This section will allow the user to easily navigate from page to page across all devices without having to revert back to the previous page via the ‘back’ button. 


- __The landing page image__

![Screenshot of homepage featuring a photo of Iced Coffee being prepared surrounded by plants.](documentation/images/screenshots/screenshot-hero-image.png)


  - The landing page features a large eye catching photograph with text overlayed, and a button which when clicked scrolls the page down to the most important information the users might be looking for.
  The text adapts so that the image does not get obscured different screens sizes.


- __Cards on Landing Page__

![Screenshot of the project's landing page cards.](documentation/images/screenshots/screenshot-cards.png)

  - Three cards with related photographs describe the three pages of the website where the user might like to visit.
  - Clicking anywhere on each of these cards takes the user to the associated page, making the links easy to tap on mobile. There is a subtle underline and color change on hover/focus.

- __The Footer__ 

<img width="397" alt="Screenshot of the project's footer on a mobile" src="https://user-images.githubusercontent.com/69420622/153711362-c6a1c47a-e7d1-4d67-b517-fc5ab8dde351.png">
<img width="1338" alt="Screenshot of the project's footer on a computer screen" src="https://user-images.githubusercontent.com/69420622/153732545-24a02860-c6a0-410b-89a3-def40e6d1628.png">

![Screenshot of the project's footer on a mobile.](documentation/images/screenshots/screenshot-footer-mobile.png)
![Screenshot of the project's footer on a computer screen.](documentation/images/screenshots/screenshot-footer-desktop.png)

  - The footer section includes the physical address and email address of the cafe, navigation links to the other pages of the website, and links to the cafe's social media accounts (all open in a new tab so as not to end the users visit to the Plant Cafe site)
  - The footer is responsive, the three sections and the nav links stack on mobile view, but use the extra available space on larger screens.

- __Menu__

  - The Menu page provides the user with the list of Food and Drink options and prices available at the cafe along side images of some of the dishes.

- __Find Us__

  - This page provides information about the facilities of the cafe, the address, an embedded Google Map of the location, and a form to to contact the cafe.

- __Events__

  - This page lists upcoming events happening at the cafe, and provides a form for a newsletter for users to find out about future events.


### Features Left to Implement

- The contact us form and newsletter signup currently don't submit to a server, but to a static page thanking the user for their submission.
- The project could be built out further to include a page of Plants for sale, or even an online shop selling houseplants and coffee.

## Technologies Used

- [HTML](https://en.wikipedia.org/wiki/HTML) for the content of the pages, which are all static .html files. I used semtantic elements where availble to help assistive technologies and improve SEO.
- [CSS](https://en.wikipedia.org/wiki/CSS) for styling the pages and creating the responive design.
  - __CSS Grid__ was invaluable for creating a responsive design in which elements are rearranged on the page depending on the screen size. I used `grid-area` and `grid-template-area` to arrange the sections on the page by name using media queries.

  Example:
  ```css
      #findus-content {
        grid-template-columns: 1fr 1fr;
        grid-template-areas:
            "page-title page-title"
            "findus-address findus-img"
            "findus-img2 findus-facilities"
            "findus-map findus-map"
            "findus-form findus-form";
    }
    ```
  - __CSS Variables__ were used to store the color pallete and fonts used, and then referenced in the styles. This improved readability and could be useful in future for changing colors, for example building a dark mode.
  ```css
  :root {
    --main-bg-color: rgb(223, 228, 227);
    --color-primary: rgba(15, 74, 59, 1);
    --color-secondary: rgba(255, 194, 101, 1);
    --color-white: rgba(255, 255, 255, 1);
    --color-black: rgba(0, 0, 0, 1);
    --color-off-white: rgb(237, 237, 237);

    --font-headings: 'Rasa', serif;
    --font-secondary: 'Biryani', sans-serif;
    }
    ```

- [Git](https://git-scm.com/) for version control.
- [GitHub](https://github.com/) for storing the repository online during development.
- [GitPod](https://gitpod.io/) as a cloud based IDE.
- [Font Awesome](https://fontawesome.com/) for icons used in the project.
- [Google Fonts](https://fonts.google.com/) for the two fonts used on the project.
- [Eagle](https://en.eagle.cool/) for organising my images locally.
- [Pixelmator Pro](https://www.pixelmator.com/pro/) for resizing and converting images.
- [Google Chrome](https://www.google.com/intl/en_ie/chrome/), [Mozilla Firefox](https://www.mozilla.org/en-US/firefox/new/) and [Safari](https://www.apple.com/safari/) for testing on macOS, Windows, iOS and Android.
- [ColorSlurp](https://colorslurp.com/) for picking my color palette and testing for perfect accessibility.
- [Concepts](https://concepts.app/en/) for sketching wireframes on an iPad.

## Testing 

In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your project’s features and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

If this section grows too long, you may want to split it off into a separate file and link to it from here.


### Validator Testing 

- HTML
  - No errors were returned when passing through the official [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fcode-institute-org.github.io%2Flove-running-2.0%2Findex.html)
- CSS
  - No errors were found when passing through the official [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fvalidator.w3.org%2Fnu%2F%3Fdoc%3Dhttps%253A%252F%252Fcode-institute-org.github.io%252Flove-running-2.0%252Findex.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en#css)

### Unfixed Bugs

You will need to mention unfixed bugs and why they were not fixed. This section should include shortcomings of the frameworks or technologies used. Although time can be a big variable to consider, paucity of time and difficulty understanding implementation is not a valid reason to leave bugs unfixed. 

## Deployment

The site was deployed to GitHub pages. The steps to deploy are as follows: 
  - In the [GitHub repository](https://github.com/davidindub/plant-cafe), navigate to the Settings tab 
  - From the source section drop-down menu, select the **Main** Branch, then click "Save".
  - The page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment.

The live link can be found [here](http://www.davidindub.com/plant-cafe)

### Local Deployment

In order to make a local copy of this project, you can clone it. In your IDE Terminal, type the following command to clone my repository:

- `git clone https://github.com/davidindub/plant-cafe.git`

Alternatively, if using Gitpod, you can click below to create your own workspace using this repository.

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/davidindub/plant-cafe)


## Credits 

### Content 

- I used [Dribble](https://dribbble.com/) to research designs to pick my color palette.
- The text for each page was written by myself, drawing on my past experience as a barista and chef.
- The icons used on the Find Us page and footer were taken from [Font Awesome](https://fontawesome.com/).
- I used the [MDN Web Docs](https://developer.mozilla.org/en-US/) for help using CSS Variables for the colors and fonts, and help using CSS Grid Template Areas.
- I read [W3 Schools](https://www.w3schools.com/) for information on semantic HTML and Accessibility guidelines. 
- I watched some videos on [Kevin Powell's YouTube channel](https://www.youtube.com/kepowob) for help with responsive design, and learned about the `clamp()` function.
- I discovered the App [Eagle](https://en.eagle.cool/) when starting the project which was invaluable for organising all my reference images in one place, and I will use it in fuutre for all my projects.

### Media

- The photos used are from [Unsplash](https://unsplash.com/), credit to [Daniela Constantini](https://www.pexels.com/@daniela-constantini), [Fernando Hernandez](https://unsplash.com/@_ferh97), [Nikola Jovanovic](https://unsplash.com/@danteov_seen), [Nathan Dumlao](https://unsplash.com/@nate_dumlao), and [Ruben Ramirez](https://unsplash.com/@pinchebesu).


## Other General Project Advice

Below you will find a couple of extra tips that may be helpful when completing your project. Remember that each of these projects will become part of your final portfolio so it’s important to allow enough time to showcase your best work! 

- One of the most basic elements of keeping a healthy commit history is with the commit message. When getting started with your project, read through [this article](https://chris.beams.io/posts/git-commit/) by Chris Beams on How to Write  a Git Commit Message 
  - Make sure to keep the messages in the imperative mood 

- When naming the files in your project directory, make sure to consider meaningful naming of files, point to specific names and sections of content.
  - For example, instead of naming an image used ‘image1.png’ consider naming it ‘landing_page_img.png’. This will ensure that there are clear file paths kept. 

- Do some extra research on good and bad coding practices, there are a handful of useful articles to read, consider reviewing the following list when getting started:
  - [Writing Your Best Code](https://learn.shayhowe.com/html-css/writing-your-best-code/)
  - [HTML & CSS Coding Best Practices](https://medium.com/@inceptiondj.info/html-css-coding-best-practice-fadb9870a00f)
  - [Google HTML/CSS Style Guide](https://google.github.io/styleguide/htmlcssguide.html#General)
