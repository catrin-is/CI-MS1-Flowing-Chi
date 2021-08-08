# Testing

## Code validators

[HTML Validator](https://validator.w3.org/)

 - Home Page

![No errors or warnings shown](https://i.ibb.co/Vt2DRLk/Screenshot-2021-08-08-1.png)

No errors or warnings shown 

 - About us Page
 
![enter image description here](https://i.ibb.co/YdwbJQ8/Screenshot-2021-08-08-2.png)

1 error was detected, I had left an empty ID attribute on the img element. 
This was rectified by the removal of the ID attribute. 
Warning message was also detected due to the section wrapping the img element did not have a h2-h6 element. 
This was rectified by changed the section in question to a div element instead. 

As shown below when re-entered the code into the validator no errors or warning messages are shown.

![enter image description here](https://i.ibb.co/1RpC385/Screenshot-2021-08-08-3.png)

 - Gallery
 
 ![enter image description here](https://i.ibb.co/pdNhW2d/Screenshot-2021-08-08-4.png)

No errors or warnings shown

 - Classes
 
 ![enter image description here](https://i.ibb.co/Z28Hxv6/Screenshot-2021-08-08-5.png)

2 error messages were detected 

 1. The frameborder attribute is obsolete - this was rectified by the changing to style attribute with a value of border:none
 2. Duplicate *ID* attribute were detected - this was rectified by changing the ID to a Class attribute
 
 As shown below when re-entered the code into the validator no errors or warning messages are shown.

![enter image description here](https://i.ibb.co/2yh9SP3/Screenshot-2021-08-08-6.png)

 - Contact Us Page
 
 ![enter image description here](https://i.ibb.co/Xk8347W/Screenshot-2021-08-08-at-7.png)

4 errors were detected 

 1. Stray end tag section this was removed
 2. Bad value width attribute - iframe element
 3. bad value height attribute - iframe element - both width and height were removed from the html code and styled instead in CSS
 4. Duplicate id attribute for email - rectified by removing 1
 
 As shown below when re-entered the code into the validator no errors or warning messages are shown.

![enter image description here](https://i.ibb.co/wSz2S9V/Screenshot-2021-08-08-8.png)

[CSS Validator](https://jigsaw.w3.org/css-validator/)

![enter image description here](https://i.ibb.co/Vv91k6q/Screenshot-2021-08-08-at-11-35-27.png)

To rectify the error within the CSS code I changed the *flex: row wrap;* to *flex-flow: row wrap;* for div .health-benefits-title and div.health-benefit 

As shown below when re-entered the code into the validator no errors or warning messages are shown.
![enter image description here](https://i.ibb.co/h9b8FBk/Screenshot-2021-08-08-at-11-41-40.png)

## Testing User Stories

  **As a potential customer I want a brief description on the services available as I’m looking to enhance my health and wellbeing.**
 
 On the home page users can get a brief description on what Tai Chi and Qigong is about 
 About-us page goes into more depth about the instructors background and also invites users to explore further through an useful link 

 
 **As a new site visitor, I want a simple and easy way to navigate through the website.**

The user can easily navigate their way through the website by using the drop-down menu button that's simple and clear 
 
 **As a returning customer I want up to date classes and price information.**
 
 The class times and location are easily accessible by using the drop-down menu. The class times, location and price information is formatted and styled in a clear and simple way
 
 **As a site editor I want a simple way of updating information such as offers and class information to ensure customers are informed**
 
 Information such as class time, location and prices can easily be updated as well as other information across the site
 
 **As a potential customer I want to read reviews from others that have used the service**

Users can view testimonial from past customers on the home page 
 
 **As a potential or returning customer I want an easy an accessible way of viewing contact information**

Contact information can be viewed in the contact-us page, this is accessible through the drop-down menu

## Browser Compatibility

[Google Chrome](https://www.google.co.uk/)
No bugs found - tested through DevTools 

[Safari](https://www.apple.com/uk/safari/) website responded well

[Firefox](https://www.mozilla.org/en-GB/firefox/new/) no issues when viewing the website on this browser

[Microsoft Edge](https://www.microsoft.com/en-us/edge) Also no issues when viewing the website through this browser 

## Responsive Testing 

Responsiveness of the website was tested on [Am I Responsive](http://ami.responsivedesign.is/)

![enter image description here](https://i.ibb.co/VMMFBzS/Screenshot-2021-08-08-at-23-07-29.png)



## Bugs

 - My main issue was when I initially developed the header and footer
   with *bootstrap*. I had a lot of problems with layout and making the
   design responsive across all media screens. This was quickly solved
   with the use of *Flexbox*
   
   Another Bug I had was making the nav bar responsive. I decided to
   solve this with a simple and user friendly drop down menu that's seen
   on all media screens. The main reason to opt for the drop down menu
   on larger screens was simple and clean design on the header. 
   
   Hero image did not scale down the quality of the image on mobile
   devices was poor, to solve this added a media query to hide the image
   
   Had the same issue with the demonstration video so decided to ad a
   media query to also hide on mobile devices 
   
   When browsing the contact us page on a mobile devise the map was too
   big and this created a white space on the right hand side of the
   screen. This was solved by changing the width and height value from
   px to % to allow for flexibility across all screens. Media query was
   also added to the margin on both mobile and ipad screens
