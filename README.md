# README.md

## The Monkees

This Project focuses on the Band The Monkees who were very successful in the 1960s.
The website has been developed to announce their "comeback" and publicize their intentions to perform at small venues such as weddings, christenings etc.

On the home section of the page there is a brief introduction with some intentionally placed song lyrics to catch the eye, and a link button straight to booking section.

Following sections give visitors a chance to listen to a select number of songs from their reportoire, view a small number of music videos and gain easy access to the bands youtube page, should users wish to see more.

The Website also has an image section so users can see who the band members are and lastly it features a booking request section so potential bookers can contact them easily if they like what they see and hear.

## UX

This Website is aimed at fans, new or existing and venue hosts who wish to book the band for a performance, be it a christmas party, themed night, wedding, prom night.
The website provides the means to do this. It also provides information on the bands availability for the current month.

Aswell as being able to listen to few songs written and performed by the band on the website, users also have access to a full catalogue of audio and video clips via links on the page.

There is an image gallery section which provides a small selection of images of the band members. And links to their verified social media pages so potential fans can follow the latest news and gossip.

* As the owner of a venue it is my job to book acts for our busy weekends, I would like to hear how an act looks and sounds before booking.
* As a new fan, I would like to listen to more of their songs and possibly book them for a 60s theme night.
* As the owner of a venue I would like to check their availabilty to see if when they are free to perform at my venue when i need them to.
* As a fan i would like access to their social media pages so i can follow them and keep updated on the latest news about them.

## Mockups

[Click Here]() to view a hand drawn mockup of the website

## Features

#### index.html

##### Home Section
* Fixed Navigation Bar at the top of the page containing social media links and page navigation 
  * All sections easily accessed at all times
  * Nav Bar also collapses into a burger icon once the page width reaches 768px or less
* Full page background image of the band
  * Eye catching for the user, doesn't look plain.
* Brief information on the band, Current intentions.
  * Kept short so as not to lose the interest of the user
* Button link to the booking section
  * To make users aware straight away they have the option to book the band

##### Audio Section
* Audio tracks
  * Allows users to listen to tracks by the band at the push of a button
* Full song library link
  * Directs the user to a full song library without having to search it

##### Video Section
* Music Videos
  * Allows users to watch a small selection of videos by pressing play
* Link to the bands youtube page should they wish to view more
  * Quick access to the bands youtube page without leaving the website

##### Image Section
* Images of the band members laid out within the section
  * Allows users to see what the band look like before booking
 
##### Booking Section
* Calender highlighting the dates the band are unavailable. Calender is not interactive
  * Gives users a quick glance at when the band is free to perform
* Booking Request Form
  * Allows users to submit contact information along with a textarea for users to personalise their request

### Features to implement at a later stage
##### JAVASCRIPT
###### Disclaimer
It is important to point out that although the collapse navigation menu uses Javascript, I am still unfamiliar with how javascript works.
The collapse menu idea and code was taken from the code institute tutorial on Styling Our Nav & Alert in module 3.

As I continue the course and learn more I would like to add
* An image carousel to tidy up the image section
* Update the booking request form to link up correctly
* Update the media sections, (audio and video) to have one media and a track list for the user to choose from

## Technologies Used
* HTML
  * Used to create the markup
* CSS
  * first-milestone-project/assets/css/styles.css
    * Used to style the elements of the HTML code
* https://stackpath.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css
  * Used to structure the website using the grid layout
* https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css
  * Used for the social link icons
* https://fonts.googleapis.com/css?family=Baloo+Chettan:100,200,300,400,500,600,700
  * Used for the text font of the website
* https://code.jquery.com/jquery-3.3.1.min.js
* https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js
  * Used for the collaspe nav menu
* https://cdnjs.cloudflare.com/ajax/libs/hover.css/2.3.1/css/hover-min.css
  * Used for the hover effect when hovering over links

## Validation
* An HTML [validator](https://www.htmlvalidator.com/) was used to check the code
* A CSS [checker](https://jigsaw.w3.org/css-validator/) was used to check the stylings
* Formatting
  * An HTML [formatter](An HTML formatter was used) was used

## Testing
For the initial testing I opened the website through the live preview changing the window size in responsive design mode, checking all links worked and that i could navigate 
my way through the website easily. 

Using dev tools i was able to fix any sections of the page that didn't look right or satisfy my liking.
I also asked my wife to test the website on her computer and mobile phone to gain feedback on how a first time user experiences the website.

## Bugs and Problems Encountered
* Links not clickable when the drop down menu was active
Because I had set the background color of the dropdown menu to transparent, I found when the collapse nav bar was down the book now button youtube and full song library links could not be clicked.
This is because the dropdown menu covers the full width of the page and the button was "underneath" the menu. This created the illusion that the button was broken or unclickable.
To eliminate the confusion on this I changed the background color so the drop down was more defined and should the links be behind the menu it would be obvious to the user why they can't be clicked.

## Deployment
To deploy my project I pushed my Cloud9 workspace to my Github repository named monkees-reunited via the command line. This was done each time edits were made to my code and I needed to save them. Please find my [GitHub](https://github.com/chrisrees85) here. To create my GitHub page I built it from the Master branch.

## Credits
#### Content
All assets where provided by the code institute apart from one video.
/assets/video/imabeliever.mp4 was downloaded from youtube. copyright info lifted from the video itself "Copyright Disclaimer Under Section 107 of the Copyright Act 1976, allowance is made for "fair use" for purposes such as criticism, comment, news reporting, teaching, scholarship, and research. Fair use is a use permitted by copyright statute that might otherwise be infringing. Non-profit, educational or personal use tips the balance in favor of fair use."

The links provided on the website are as follows
* Verified Twitter Account
  * https://twitter.com/themonkees?lang=en
* Verified Facebook Account
  * https://en-gb.facebook.com/TheMonkees/
* Official Youtube Page
  * https://www.youtube.com/user/themonkees
* Full song library
  * http://songs-tube.net/artist.php?id=10422

#### About us 
The about us paragrapgh is taken from [The Monkees wikipedia page](https://en.wikipedia.org/wiki/The_Monkees), the openeing sentence reads "The Monkees are an American rock and pop band originally active between 1966 and 1971, with reunion albums and tours in the decades that followed."


I used this and made a slight alteration to the opening line to "Hey Hey We're the Monkees, We are an American Rock and Pop Band originally active between 1966 and 1971, with reunion albums and tours in the decades that followed."

## Acknowledgements
* Thank you to my mentor Antonija Simic for the feedback she has given me throughout my project. She has been very helpful in giving me constructive critisism of my work and has given me confidence in my approach to website developement.
* Thank you to my Wife Amanda who is my biggest critic and "Unofficial Tester" of any websites and projects I work on.
* Inspiration for my one page with multiple sections design came from the code institute [sample project](https://code-institute-solutions.github.io/StudentExampleProjectGradeFive/) by Haley Schafer.