# Letter Match

_Javascript Essentials Project Portfolio - Code Institute_

View deployed site [here.](https://queenisabaer.github.io/letter-match/)

Letter Match is a game for kindergarten and preschool children. Its main goal is to help children to learn the alphabet and get to know the capital letters better. The game was inspired by an Instagram post by [create25printables](https://www.instagram.com/p/Cv2fjIxuwVR/?igshid=MTc4MmM1YmI2Ng%3D%3D&epik=dj0yJnU9XzBHMi1OY2sya2JpMS03RV9JVENYbWdhS0FzcldUOTgmcD0wJm49RGJFR2Q1d2Vxc0ZtLU1fdkJQa21SQSZ0PUFBQUFBR1djR0ZV). 

![Responsive Mockup](documentation/readme/am-i-responsive.png)

## Table of contents

- [User Experience (UX)](#user-experience)
- [Design](#design)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Testing](#testing)
- [Deployment](#deployment)
- [Credits](#credits)

## User Experience (UX)

### User stories

Goals for:

- **First time visitor:**

- **Returning visitor:**

- **Frequent user:**
  

## Design

- **Imagery:**
  The background image was discovered when searching for a letter image, it perfectly fits the theme that letters need to be searched. In addition, it was very colorful and perfect to generate the colors for the game. 
- **Colour Scheme:**
  The colors were determined with the pipette function of the website coloors. In general, the colors are very cheerful and colorful, as it is a game for small children. <br>

  <details>
  <summary> Color palette </summary>
  <br>

  ![Color pallette 1](documentation/readme/letter-match-coloors-1.png)
  ![Color palette 2](documentation/readme/letter-match-coloors-2.png)
</details>

- **Typography:**
  [Annie use your teleskope](https://fonts.google.com/specimen/Annie+Use+Your+Telescope) was selected for text content. It's a cute font that is easy to read by children and yet has a certain lightness. 
  [Barlow Semi Condensed](https://fonts.google.com/specimen/Barlow+Semi+Condensed) is an easy-to-read, clear font that is simple to grasp, so it was used for the instructions. 
  The font [Are you serious](https://fonts.google.com/specimen/Are+You+Serious) was selected for the logo. It represents the fun and joy the game should bring. 
  > Are You Serious doesn't take itself seriously at all. This is a fun playful font with a very joyful spirit. _(Google Fonts)_

### Wireframes

<details>
<summary> Welcome page before game starts </summary>
<br>

![Mobile wireframe](documentation/wireframes/letter-match-start-mobile.png)
![Desktop wireframe](documentation/wireframes/letter-match-start-desktop.png)

</details>

<details>
<summary> Instructions </summary>
<br>

![Mobile wireframe](documentation/wireframes/letter-match-start-mobile-instructions.png)
![Desktop wireframe](documentation/wireframes/letter-match-start-desktop-instructions.png)

</details>

<details>
<summary> Game </summary>
<br>

![Mobile wireframe](documentation/wireframes/letter-match-game-mobile.png)
![Desktop wireframe](documentation/wireframes/letter-match-game-desktop.png)

</details>

<details>
<summary> Correct answer </summary>
<br>
Unfortunately, due to lack of time, I did not manage to set the background colors for the letter row correctly for wrong or correct answers.<br>

![Mobile wireframe](documentation/wireframes/letter-match-game-mobil-correct.png)
![Desktop wireframe](documentation/wireframes/letter-match-game-desktop-correct.png)

</details>

<details>
<summary> Wrong answer </summary>
<br>
During coding I decided to give the child another try to find the correct answer, so that he/she/they could improve his/her/their skill. Therefore, displaying the correct letter was no longer necessary.<br>

![Mobile wireframe](documentation/wireframes/letter-match-game-mobil-wrong.png)
![Desktop wireframe](documentation/wireframes/letter-match-game-mobil-wrong.png)

</details>

<details>
<summary> Game ending </summary>
<br>

![Mobile wireframe](documentation/wireframes/letter-match-end-mobile.png)
![Desktop wireframe](documentation/wireframes/letter-match-end-desktop.png)

</details>

## Features

### Existing Features

All the pages were created with a mobile first approach and are made responsive. To ensure that the layout of the pages remains consistent even on very large screens, the game body has been given a maximum width and a margin on both sides.  
In the game body, the logo is centered at the top. It works as a link to reset the game to the welcome screen.<br> 
![Logo](documentation/readme/letter-match-logo-header.png)<br>

<details>
<summary> Footer </summary>
<br>

The footer stays on the bottom of the game body and features clickable social media icons and a link to the british council - learn the alphabet website. All links on the footer are opened in a new tab. On tablets or larger screens,the text and the social media icons should appear in one row.<br>
![Footer mobile version](documentation/readme/letter-match-footer-mobile.png)<br>
![Footer desktop version](documentation/readme/letter-match-footer-desktop.png)<br>

</details>

<details>
<summary> Instructions </summary>
<br>

The instructions modal opens and closes, when you click the instructions button. You can also close the modal with the escape key or by clicking on the x on the right corner.<br>
![Footer mobile version](documentation/readme)<br>
![Footer desktop version](documentation/readme)<br>

</details>

<details>
<summary> Name input </summary>
<br>

In the welcome/start game panel or when you load the page, you will be asked for your name. If you enter a name with numbers in it, the game doesn't start and a warning is shown. I decided not to limit the use of special characters, so as not to exclude children with extraordinary names, like the children of Elon Musk. However, it is possible not to specify a name at all, then a placeholder (Abcedarian) is displayed as name. You can submit your name input by clicking on the start game button or with the enter key. This will start the game as well.<br>
![Name input field](documentation/readme)<br>
![Name input with numbers](documentation/readme)<br>
![Name inside the game](documentation/readme)<br>

</details>



### Features, which I would like to implement in the future

- I would like to create different levels of difficulty for the game. For example, that you can choose whether you want to match only uppercase letters or whether you compare between uppercase and lowercase letters. 
- I would like to allow a selection where you can set the time (e.g. 20/30/45/60 seconds).
- Add a highscore. 
- Adjust the background color of the lettercards in the letter row according to the correct or wrong answer.
- Add audio content to the instruction modal (Instructions to be read out loud). 

## Technologies Used

- [HTML5](https://en.wikipedia.org/wiki/HTML5)
- [CSS3](https://en.wikipedia.org/wiki/Cascading_Style_Sheets)
- [JavaScript](https://en.wikipedia.org/wiki/JavaScript) 
- [Google Fonts](https://fonts.google.com/) was used to import fonts into the style.css.
- [Font Awesome](https://fontawesome.com/) was used to add icons.
- [Git](https://git-scm.com/) was used for version control by utilizing the Gitpod terminal to commit to Git and Push to GitHub.
- [GitHub](https://github.com/) was used to save and store the files for the website.
- [Balsamiq](https://balsamiq.com/) was used to design the wireframes.
- [Coloors](https://coolors.co/image-picker) was used to create the color scheme.
- [iLoveIMG](https://www.iloveimg.com/) was used to cropp and resize the images.
- [Pixelied](https://pixelied.com/) was used to convert images from jpg to webp
- [imgtools](https://www.imgtools.co/) was used to resize webp images
- [CSS Gradient](https://cssgradient.io/) was used to create the gradient background of the instruction button
- [Am I Responsive](https://ui.dev/amiresponsive) was used to display the website on different devices.
- [beautifier](https://beautifier.io/) to beautify the code
- [Pexels](https://www.pexels.com/de-de/) was used to search and load the background image
- [Favicon.io](https://favicon.io/favicon-generator/) was used to create the favicon

## Testing

1. **Validator Testing**

- **[HTML Validator](https://validator.w3.org/)**

  - result for index.html<br>
  In the first attempt I was shown a warning regarding the section where my instruction modal is located.
    ![HTML result index with error](documentation/readme/html-validator-index-error-letter-match.png)<br>
   After changing this section into a div no more warnings or errors were detected.     
    ![HTML final result](documentation/readme/html-validator-letter-match.png)
   
I also checked the page in the validator via text-input, and likewise no errors were detected in this way. All I got was an information to avoid trailing slashes in void elements.

- **[CSS Validator](https://jigsaw.w3.org/css-validator/)**
   - result for styles.css <br>
     ![CSS result](documentation/readme/css-validator-result.png)
     The warning is due to import of the Google fonts.
- **[JSHint](https://jshint.com/)**
  - result for sript.js <br>
  On the first attempt there were some warnings about missing semicolons. After adding this to my javascript, no further warnings or errors were detected.
    ![JSHint result](documentation/readme/jshint-letter-match.png)

2. **Lighthouse Test** <br>
   To measure the website against performance, accessibility, SEO and best practice I used [Lighthouse](https://chromewebstore.google.com/detail/lighthouse/blipmdconlkpinefehnmjammfjpmpbjk?hl=de).<br>
   - result for index.html<br>
   First, it gave a warning that the form element did not have the correct associated label. 
   ![Lighthouse with warning for accessibility](documentation/readme/lighthouse-accessibility-letter-match.png)
   After adjusting the label for the name input, I could increase the accessibility to 100.
   ![Lighthouse with warning for accessibility](documentation/readme/lighthouse-letter-match.png)<br>
   This is the result for desktop device:
   ![Lighthouse with warning for accessibility](documentation/readme/lighthouse-letter-match-desktop.png)


3. **Manual testing** <br>
To ensure the pages are responsive, I used the Google Chrome developer tools.

| **Test** | **Test Description** | **Expected Outcome** | **Result**|
|:---|:---|:---|:---|
| Header - Logo | Click on the logo to return welcome/name panel | Clicking on the logo, even in the game, will return you to the main page | Pass |
| Footer - arrangement | Enlarge the view of the page to at least 768px to show the footer in one line | On tablets or bigger screen the footer should be presented in one line | Pass |
| Footer - British Council | Click on the British Council text and a new tab with the website opens | After clicking on the text for the british council, a new tab to the website of the British Council should open | Pass|
| Footer - Social Media icons | Click on the logo of Facebook or Instagram and a new tab with Facebook page or Instagram page opens | After clicking on the logo of Facebook it should open a new tab with the Facebook page, and after clicking on the Instagram logo, Instagram should open in a new tab as well | Pass |
| Start panel - name input | Name input field should be in focus | After the DOM is loaded the name input field should be in focus and ready to use(mouse pointer inside the field) | Pass |
| Start panel - name input | Enter a name with numbers | If a name is entered with a number, an error message should be displayed and the game should not start. | Pass |
| Start panel - name input | Enter a valid name in the name input field and click the start game button or press the Enter key. | If a valid name was entered and the start game button is clicked or the Enter key is pressed, the game should start. | Pass |
| Start panel - name input | Don’t type a name in the name field or just use a space as name and click the start game button or press the Enter key. | If no name was entered or only spaces and the start game button is clicked or the Enter key is pressed, the game should start and in the name area of the game a placeholder("Abeccderian") should be visible  | Pass |


4. **Browser Compatibility**<br>
   The tests were conducted using the following browsers:

- 

5. **Bugs**

- 

## Deployment

This site is deployed using GitHub Pages. To deploy it from its GitHub repository to GitHub Pages, I took the following steps:
1. Log in (or sign up) to GitHub.
2. Navigate to the repository for this project by selecting [*queenisabaer/isbaner-vineyard*](https://github.com/queenisabaer/isbaner-vineyard)
3. Click the *Settings* tab above the repository 
4. In the left-hand menu, select *Pages*
5. In the section **"Build and deployment"** under *Source* select *Deploy from a branch* 
6. In the section **"Build and deployment"** under *Branch* select in the first area *main* and in the second *root*
7. Click the *Save* Button<br>
After refreshing the settings site for this repository above the **"Build and deployment"** section, you will see the GitHub Pages area with the link to the [view of the live site](https://queenisabaer.github.io/isbaner-vineyard/)

- Forking this GitHub repository
1.  Log in to GitHub.
2.  Navigate to the repository for this project by selecting [*queenisabaer/isbaner-vineyard*](https://github.com/queenisabaer/isbaner-vineyard)
3. Click at the top of the repository on the **Fork** button on the right side

- Clone this repository
1.  Log in to GitHub.
2.  Navigate to the repository for this project by selecting [*queenisabaer/isbaner-vineyard*](https://github.com/queenisabaer/isbaner-vineyard)
3. In the top right corner, click on the green *Code* button
4. Copy the HTTPS URL in the tab *Local*
5. Go to the code editor of your choice and open the terminal
5. Type `git clone` and paste the URL you copied into your terminal
6. Press the enter key

## Credits

### Content

- The background image is from Magda Ehlers and was found on the [Pexels](https://www.pexels.com/de-de/foto/kunst-muster-textur-abstrakt-4116706/) website.
-  by [7ESL](https://7esl.com/well-done/)

### Code

- The instructions modal was created with the help of the tutorial by [Viktor Eke from freeCodeCamp](https://www.freecodecamp.org/news/how-to-build-a-modal-with-javascript/)
- To center the instructions modal I used an explanation from [Stack Overflow](https://stackoverflow.com/questions/8508275/how-to-center-a-position-absolute-element).
- To create the countdown I used the instruction by [James McDowell on Stack Overflow](https://stackoverflow.com/questions/31106189/create-a-simple-10-second-countdown)
- I found a great explanation for setting the restart button in the [Treehouse Community](https://teamtreehouse.com/community/any-one-know-how-to-make-a-restart-button)
- How to add and remove a class after a certain time, was found at [ITSourceCode.com] (https://itsourcecode.com/javascript-tutorial/how-to-add-and-remove-class-after-5-seconds-in-javascript/).
- The functions to check whether the right or wrong letter is clicked have been inspired by [CodingNepal] (https://www.codingnepalweb.com/build-memory-card-game-html-javascript/) among others. 
- To understand more about the concepts of JavaScript I used the udemy course: [The complete 2023 Web Development Bootcamp by Dr. Angela Yu](https://www.udemy.com/course/the-complete-web-development-bootcamp/)
- The following websites were used as a source of knowledge: <br>
  - [Google](www.google.com)
  - [mdn](https://developer.mozilla.org/en-US/)
  - [W3C](https://www.w3.org/)
  - [W3schools](https://www.w3schools.com/)
  - [DevDocs](https://devdocs.io/)
  - [Stack Overflow](https://stackoverflow.com/)
  - Slack Community

### Media

- Icons on the footer, the game and for links were taken from [Font Awesome](https://fontawesome.com/)
- The fonts were imported from [Google Fonts](https://fonts.google.com/)

### ReadMe

- A big thank you to [Kera Cudmore](https://github.com/kera-cudmore) and all of her tips on what makes a good README.

### Acknowledgments

- I would like to thank my wonderful mentor Brian Macheria for his numerous tips and great assistance during the creation of this project. In particular, his guidance for the letter functions and the corresponding event listeners.
- Furthermore I would like to thank Niclas Hugdahl who helped me on Slack to get the right twist for my name input function and setting the checkAnswer/correctAnswer function. 

**This is for educational use.**