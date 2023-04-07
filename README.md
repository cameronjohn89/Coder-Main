###### Cameron Lawrence portfolio

## Overview and Purpose - This website is created to give information about me (Cameron Lawrence) and the services I provide, along with a blog and some projects I have been a part of or created as a Full-Stack Developer. The intended target audience is any potential client or anyone looking for help information about full-stack development.

### Links to associated accounts and presentation videos:
## Website URL: https://stunning-souffle-3319d1.netlify.app/
## Presentation Video: https://youtu.be/WlRIG1Ai4Rk
## Github Account: https://github.com/cameronjohn89

## Functionality/Features - This website will be similar to most other websites in that it will have a theme/layout across the entire site but will have some variations. Its features will be individal pages, links and blog posts linked in through either the navigation bar, the footer social media links or images linked to new pages or linking the user back to the homepage. The individual features that it will have are links to all my social media and work accounts and emails, a feature embedded spotify bar on my portfolio page, and submission form for my contact page.

## Sitemap - Sitemap can be found by following the link: ![Layout](/docs/Layout.png)

## Components - This website will have several big components or pages and each of those will contain sub components. Each page will have a header and footer that will be the same across the website. It will also contain a body which will differ depending on the page. In the header there is all the seperate HTML links to different pages - About, Services, Portfolio, Blog and Contact. Then there will be the footer which contains links to social media/work media accounts and an email address in the form of icons, and finally contract address and phone number.

#### CameronLawrence_T1A2 file - this is the main folder for my project. It contains the following ###'d folders and a single file which is README.md (what you are currently reading).

### Documents Folder (docs) - Docs contains all the images used in my slidedeck as well as screenshots that are to be used in my README.md

### PowerPoint/Slide Deck (ppt) - this contains the single powerpoint/slide deck for my assignment - it is in PDF format.

### Source Folder (src) - this is the root folder for all of my html, scss/css, folders and images to do with my website. In the folder is the main html document for my website (index. html). The folder inside .src are as follows -

## .docs - contains the mock CV file for my website.

## .images - contains all the images that have been used on my website

## .pages - contains all of the individual html files for my website - about., blog., blogpost., contact., portfolio., services..

## .styles - styles contains a further 3 folders - 

# components - this folder holds three scss documents footer. header. and utils. All of these documents provide styling for individaul elements of my website. The _header. is for the navigation bar and its embedded html.  _footer. contains the styling for the footer, including all my social media links and contact info. And the _utils. is a specific file for my single mixin styling rule. All fo these individual scss. files are to create fluidity and easy reading of my code. They can be used easily in any scss via the @import tag.

# defaults - like the above the defaults folder contains two individual scss styling files/rules. The _color. is so that I can designate colors to names and therefore can use the colors throughout without copy pasting or finding their value again. The _breakpoint. is a simple defaulty breakpoint rule for the entire html/scss. Both these files must be linked in to scss. files they are used on with the @import tag.

# pages - pages is where all my scss/css files for my entire pages are held. Each of the documents is a set of styling rules for the corresponding and samely named html. documents. They will mainly be the same but some will have slight variations and rule changes to effect the layout and viewability of the said pages. 


## index.html - this is the code for the homepage of my site. It will have a small bit of information (blurb) about me and an image, along with the default header and footer. Default layout for my pages is below.

### Pages - The pages folder (src/pages) contains the individual html files for each page except the index.html which will be in the root src folder. Below is the default layout of each page.


## Header - the header will be identical on each page. It will contain the title of my website and the navigation bar. 

```html
<header>
        <div>
            <a class="name" href="./index.html">
                <span class="cameron-text">Coding With Cameron</span>
            </a>
        </div>
        <nav class="nav-items">
            <a href="./pages/about.html">About</a>
            <a href="./pages/services.html">Services</a>
            <a href="./pages/portfolio.html">Portfolio</a>
            <a href="./pages/blog.html">Blog</a>
            <a href="./pages/contact.html">Contact</a>
        </nav>
    </header>
```

