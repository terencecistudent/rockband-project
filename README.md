# The Monkees

This website is for fans or potential fans of The Monkees who wish to know a bit more about this band
and to also make bookings to perform as special events.  There are five pages on this website which are: 
Home, Shows, Media, About and Contact.

Each page has a callout section and a subscribe section.  The reason behind this is to show that 
The Monkees are availabe for bookings which has a link to the Contact page, and it is simple to subscribe 
to get the latest news or offers about the band.


## UX

I have tried to create an easy to follow website with each of the sections well spaced out.  The website
is for fans or potential fans and it is important that the layout is clear and the font is big for the
user to read.  I have kept the font family the same all the way through for consistency and have used a small
variety of font sizes such as headings so that users would not get confused.  

I have used Bootstrap 4 as a wireframe to create an effective layout for users to navigate around.  The navigational
bar sits at the top with a dark background and white writing so it is easily seen.  This includes the navigational
links to each page.  Whatever page is active, on the navigational bar, the name of that page should be coloured 
white compared to the other four pages which are a grey colour.  The footer includes social icon links to the 
Facebook, Twitter and YouTube pages.

#### User Stories:

##### Implemented:

* As a user, I would like to click on the 'Click Here' link in the callout section which takes me to the Contact page.  
  __End User Goal:__ Hyperlink used which is linked to the Contact page.  
  __End Business Goal:__ Easy navigation.
  __Acceptance Criteria:__ Example, <a href="contact.html"> Click Here </a>  
  __Measuremeant Of Success:__ _________ .

* As a user, I would like to control the volume when listening to an audio clip.  
  __End User Goal:__ Control volume on the audio element.  
  __End Business Goal:__ Effective running website.
  __Acceptance Criteria:__ Audio clip to run using audio element and to change volume level.  
  __Measuremeant Of Success:__ _________ .

* As a user, I would like to click on the social media icons to take me to their social media pages.  
  __End User Goal:__ Hyperlinks used within icon images directing them the social media pages.  
  __End Business Goal:__ Social media fan base growth.  
  __Acceptance Criteria:__ Example, <a href="https/facebook.com" target="_blank"> Facebook Icon </a>  
  __Measuremeant Of Success:__ _________ .

* As a user, I would like to view the music video on full screen.  
  __End User Goal:__ Allow music video to go full screen.  
  __End Business Goal:__ Better user satisfaction.  
  __Acceptance Criteria:__ Music video to function properly and allow fullscreen.
  __Measuremeant Of Success:__ _________ .


##### Not Implemented:

* As a user, I would like more audio clips for a better user experience.  
  __End User Goal:__ The ability to listen to more songs.  
  __End Business Goal:__ Better user satisfaction.
  __Acceptance Criteria:__ Adding more audio clips to the website.  
  __Measuremeant Of Success:__ _________ .

* As a user, I would like there to be a table showing the available dates and times to make a booking.
  __End User Goal:__ Create a database showing availabe dates and times.  
  __End Business Goal:__ Potentially more bookings.  
  __Acceptance Criteria:__ Available every day after 18.00hrs.
  __Measuremeant Of Success:__ _________ .

* As a user, I would like The Monkees to be on more social media platforms such as Instagram as I don't use Facebook or Twitter.
  __End User Goal:__ Create more social icon links to the band pages.  
  __End Business Goal:__  Bigger target audience.
  __Acceptance Criteria:__ The Monkees to be active on a wider range of social medias.  
  __Measuremeant Of Success:__ _________ .

* As a user, I would like to watch more videos of the band for a better user experience.
  __End User Goal:__ Add more video links to the website.  
  __End Business Goal:__ Better user satisfaction.
  __Acceptance Criteria:__ Permission from video providers such as YouTube to implement videos on this website. 
  __Measuremeant Of Success:__ _________ .


## Features 

#### Existing Features:

* **Feature 1:** Hyperlinks take users straight to the hyperlinked page when clicked on.
* **Feature 2:** Validation allow users to subscribe or contact the band by filling out a form.
* **Feature 3:** Tables allow users to view information in an effective and simple layout.
* **Feature 4:** Social media icons take users straight to the social media page.
* **Feature 5:** Responsive which allows users to view the website across mobile, tablets or desktops.
* **Feature 6:** Easily Customisable which allows the developer to add additional content on a webpage.
* **Feature 7:** Components of Bootstrap which make it pleasing to the eye of users giving them an exciting experience.

#### Features Left To Implement:

* **Feature 1:** Dropdown Navbar Link when more pages are included and this keeps navigation easy for the user.


## Technologies Used:

* **Bootstrap 4:** Wireframe used to create a simple and effective website for users of all ages.
* **Cloud 9:** Command Line Interface to execute code and store files on Git.
* **HTML:** Language used to enhance layout and design of website.
* **CSS:** Language used to style elements in style sheet. 


## Testing:

1. Navigation:
* Click on Home or any other page link on navbar.
* You will appear on the clicked page.

2. Audio Clips: 
* Try to press play or pause to start or stop the audio.
* Try to change the minute the song is at.
* Try to change the volume control.

3. Music Video:
* Try to press play or pause to start or stop the video.
* Try to change the minute the video is at.
* Try to change the volume control.
* Try to view video in fullscreen.

4. **Click Here** link in the callout section:
* Try to hover over link to change colour.
* Try to click on link to bring you to the contact page. 

5. Subscribe Section: 
* Try to submit the empty field and verify that a required field message appears.
* Try to submit without **@** and verify that an error message appears.
* Try to submit with only **@** and verify error message appears.
* Try to submit either **example@** or **@example** and verify error message appears.
* Try to submit **example@example** which goes into empty database and page refreshed.

6. Contact Form: 
* Try to submit the empty fields and verify that a required field message appears.
* Try to submit empty First Name and Last Name fields and verify a required field message appears.
* Try to submit without **@** and verify that an error message appears.
* Try to submit with only **@** and verify error message appears.
* Try to submit either **example@** or **@example** and verify error message appears.
* Try to submit **example@example** which goes into empty database and page refreshed.
* Try to enter text in Phone Number field, no letter should be allowed.
* Try to enter numbers in Phone Number field, data will accept.
* Try to submit empty Message field and verify a required field message appears.
* Try to submit all correct data in fields to submit properly.

7. Social Media Icons:
* Try to hover over social media to change colour.
* Try and click social media icons to be directed to their website.

8. Sub-headings in each page e.g. Music in Media page:
* Try and hover over links to change colour.
* Try and click on links to be directed to those pages.


## Deployment:

I used Cloud 9 to deploy my website onto the internet.
I have used Git to save my files which I then pushed into Github.

There are a few commands to doing this which are:

1. First we create a repository by using: 
Example: git init

2. This is now waiting to be committed into Github.
Example: git add index.html

3. The code is then committed which includes leaving a message. 
Example: git commit -m "index.html inital commit"

4. Set a new remote by adding:
Example: git remote add origin [URL]

5. This pushes changes from the local repository into a remote repository.


## Credits:

**Font Icons**
* Font Icons used throughout the website where from: https://fontawesome.com/

**Media**
* The audio clips, images and videos where from a github repository by Code Institute.

**Credits**
* I was inspired to create this website by Code Institute.