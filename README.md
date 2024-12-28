# Exercise: John Doe's Resume

!NOTE! The "Jon Doe" is a placeholder for your first and last names.

## Introduction

In this activity, you will create a basic resume webpage using HTML. This activity will demonstrate that by understanding the fundamentals of HTML, you can construct actual web pages!

To preview your created app, simply click the "Go Live" button found in the VSCODE status bar. This will open your webpage in your browser.

If you are not using VSCode you can install and run the "live-server" npm package following the list of commands:

- [ ] Use `npm i live-server` to install the live-server package
- [ ] Use `npm run live-server` or `npx live-server --port=5551` to run the live-server. The port number should be 5551 strictly.

The live-server installation video: [Video](https://www.loom.com/share/ca99ebec79d14bfa9fc4dd012661f919?sid=0c702a22-c5bd-4608-93d2-0643aecb4b07)  
The live-server NPM package page: [Link](https://www.npmjs.com/package/live-server)

Make sure to watch the [INTRO VIDEO](https://www.loom.com/share/7dc80d1a15f74d718dba51ed8490cacd?sid=40bfa1ba-526c-49b2-993f-7822deb6f731) before you start.

## Learning objectives

This assignment should prove that a student is able to:

- Create an index.html file in VSCode.
- Add the HTML Boilerplate to the HTML document.
- Update the document title through the `title` tag content.
- Create the page main heading with the `h1` tag.
- Create an image element with the `img` tag.
- Set the required `src` and important `alt` image attributes.
- Set a relative/absolute image `src` attribute value.
- Create a paragraph of text with the `p` tag.
- Create section headings with the `h2` tags.
- Create an ordered list of items with the `ol` and `li` tags.
- Create an unordered list of items with the `ul` and `li` tags.
- Create a table with the `table` tag.
- Utilize `th` tag to create a table header cell.
- Utilize `td` tag to create a table data cell.
- Set a link with the `a` tag.
- Utilize the anchor `target` attribute to open the destination resource it in a new tab.
- Set the link that starts the default email client by a click with the `mailto:` `href` attribute value.
- Add global attributes to HTML elements.
- Utilize the `link` tag to connect a css file.
- Utilize the `script` tag to connect a js file.

## Standard requirements

- [X] Fork the project to your github account
- [X] Clone the project to your computer
- [X] Open the project in VSCode with `code <cloned_repo_folder_name>`
- [X] Initialize playwright and install project packages
  - [X] Use `npm i` to install packages
  - [X] Use `npm run browser-install` to install the browser environment for testing (~131mb will be downloaded)
  - [ ] (Windows users only) Use `npm run deps-install` to install playwright additional dependencies (160mb will be downloaded)
- [X] All the tasks of the "Specific requirements" section MUST be solved
- [ ] All the tests MUST pass. Fix any errors before you submit (acceptance criteria).
  - [X] Use `npm run test` to run all tests in the terminal
  - [X] Use `npm run test-part1` to run the tests for the first part of specific requirements in the terminal
  - [X] Use `npm run test-part2` to run the tests for the second part of specific requirements in the terminal
  - [X] (Optional) Use `npm run test-ui` to run all the tests with GUI
  - [X] (Optional) Use `npm run show-report` to see the latest report in the browser
- [X] VSCode IDE MUST have 0 code problems listed (spelling problems are fine)
- [X] The code MUST be formatted with Prettier
- [ ] Push the changes to the Github repo, when finished.
- [ ] Submit a .txt file with the Github repo url.

## Specific requirements

### Part 1: Setting up HTML elements

All the tasks in the requirements are related to the index.html file! Consider "Jon Doe" to be replaced with your real first and last name.

- [X] Create an html file with the name of "index" in the root of the project
- [X] Add HTML Boilerplate to the document
- [X] Set the document title to be "Jon Doe's resume".
- [X] Set the page heading to be "Jon Doe"
- [X] Add a section heading with the content of "Talented Frontend developer" that represents the desired role.
- [X] Add an image with required and important attributes
  - [X] The image path should be `https://randomuser.me/api/portraits/men/20.jpg`. Feel free to change the number in the file name to get a new image.
  - [X] The image alternative text should match the page title.
- [X] Add a section heading with the content of "About Me".
- [X] Add a paragraph of text (50 words at least) as the John Doe's bio. You can use random text for the paragraph content.
- [X] Add the section heading "My Skills" with h2 tag
- [X] Add the ORDERED list and add 6 random item into it. (Feel free to use the devslopes website to get the real skill names or use some random skill names)
- [X] Add the section heading "My Hobbies" with h2 tag
- [X] Add the UNORDERED list of 4 hobbies
- [X] Add the section heading "Contact Me" with h2 tag
- [X] Add the table of two columns and 4 rows. The first column for every row is the table header with the service name. The second column is for the value.
- [X] Add Discord as a service and your discord's real username as a value to the table.
- [X] Add LinkedIn as a service and your linkedIn's real username as a value to the table. Make the value to be a link to your LinkedIn profile page opened in a new tab.
- [X] Add Email as a service and your real email as the value. Make it to be a link that starts the new email message app.
- [X] Add Github as a service and use your real github username as a value. Make the value to be a link that leads to your github profile in a new browser tab.
- [X] Check the result mockup to make sure your page looks EXACTLY as the mockup (/assets/images/p1-solved-mockup.png).

### Part 2: Testing the magic of id and class attributes

- [X] In the head section connect the CSS file, available by the following path: `./css/styles.css`.
- [X] In the head section connect a JS file, available by the following path: `./js/scripts.js`. Make sure it will be executed after the html is parsed.
- [X] The page heading should have the id of "candidate-name"
- [X] The desired role section heading should the id of "candidate-desired-role"
- [X] The "About me" section heading should have an id of "about-me".
- [X] The image should have the id of "candidate-image"
- [X] The bio paragraph should have a class name of "candidate-bio"
- [X] The skills section heading should have the id of "skills"
- [X] The skills list should have the id of "skills-list"
- [X] The Hobbies section heading should have the id of "hobbies"
- [X] The hobbies list should have the id of "hobbies-list"
- [X] The contacts section heading should have the id of "contacts"
- [X] The contacts table should have a class name of "contacts-table".
- [X] The body should have a class name of "fancy-body".
- [X] Check the result mockup to make sure your page looks EXACTLY as the mockup (/assets/images/p2-solved-mockup.png).
