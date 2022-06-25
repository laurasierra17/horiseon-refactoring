# Horiseon Marketing Agency - A Refactoring Project

## Screenshots
Screenshot of the Horiseon Marketing Agency landing page:
![Screenshot of the Horiseon Marketing Agency landing page](./assets/images/website-screenshot.png)

## Description

The goal of this project is to refactor a marketing agency's landing page codebase to follow accessibility standards -- so their site is optimized for search engines -- and logical and semantic structure. The website provides information on Horiseon Marketing Agency's marketing specialties and strategies as well as the benefits of a partnership.

## The WHY

To assess my understanding of HTML and CSS best practices. The first week of UC Berkeley's coding bootcamp delved into the fundamentals of HTML and CSS with a range of activities that covered building webpages from scratch, adding styling and elements on top of some, and refactoring code that met accessibility and semantic standards. This project defines the outcome of a week's worth of hard work.

## The problems

Changes I implemented:
- Transformed `<div>` elements into their correct semantic element. Example: from `<div class="header">` to `<header>`.
- Added alternative text to every image instance.
- Correctly linked each link in the navigation bar with its corresponding section of the page.
- Removed the existence of several one-instance classes with repeated styling.
- Ensured heading elements fall in sequential order.
- Reworded the title to be more concise and descriptive.
- Adjusted indentation of HTML file for better readability.
- Included the `type` attribute to the stylesheet link tag in the head of the HTML file.
- Left descriptive comments on both the HTML and CSS files for better readability.

## Technologies

HTML, CSS, and Git

## Future implementations

For a better user experience, I would make changes to the UI and implement more interactive functionality. Currently, the user is bombarded with small text and too much information to process in 6 seconds. The website lacks call-to-action elements that prompt the user to connect with the company. The website needs to clearly and easily point out what it is that they do and how it can satisfy the user's demand. Finally, I believe it lacks eye-catching functionality to hook the user.

## Code Snippet
```
<!-- Footer of the page indicating authoring and other rights -->
<!-- To create a semantic file, I've replaced the previous div element with a class
of footer, for a footer element. -->
<footer>
    <!-- To correct the file's heading sequential order, I changed the following heading for an h4
    from an h2. -->
    <h4>Made with ❤️️ by Horiseon</h4>
    <p>
        &copy; 2019 Horiseon Social Solution Services, Inc.
    </p>
</footer>
```
For every section and refactoring I worked on, I included comments close to the ones seen above. One comment describes what the section is about, while the rest explain the refactoring changes I implemented. For future instances and collaboration purposes, I consider both types of comments necessary for familiarization.

## Deployed website link

https://laurasierra17.github.io/horiseon-refactoring/