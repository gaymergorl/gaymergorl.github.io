# gaymergorl.github.io

This is my first webpage on Github.
Module name: Web Site Development ND00CC68-3001
Information on assignment :

HTML Hands-on Assignment 1
📝 Option 1
Assignment: “Spotlight on a Favorite Book or Movie”.

A screenshot showing an example of the expected HTML webpage output is provided below at the end of the page
 

📝 Option 2
You may also develop a website based on your own idea but it MUST have the required structure described in this hands on assignment instructions. 

 

🎯 Objective
Create a single HTML page that showcases your favorite book or movie using all of the specified HTML elements, tags, and attributes.

📌 Instructions
You will design a web page that introduces and celebrates a book or movie you love. Your webpage is required to have the following structure and content provided below.


✅ Required Structure and Content
Each of the listed HTML elements and tags MUST be demonstrated at least once in your code. You may use them multiple times if it makes sense for your design. You can add additional elements and tags that you see fit for creating your website as long as the minimum requirements are met.

1. HTML Boilerplate
Use <!DOCTYPE html> to declare HTML5.
Use <html>, <head>, and <body> to structure your page.
Inside <head>, include a <title> with the name of your book or movie.

2. Header Section
Use <h1> for the main title.
Use <h2> to <h6> for subheadings like:

Author/Director
Genre
Year Released
Awards
Fun Fact
Use a <div> to group the header content (e.g., <div class="header">).

3. Introduction Paragraph
Use a <p> to describe the plot or theme.
Use <em> to italicize the title.
Use <strong> to emphasize a key point.
Use <br> to break lines for readability.
Use <span> to highlight a specific word or phrase.
Add an id attribute (e.g., id="intro") to this section for internal linking.

4. Image Section
Use an <img> tag to display a poster or cover.
Use the src attribute for the image path.
Use the alt attribute to describe the image.
Add a title attribute to show a tooltip on hover.

Example:

<img src="cover.jpg" alt="Book Cover" title="Official Cover">

5. Character or Scene List
Use a <ul> for a list of characters.
Use an <ol> for a list of memorable scenes.
Use <li> for each item.

6. Video Section
Use <iframe> or <video> tag to embed a video into website:

 

🟥➡️ Option 1: <iframe> tag for external video sources (YouTube or Vimeo...).

Use the <iframe> tag to embed videos from external sources such as YouTube or Vimeo. Include the following attributes: src, width, height, and controls.

 

Example 1: width and height adjustments added.

<iframe width="540" height="260" src="https://www.youtube.com/embed/ok-plXXHlWw?si=y8xomXaiIS0XWMJl"></iframe>

 

Example 2: adding allowfullscreen for enabling full-screen.

<iframe width="540" height="260" src="https://www.youtube.com/embed/ok-plXXHlWw?si=y8xomXaiIS0XWMJl" allowfullscreen></iframe>

 

NOTE! When embedding a YouTube video, make sure to use the embed link, not the regular video URL.
You can get the embed link by clicking the Share button below the video and then selecting Embed.

 

Links:

HTML YouTube VideosLinks to an external site.
HTML <iframe> TagLinks to an external site.
HTML IframesLinks to an external site.
 

🟥➡️ Option 2: <video> tag for local video files or website link to a raw video file (.mp4 or .webm...).

Use the <video> tag to embed a trailer or related clip.
Include the following attributes: src, width, height, and controls.

Example 1: Using local file.

<video src="trailer.mp4" width="640" height="360" controls>Video not supported in your browser</video>

 

Example 2: Using website link to raw file (video source W3schools).

<video src="https://www.w3schools.com/html/mov_bbb.mp4" width="320" height="240" controls>Video not supported in your browser</video>

7. Links Section
Use an <a> tag to add a hyperlink to:

An official website, Wikipedia article, or fan page (use target="_blank")

A review or article (use target="_self")

Include the href and title attributes.
Use href="#sectionID" for at least one internal link that jumps to a section.

Example:

<a href="https://wikipedia.org" title="Visit Wikipedia" target="_blank">Wikipedia</a>

8. Table Section
Create a table using these elements:

<table> to begin the table
<thead> for the table header
<tbody> for the main content
<tfoot> for the footer
Structure rows with <tr>.
Use <th scope="col"> for column headers such as "Character" or "Actor".
Use <th scope="row"> for row headers.
Use <td> for table data.
Include at least one colspan or rowspan for merged cells.

Example:

<td colspan="2">Combined Cell</td>
 

colspan2.png
9. Comments
Add at least 3 HTML comments like this:

<!-- This section contains the introduction paragraph -->

<!-- List of main characters from the story -->

<!-- Link to an official fan page -->
