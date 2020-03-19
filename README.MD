## Sign up and login form
### Tools & Design:

 - font awesome for icons
 - "Montserrat" font. It can be found here [https://fonts.google.com/specimen/Montserrat](https://fonts.google.com/specimen/Montserrat)
 - CSS Flexbox for layout
 - https://unsplash.com/ used for images

### Helpful Links
- [http://vclever.com/blog/how-to-style-a-heading-with-horizontal-lines-either-side-using-css/](http://vclever.com/blog/how-to-style-a-heading-with-horizontal-lines-either-side-using-css/) how to add horizontal lines between titles.
- [https://unsplash.com/](https://unsplash.com/) where I get my images (free)
- [http://cssdeck.com/labs/16-box-shadows-to-save-your-time](http://cssdeck.com/labs/16-box-shadows-to-save-your-time) nice box shadows options
- [https://bryanlrobinson.com/blog/how-to-css-after-elements-for-background-overlays/](https://bryanlrobinson.com/blog/how-to-css-after-elements-for-background-overlays/) how I made my stars image a background overlay to my main image.

### About the project
Starting this project I originally suppose to do the sign up form, but I thought doing a login form as well would be great practice.

### Sign up form
I designed this page with mobile first in mind. I again, was going off the design images from the "design" folder. The gradient background is just a simple image I found on unsplash. However, the stars background is a free png image with a transparency background I found online (It has a lot more other images with transparency backgrounds ) to achieve a "stars in the sky" effect. Since I was familiar with putting icons inside inputs from the previous project. i decided to create a box shadow to the inputs to make them pop out more. I did some googling to find out how to style a horizontal rule and apply a background gradient to it. I also decided to color to the placeholder text. 

### Login form
For this page the styles are similar to the sign up page, only difference is that there are only two fields. I had a slight challenge with getting the fancy lines between the "or" text. I had to take a different approach since this couldn't be achieved using `<hr>`tags. 
Therefore, I went for good ole' google and did some research on how to achieve this, which consist of using `::before`and `::after` pseudo classes. The third and last lines were just horizontal rules.
