# Individual Project 1
## WAPH-Web Application Programming and Hacking

## Instructor: Dr. Phu Phung

## Student
![Headshot](images/headshot.jpg "Headshot")

**Name**: Cole Duffy

**Email**: duffycf@mail.uc.edu

### Overview
This project essentially the first "real" thing we have been asked to build which has introduced us to developing websites that are useful for us and others which is extremely helpful. I learned about a new lightweight framework called PureCSS which was pretty interesting to mess around with. I also fought with CORS to get this thing done which was an adventure to say the least.

[Individual Project 1](https://github.com/duffycf-uc/duffycf-uc.github.io)
[Individual Project 1 Site](https://duffycf-uc.github.io)

### General Requirements
#### Task 1: Creating the personal site
First, I started by creating the repository out in gitlab, making sure I used .gitlab.io as a suffix in order to make it a website and ensuring it was public in order to be a website. Next, I put together the required waph.html page that is rather simple and is really just some high level information. Next, I slowly copied over parts of my resume into index.html (after creating it) and formatted it as HTML.

### Non-Technical Requirements
#### Task 3: Framework/Lib
I selected PureCSS and found a basic template they have for a blog that I built from after I tweaked it a bit, it was actually pretty cool and can be seen in index-style.css but some parts are bundled in the PureCSS framework.

#### Task 4: FlagCounter
I used Flag Counter as recommended, essentially I just copied and pasted what was generated into my website.

### Technical Requirements
I used jQuery for most of the API integration stuff, I also wrote some very basic show and hide functions for my email address, for the required JSCookie welcome message I used a third party library called js-cookie which made it really easy to work with cookies which was nice. Beyond that, I made sure to integrate a public API for graphics (this is where I ran into the CORS issue and decided to just do a Dogs API). All scripts are inline because I wanted to do it that way. I also added a random math facts request using jQuery as my final thing to write.