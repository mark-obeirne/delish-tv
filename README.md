# [Delish TV - Find the stars of Netflix's original culinary series](https://mark-obeirne.github.io/culinary-world-tour/)

Code Institute - Milestone Project 2


Deadline: 28/06/20


Live GitHub Pages Link: https://mark-obeirne.github.io/culinary-world-tour/

[Image of multi-device preview - http://techsini.com/multi-mockup/index.php]

## Summary
Delish TV is a Netflix companion site that enables users to find the various restaurants featured in their favourite Netflix Original culinary shows. 

## Aim of the site
Food television is the fastest-growing niche in unscripted TV, according to [a recent study by The Hollywood Reporter](https://www.hollywoodreporter.com/features/gordon-ramsay-more-hollywoods-growing-hunger-food-tv-shows-1225214). After dipping its toe into the waters in 2015 with the release of Chef's Table, Netflix became one of the leaders in investing in original culinary programming. Today, Netflix's catalogue of culinary shows includes The Chef Show, starring Hollywood superstar Jon Favreau; the humble street stands of Street Food Asia; Michelin star chefs in Chef's Table and Chef's Table France; and a smorgasbord of cuisines and settings in Ugly Delicious, starring celeb chef David Chang. 

Brandon Riegg, Netflix VP of nonfiction series and comedy specials, said that food and cooking shows are the frontrunners when looking at categories of programming that people respond to globally. Lisa Nishimura, Netflix VP independent film and documentary features, said that people connect with these shows because "even though you can't smell or taste this food through the screen, you can absolutely feel it."

While shows such as Ugly Delicious and Street Food can give us a sense of what it is like to visit a particular business and we can witness our hosts delighting at the food on offer, it can be challenging to find more information about the various settings that they explore. If a viewer wishes to find more information, they must become proficient with Google and be very willing to peruse article after article that may provide them with some tidbits of information.

The purpose of this site is to connect users with the restaurants and businesses featured in Netflix Original culinary shows and provide them with relevant information should they wish to experience it for themselves rather than live through an on-screen host. The link between restaurant and Netflix show adds another dimension when a user is looking for a restaurant as they will be able to judge a restaurant on more than the menu, still pictures, and reviews from users who they do not know; instead, they can see the food preparation and presentation brought to life as well as reactions to a dish. 

## Scope 
The site targets not only viewers of Netflix Original culinary shows, but is of use to foodies living in an area in which a series have taken place as well as travellers. As a business, we have our own distinct goals, as reflected by the user stories.

### User Stories
"As a viewer of culinary shows, I am often automatically recommended other reality TV shows that have nothing to do with food. I would like to find similarly themed series that would be of interest to me."

"As a fan of Ugly Delicious, I would like to find out more information about some of my favourite restaurants featured in the series."

"As someone travelling to Japan, I would like an easy way to find out more about the Toyo street food restaurant, as seen on Street Food Asia, so that I can experience the food and performance for myself." 

"As a foodie, I would like to thoroughly research restaurants in my area to ensure that it appeals to me and that I will get value for money." 

#### Meeting User Expectations
[Include screenshots for added reference]

### Business Goals
"As a business, we would like to showcase our range of culinary series, as we would like users to keep finding value for money in their subscription or attract new customers."

"As a business, we would like to highlight the restaurants involved in series, which rewards them for allowing a series to be filmed there."

"As a business, we wish to continue making original culinary series and providing this added value to participating restaurants could encourage others to get involved."

### Design Choices
#### Colours
As Delish TV is built as a Netflix companion site, we have chosen to base our colour scheme on that used by Netflix. 

The background and text colour of #181818 provides good contrast, making it a suitable choice for text and the background to other elements. When acting as a background colour, it allows the map, series jumbotron, individual restaurant cards, and additional buttons to stand out. The exception to this is the navbar colour (#313131), which is 10% lighter according to https://www.colorbook.io/, which enables the logo to be displayed correctly.

The red shade (#E30914) is perfectly suited to smaller buttons, such as the dropdown menus and buttons that are created when a user clicks on an individual restaurant card. These draw the eye without being overpowering and provides good contrast to white text or background elements.

Finally, a grey shade (#CCCCCC) is used for added flourishes such as hover colours as it provides the user with information that an element is being hovered over or can be interacted with without impacting the readability of the text.

#### Fonts
While researching this project, Nunito Sans was highlighted as a font that is close to Netflix's own custom font. This is used for headings, most notably in the Featured Restaurants section where it is used for the section heading as well as the name of the restaurant and the series that it is featured in. 

The site uses Roboto for non-heading text. It is a good pairing for Nunito Sans without shifting the overall font style of the site.  

## Wireframe Mockups

### Mobile Wireframe
* [Index on Mobile - Original Layout](https://f6e340d7-6a4e-4496-9b03-f60438b4cd48.ws-eu01.gitpod.io/files/download/?id=6477c8de-4ec2-4cac-a0e6-a7467ce6e06c)
* [Index on Mobile - Revised Layout]()

### Tablet Wireframe
* [Index on Tablet]

### Desktop Wireframe
* [Index on Desktop]

## Changes to Wireframe
Originally, the tablet and desktop sites were larger versions of the mobile site, spacing out the individual restaurant cards better. 

However, in testing it became clear and was recommended that the space could be better utilised. The result is the altered layout that can be seen on the desktop site where the restaurant cards push up alongside the map allowing users access to all information easily. This did result in an issue whereby there was a lot of unused space beneath the map so a max height was added to the restaurant card column with a scrollbar available if there were more cards.

## Site Features
### Spotlight Series Jumbotron
When a user visits the site, a Netflix Original series is chosen at random to be displayed as the Jumbotron. This provides the user with more details about the series, the opportunity to watch a trailer to see if it is to their liking, and the option to watch it on Netflix if it is. If a user chooses a different series from the dropdown menu, this jumbotron is updated to reflect this. The jumbotron also ties in with the Google Maps feature, as detailed below.

### Google Maps
The Google Map is one of the focal points of this project. Upon an initial visit, the map is populated based on the restaurants featured in the randomly chosen spotlight series. When a user chooses a new series or location, the map updates to reflect the locations of restaurants that match the chosen filter. The user is also able to find out more information by clicking on a marker, which provides them with the address, series name, episode, and an episode link so that they can watch immediately. It is also possible to choose an individual restaurant card, which focuses the map on this location.

### Individual Restaurant cards
A number of individual restaurant cards are displayed to a user depending on the chosen filter. These cards present the user with information about the restaurant such as its general address and the series that it is featured in. When an individual card is selected by the user, the map zooms in on that location as previously mentioned and the card provides the user with a button to watch the episode that the restaurant is featured in. 

## Future Features
### Restaurant Wishlist
While enabling users to find out so much more about restaurants can be helpful, we hope to do more in the future. We would like to add a feature which enables users to add individual restaurants to a wishlist of places that they would like to visit or save for looking up again later; perhaps it will entice them to rewatch the episode that takes place at that restaurant (or, in some cases, watch for the first time).

### Search bar Functionality
Currently, users are able to search based on the series that a restaurant is featured in or its country. We would like to be able to offer users more choice in how they search. In the future, we would like to add a search bar, which will enable users to search by restaurant name, its city, its country, or the series that it features in. This search bar will suggest searches based on the user's input or, if no matches are found, will offer suggestions, including a restaurant, a city, a country, or a series.

### Embedded YouTube Trailers
While we tested embedding YouTube trailers in a hidden iframe that displayed when a user clicked on the More Info button in the spotlight panel, since replaced by the Trailer button, we found that it resulted in errors and slowed down the performance of the site. For the next release, we would have time to utilise the YouTube API in order to display trailers for the featured series in a more streamlined way than embedded iframes.

## Technology Used

[HTML](https://en.wikipedia.org/wiki/HTML) & [CSS](https://en.wikipedia.org/wiki/Cascading_Style_Sheets) programming languages - For the basic site structure and design elements.

[JavaScript](https://en.wikipedia.org/wiki/JavaScript) - JavaScript makes up the lion's share of this project as it is used extensively to build and populate the site based on either a randomly chosen series or user choices.

[Bootstrap 4](https://getbootstrap.com/) - Bootstrap 4 was used to prioritise the mobile design, while enabling the site to be responsive and look its best across a variety of screen sizes. 

[Balsamiq](https://balsamiq.com/wireframes/desktop/#) - Balsamiq was used to create a series of wireframes that the site was built based on.

[Coolors](https://coolors.co/) - Coolors assisted in finding a colour palette that worked well. 

[Google Fonts](https://fonts.google.com/) - Google Fonts assisted in finding and sourcing fonts that would suit a site of this type.

[Font Awesome](https://fontawesome.com/) - Font Awesome was used to find icons that would provide more detail for buttons such as the Play Now and More Info buttons as well as visual representations of social media platforms. 

[Git](https://git-scm.com/) - To track changes in code during development.

[GitHub](https://github.com/) - To host the project’s repository and to host the live website via GitHub Pages.

[Gimp 2](https://www.gimp.org/) - Gimp 2 allowed for image manipulation and was used to create the brand’s logo.

[Favicon Converter](https://favicon.io/favicon-converter/) - To create the favicon based on the brand logo.

[FreeFormatter](https://www.freeformatter.com/) - Used to tidy up and properly format the index.html file. 

[FreeFormatter CSS Beautifier](https://www.freeformatter.com/css-beautifier.html) - Used to standardise indents and tidy up the style.css layout and formatting.

[Multi Device Website Mockup Generator](http://techsini.com/multi-mockup/index.php) - Used to create the multi-device image featured at the top of this README file.


## Testing

HTML Validator - https://validator.w3.org/nu/ 
HTML Validator - https://www.freeformatter.com/html-validator.html

CSS Validator - https://jigsaw.w3.org/css-validator/validator

JavaScript Validator - https://esprima.org/demo/validate.html
JS Validator (mainly used for missing semicolons) - http://beautifytools.com/javascript-validator.php

-- Any tools and validators. Results, if not screenshots, of said tools
HTML Validator - https://validator.w3.org/nu/
Accessibility:
    https://wave.webaim.org/
    https://www.webaccessibility.com/results
    https://color.a11y.com/Contrast/

## Testing Process

-- Include any automated or lots of details about the manual testing performed, including tests and steps

-- Devices and browsers Used


## Issues Encountered and Resolutions
### Error on page load
Initially, the selectSpotlight function was used as the callback function in the google maps apis script, but this produced an error on page load occasionally. Removing the callback and instead adding a load event listener to the window that called this function has rectified this issue.

### Individual restaurant card produces multiple "Watch on Netfix" buttons
When a user clicks on an individual div, a Watch on Netflix button is generated with the relevant link. However, when viewing only a single restaurant, clicking on the div again would produce multiple instances of this button. This issue was solved by adding an if statement to check that there were no other such spans on the page already. If this is true, the function runs and generates the span and relevant link; otherwise, the function simply returns.

### Any known issues?
#### Filter By Location dropdown
This filter dropdown allows the user to type in a country name to filter the dropdown options to just the countries that match the text entered. If the dropdown menu is displayed above the button, the text entry field is at the top of the list and entering text causes the remaining menu options to seemingly float in the middle of the page.

## Deployment
### GitHub Pages
To deploy this website on GitHub Pages, I followed the following steps:
1. Navigate to the [project’s repository](https://github.com/mark-obeirne/culinary-world-tour)

2. Navigate to the [settings page](https://github.com/mark-obeirne/culinary-world-tour/settings)

3. Scroll down to the section titled GitHub Pages

4. As my repository was private while I was working on it, I had to choose to make it public

5. Select Master Branch from the Source dropdown

6. The GitHub Pages section changed to inform me that my site "is ready to be published at https://mark-obeirne.github.io/culinary-world-tour/"

### Local Deployment
To clone this project and to deploy it locally, follow these steps:

1. Navigate to the [project’s repository](https://github.com/mark-obeirne/culinary-world-tour)

2. Click the green button marked “Clone or download”

3. Highlight the provided URL and copy it or click the copy button to the right. Alternatively, you can download a .zip file of the repository to run the website locally

4. Open your terminal

5. Navigate to the working directory where you would like to place the cloned repository

6. In the command line, type “git clone” followed by the URL copied previously

For more information or guidance, please see [GitHub’s Help Section](https://help.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository).


## Credits 
### Content


### Media


## Acknowledgements
I would like to thank my mentor, [Antonio Rodriguez](https://github.com/AkaAnto) for their support and advice. In particular, I would like to thank them for their feedback during our second call, which prompted a revision of the site's layout, leading to better flow and overall UI. 


I would also like to thank my fellow Code Institute students and the alumni who provided support, advice, and a second opinion on Slack.

Finally, I would like to thank all those who took the time to test this website and provide feedback and suggestions. 


## Disclaimer
This project is for educational purposes only.