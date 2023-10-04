# Nurture

Nurture is a site designed to attract those interested in leading a healthier lifestyle, through lifestyle changes such as yoga and mindfulness. It will provide a brief introduction to 'Nurture', the brand, with the intent of selling courses to prospective members. The site is informative and is designed to emote a positive experience in the user. There is a brief overview of the courses that Nurture can offer, and the opportunity for the user to request a brochure to be sent to their email address with further information. The site will also direct traffic to Nurture's social media channels.

![Screenshot of Nurture website on different screen sizes to show the site is responsive](/assets/images/website-mockup.png)

# UX

The site's intended users are customers, who have an interest in health and wellbeing. In particular those who are looking for guidance in some way. The site is designed to be informative, while representing the values of brand.

## User stories

- As a user, I want to navigate this website with ease and simplicity
- As a user, I want to find out more about health and wellness
- As a user, I want to find out what I can do, to imrpove my own wellbeing
- As a user, I want to find out more about the courses Nurture offer, so that I can make a decision about which course is best for me
- As a user, I want to request full course details
- As a user, I want to see other customers experiences using the courses, so that I know whether I can trust the brand
- As a user, I want to be able to see Nurture's social media pages, so that I can find a community of like-minded people

## Strategy

The intent of the website is to deliver information regarding health and wellbeing to a customer, in a visually pleasing manner.This information will solve a problem for the user, such as the need to quit smoking, or find guidance on losing weight. The goal is the user requesting a brochure, and booking a course.

The site was designed first in Balsamiq, which allowed for the layout to be loosely designed for different screen sizes beforehand

![Wireframe](/assets/images/wireframe-screenshot.png)

A colour palette of greens and neutrals was chosen to compliment the brand, because of it's association with nature. Dark and light colour tones are used in contrast to make text stand out against background colours. This makes the site more accessible for the user

![Colour scheme](/assets/images/colour-scheme.png)

## Features

### Existing features

**Navigation bar**

![Screenshot of navigation bar](/assets/images/navigation-bar.png)

- This includes a link to the 'Home' page, the 'Courses' page and the 'Request a brochure' page
- This is designed to be responsive so it collapses into a hidden menu on smaller screens
- It allows the user to navigate easily throughout the website without using the 'back' button

**Banner image**

![Screenshot of banner image at the top of the page](/assets/images/hero-image.png)

- This shows an inspirational image of a woman looking out over a sunset
- It's designed to emote a positive reaction in the user, and hold their attention long enough to keep scrolling through the website
- The image itself is on brand, and relates to the content of the courses that Nurture offer

**Why Choose Nurture?**