### Main - the main will hold the main content to be displayed on each page. It is default in the sense of the elements inside of the section. This is unlike the header and footer which both are identical on every page.
```html
<main>
        <section>
            <div class="details">
                <h1>WELCOME TO MY WEBSITE
                    <div class="logo-image">
                        <a href="./index.html">
                            <img src="./images/Logo.png" alt="Cameron Lawrence Logo" width="400px" height="400
                                ">
                        </a>
                </h1>
                <p>
                    As a creative entrepreneur, I am excited to share my passion for coding, photography, and art
                    with
                    you. I have always been fascinated by the intersection of these disciplines and how they can be
                    combined to create unique and innovative products.
                </p>
            </div>
        </section>
    </main>
```

### Footer - Footer like the header is identical on each page. It has social media links, contact number and address. Here is the code that we have:
```html
<footer>
        <div class="social-media">
            <a href="https://www.github.com" target="_blank">
                <i class="fa-brands fa-github"></i>
            </a>
            <a href="https://www.linkedin.com" target="_blank">
                <i class="fa-brands fa-linkedin"></i>
            </a>
            <a href="https://www.instagram.com" target="_blank">
                <i class="fa-brands fa-square-instagram"></i>
            </a>
            <a href="https://www.messenger.com/" target="_blank">
                <i class="fa-brands fa-facebook-messenger"></i>
            </a>
            <a href="https://www.facebook.com/" target="_blank">
                <i class="fa-brands fa-square-facebook"></i>
            </a>
            <a href="mailto:14256@coderacademy.edu.au" target="_blank">
                <i class="fa-solid fa-envelope"></i>
            </a>
        </div>
        <div class="info">
            <p>Contact: 0000000000</p>
            <p>Address: 1 Street St, Suburb</p>
        </div>
    </footer>
```
## Further pages below will outline the html page and what it consists of and how it will appear in my website. Each page contains the defaut layout as previous shown for their headers and footers and will only vary slightly in the main section of the file.

# about. - This html file contains all of the information displayed on my About page. It is intented to give the user some general information about me as well as information about my education, experience, skillset and a link to my CV. 

# blog. - This html file contains a set of images and associated headers. Each individual header will have a name and date and is intended to be linked to blog posts. These blog posts can be general blogs about my life, coding and development and even personal life things. The layout is that of boxes in a column down the centre of the page, meaning the newest blog will appear at the top.

# blogpost. - This is a specific html file for the single blogpost that I have created. It contains the default website page layout and is filled with "Lorem" text.

# contact. - This html file is a simple webform where users can input the name, contact details and a message that they can send with a submit button.

# portfolio. - This html file contains all the information for my portfolio. There is several divisions each with an image (related to the job or project) and a header text which names what the said project was or is. The layout is that of boxes in a column down the centre of the page.

# services. - This services html file contains information about all of the services that I offer. They could further be linked to associated projects or jobs that I have completed that are associated with the said kind of service. The layout is that of boxes in a column down the centre of the page, this is mainly to keep form with the rest of the website. It also maintains readability across the website.

### The tech stack which I have used in the production of this site is HTML > SCSS/CSS > Github > Netlify it can be seen again here in the linked image ![Tech Stack](/docs/Tech%20Stack.png)

### The layout for my page was very simple and started out with the intention of each page being built off of the same default layout. With the only changes coming in the main section of the page and the blogpost where I chose to use a block color to improve readability. Please see the screenshots below of each page in their web and mobile/tablet form.

# Index - Web: ![Home](/docs/Home.png) Mobile/tablet: ![Home Mobile](/docs/Home%20Mobile.png)

# About - Web: ![About](/docs/About.png) Mobile/tablet: ![About Mobile](/docs/About%20Mobile.png)

# Portfolio - Web: ![Portfolio](/docs/Portfolio.png) Mobile/tablet: ![Portfolio Mobile](/docs/Portfolio%20Mobile.png)

# Services - Web: ![Services](/docs/Services.png) Mobile/tablet: ![Services Mobile](/docs/Services%20Mobile.png)

# Blog - Web: ![Blog](/docs/Blog.png) Mobile/tablet: ![Blog Mobile](/docs/Blog%20Mobile.png)

# Blog Post - Web: ![Blog Post](/docs/Blog%20Post.png) Mobile/tablet: ![Blog Post Mobile](/docs/Blog%20Post%20Mobile.png)

# Contact - Web: ![Contact](/docs/Contact.png) Mobile/tablet: ![Contact Mobile](/docs/Contact%20Mobile.png)


##### That is the end of my README.md thank you for reading and enjoy.