# Technology in our life

The Technology in our life website is a page for people addicted to technology, people who are getting away from personal relationships in favor of virtual ones.
The idea was to create a simple and straightforward page that did not need a vast content, considering that the focus is to reduce the use of technology, however it was possible to apply practically all the HTML and CSS content of the course.

Users can find information to learn more about Tech in our life: Introduction with a video by Jaron Lanier for TED, talking about technology in our lives, About us, with information about what we offer, sign up form and session times and our contacts. Our focus is to help people balance their digital and in-person lives. 
![Responsice Mockup](https://github.com/caflavio/tech-life/blob/main/assets/images/readme/mockup.png)


## Features

### Existing Features

- __Navigation Bar__

    - The navigation bar is responsive and includes links to the About Us section, Sign Up section and Contact section.
    - This section will allow the user to navigate and switch to the desired session.
![Nav Bar](https://github.com/caflavio/tech-life/blob/main/assets/images/readme/nav.png)

- __The intro page image__

    - The Intro page includes a photograph and superimposed text to allow the user to understand the purpose of the page.
    - On the side, a sentence from Jaron Lainer (http://www.jaronlanier.com/gadgetwebresources.html) is placed, to make the user reflect if he really needs help.
    - Below the sentence was added a video of Jaron Lainer speaking to TED Talk.
    - The idea of the content is to make an impact on the user and draw attention to the need to talk about it.
![Intro](https://github.com/caflavio/tech-life/blob/main/assets/images/readme/intro.png)

- __About Us__

    - The About Us section will allow the user to see a little more about how we can help.
    - He will also see the topics of the lectures that can help in this moment of self-reflection.
    - This should encourage the user to consider participating in individual sessions or with small groups. 
![About Us](https://github.com/caflavio/tech-life/blob/main/assets/images/readme/aboutus.png)

- __Sign Up__

    - This session allows the user to sign up for a session or lecture to start their fight against technology addiction.
    - You will be required to provide your full name and email address.
    - The user will be able to see when and where the meetings will take place, the duration of each session or speech. 
![Sign Up](https://github.com/caflavio/tech-life/blob/main/assets/images/readme/form.png)

- __Contact__

    - For the footer section a phone number has been added to remind the user that we can still talk by voice, instead of just writing text messages.
    - Added links to relevant social media sites.
    - The links will open in a new tab to allow easy navigation for the user.
    - A WhatsApp icon was added where the user can open a conversation requesting help for the number informed, the idea and create connection mechanisms with the user to strengthen the relationship.
    - The user will also be able to follow all the content available on social networks in order to have a better understanding of the project's idea and stay connected through social media.
![Contact](https://github.com/caflavio/tech-life/blob/main/assets/images/readme/contact.png)


### Features Left to Implement

- Create a new page with videos of speeches.
- Have virtual sessions integrated into the page for users who still don't want to have direct contact with other people.
- Automate the scheduling process to send an invitation directly to the user with the location and date.


### Validator Testing 

- I have tested the webpage in different devices: iPhone 7/7Plus/12, Motorola: G8, Samsumng, browsers: Chrome, Firefox and Safari and share the link with family and friends.
- HTML
  - No errors were returned when passing through the official [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fcaflavio.github.io%2Ftech-life%2F)
- CSS
  - No errors were found when passing through the official [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fcaflavio.github.io%2Ftech-life%2F&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)
- Accessibility
  - I confirmed that the colors and fonts chosen are easy to read and accessible by running lighthouse in devtools
![Accessibility](https://github.com/caflavio/tech-life/blob/main/assets/images/readme/lighthouse.png)


### Bugs

  - __Solved bugs__

- I used the link provided by youtube to publish the video, but I realized that it came with the predefined width and height, so I wasn't able to adjust the video: ("iframe width="560" height="315"), I removed the  width and height from the iframe and adjusted the size in css.
- I was having trouble centering the text in the About Us section, because when I checked the code on smaller screens it was not centered.
    Before:    
    left: 40%;
    top: 10%;
    padding: 40px;
    
    After:
    left: 50%;
    top: 10%;
    transform: translateX(-50%);
- The intro session wasn't getting the same size as the other sessions because it used two div, so the frame was with the full size of the screen, I made two changes to solve the problem:
    Before:
    #tech-addiction {width: 1920px;}
    After (A max-width was included to make the session with the size of the others and the width was changed to 100%):
    #tech-addiction {width: 100%; max-width: 1924px;}


## Deployment

- The site was deployed to GitHub pages. The steps to deploy are as follows:
    - In GitHub, navigate to my https://github.com/caflavio/tech-life repository and clicked Settings.  
    - In the GitHub repository Settings tab, clicked in Pages in the left Menu
    - From the source section drop-down menu, select the Master Branch
    - Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment. 

The live link can be found here - https://caflavio.github.io/tech-life/index.html


## Credits

I would like to thank my mentor who helped me with some tips when I was stuck creating the responsive part of the site.
Also to my cousin Patrick who answered some questions in the development of the site. 


### Content   

- The validation form were used from [Code Intitute](https://formdump.codeinstitute.net/)
- The font in Intro was used from [Google](https://fonts.googleapis.com/)
- The icons in the footer were taken from [Font Awesome](https://fontawesome.com/)


### Media

- The photos used on the page are from [Pexels](https://www.pexels.com/)
- The photos used on the page were converted to WebP on [OnlineConvert](https://www.online-convert.com)
- The video used on the Intro section is from [Youtube - TED Channel](https://www.youtube.com/channel/UCAuUUnT6oDeKwE6v1NGQxug)
- The text used on the Intro section is from [Jaron Lanier](http://www.jaronlanier.com/gadgetwebresources.html)