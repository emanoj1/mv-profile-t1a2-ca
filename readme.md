# Manoj's Portfolio

## Overview
This is a portfolio website designed as a part of the CA bootcamp course assignment (T1A2). Commenced on Saturday, 04/11/23, this is currently under development, and scheduled to be completed by Friday, 17/11/23. The assignment is due Sunday, 19/11/23.

## Design overview
This website is built using HTML and CSS.

## Components

### Header
The Header, which is the top part of the site, features only the profile picture of the owner, which also serves as the home button. Hence, it's a simple implementation using the following syntax:

```html
<header>
        <div class="profile-logo">
            <a href="./index.html">
            <img src="./images/Cyan Blue backdrop Manoj profile photo.png" alt="Manoj profile pic">
            </a>
        </div>
    </header>

```
### Footer
The footer styling for the homepage and subsequent pages are different. As I am after a minimalist design for the homepage, it features only the social links in the footer. All other pages (About, Experience, Skills and Contact) have a footer that displays both social media accounts, and a copy right info.

#### (a) Social Media implementation
```html
 <footer>
        
        <div class="socials">
            
            <a href="https://github.com" target="_blank">
                <img src="./images/github.png" alt="Github logo">
            </a>
            <a href="https://linkedin.com" target="_blank">
                <img src="./images/linkedin.png"  alt="Linkedin logo" >
            </a>
            <a href="https://twitter.com" target="_blank">
                <img src="./images/twitterx.png"  alt="Twitter logo" >
            </a>
            <a href="https://instagram.com" target="_blank">
                <img src="./images/instagram.png"  alt="Instagram logo" >
            </a>
            <a href="https://youtube.com" target="_blank">
                <img src="./images/youtube.png"  alt="YouTube logo" >
            </a>

        </div>
    </footer>
```
#### (b) Copyright info implementation
This is a basically straightforward text informing browsers about cookies and rights to the information on the site belongs to the owner of the site. This commands were placed within the above footer tags:

```html
    <div class="footer-copyright">
        <p>
            (C) 2023 Manoj Kumar | All rights Reserved.
        </p>
    </div>
```

## Nav Bar

## Main Body

### Homepage


### About page


### Skills page


### Contact page


### Blog page


## Responsiveness

Header & Footer responsiveness

Device responsiveness