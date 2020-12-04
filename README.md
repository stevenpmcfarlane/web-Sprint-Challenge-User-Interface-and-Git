# Sprint Challenge: User Interface and Git - Multi-Page Website

This challenge allows you to practice the concepts and techniques learned over the past week and apply them in a concrete project. This Sprint explored User Interface and Git. During this Sprint, you studied Semantic HTML, CSS Fundamentals, CSS Flexbox Module, and Git. In your challenge this week, you will demonstrate proficiency by creating a multi page website that has some missing HTML elements as well as CSS specificity problems that need to be solved. You will also create an additional web page that will be linked to from a navigation you will build.

## Instructions

**Read these instructions carefully. Understand exactly what is expected _before_ starting this Sprint Challenge.**

This is an individual assessment. All work must be your own. Your challenge score is a measure of your ability to work independently using the material covered through this sprint. You need to demonstrate proficiency in the concepts and objectives introduced and practiced in preceding days.

You are not allowed to collaborate during the Sprint Challenge. Your work reflects your proficiency in user interface and your command of the concepts and techniques in semantic HTML, CSS fundamentals, CSS flexbox module, and git.

You have three hours to complete this challenge. Plan your time accordingly.

## Commits

Commit your code regularly and meaningfully. This helps both you (in case you ever need to return to old code for any number of reasons)

## Description

In this challenge, you build a missing header (navigation and image) on the home page, update some CSS styling on the home page, and create an additional page (About) which will link from the navigation you created.

In meeting the minimum viable product (MVP) specifications listed below, your web page should look like the solution screen shots of the home and about pages (found in the design-files folder):

[Click here for the home page example](https://tk-assets.lambdaschool.com/39a49225-8ac9-43da-aa90-514fd60ae99a_sprint-challenge-ui-home-example.png)

[Click here for the about page example](https://tk-assets.lambdaschool.com/ede1bb1a-63ff-4801-8c02-3efa2f603190_sprint-challenge-ui-about-example.png)

## Self-Study Questions

Demonstrate your understanding of this week's concepts by answering the following free-form questions.

Edit this document to include your answers after each question. Make sure to leave a blank line above and below your answer so it is clear and easy to read by your Team Lead

1. If you were to describe semantic HTML to the next cohort of students, what would you say?
   Semantic HTML is a markup language that displays on virtually all webpages. Developers use HTML to display images, links, and text in an organized and attractive way. In particular, semantic HTML uses tags that contain meaningful information about the related element.

2. Name two big differences between `display: block;` and `display: inline;`.
   For display:block; there can be nothing else on the line - it pushes everything beneath it. display:inline is different in that other elements can be in the same line. This means that block elements have dimensions, so you can manipulate their width and height, for instance, whereas as inline elements don't have these dimensions, you have to think of ways to give them these dimensions to work with.
3. What are the 4 areas of the box model?
   A. Content - the informational thing
   B. Padding - pushes stuff around inside the box
   C. Border - the outline of the box
   D. Margin - pushes stuff away from the outside the box
4. While using flexbox, what axis does the following property work on: `align-items: center`?
   Align-items works on the cross axis, not the main axis. Which direction the cross axis depends on whether you are in a row or column for flex-direction. If row, then cross axis is vertical. If you are in column, then cross axis is horizontal.
5. Explain why git is valuable to a team of developers.
   git allows for version control, which means that several people can work on a shared project without messing things up for others, at least without a chance for everyone to view changes before deciding to merge. So the idea is that you take the larger shared project from a remote server, make a clone, and then put it on your computer, locally. Then you can work on the cloned file independently of what the rest of the team is doing. When you make changes, you can commit and then push them back to the remote server, but you haven't made changes to the shared project yet. So no single person can bring the whole thing down, but everyone can continue to work on the project at the same time.

You are expected to be able to answer all these questions. Your responses contribute to your Sprint Challenge grade. Skipping this section _will_ prevent you from passing this challenge.

## Project Set Up

- [ ] Create a forked copy of this project.
- [ ] Clone your OWN version of the repository (Not Lambda's by mistake!).
- [ ] Create a new branch: git checkout -b `<firstName-lastName>`.
- [ ] Implement the project on your newly created `<firstName-lastName>` branch, committing changes regularly.
- [ ] Push commits: git push -u origin `<firstName-lastName>`.

Follow these steps for completing your project.

- [ ] Submit a Pull-Request to merge <firstName-lastName> Branch into master (student's Repo). **Please don't merge your own pull request**

## Minimum Viable Product

Your finished project must include all of the following requirements:

### Home Page

[Review the provided design file for the home page](design-files/home.png). Notice the navigation and header images are missing.

- [ ] Build the HTML and CSS to create the missing navigation and header.
- [ ] Link the `About` navigation item to the [about.html](about.html) page

You will also notice there are 10 boxes on the home page that need background colors. Use this list below to correctly style each box:

- [ ] box1: `teal`
- [ ] box2: `gold`
- [ ] box3: `cadetblue`
- [ ] box4: `coral`
- [ ] box5: `crimson`
- [ ] box6: `forestgreen`
- [ ] box7: `darkorchid`
- [ ] box8: `hotpink`
- [ ] box9: `indigo`
- [ ] box10: `dodgerblue`

### About Page

[Review the provided design file for the about page](design-files/about.png). You have been provided the HTML wrapper, footer, and page content for the about page. Create the rest of the missing HTML and CSS to match the design file.

- [ ] Copy and paste your home page navigation and header into the about page
- [ ] Update the header image with the about page image
- [ ] Link the `Home` navigation item back to the `index.html` page.
- [ ] Build the rest of the about page layout to match the design

In your solution, it is essential that you follow best practices and produce clean and professional results. Schedule time to review, refine, and assess your work and perform basic professional polishing including spell-checking and grammar-checking on your work. It is better to submit a challenge that meets MVP than one that attempts too much and does not.

Note: Please make sure you are using flexbox to layout your website. Floats, inline-block, tables, etc, should not be used for layout.

## Stretch Problems

After finishing your required elements, you can push your work further. These goals may or may not be things you have learned in this module but they build on the material you just studied. Time allowing, stretch your limits and see if you can deliver on the following optional goals:

- [ ] refactor your HTML, make sure it's indented properly, clean, readable, you have written appropriate comments where necessary and that all attributes (required and encouraged) are filled out correctly.
- [ ] Ensure your CSS is organized and readable, you've seperated your code by section and that you are using descriptive class names and adding classes in your HTML where styles repeat rather than rewrting the same styles over again
- [ ] Use a flex item property of your choice when laying out a section of your website, ensure you can explain how and why you've used this property
