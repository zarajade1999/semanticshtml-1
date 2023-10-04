# 01 HTML, CSS, and Git: Code Refactor

## Description

Provide a short description explaining the what, why, and how of your project. Use the following questions as a guide:

- What was your motivation? My motivation for this challenge was to make the code easier to read for other developers and to show how combining selectors in CSS with the same styling properties is better than repeating code. 
- Why did you build this project? I didnt build the project for this challenge but i wanted to show that i can identify problems with code. 
- What problem does it solve? Completing the task meant there was not as much duplicated code in CSS and i changed a '<div>' element to a '<nav>' bar at the top of the HTML so the HTML knew what to look for.
- What did you learn? I learnt how to combine code, become more comfortable with HTML semantics and learnt the imporatance of using an 'alt' attribute. 

## Table of Contents (Optional)

If your README is long, add a table of contents to make it easy for users to find what they need.

- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)
- [License](#license)
N.A 
## Installation

To run the project, download the file on Github as a zip folder. Extract the folder and open the terminal then CD into the project, type 'code .' which will mean you can install and edit my project.

## Usage

Provide instructions and examples for use. Include screenshots as needed.

To add a screenshot, create an `assets/images` folder in your repository and upload your screenshot to it. Then, using the relative file path, add it to your README using the following syntax:

![alt text](assets/images/screenshot.png)

## Credits

N.A 

## License

N.A

🏆 The previous sections are the bare minimum, and your project will ultimately determine the content of this document. You might also want to consider adding the following sections.

## Badges

N.A

## Features

If your project has a lot of features, list them here.

## How to Contribute

If you created an application or package and would like other developers to contribute to it, you can include guidelines for how to do so. The [Contributor Covenant](https://www.contributor-covenant.org/) is an industry standard, but you can always write your own if you'd prefer.

## Tests

# 01 HTML, CSS, and Git: Code Refactor

## Challenges in This Course

There are two types of Challenges in this course. Each one is designed to prepare you for a scenario that you're likely to encounter as a web developer.

### Challenge Types 

The two types of Challenges are the following:

* **On-the-job ticket** or **feature request Challenges** give you starter code in a folder called `Develop`, which you'll modify to complete the Challenge. Odd-numbered modules follow this format.

> **Important**: For assignments with starter code, be sure to copy the contents of the `Develop` folder directly into your repository. Do not include the `Develop` folder itself.

* **Job-seeking coding assessments** or **take-home assignments** don't provide starter code. You'll build these from scratch. Even-numbered modules follow this format.

### Challenge Elements

Challenges adhere to a format that's commonly used by software development teams that use **agile project management** to manage their work. Practicing this will prepare you for the workflows you'll experience as a professional full-stack web developer. 

> **Deep Dive**: To learn more about agile, read this [Wikipedia article on agile software development](https://en.wikipedia.org/wiki/Agile_software_development).

Each Challenge contains the following elements:

* **User Story**: This is a short, simple description of a feature told from the perspective of the person who is requesting the new capability, usually a user or customer of the system. This follows an AS AN / I WANT / SO THAT format. For example, "AS A shopper visiting an online store, I WANT to place items in a shopping cart, SO THAT I can purchase them." 

* **Acceptance Criteria**: These are the requirements that you must meet to satisfy the scope of work. They are not exhaustive, but they do entail the minimum aspects of a working solution. Consider this a checklist of baseline requirements. Acceptance criteria can be presented in various ways. In this case, we'll use a common format called **scenario-oriented criteria** which expresses each requirement in a WHEN / THEN format. Don't worry if this doesn't make sense now; it will become very familiar to you after you complete a couple of Challenges. 

* **Mock-up**: This is an image or animation that demonstrates the design and functionality of the web application that you'll build for the Challenge.

* **Submission**: You'll submit your completed Challenge for review. In the real world, when a developer finishes working on a project, another developer reviews the code, providing feedback on errors and making sure that all of the acceptance criteria have been met. For each Challenge, your instructional staff will serve as your team of reviewers.

## Your Task

This week is an odd-numbered week, so your Challenge is an on-the-job ticket&mdash;meaning that you'll begin with starter code that you need to modify. 

**Refactoring** existing code (improving it without changing what it does) to meet a certain set of standards or to implement a new technology is a common task for front-end and junior developers. For this particular Challenge, a marketing agency has hired you to refactor an existing site to make it more accessible. 

> **Important**: When working with someone else's code, you should adhere to the **Scout Rule**&mdash;always leave the code a little cleaner than when you found it.

An increasingly important consideration for businesses, web **accessibility** ensures that people with disabilities can access a website using assistive technologies like video captions, screen readers, and braille keyboards. Accessibility is good for business&mdash;for one thing, accessible sites rank higher in search engines like Google. It also helps companies avoid litigation, which might arise if people with disabilities can't access a website.

Accessibility can include complex requirements, but your tech lead has given you a small list of specific criteria for this project. These criteria are documented in the Acceptance Criteria section.

To impress clients, you should always exceed expectations and improve the codebase for long-term sustainability. For example, check that all links are functioning correctly. You can also increase the efficiency of the CSS by consolidating the selectors and properties, organizing them to follow the semantic structure of the HTML elements, and including comments before each element or section of the page.

Are you ready to begin? Here are this week's Challenge requirements.

## User Story

```
AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines
```

## Acceptance Criteria

```
GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the icon and image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title
```

## Mock-Up

The following image shows the web application's appearance and functionality:

![The Horiseon webpage includes a navigation bar, a header image, and cards with text and images at the bottom of the page.](./Assets/01-html-css-git-homework-demo.png)

> **Note**: This layout is designed for desktop viewing, so you may notice that some of the elements don't look like the mock-up at a resolution smaller than 768px. Eventually you'll learn how to make elements responsive so that your web application is optimized for any screen size.

## Getting Started

Follow these instructions to create your project and deploy it to GitHub Pages:

1. Create a new repository on your GitHub account and clone it to your computer.

2. When you're ready to deploy, use the `git add`, `git commit`, and `git push` commands to save and push your code to your GitHub repository.

3. Navigate to your GitHub repository in the browser and then select the Settings tab on the right side of the page.

4. On the Settings page, select Pages on the left side of the page. On the GitHub Pages screen, choose `main` in the dropdown under Branch. Click the Save button.

5. Navigate to <your-github-username.github.io/your-repository-name> and you will find that your new webpage has gone live! For example, if your GitHub username is "lernantino" and the project is "css-demo-site", then your URL would be <lernantino.github.io/css-demo-site>.

> **Important**: It might take a few minutes for GitHub pages to display your site correctly. If your project does not deploy or display correctly, check that all file paths in your application are relative and use the right casing. GitHub is case-sensitive, an inccorect capital or lowercase letter could cause problems in deployment.

Be sure to add, commit, and push your work to see the most up-to-date version of your app!

## Grading Requirements

> **Note**: If a Challenge assignment submission is marked as “0”, it is considered incomplete and will not count towards your graduation requirements. Examples of incomplete submissions include the following:
>
> * A repository that has no code
>
> * A repository that includes a unique name but nothing else
>
> * A repository that includes only a README file but nothing else
>
> * A repository that only includes starter code

This Challenge is graded based on the following criteria: 

### Technical Acceptance Criteria: 40%

* Satisfies all of the preceding acceptance criteria plus the following code improvements:

  * Application's links all function correctly.

  * Application's CSS selectors and properties are consolidated and organized to follow semantic structure.

  * Application's CSS file is properly commented.

### Deployment: 32%

* Application deployed at live URL.

* Application loads with no errors.

* Application GitHub URL submitted.

* GitHub repository contains application code.

### Application Quality: 15%

* Application resembles mock-up provided in the Challenge instructions (at least 90%).

### Repository Quality: 13%

* Repository has a unique name.

* Repository follows best practices for file structure and naming conventions.

* Repository follows best practices for class/id naming conventions, indentation, quality comments, etc.

* Repository contains multiple descriptive commit messages.

* Repository contains quality README file with description, screenshot, and link to deployed application.

## Review

You are required to submit the following for review:

* The URL of the deployed application.

* The URL of the GitHub repository, with a unique name and a README that describes the project.

---
© 2023 edX Boot Camps LLC. Confidential and Proprietary. All Rights Reserved.
