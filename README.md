# Neville Sexton - Author Website

Code Institute - Milestone Project1: User Centric frontend Development.

My project is an author website. It serves two functions: firstly to act 
as shop window to potential readers, displaying books, videos and information
relevant to the author, and secondly, as a landing page whereby the author can grow
an email subscriber list based on a free book offering when email details are supplied. 
It's designed to be responsive on all devices. 


## Deployment

The site is hosted on GithHub Pages at https://github.com/nevdevtrev/project1-author-site.git
Should you wish to clone this simply use git clone https://github.com/nevdevtrev/project1-author-site.git 
in your terminal. 

You can see the published live site [here] (https://nevdevtrev.github.io/project1-author-site/)

## Technologies

1. HTML
2. Boostrap
3. Flexbox Grid System
4. CSS3
5. JavaScript


## Design - UX

The design concept for this site was essentially this - 'clean and simple'. The purpose for the site was two-fold: firstly
as a shop window to the authors catalogue of books and contact information, but equally as a funnel for building up
a readership emailing list. An author's lifeblood is their readers so being able to compile an ever-growing contact 
database of their readers/fans is an essential tool for any author's marketing toolbox. To facilitate higher 
subscriber turnover I placed a simple email-input bootstrap toast component on the initial landing page to the website. This is closeable,
and ignorable, for any exisiting subscribers but is front-of-house for all new visitors to the site. 

The site is designed as a mobile first single, multi-sectioned, page with top navigation bar links (collapsible on small devices) to books, events, media,
blog, contact and author information. Sections are reached through a smooth scrollspy effect, again keeping the user
experience as simple and pleasant as possible. I've also utilised a fixed footer for quick access to author social links.

### Design Features

The core features implemented were built upont the flexbox grid layout system and include: bootstrap toast input, bootstrap popovers 
(only on larger screens) and scrollspy - with the addition of a java based smooth scrolling feature. 

### Future Features

The main expansion of the current site will be to build and link an SQL database backend to the current email subscription toast. Also the 
intention will be to modify the current book presentations into a carousel as more and more books become availble for sale. 

## Testing

Testing was ongoing throughout the build and design process. Many iteratrions of layout were tried and often sidelined as difficulties and 
changing preferences were met. I had some real fundamental issues with nested classes and section structuring, particularly with bleeding 
content from divs when viewing on different portals. This was a highly frustrating recurrence which reduced my progress to a snail's pace,
but ultimately proved surmountable. Finally grasping just how divs, containers and their content interoperate pushed me past those initial 
frustrations, allowing me to get on with design. Using Chrome developer tool proved instrumental for this transition.

The toast used for email subscriptions has been tested for the input components, namely that the email added is (a)correct format and (b) 
not blank, and that the final checkbox selection is made. If not adhered to an error message will inform the user. 

Book links implemented with target="_blank" have been tested for new tab opening, bringing the user to the respective websites without
losing the authorsite.  

Popover links have been tested so that they appear on top (data-placement="top") and that they close (data-trigger="focus") when clicked 
outside the element. 

The final layout was tested across multiple devices (using the developer's tool (chrome and firefox)) and on a variety of browsers. 
Media queries have been used where necessary for various layout tweeks and preferences for larger screens. In some cases these have been 
used so that certain columns and divs are only visible on larger screens, while in other circumstances they're used for simple 
formatting variations. 


## Academic Pedigree

This project was completed as part of a quarterly module for The Code Institute Diploma in Full Stack Software Development.

## References/Credits

### General Content

All of the content supply and design aspects were implemented and brought together by myself using a combination of The Code Instite course material, 
www.w3schools.com and www.getbootstrap.com. The only aspects indirectly added pertain to the javascript functionality which I've yet to 
undertake as part of The Code Institute Diploma.

### Pictures

The underlying pictures used for the landing page website background and blog section were obtained from https://www.pexels.com 
and https://unsplash.com. However these were heavily modified by myself using the image manipulation capabilities of MS Powerpoint
to build these into the layered and tailored final product seen on the website.

The book covers for the self-published books were designed by me using 'free license images' found through google, and subsequently
modified again through MS Powerpoint.

### Videos

The video documentary from ABC TV was supplied directly to me from the TV Network which I subsequently added to my youtube channel.

The personal tribute video to my beautiful son Craig was created by me using defacto microsoft video software and added to my youtube 
channel.

### Acknowledgements

* Smooth scrollspy effect tutorial, which utilises JavaScript was found at csstricks.com
* www.w3schools.com and www.getbootstrap.com were referenced heavily to bring this together
* I had looked at several author websites as inspiration, including http://www.neilgaiman.com. These were a good beacon but ultimately
  I could only emulate inline with my current level of capability. I tried...

