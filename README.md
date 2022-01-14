![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)

## Python Terminal Info

To run a frontend (HTML, CSS, Javascript only) application in Gitpod, in the terminal, type:

`python3 -m http.server`

A blue button should appear to click: _Make Public_,

Another blue button should appear to click: _Open Browser_.

## Step 1
The first step was to create index.html and load in the Bootstrap CDN located at (https://getbootstrap.com/docs/4.0/getting-started/download/#bootstrapcdn).

I then created the assets, css and images folder before creating the style.css file within the css folder.
I also imported some Google Fonts into the style.css sheet.

At this point, I decided to test my style.css file and came across my first issue. It didn't seem as if the styles applied within style.css were being applied to the web-page.

To resolve this, I inspected the code and realised that the issue was due to a typo in the header where I had typed 'stylsheet' instead of 'stylesheet' PUT IN SCREENSHOT OF THIS.

Typo Error Screenshot

Once I validated that the style sheet was working, I utilised the Bootstrap Grid to create three responsive columns within a container. I gave the container a class of 'section-one'.

## Step 2
I then created another container and placed this above the 'section-one' container to create a navbar for the website with an id pf header. The navbar consisted of a branded logo to the left of the page and three links to the right of the page, namely, Home, Pricing and Join Us.

## Step 3
I wanted to place a 'hero image' between the navbar and section-one so I utilised and modified the following code (https://stackoverflow.com/questions/12393382/positioning-text-relative-to-an-image-when-the-image-size-changes) to ensure the content overlayed on the image would re-size relative to the screensize/viewport. STRUGGLING TO GET THIS TO WORK!
Image from (https://simplifaster.com/articles/weightlifting-progressions-tall-long-limbed-athletes/).

## Step 4
I then created another bootstrap container which contained three responsive columns with an id of 'footer'.

## Step 5
I replicated the container containing three columns layout utilised in index.html for pricing.html however the background colour for each column has a different level of transparency to highlight the different pricing tiers.

## Step 6
I created a container on the 'join-us' page and placed a form within a Bootstrap col-12. The form has four required inputs (one of which is a dropdown) and two buttons (submit and restet).
I utilised and modified the following code to create a placeholder for my dropdown list (https://stackoverflow.com/questions/5805059/how-do-i-make-a-placeholder-for-a-select-box) and I have populated the 'action' section of my form with the following url (https://formdump.codeinstitute.net).

# SJ Fitness

SJ Fitness is a website for a personal trainer owned gym located in West Wales. The site is aimed at fitness enthusiasts of all levels. The website will be used to attract new members to the gym and to enable the gym to receive new member enquiries at the client's desired tier/price point.

MAKE THIS FOR MY WEBSITE
![Responsice Mockup](https://github.com/lucyrush/readme-template/blob/master/media/love_running_mockup.png)

## Features 

In this section, you should go over the different parts of your project, and describe each in a sentence or so. You will need to explain what value each of the features provides for the user, focusing on who this website is for, what it is that they want to achieve and how your project is the best way to help them achieve these things.

### Existing Features

- __Navigation Bar__

  - This features on all pages and includes links to the gym's branding, Home page, Pricing page and Join Us page. The navigation bar is fully responsive and  is the same on each page to facilitate easy navigation.
  - The navigation bar will allow users to navigate the site on all devices without having to use the 'back' button. 

SCREENSHOT OF NAVBAR
![Nav Bar](https://github.com/lucyrush/readme-template/blob/master/media/love_running_nav.png)

- __The Home/Landing Page__

  - The home/landing page contains a photo a photograph with the SJ Fitness motto of 'Better Starts Today' overlayed on it. This motto is present to convey that the aim of the gym is to improve their fitness and engcourages the user to start their journey as soon as possible. 

![Landing Page](https://github.com/lucyrush/readme-template/blob/master/media/love_running_landing.png)

- __The 'SJ Fitness Approach' Section__

  - The SJ Fitness Approach section describes to the user how the gym will cater to their individual needs. It highllights that the gym does not a 'one size fits all' approach to health and fitness and that the gym wants to ensure everyone is treated as an individual. This is expanded upton in the adjacent 'How Can We Help You?' section.

![SJ Fitness Approach](https://github.com/lucyrush/readme-template/blob/master/media/love_running_ethos.png)

- __The 'How Can We Help You? Section__

  - This section also mentions numerous goals that clients may have in order to appeal to as wide an audience as possible. It leads on from the 'SJ Fitness Approach' section to highlight to clients and prospective clients that this is a gym for all abilities and all goals as opposed to only focussing on one type of training.

  ![How Can We Help You?](https://github.com/lucyrush/readme-template/blob/master/media/love_running_ethos.png)

  - __The 'Find Us!' Section__

  - This section is simply a Google Maps snapshot to assist clients in finding the gym.

![Find Us](https://github.com/lucyrush/readme-template/blob/master/media/love_running_times.png)

- __The Footer__ 

  - The footer section includes links to social media sites (facebook, twitter, instagram), and an email address to help potential clients get in contact with SJ Fitness. The social media links open to a new tab for easier navigation. 
  - The footer is valuable for the gym business as it allows prospective clients to follow them on social media and to get in touch about new memberships. It is also valuable for the user as it directs them to the social media sites and gives them an email point of contact to ask any questions prior to signing up via the 'Join Us' page.

PUT IN OWN FOOTER SCREENSHOT
![Footer](https://github.com/lucyrush/readme-template/blob/master/media/love_running_footer.png)

- __The Pricing Page__

  - The pricing page has a brief explanation at the top of the page below the navigation bar which also contains a hyperlink to the Join Us page so that the user can immediately navigate to sign up.
  - The pricing page is then split into three columns which represents the different membership tiers and their respecting monthly cost. The information on different tiers is concisely summarised via the use of bullet points so that the user is not overloaded with too much information regarding the membership types.
  - The membership tiers and bullet points are positioned in such a way that it is clear to see what is omitted as the pricing tier decreases which makes comparison of membership tiers easier for the user. This is also a strategy to increase the gym's revenue by convincing prospective clients to sign up for the top tier as they can see that the top ties does provide more for their money when comparing membership options.

![Pricing](https://github.com/lucyrush/readme-template/blob/master/media/love_running_gallery.png)

- __The Join Us Page__

  - This page will allow the user to get join SJ Fitness. The user will be able select their desired membership type whilst also being asked to provide their full name and email address.
  - Below the Join Us form, there is a looped video of a group of people high fiving each other which is used to convey the fact that the client is joining a supportive community by joining SJ Fitness.
  
  [Join Us](https://github.com/lucyrush/readme-template/blob/master/media/love_running_signup.png)


### Features Left to Implement

- A future feature to implement would be the embedding of fitness related videos which loop on all pages as opposed to the Join Us page only.

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

### Content 

- XXX
- The text for the Home page was taken from Wikipedia Article A
- Instructions on how to implement form validation on the Sign Up page was taken from [Specific YouTube Tutorial](https://www.youtube.com/)

### Media

- The photo used on the landing/home page was taken from XXX.
- The icons used for the Pricing tiers and for the social media icons in the footer were taken from [Font Awesome](https://fontawesome.com/)
- The video used on the Join Us page is from (https://www.pexels.com/video/silhouette-of-friends-doing-high-five-8692158/)