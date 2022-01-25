# Plant Cafe

The project is to make a simple website for a Cafe and Houseplant Shop in Dublin City.

The shop serves specialty coffee and plant-based food, sells houseplants in store and frequently hosts events about growing plants.

The plants are not sold online, but the website will include some tips on keeping houseplants, as well as a signup form for a newsletter on upcoming events.

The main target of the website are people looking for quick information such as the food & drinks menu, or the location and opening house of the shop and it is expected most of these visitors will be checking the website quickly on a mobile device. Delivering this information quickly and clearly is the main aim of the project.


## Use Stories

- As a tourist, I want to find out when the café is open and where it is so I can visit.

- As a plant enthusiast, I want to find out about upcoming events.

- As a vegan, I want to find out if there is many options for me to eat at the cafe.

## Features 

In this section, you should go over the different parts of your project, and describe each in a sentence or so. You will need to explain what value each of the features provides for the user, focusing on who this website is for, what it is that they want to achieve and how your project is the best way to help them achieve these things.

### Existing Features

- __Navigation Bar__

  - All pages feature the same responsive navigation bar with links to the homepage, Food Menu, Location & Contact Form, and Events page. This allows the user to easily navigate the site.

  - Featured on all three pages, the full responsive navigation bar includes links to the Logo, Home page, Gallery and Sign Up page and is identical in each page to allow for easy navigation.
  - This section will allow the user to easily navigate from page to page across all devices without having to revert back to the previous page via the ‘back’ button. 

![Nav Bar](https://github.com/lucyrush/readme-template/blob/master/media/love_running_nav.png)

- __The landing page image__

  - The landing page features a large eye catching photograph with text overlayed, on smaller displays such as a phone it includes a button which when clicked scrolls the page down to the most important information the users might be looking for,


- __Cards on Landing Page__

  - Three cards with related photographs describe the three pages of the website where the user might like to visit.
  - Clicking anywhere on each of these cards takes the user to the associated page, making the links easy to tap on mobile. There is a subtle underline and color change on hover/focus.

- __The Footer__ 

  - The footer section includes the physical address and email address of the cafe, navigation links to the other pages of the website, and links to the cafe's social media accounts (all open in a new tab so as not to end the users visit to the Plant Cafe site)
  - The footer is responsive, the three sections and the nav links stack on mobile view, but use the extra available space on larger screens.

- __Menu__

  - The Menu page provides the user with the list of Food and Drink options and prices available at the cafe.

- __Find Us__

  - This page provides the address of the cafe, an embedded Google Map of the location, and email and telephone details to contact the cafe.

- __Events__

  - This page lists upcoming events happening at the cafe, and provides a form for a newsletter for users to find out about future events.

For some/all of your features, you may choose to reference the specific project files that implement them.

In addition, you may also use this section to discuss plans for additional features to be implemented in the future:

### Features Left to Implement

- Another feature idea

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

This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub) 

- The site was deployed to GitHub pages. The steps to deploy are as follows: 
  - In the GitHub repository, navigate to the Settings tab 
  - From the source section drop-down menu, select the Master Branch
  - Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment. 

The live link can be found here - https://code-institute-org.github.io/love-running-2.0/index.html 


## Credits 

In this section you need to reference where you got your content, media and extra help from. It is common practice to use code from other repositories and tutorials, however, it is important to be very specific about these sources to avoid plagiarism. 

You can break the credits section up into Content and Media, depending on what you have included in your project. 

- [Stack Overflow - Can't figure out what is causing the side scroll on my website](https://stackoverflow.com/questions/35193617/cant-figure-out-what-is-causing-the-side-scroll-on-my-website)
I encountered problem where my page would have a horizontal scroll to the right in Chrome yet no content seemed to be causing it, and the problem was to do with the browser scroll bar, adding overflow-x: hidden to the body element fixed this issue.

### Content 

- The text for the Home page was taken from Wikipedia Article A
- Instructions on how to implement form validation on the Sign Up page was taken from [Specific YouTube Tutorial](https://www.youtube.com/)
- The icons in the footer were taken from [Font Awesome](https://fontawesome.com/)

### Media

- The photos used on the home and sign up page are from This Open Source site
- The images used for the gallery page were taken from this other open source site


Congratulations on completing your Readme, you have made another big stride in the direction of being a developer! 

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

Getting started with your Portfolio Projects can be daunting, planning your project can make it a lot easier to tackle, take small steps to reach the final outcome and enjoy the process! 