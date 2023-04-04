#Cameron Lawrence portfolio

## Overview - This website is created to give information about Cameron Lawrence and the services he provides, along with a blog and some projects he has already been a part of or created as a Full-Stack Developer.

## Components - This website will have several big components or pages and each of those will contain sub components. Each page will have a header and footer that will be the same across the website. It will also contain a body which will differ depending on the page. In the header there is all the seperate HTML links to different pages - About, Services, Portfolio, Blog and Contact. Then there will be the footer which contains links to social media/work media accounts and an email address in the form of icons, and finally contract address and phone number.

### Pages - The pages folder in the root src contains the individual html files for each page. Below is the default layout of each page.

### Header

'''html
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
'''

### Main



### Footer - Footer has social media links, contact number and address. Here is the code that we have:
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