![Screenshot of section that lists reasons to join Nurture's classes](/assets/images/why-nurture.png)

- A brief section listing there reasons why the user should be interested in Nurture.
-This is designed to pique their interest and encourage them to keep reading

**Introduction to Courses**

![Screenshot of courses overview on home page](/assets/images/our-courses-screenshot.png)

- A brief introduction to the types of courses on offer, with images that spark the imagination and help the user to visualise the classes better
- These are designed to be responsive on different screen sizes

**Testimonials**

![Screenshot of member testimonials](/assets/images/members.png)

- A series of testimonials from current or previous course attendees
- Designed to illicit a sense of trust in the brand
- Images are used to make the testimonials feel more personal

**The Footer**

![Screenshot of website footer](/assets/images/footer-screenshot.png)

- Includes links to Nurture's social media pages
- This will encourage traffic to the social media pages

**Courses**

![Screenshot showing courses page](/assets/images/courses-page.png)

- This provides a more detailed overview of each of the courses, who the course is for, and what the intended outcome is
- Each course is combined with an image to help the user better visualise the courses
- At the bottom of the courses page is a link to take the user directly to the page to request a brochure
 
**Request a brochure**

![Screenshot showing form on Request a brochure page](/assets/images/form-1.png)

- This page is designed to help the user request more information about the courses. They are required to fill in first and surname, as well as email address, and which courses they are interested in.
- The text alongside the form explains what they can expect to happen next, and directs them to the youtube channel while they wait

![Screenshot of image gallery on Request a brochure page](/assets/images/form-2.png)

- The form sits alongside a short gallery of course related imagery for visual interest

### Features left to implement

**Course leaders**
 
- An additional section to be added to the courses page which has an image and a brief introduction to the course leaders and their qualifications
- This would help to increase a sense of trust in the user

**An embedded section of videos from Nurture's youtube channel with hints and tips about wellbeing**

- This could allow more potential for views on the youtube channel, as the user doesn't even have to click to leave the website

## Testing

- Testing has been performed manually across each of the pages to ensure links work correctly. This includes the links in the header and footer, as well as the 'Request a brochure' button on the courses page
- On the 'Request a brochure' page, each of the form entries has been marked as required, so I have tested that the user can only submit the form once each of these is filled out. I have also submitted forms as a test to see that the data is sent correctly
- Chrome developer tools has been used to view the website across different viewport sizes, on different devices. This has enabled me to make the site reponsive, and design the elements so that they are user friendly regardless of screen size

## Bugs

- After deploying the website and reviewing with my mentor, I discovered the testimonial images were not displaying correctly as perfect circles on every screen size. We discovered it was an issue with padding interfering with the border-radius of each image. As a solution, each image was wrapped in a div, and the padding added to the div instead of the image element. The images now display correctly

## Validator Testing

- No errors were found in the HTML when testing with the official W3C Validator
![Screenshot of W3c Validator](/assets/images/html-validator-test.png)

- No errors were found in CSS when testing with the official Jigsaw validator
![Screenshot of Jigsaw validator](/assets/images/css-validator-test.png)

## Deployment

The site was deployed in Github, using the following steps:
- Under the repository name, click settings
- Under the code and automation section, click 'pages'
- Underneath 'build and deployment', under 'source', make sure 'Deploy from a branch' is selected
- Under the 'branch' section, select 'main' and 'root', and click 'save'

The live link is located here - [Nurture](https://katiecampbs.github.io/Nurture/)

## Credits

### Images
All images are licences for use and taken from [Unsplash](https://unsplash.com/license)

[Favicon](https://unsplash.com/photos/w1JE5duY62M?utm_source=unsplash&utm_medium=referral&utm_content=creditShareLink)

[Woman on mountain](https://unsplash.com/photos/z0nVqfrOqWA)

[Woman in dunes](https://unsplash.com/photos/4ydjTMLKdR4)

[Yoga 1](https://unsplash.com/photos/xce530fBHrk)

[Yoga 2](https://unsplash.com/photos/F2qh3yjz6Jk)

[Walking](https://unsplash.com/photos/RRZM3cwS1DU)

[Walking 2](https://unsplash.com/photos/mNGaaLeWEp0)

[Cbt therapy](https://unsplash.com/photos/LQ1t-8Ms5PY)

[Stop smoking](https://unsplash.com/photos/X00q3RXcyZ4)

[Testimonial image 1](https://unsplash.com/photos/IF9TK5Uy-KI)

[Testimonial image 2](https://unsplash.com/photos/KriecpTIWgY)

[Testimonial image 3](https://unsplash.com/photos/DlgFZG0MvaU)

[Water ](https://unsplash.com/photos/LCaKuYefLQk)

[Yoga 3](https://unsplash.com/photos/t1NEMSm1rgI)

[Beach woman](https://unsplash.com/photos/fk3XUcfTAvk)

[Teamwork](https://unsplash.com/photos/Zyx1bK9mqmA)

### Content

- Social media icons, and collapsed menu symbol are free from [Font Awesome](https://fontawesome.com/)

- Asterisk wildcard selector code taken from the Love Running Code Institute project

- Nav bar drop down with toggle is based on the menu for the Love Running Code Institute project

- Banner image on home page was created using code from [this](https://www.bannerbear.com/blog/how-to-overlay-text-on-an-image-in-html-and-css/#:~:text=Overlaying%20Text%20on%20an%20Image%20in%20HTML%20and%20CSS,-HTML&text=In%20the%20body%20section%2C%20create,and%20add%20your%20text%20inside.) article on Banner Bear

- Button for the 'Request a brochure' link on the courses page was created by amending code from [this](https://www.freecodecamp.org/news/html-button-link-code-examples-how-to-make-html-hyperlinks-using-the-href-attribute-on-tags/) article at FreeCodeCamp

- [Hashtagcolor Website](https://hashtagcolor.com/c5d3cf) was used for colour scheme inspiration

- [CSS-Tricks Website](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) - For help utilising flex box properties in CSS
- Medale Oluwafemi, my mentor, for reviewing the project and troubleshooting with me - [Github](https://github.com/omedale)
- Text content for courses created using [CHAT GPT](https://chat.openai.com/)

 


 
 