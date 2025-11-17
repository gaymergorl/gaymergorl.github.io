📝 Option 1
Assignment: “Styling a Job Application Form with CSS”.

You can add additional HTML elements and tags for CSS styling to meet the assignment requirements described below. A screenshot showing an example of the expected HTML webpage with CSS styling is provided below at the end of the page.


📝 Option 2
You may also style a website based on your own idea but it MUST have the required structure described in this hands on assignment instructions. You can add additional HTML elements, tags and CSS styling as you see fit to create your website, as long as the minimum requirements are met.

🎯 Objective
Apply CSS styling to HTML website showcasing your understanding of the specified CSS rulesets in the first half of Learn CSS course provided by Codecademy.

📌 Instructions
You will apply CSS styling to the job application form or HTML website submitted in 'Module 1: HTML Hands-on assignment 2'. You may use the exact same HTML file (index.html) with all its assets (images, videos, subfolders...) submitted in the second HTML hands-on assignment (Job application webpage or your own website). Changing its content is also allowed but the requirements listed below need to be fulfilled for this assignment. 

Your task includes applying CSS styling to demonstrate understanding of the CSS concepts drawn from the course Learn CSS by Codecademy. This applies especially to the rulesets covered in chapters Syntax and Selectors, Visual Rules and The Box Model. The requirement is to create a well-structured and visually styled form using an external CSS stylesheets file (styles.css).


📁 Required Files and Setup Process to Link HTML and CSS Files

Duplicate the folder Firstname_Surname_HTML_2 with all its contents and files (index.html, subfolders, assets like images, videos, and other files) used to submit Module 1: HTML Hands-on Assignment 2.
Rename the duplicated folder to Firstname_Surname_CSS_1.
Open Visual Studio Code and open the folder Firstname_Surname_CSS_1.
Create a CSS file named styles.css in that same folder. Note that .css is a CSS file extension.
Link the CSS file in your <head> section of index.html by adding the following code or link: <link rel="stylesheet" href="styles.css">
As learnt earlier, step 5 will connect your CSS external stylesheet to the HTML file for styling purposes. After completing these steps, you may proceed to apply CSS styling using the instructions provided below.


✅ Required Structure and Content
Each of the listed CSS rulesets and properties MUST be demonstrated at least once in your code. You may use them multiple times if it makes sense for your design. You can add additional HTML and CSS content that you see fit for creating your website as long as the minimum requirements are met.

1. Reset Defaults
Use the universal selector to reset browser defaults:

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

2. Selectors
Use the following CSS selectors with examples provided for reference:

Type selectors: h1, form, p

Class selectors: .form-section

ID selectors: #main-title

Multiple class selectors: .green.bold

Attribute selectors: type[attribute*=value], img[src*='winter']

Descendant combinators: .form label, .main-list li

Multiple selectors: h1, h2, .menu {}

Chaining: h1.title

Pseudo-classes: :hover, :focus, :disabled, :visited, :active

3. Visual Rules
Apply the following visual styling properties:

font-family

font-size

color

background-color

text-align

opacity

background-image

!important to override styles where needed.

4. The Box Model
Utilize box model properties:

margin

padding

Margin shorthand: margin: 6px 11px 4px 9px;
Padding shorthand: padding: 6px 10px 5px 12px;

auto, margin: 0 auto;
border

border-radius

width

height

min-width

max-width

min-height

max-height

overflow

Understand and manage individual margin and padding properties:

margin-top, margin-right, margin-bottom, margin-left, padding-top, padding-right, padding-bottom, padding-left

Apply box-sizing: border-box to all elements

Use visibility to show/hide element(s)

5. Comments
The inline, internal, and external CSS styles used in your files should include comments that explain the rulesets in relation to the required structure provided in this assignment. Examples include the following:

/* This ruleset uses multiple class selectors to apply the same styles to... */

/* This is an ID selector targeting paragraphs */

/* This is a visibility property used to hide a table list */
 
