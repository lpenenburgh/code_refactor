# Code Refactor
Homework assignment 1: Refactoring an existing HTML and CSS code

## Goals
My goal for this assignment was to improve Horiseon's existing site code to meet accessibility and semantic HTML standards without changing the function of the existing site.

### How I improved accessibility:
1. Added a <title> to optimize site for search engines
    1. Changed the title to the company's full name- as represented in the footer of the page
2. Added <alt> attributes to images on site page
    2. Assigned each image an <alt> tag with literal descriptions of what is in the image in the case that the image cannot be displayed due to issues loading or if someone is using a screen reader
3. Using a <lang> tag to state what language is used
4. Changed the code to reflect semantic HTML
    4. Semantic html tags give meaning and are descriptive of what type of element an attribute contains, making it easier for web browsers and coders to follow
        4. Semantic tags I used to describe attributes as well as present the code in a logical order:
            4. <header>
            4. <nav>
            4. <section>
            4. <article>
            4. <h1-h3>
            4. <p>
            4. <aside>
            4. <footer>
5. Added commentary to CSS and presented it in a logical order
    5. Commentary allows the reader to easily find the section they are trying to style
6. Links on page all funtion properly
    6. The "Search Engine Opitmization" link was not working. To fix this, I added and #id to the SEO article within the section, before the class


Published site: https://lpenenburgh.github.io/coderefactor/ 