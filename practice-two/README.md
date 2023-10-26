
# LaslesVPN Landing Page

## Overview

- This document is for plain training for HTML / CSS.
## Design

- This is the design of the site : [link](https://www.figma.com/file/y4g7B9BSJsuPkI101iyF5E/FREEBIES-Landingpage-LaslesVPN-(Community)?node-id=0%3A1&mode=dev)

## Team Size 

- 1 Dev

***Start date:*** 13/10/2023


***Timeline:*** 7 days (13/10/2023 - 23/10/2023)

***Actual:*** 8 days

***Target:***

- Apply knowledge to responsive practice one design
- Used media queries for popular screen size
    
## Documents
- [Plan Training HTML/CSS](https://docs.google.com/document/d/1hyZKoIRZaJqHnqBHsTxxtCYw0OTPXrZ3bTxcM0TrViE/edit?usp=sharing)
- [Estimate](https://docs.google.com/document/d/1hN62pUtlZYH6v510XsXxWlhQk0irXWdublbdArG5bBQ/edit?usp=sharing)
​
## Deploy:
[Here](https://html-css-training-fw5q7ebij-linhnguyen2606s-projects.vercel.app/)

## Folder structure ##
practice-two

## Breakpoint ##
- Mobile: min-width: 335px and max-width: 576px
- Tablet: max-width: 992px
- Large screen: min-width: 992px

~~~
|-- src
    |-- assets
        |-- fonts
            |-- ...
        |-- images
            |-- ...
    |-- style
        |-- base
            |-- global.scss
            |-- index.scss
            |-- reset.scss
            |-- typography.scss
        |-- components
            |-- button.scss
            |-- index.scss
            |-- navbar.scss
            |-- typography.scss
        |-- layout
            |-- container.scss
            |-- footer.scss
            |-- header.scss
            |-- index.scss
        |-- pages
            |-- home
                |--customer.scss
                |--feature.scss
                |--footer.scss
                |--hero.scss
                |--intro.scss
                |--network.scss
                |--plan.scss
                |--sponsor.scss
                |--subscribe.scss
            |-- index.scss
        |-- utilities
            |-- index.scss
            |-- mixin.scss
            |-- variables.scss
        |-- vendors
            |-- custom.scss
            |-- index.scss
        |-- index.scss
    |-- index.html
    |-- index.js
|-- .gitignore
|-- .sassrc
|-- package-lock.json
|-- package.json
|-- README.md
~~~


## Getting started:
- Step 01: Clone repository with HTTPS:
~~~
git clone https://github.com/LinhNguyen2606/html-css-training.git
~~~

- Step 02: Move to the folder that just cloned in your computer:
~~~
cd html-css-training
~~~

- Step 03: Checkout branch:
~~~
git checkout feature/practice-two
~~~

- Step 04: Next open the folder practice-two
~~~
cd practice-two
~~~

- Step 05: Open the terminal and type:
~~~
npm install
~~~

- Step 06: Finally run with:
~~~
npm start
~~~