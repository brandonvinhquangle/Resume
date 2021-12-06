# WebDev_Project
This "Final Project" is very different from your other end-of-module assessments. It is not timed and there are no questions to answer. Instead, you're going to build a super awesome professional-looking website based on your résumé and the bootstrap technique taught in the last chapter of this module. You can begin this project by using what you built in that chapter. Next, if you haven't already, you should implement all of the details of your résumé in that bootstrap-based website. Finally, make sure each of the requirements below is met in your finished website. Each requirement below will necessitate you to apply one or more principles taught in the WebDev module.

This project is completely open book and open web, yet closed person—as usual. There is also no time limit except it should be completed by the due date. So take your time and make this website look great! Also, if you are a graduate student taking this class, please notice the additional requirements at the end.

REQUIREMENTS:

General:
Pages: You must implement a bootstrap theme to create a personal website that includes the following separate pages:
an index page,
an "about me" page, and
a tableau.html page that is also separate from your other pages and is built completely from scratch that implements your own stylesheet and not any bootstrap theme (see details later).
Bootstrap Template: You can use either of the two bootstrap templates on the pre-approved list found below and available here: https://startbootstrap.com/. If you would like to use a different template, you need to get it approved by a TA. Some of the templates (not on the pre-approved list) keep the content all on one page using on-page anchors, whereas the two pre-approved templates use separate html files for everything. Even if you use a single-page template, you’ll still have to create an aboutme.html page and a tableau.html page (see requirements below) as separate files. This will probably be simplest if you use a multi-page template to start with (rather than a single-page template).
Pre-approved templates:
"Clean Blog" 
"Business Casual"
Hosting: The site must be hosted online (this criteria may vary* based on instructor and university, but assume it is the default requirement unless you hear otherwise from your instructor). Some universities offer some form of subsidized internet hosting. 
*This requirement is not applicable to Independent Studies students
Details:
For this assignment, your website MUST follow a specific folder structure: 
html folder: All html files (including those that came with your bootstrap theme) should be in one folder called "html" EXCEPT for the home page (named index.html)
images folder: All image files (including those that came with your bootstrap theme - if keeping any of those) should be in one folder called "images". This images folder should be located directly inside the home folder. If your bootstrap template comes with an "img" folder, please use this folder, but rename it to "images".
styles folder: Rename the CSS folder (currently in the root directory) to "styles" and add your own css files to that folder. DO NOT MOVE the buried css files (that are not already in the CSS folder).
PLEASE DO NOT MOVE ANY OTHER FOLDERS OR FILES (e.g., .js files) THAT CAME WITH THE BOOTSTRAP FOLDER!!!
Be aware that when you change the names and locations of files and folders, links between pages and to CSS, javascript, and image files will break, and you'll need to fix these references. 
Please make sure all folders and files exist within the root directory (home folder) or one of its subfolders (html, images, styles, js, vendor, and possibly a few others). When you submit your website, anything that was outside of that root directory will no longer be accessible to someone viewing your website.
Add a comment (so it’s only seen in the code) at the top of every html page that includes your name and the last date that you edited the file. 
Tabbing should be used appropriately to indent your code. This means everything should follow a standard nesting pattern (e.g. 2 spaces or a tab for every child element, sibling elements at the same level, etc). 
Every page must implement a custom background (this can be consistent or different across pages). 
Appropriate tab/window < title > for every page (e.g. Your Name - Home Page) 
All pages must have navigation links to all other pages. 
All images must include the alt attribute and use it properly (in case there are broken images or your pages are read by a screen reader).
There must be at least one external link (to outside your site) included somewhere on each page (e.g., link to BYU on homepage, link to something awesome on about me page, link to tableau.com on tableau page).
For the index and About Me page, overwrite a total of at least 4 style attributes (e.g. font-family, color, text-alignment, etc.) using at least 4 custom style definitions (e.g. p, H1, .bold, .italic) with custom styles defined in a custom, separate stylesheet. Do not directly edit the bootstrap css files and do not add your own styles to the existing css sheets. Make your own custom stylesheet called "mystyles.css" and link to it from these two pages. You will not receive points for styles we cannot find in the mystyles.css file.
There must be at least 2 on-page anchors somewhere in the site. 
There must be at least 3 images (total between first two pages) included separate from your background. 
There must be a résumé (either on the About Me page or index page or as a separate HTML file - not a pdf) with at least three sections (education, work experience, skills). 
There must be an ordered list in your résumé.
There must be an unordered list in your résumé.
There must be at least one embedded video that plays directly on your Homepage or About Me page. 
This is not hard to do, but we intentionally didn’t cover it. Why? The most important skill you can learn is how to find web-dev examples on Google. Search for “how to embed a YouTube video in HTML” on Google and you should be able to figure this out. Beware though that some videos cannot be embedded (it is an option when someone uploads a new video). So, if your video does not play, then choose a different video (probably from a different creator). 
Your contact information (fake phone and email info if you prefer) must be located somewhere on the About Me page.
There must be a separate tableau.html page that does not use or link to any of the bootstrap styles. Rather, you will create a custom stylesheet (named bootstyles.css) for this page and link to it. All styles for this tableau page must be contained in your custom stylesheet.
Implement three < div > elements that each use a custom style for positioning:
Navigation (header) 
expands and contracts horizontally as the page is resized
includes the intra-site navigation links here
Tableau (main body) 
expands and contracts vertically and horizontally as the page is resized
include the live Tableau dashboards here
Footer (at the bottom)
expands and contracts horizontally as the page is resized
include copyright, year, and your name, and any other info you want here (e.g., your social profile links)
There are working links back to all other pages on the site (they do not have to follow the same style as the other pages). 
There must be at least two custom styles, beyond the styles applied globally to the divs. You might use a custom style for captions and for footer content.
Implement the following on the Tableau < div >: 
Create and export four Tableau charts as live graphs that answer the following questions:
How are profits faring in each of the 50 states?
How has one of the highest-profit states fared for the last two years by profit, shown by month?
How are profits within that state doing for each product category?
For the most profitable category, forecast sales (pick a state that has enough data for a forecast) through November 2015
Write a caption (in HTML) for each chart that very briefly explains the chart (e.g. profits are strongest in Utah), and place it below the chart.
Errors: as we find errors (e.g., broken links, missing images), we will deduct points. We may also deduct points if you make it difficult to grade (e.g., didn't follow folder structure or naming conventions, or poor nesting). 
We also reserve the right to deduct points for clear aesthetic errors. These include, but are not limited to:
blue text on red background is atrocious
animated gif backgrounds are horrific
red text on gray background is so bad
There is a sample website included below as a pdf. This is not exactly what we are looking for (and therefore does not imply or constitute a 100% score), but it does illustrate the caliber (level of quality) we are expecting. Less than this will probably not earn full credit. More than this is welcome. 
We have also given the rubric that the TAs will be using to grade your projects. We advise you not to use it as a check-off list while you are doing your project, so you can use your creativity. Instead, use it as a check-list after you have completed the project. We will be grading strictly on aesthetics, if you use the rubric as a check-list we will be able to tell because students that do that don't tend to put a lot of effort into the physical look of their website.
Remember to avoid using copyrighted material on your websites. Here is a video to help: https://www.youtube.com/watch?v=_0Dw_ay--qY
