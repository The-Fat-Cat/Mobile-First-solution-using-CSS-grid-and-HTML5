# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### Screenshot

![finished-results](https://user-images.githubusercontent.com/26780054/161859089-14f8e1e0-9dd6-42ef-a6e3-7a98442fdb09.png)


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process
1- I first downloaded all of the media and resources I would be needing to build the project.

2- I opened some websites I know I have been using a lot lately in my journey of learning. This was going to help prep my mind for thinking about some of the code I was going to be using and it also helps with motivation and planning. 

3- I thoroughly read through instructions and tips and looked at everything I was provided with. This helped me see where I was starting and how the pieces all were going to connect so my mind can already start visualizing it coming together. 

4- Then I opened the final design I was supposed to achieve and jotted down some patterns I noticed in the styling of the elements on a piece of paper. I also made notes about how the current HTML was layed out and how I needed to end up layed out. This helped me see how I could lay out my code to be more organized by simplifying the elements and styles down. This also helps my mind see the changes it needed to make to the given resources. 

5- I started out by adding a break between the  top and bottom text as I noticed that they were in a single line.

6- I then undid that because I realized I had 3 elements I was going to positioning in my webpage. 

7- I added the image to my page using the img element and src as the source code for that image. 

8- I proceeded to put my image and the top text and bottom text into seperate div containers to make 3 in total (not counting the last div for attribution as I commented that out). 

9- I gave my div elements different class names so that I could style them individually later. I also added the alt property to my img element for more accessability.

10- In my style block the first thing I added was the backgorund color to my html sheet. I copied the hsl code provided in the style.md.

11- Then I proceeded to style the body element as I knew this white box would be the one that contains the picture and the other text. If you look back at the html code you can see that the body contians all 3. 

12- I added first a height and width using and approximation based on the given widths in the style guide. It said on desktop is was created for 1440px so I divided that by 4 (so I visualized my screen divided into 4 sections) and chose that as my width and then experimented going back and forth around there until it resembled the desktop preview provided. And for my height I saw it was arectangle and thus couldn't be the same as my width but a bit more so I also eyeballed that using the desktop preview as a guide. 

13- I then proceeded to position it using margin to add space between the box and the edges of the page. I put auto for the right and left as I wanted it to be in the center but I wanted the top and bottom to be different since the box seemed to be in the top half of the screen. 

14- I then noticed that the corners were rounded on both the outside box and the image and I knew from my studies this was the border-radius (but one of my resources helped me understand which one made it rounded). 

15- Next I started editing the image and I first gave it a box and height based on the height and width of the body. I approximated that the width would be below 300px and the height would be around half the size of the white box container. 

16- I also gave it a border-radius similar to the body. I wanted to position the image inside the box in the center of it but I noticed it was inline along with the text and so I needed it to break out of the line so I used the display property to make it a block and then choose the margins to position it. 

17- I added some padding to add space between the image and the top of the box. 

18- I then proceeded to style the texts. For both of them I needed the font-family to be Outift, so I used the link element to do that. I followed the link to google fonts and copied the embedidng code to add it to the head of the html code. Once that was added I just chose the font-family that I needed to choose. I did the same for both texts and the specified the font-weight differently for each one.

19- I then added the colors of the text provided to me by the style.md file. I noticed the top text had a boxlike space between the image and the rest of the box and text so I added some padding until it was sort of centered. That still didn't compeltely resemble the results I was mimicking so I also added the text align property to center it. I also added the font size for both of the texts that were provided by the style guide. 

20- To style the other text I aligned the text in the center and added some padding to palce it where I wanted it to be. I noticed the text wasn't indented like the first one so I added text-indent to give the first line some indent to match the results I needed to copy.


### Built with

- Adobe Dreamweaver
- Basic HTML5 and CSS

### What I learned
I learned during this coding session that there are several ways to position elements on a page but that they do affect each other and the responsivenes of the grid when you resize the page.
I also learned about margin and padding and how px is a bit confusing considering that you could use different numbers to achieve the same results. That's something I need to spend more time working on so I can fully understand it. 
I learned about prepping before coding so when I start styling and moving things around my code stays organzied. 

### Continued development
Some concepts I'm still unfamiliar with are positioning and margin and padding. While I know what they are supposed to do I'm still learning the scope of their ussage and the most apprpriate way to use them.
I'll spend some time researching what different scenarios each of them might be used in. I also know that for margin and padding you can us pixels percentage and em but I'm still fairly new to that so I'll study on that as well. 

### Useful resources

-[ https://www.w3schools.com/cssref/pr_class_display.asp ] This one was useful for learning about the display property. 
-[https://tympanus.net/codrops/css_reference/ ] This website is very useful for having CSS properties at a glance that way if you can't remember them they are all laid out for you. 
-[https://www.w3schools.com/css/css_boxmodel.asp ]This one was useful for learning about the CSS model and seeing how the properties affect the boxes you're styling. 
-[https://www.w3schools.com/css/css_positioning.asp ] This one was useful for learning about the position proerty and it's different values but I do recommend other sources for fully learning in what different scenarios each of the values should be used. 

## Author

- Frontend Mentor - [@The-Fat-Cat](https://www.frontendmentor.io/profile/The-Fat-Cat)

## Acknowledgments

I had no help for this challenge but I did receive feedback from a software engineer I live with, Spencer, who is more familiar with coding and all the properties. 
