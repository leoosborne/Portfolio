**Portfolio Website for Q1 '23** 

Portfolio projects will likely include: 

* StructuRight Portal MVP redesign: Case Study and clickable Prototype (desktop only)
* StructuRight iOS app design: Case Study, and clickable Prototype
* Custom Design System for StructuRight
* Juniata.edu case study: Case Study, Wireframe Prototype and link to site


**Project Brief:** My portfolio needs a refresh. This simple portfolio website will highlight my front-end dev and UX/UL design skills and experience. The project will meet the standards for semantic HTML and WCAG Level AA accessibility. The mobile first layout will be styled with flexbox and grid and use media queries for the following viewport sizes: 
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

1) Under the **Performance** category, there is a recurring issue with Cummulative Layout Shift. If you analyze the page multiple times, you will see different values for this test. I know it is caused by the "case study cards" changing from a single column layout on mobile to a side-by-side layout on 491px+. I got this idea from the starbucks website (I checked; they consistently flunked the Cumulative Layout Shift test by a large margin). You win some and you lose some, I guess. The other big ding was page load speed. I followed the recommendation to use .webp instead of .jpg for the images, and shrunk the size of each image. 

2) **Accessibility** seemed pretty good (Following the guidelines from Arizona State University IT Department (https://bit.ly/3TS21yI)). Actually, many of those suggestions were overkill; the HTML checker recommended I strip out about half of those, which I did. 

3) Under the **Best Practices** category there were some issues with the server. Biggest problem on performance comes from using Github Pages: javascript doesn’t load as it is a static page. The other ding was the site cache lasting only 10 seconds. Both of these issues will be resolved when site goes live. 

4) SEO was pretty easey to fix. I was missing a "meta description" for the site and the site was not crawlable by search bots. Added two tags in Head which fixed it.

**Page Speed Results After Fixes**: March 29 2023

Mobile: https://bit.ly/40pU5HH
* Performance: 99
* Accessibility: 100
* Best Practices: 92
* SEO: 98

Desktop: https://bit.ly/40qJiNk
* Performance: 100
* Accessibility: 100
* Best Practices: 92
* SEO: 100

**Materials:** Links to Figma prototypes, content wireframes and content spreadsheet, typography and colors used in portfolio. (No UX research on this one, but will be included in all projects in the finished portfolio).

* Large Computer prototype and content wireframe: https://bit.ly/41pgW71
* Small Mobile prototype and content wireframe: https://bit.ly/41EMupN  
* Content wireframes and content spreadsheet located in "research" directory in GitHub repo: https://github.com/leoosborne/Portfolio


**Accessibility Check:** 
Mobile: 
https://pagespeed.web.dev/analysis/https-leoosborne-github-io-Portfolio/5eu2mrqjzt?form_factor=mobile

Desktop:
https://pagespeed.web.dev/analysis/https-leoosborne-github-io-Portfolio/5eu2mrqjzt?form_factor=desktop

**HTML Validator**

https://validator.w3.org/nu/?doc=https%3A%2F%2Fleoosborne.github.io%2FPortfolio%2F

**Special Instructions**
* Github Pages site: https://leoosborne.github.io/Portfolio/. * (Note 1: Hamburger menu doesn't work as the main.js doesn't load (static files only)). * (Note 2: PDF was not dislaying on Github Pages site, so it has been commented out for now. Will uncomment once the case studies are complete and site in launched on leocast.com).

* The Javascript Hamburger Menu uses an @media screen (max-width: 490px), which is too small to see by resizing the screen on a desktop view. Resize to 490 or below in the dev tools to see the menu functionality. 

