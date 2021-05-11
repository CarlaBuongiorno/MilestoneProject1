<h1 align="center">Delicious Monster</h1>


[View the live site here](https://carlabuongiorno.github.io/MilestoneProject1/)

Delicious Monster is a comprehensive website incorporating various technological elements to offer users a variety of recipes and inspiration to make sweets and desserts at home. Additionally, it offers some _Fun Facts_ and a quote about desserts in order to put the user in a playful, creative mood.

![Responsive mockup of the website](https://github.com/CarlaBuongiorno/MilestoneProject1/blob/master/assets/responsive/responsive-img.png)

## 2. UXD – User Experience Design

The target demographic are users aged 8 to 80. With delicious recipes for sweets and desserts ranging from a simple Chocolate Pudding to a challenging Cream Puff. Links are provided for step-by-step instructions and videos. This, together with the subcription for access to many more free recipes, a weekly newsletter, and social media interaction, will result in fun and delicious desserts to be enjoyed by even the most discerning gastronome. 


### Strategy

#### Customer Goals

Visitors to this website are searching for easy to follow dessert recipes that promises a delicious and aesthetically pleasing outcome.

#### Project Goals

This project is the best way to help them achieve this because it is easy to navigate, whether by mobile, tablet, or desktop. The navigation bar is always in the viewport no matter where in the site the user has navigated to.

The site is designed so that upon entering, the user immediately anticipates a sense of deliciousness and feels inspired enough to Subscribe - being the ultimate goal of this website.

#### User Stories

1. As a site visitor, I wish to understand how to navigate this site, so that I can find what I am looking for easily.
2. As a site visitor, I wish to view this site on all my devices.
3. As a site visitor, I wish to feel inspired by what I see and find on this site.
4. As a site visitor, I wish to be able to subscribe to a newsletter in order to have access the latest recipes.
5. As a site visitor, I wish to have visible access to social media, so I can follow and be a part of the community.

### Scope

For the initial release of this website, I have decided on a "Minimal Viable Product" approach - considering my current skillset is at beginner level.

Features include:
- The ability to navigate with ease through a single page site; either by scrolling through the varous sections, or by clicking on the links on the navigation bar - which is always in view.
- An eye catching, aesthetically pleasing __Home__ page.
- A __Fun Facts__ section to grab the users attention.
- A __Recipes__ section that is minimal and comprehensible due to the layout. Links to step-by-step instructions are provided for each recipe which opens in a new tab so that users can easily return to the site.
- A step-by-step video for the user to be inspired to take immediate action followingin the kitchen.
- A __Subscribe | Contact Us__ form for more free recipes and weekly newsletter.
- A footer with a copyright and social media links for user to interact and become part of the Delicious Monster Community.

### Structure

I have intentionally created a single page website with minimal written content in order for the user not to feel overwhelmed, but rather inspired. 

The __Home__ sections features a hero image with a navigation bar, and a small piece of information inviting the user to discover the dessert recipes below.

The pictures in the __Fun Facts__ section are purely for aesthetic purposes, matching the short and fun 'Did You Know?' pieces.

The __Recipes__ section features:-
- several recipes
- each with a picture of the dessert
- a short but tantalizing description
- quick to understand information about the total time it takes to complete the recipe
- the skilllevel it requires
- the amount of servings it renders
- a link to an external page containing step-by-step instructions, pictures and videos.
- a step-by-step video of one of the above recipes for immediate inspiration, and action.

The __Subscription | Contact Us__ form is simple and clean. Subscription promises 100s more free recipes and a weekly newsletter.

The footer features linked icons for ease of access to social media, which all open on seperate pages.

### Skeleton

- [Wireframes:](assets/wireframes/wireframes.pdf) 1 Page website with 4 main sections :- 
1. Home
2. Fun Facts
3. Recipes
4. Subscribe | Contact Us

### Surface

#### Colours
1. Black #0a0a0c
2. Pink #ff536e
3. Mint #d6efcf

I decided to use a colour picker tool to pick out 3 colours from my hero image. I then defined each section by 1 of these 3 colours.

I used these colours interchangeably within the content of the site to keep consistency thoughout.

#### Typography

I selected 2 different fonts for this site: 

1. "Dancing Script", (cursive) - For the main headings to bring in a feeling of playfulness and excitement.
2. "Open Sans", (sans-serif) - For the main content for contrast and ease of reading.

#### Images

The images I selected are eye catching with the intention to tickle the taste buds. The recipe images are directly related to the dessert being focused on.

## 3. Features
 
### Existing Features
 - 1 Page site with 4 main sections.
 - Navigation bar which takes the user to each section and is responsive.
 - Footer with copyright and Social links.
 - Responsive images sized for different screen views.
 - Subscribe form with a checked checkbox to subscribe for free recipes and a newsletter, as well as the possiblity to write a message containing feedback of the recipes.
 - Recipes section features 6 recipe cards with links to external pages in order to see the complete recipe.
 - Recipes section also features an embedded YouTube video of a step-by-step recipe.
 - A 404 page to help the user navigate back home.

### Features Left to Implement
- Form submission button to be functional.
- Recipe links will be directed to my own recipe pages, designed consistently with respect to the main website.
- Social media links to Delicious Monster business pages.

## 4. Technologies and Resources Used

https://tinyjpg.com/ - for downsizing images while retaining quality */
https://imagecolorpicker.com/ for choosing colours from Hero Image Strawberry
MS1 Planning Session - Jim Lynx https://www.youtube.com/watch?v=sH0m9N875SU&list=PLrq7lxF8EYVrvcejINzdH1RtqB2Ax7TlK&index=1
Using the Bootstrap 4 Grid | BOOTSTRAP 4 TUTORIAL https://www.youtube.com/watch?v=qmPmwdshCMw
ANNA GREAVES https://ajgreaves.github.io/bootstrap-grid-demo/responsive.html
README.md example - https://github.com/AJGreaves/portrait-artist
https://css-tricks.com/fluid-width-video/ CSS Tricks: Fluid Video width - To make video responsive
https://favicon.io/favicon-generator/


In this section, you should mention all of the languages, frameworks, libraries, and any other tools that you have used to construct this project. For each, provide its name, a link to its official site and a short sentence of why it was used.

- [JQuery](https://jquery.com)
    - The project uses **JQuery** to simplify DOM manipulation.


## 5. Testing

https://jigsaw.w3.org/css-validator/validator - css validator

In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your user stories from the UX section and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

Whenever it is feasible, prefer to automate your tests, and if you've done so, provide a brief explanation of your approach, link to the test file(s) and explain how to run them.

For any scenarios that have not been automated, test the user stories manually and provide as much detail as is relevant. A particularly useful form for describing your testing process is via scenarios, such as:

1. Contact form:
    1. Go to the "Contact Us" page
    2. Try to submit the empty form and verify that an error message about the required fields appears
    3. Try to submit the form with an invalid email address and verify that a relevant error message appears
    4. Try to submit the form with all inputs valid and verify that a success message appears.

In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

## 6. Project barriers and solutions

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

If this section grows too long, you may want to split it off into a separate file and link to it from here.

## 7. Version Control

## 8. Deployment

This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub Pages or Heroku).

In particular, you should provide all details of the differences between the deployed version and the development version, if any, including:
- Different values for environment variables (Heroku Config Vars)?
- Different configuration files?
- Separate git branch?

In addition, if it is not obvious, you should also describe how to run your code locally.


## 9. Credits

### Content
- The text for section Y was copied from the [Wikipedia article Z](https://en.wikipedia.org/wiki/Z)

### Media
- The photos used in this site were obtained from ...

## 10. Acknowledgements

- I received inspiration for this project from X
