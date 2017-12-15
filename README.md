# CSS Week4 Solo SASS Project

### This is a personal portfolio page using all of the skills I've acquired and practiced in the last four weeks

#### By _Cat Janowitz_

## Description

This portfolio page is a scroll-down site that features stylized blocks of info about me.  I'm using the site loflorecords.com as inspiration. The nav bar will be responsive; the upper-left logo will be fixed-position; the hero will have bigger and smaller versions.  The main content "about me blocks" will be arranged in a mosaic style.




## SASS that I'm using:
| Term | Description | Implementation |
| :-------------     | :------------- | :------------- |
| **SASS partials** | Partials are .scss files containing code snippets that will be compiled into final CSS code. Uses the 7-1 file structure -- 7 folders with partials, 1 main.scss input file | Examples of how we're using partials include a folder that contains layout items specifically, nav, hero, intro, etc. Each file has element-specific styling |
| **grid system** | Flexbox!| I will utilize Flexbox when designing this portfolio, aiming for most if not all of my elements created using Flex |
| **SASS @extend** | @extend is a SASS tool that allows you to share sets of CSS properties from one selector to another | I will use this for a clearfix on parent containers in our document.  |
| **SASS @mixin** | @mixin is a directive which allows you to reuse css rules through your site.| I will use @mixins for border radius. For example @mixin border-radius ($radius) {border-radius: $radius} (after you create this mixin you can you use it as a css declaration with @include border-radius(5px))|
|**SASS variables**| variables are a way to store information that you want to reuse throughout your stylesheet | I plan on using a couple of variables for this site, mainly $color variables.|
| **Nesting** | SASS nesting places additional child selectors within parent selectors; it is a good way to organize CSS. | I am using nested selectors to style many elements |


## Setup/Installation Requirements

* access computer with internet connection and a browser
* go to github.com and search "thatcat13"
* browse thatcat13's repositories to find 'product' repository
* click on 'portfolio-week9' repository and copy URL link that directs to this specific repository
* access computer terminal and make sure you are at the top directory
* in terminal, after $ prompt, type in: git clone {-don't type the following, just do the following: paste URL into terminal after git clone-} then hit enter
* complete 'portfolio-week9' repository should be available at top directory (although desktop is suggested)
* browse folder of repository to find 'index.html'; drag file directly into browser OR in browser click file open and access 'index.html'


* or access gh-pages assigned to this project:
* thatcat13.github.io/portfolio-week9

## Support and Contact Details
* For any questions please reach out to any of our team members below. Here are email and GitHub account details for each:

  * [Cat Janowitz](https://github.com/thatcat13) - thatcat13@gmail.com


## Technologies Used
* SASS
* CSS
* HTML


### License
* Font Awesome: License: SIL OFL 1.1



Copyright (c) 2017 **Cat Janowitz**
