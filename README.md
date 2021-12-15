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

Once I validated that the style sheet was working, I utilised the Bootstrap Grid to create four responsive columns within a container. I gave the container a class of 'section-one'.

## Step 2
I then created another container and placed this above the 'section-one' container to create a navbar for the website. The navbar consisted of a branded logo to the left of the page and three links to the right of the page, namely, Home, Pricing and Join Us.

## Step 3
I wanted to place a 'hero image' between the navbar and section-one so I utilised and modified the following code (https://stackoverflow.com/questions/12393382/positioning-text-relative-to-an-image-when-the-image-size-changes) to ensure the content overlayed on the image would re-size relative to the screensize/viewport.
Image from (https://simplifaster.com/articles/weightlifting-progressions-tall-long-limbed-athletes/).