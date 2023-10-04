**Portfolio Website for Q1 '23** 

Portfolio projects will likely include: 

* StructuRight Portal MVP redesign: Case Study and clickable Prototype (desktop only)
* StructuRight iOS app design: Case Study, and clickable Prototype
* Custom Design System for StructuRight
* Juniata.edu case study: Case Study, Wireframe Prototype and link to site


**Project Brief:** My portfolio needs a refresh. This simple portfolio website will highlight my front-end dev and UX/UI design skills and experience. The project will meet the standards for semantic HTML and WCAG Level AA accessibility. The mobile first layout will be styled with flexbox and grid and use media queries for the following viewport sizes: 
* Mobile: Less than 490px
* Tablet, laptop and desktop: Greater than 491px


**Project Goals:** The site will allow users to...
1) Quickly see a few examples of my projects.
2) Obtain a high-level view of my lean startup and project management experience.
3) Easily take the next steps to get in touch with me.

**Features:** The three required features project will use.
1) Create an accessible, responsive menu with CSS, HTML and JavaScript.
2) Obtain PageSpeed Insights with scores of 80 or better in all four categories.
3) Run an accessibility check, fix any issues and document process in the final README.md.

**Accessibility Check:** 
The initial accessibility check happened in the Page Speed checker on Mar 21, 2023. Link to the original results:

Mobile: https://bit.ly/42I3JH0
* Performance: 92
* Accessibility: 97
* Best Practices: 92
* SEO: 83

Desktop: https://bit.ly/3ZGBtC9
* Performance: 100
* Accessibility: 98
* Best Practices: 92
* SEO: 80

1) Under the **Performance** category, there is a recurring issue with Cummulative Layout Shift. If you analyze the page multiple times, you will see different values for this test. I know it is caused by the "case study cards" changing from a single column layout on mobile to a side-by-side layout on 491px+. I got this idea from the starbucks website (I checked; they consistently flunked the Cumulative Layout Shift test by a large margin). You win some and you lose some, I guess. The other big ding was page load speed. I followed the recommendation to use .webp instead of .jpg for the images, and shrunk the size of each image. There was also a hit from the site cache lasting only 10 seconds, which will be remedied on the server when site goes live.

2) **Accessibility** seemed pretty good (Following the guidelines from Arizona State University IT Department (https://bit.ly/3TS21yI)). Actually, many of those suggestions were overkill; the HTML checker recommended I strip out about half of those, which I did. 

3) Under the **Best Practices** category there were some issues with main.js not loading properly. I thought this was an issue from using Github Pages only loading static files, but it turned out that javascript wasn’t loading because I was pointing it to the file folder root and not the local root. Brian Dickens showed me the error, I corrected it and all works as expected now. Thanks Brian.

4) SEO was pretty easey to fix. I was missing a "meta description" for the site and the site was not crawlable by search bots. Added two tags in Head which fixed it.

**Page Speed Results After Fixes**: March 30, 2023

Mobile: https://bit.ly/40L2x42
* Performance: 90
* Accessibility: 100
* Best Practices: 100
* SEO: 100

Desktop: https://bit.ly/3ZvnKhk
* Performance: 100
* Accessibility: 100
* Best Practices: 100
* SEO: 100


**HTML Validator**: Mar 30, 2023
Validated: https://bit.ly/3KiuDy8


**Materials:** Links to Figma prototypes, content wireframes and content spreadsheet, typography and colors used in portfolio. (No UX research on this one, but will be included in all projects in the finished portfolio).

* Large Computer prototype and content wireframe: https://bit.ly/41pgW71
* Small Mobile prototype and content wireframe: https://bit.ly/41EMupN  
* Content wireframes and content spreadsheet located in "research" directory in GitHub repo: https://github.com/leoosborne/Portfolio


**Special Instructions**

* The Javascript Hamburger Menu uses an @media screen (max-width: 490px), which is too small to see by resizing the screen on a desktop view. Resize to 490 or below in the dev tools to see the menu functionality. 

