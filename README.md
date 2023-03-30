# SUMMER PROJECT

Get ready for this year's summer festival. With a new theme every year. Here you will find all the information that is important right now. We release artists from time to time and the tickets have not gone on sale yet.
If you want information before everyone else, you can sign up for the newsletters on the contact page.

The purpose of this website is to get important news in an easy way. You should also be able to dream of previous years by looking through the pictures on the gallery page.

![Image of differents screen, if the website is responsive to all devices](/assets/images/images_readme/responsive.png)

## Features

### Existing Features

## - Landing page

**Navigation:**
 
The navigation is important to see clear so the user always can know were them want to go. It also have an underline under so the user can see which page them are on. The user can navigate through 3 pages "HOME", "GALLERY" and "CONTACT".

- I chose to put the navigation in the middle of the screen so that everything is centered here. It should be perceived as easy for the user to find the navigation.

 ![The header with navigation](/assets/images/images_readme/header_nav.png)

**Loadingbox:**

This will be the first the user will see. This is a colorful "loadingbox" that provide info about how many days it's left before they release the tickets.

- The colors in the box have a meaning. The pink color is how much time has passed and the blue color is how much time is left until the tickets are released.

 ![loadingbox that provide info how many days it is left to ticket release](/assets/images/images_readme/release_days.png)

 **Dates:**

Information about when the festival takes place.

- I think it is important that the dates have the largest text size on the page. Because right now, that is the most important information. So the user can book into the calendar and take time off from work or school


 ![Information about when the festival takes place.](/assets/images/images_readme/festival_dates.png)

 **Artist:**

Info about which artists have been released so far. The bigger the artists, the bigger the text.

- The artists are centered in vertical order. So that it doesn't get messy and crowded. Smooth, simple information to the user.

![Artist that have been released so far](/assets/images/images_readme/artist.png)


## - Gallery

Here we show pictures from the previous year. With small information text. It is important for us to show what happened in previous years so you know what to expect. Those who have attended in previous years can dream back by looking at the pictures.

- Here I have chosen to use a black background and faded text because here it is the images that should take focus from the user.

![Pictures from 2022](/assets/images/images_readme/gallery_2022.png)
![Pictures from 2021](/assets/images/images_readme/gallery_2021.png)


## - Contact

**Subscribe:**

Now is the time to sign up for the newsletter. Here we have different options where the user can tick the information you want in the email. This week's newsletter is already ticked.

- It is important that the user should be able to receive information before it appears on the website or at the same time as it is published. So they never miss anything. The user can decide which information is most important to them. After they press subscribe, a message appears that says thank you very much.

![Subscribe box, befor user subscribe](/assets/images/images_readme/subscribe.png)

![Subscribe box, after user subscribe](/assets/images/images_readme/thank-you.png)


**Contact:**

If the user wants to get in touch with the suppliers, there is clear and concise information next to the subscription. Address, number and email.

- It should never be difficult to find the contact details. So that's why it has its own navigation and is clearly visible in the middle of the page.

![Contact information](/assets/images/images_readme/contact.png)


## - Footer and social links

In the footer we have the social links. Where the user can check all their social platforms.

- The icons are in the same color theme as the main header. So that everything has a common thread. The icons are linked to e.g. Facebook. Stylish footer with simple icons.

![Footer with social links](/assets/images/images_readme/footer.png)

## Testing

- After the problems with the pages being responsive to mobile devices, it works without problems now. I received very good help from my teachers.

- I confirmed the navigation and it works, it switches to the right pages. Even the main heading works as a link so that it navigates to the home page. 

- I confirm The subscribe box. It works without problems. The email must be filled in, otherwise you cannot subscribe. When you subscribe, thank you text appears. So everything works perfectly.


## Bugs

**Solved bugs**

- I was reminded by the lighthouse in devtools that I forgot the aria label in the footer, for the social links. So I fixed that by changing my codes.
![arial-label link](/assets/images/images_readme/arial_link.png)

- When I checked how it looked on mobile devices, I saw that the body element was not all the way to the edges. 
I contacted the teachers and got advice right away.

There were three problems that caused the page to be pushed out to the sides. So I had to change the width of the header and the menu in the first place. 

![width Code](/assets/images/images_readme/header-width.png)

I started by having two divs next to each other, which I have when the page is responsive to 800px and up. But it also pushed the side on the width when I change it to mobile devices. So I had to make the one div hidden and then add contact info to the subscribe to get everything centered and not push the page to the right.

**HTML**

![contact-html](/assets/images/images_readme/html-contact.png)

**CSS**

![contact](/assets/images/images_readme/contact-text.png)

## Validator testing

**Html**
- html files pass through the [W3C validator](https://validator.w3.org/#validate_by_input) with no issues found.
![Html validator](/assets/images/images_readme/html-validator.png)


**CSS**
- css files pass through the [Jigsaw validator](https://jigsaw.w3.org/css-validator/#validate_by_input) with no issues found.
![CSS validator](/assets/images/images_readme/validator-css.png) 

**Accessibility**
- The website went through lighthouse without any problems.
![Accessibility](/assets/images/images_readme/lighthouse.png)

## Technologies Used

### Frameworks, Libraries & Programs Used

- Google Fonts - for the font families: Allerta Stencil, Poiret One, Stick No Bills.
- [Font Awesome](https://fontawesome.com/) - to add icons to the social links in the footer element and the icon in the header.
- GitPod - to creat my html files & styling sheet before pushing the project to Github.
- GitHub - to store my repository for submission.
- Am I Responsive? - to ensure the project looked good across all devices.

## Deployment

The site was deployed to GitHub pages. The steps to deploy are as follows:

- In the GitHub repository, navigate to the Settings tab
- From the source section drop-down menu, select the Master Branch
- Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment.
- The live link can be found HERE - [Summer Project](https://karroroenning.github.io/Project_1_layout/)

## Credits


### Content

- I got inspiration to my header and navigation menu from another festival page [Sweden Rock](https://www.swedenrock.com/en/). 

- The inspiration for my gallery I look around on [Tomorrowland's](https://www.tomorrowland.com/en/festival/welcome) page. I mostly got the inspiration from the years that were above the pictures and some info text about the year that was.

- When I got stuck and wanted help with some codes, I searched on [Mozilla's](https://developer.mozilla.org/en-US/docs/Web/CSS) site. Find many good aids there.

- I got stuck with a code where my body element was not responsive to mobile devices. So I ask on slack first, but no one could help me there. Then I contacted Tutor support. There I got help right away and the problem was solved.

### Media

- The background image is from [pexels](https://www.pexels.com/sv-se/sok/music%20festival/) and also the images in gallery are from pexels. My search term was music festival.