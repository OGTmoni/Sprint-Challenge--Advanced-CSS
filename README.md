# Sprint Challenge: Advanced CSS - Space Walkers Web Page

This challenge allows you to practice the concepts and techniques learned over the past week and apply them in a concrete project. This Sprint explored advanced CSS techniques using Responsive Design and Preprocessing. During this Sprint, you studied how to use the viewport meta tag, media queries, setting up a preprocessor, and advanced use of preprocessing techniques. In your challenge this week, you will demonstrate proficiency by updating a website that is missing content as well as adding mobile styling.

## Instructions

**Read these instructions carefully. Understand exactly what is expected _before_ starting this Sprint Challenge.**

This is an individual assessment. All work must be your own. Your challenge score is a measure of your ability to work independently using the material covered through this sprint. You need to demonstrate proficiency in the concepts and objectives introduced and practiced in preceding days.

You are not allowed to collaborate during the Sprint Challenge. However, you are encouraged to follow the twenty-minute rule and seek support from your PM and Instructor in your cohort help channel on Slack. Your work reflects your proficiency in advanced css and your command of the concepts and techniques in responsive web design and preprocessing.

You have three hours to complete this challenge. Plan your time accordingly.

## Commits

Commit your code regularly and meaningfully. This helps both you (in case you ever need to return to old code for any number of reasons) and your project manager.

## Description

The client for this challenge is _Spacewalkers Magazine_. Spacewalkers needs your help to build a small proof of concept website for their marketing team. They have provided designs for both desktop and phone views. In addition to designs and content they have most of the home page coded for you. You just need to finish the navigation and header as well as the mobile styles.

In meeting the minimum viable product (MVP) specifications listed below, your web page should look like the solution design files of the desktop and mobile views:

[Click here to review the home design](design-files/home-desktop.png)

[Click here to review the mobile design](design-files/home-mobile.png)

## Self-Study Questions

Demonstrate your understanding of this week's concepts by answering the following free-form questions.

Edit this document to include your answers after each question. Make sure to leave a blank line above and below your answer so it is clear and easy to read by your project manager

1. What is the difference between an adaptive website and a fully responsive website?

Responsive websites move with the size of the window the user is viewing it on. An example of a responsive site would be one that display certain pictures and aspects of the web design on a desktop and a more condensed version on tablets and mobile phones. 
Adaptive websites adjust to the width of the browser and only at certain areas of the browser. Does not adjust beyond the set specifications. 

2. Describe what it means to be mobile first vs desktop first.
Mobile first design is a focused approach that starts with the design of for the main function of the site, then works toward higher resolutions. Also known as progressive enhancement. Good for site that: 
•	The number of hits from mobile is 80% and above or 50%, but the sales are higher on mobile devices
•	The user experience needs to be optimized for mobile and it’s enough to be merely functional on desktop
•	The site or interface has only a few core features
•	The service or product has a rather interactive nature (entertainment, lifestyle, networking, news etc.)

Desktop first design

The Desktop approach means designing for the utmost specifications as per design layout and the gracefully moving down to smaller resolutions. Also known as graceful degradation. 
A good choice if:
•	Both the number of visitors and the sales are higher on the desktop
•	The site or interface is quite feature-rich, e.g. productivity, office or business tools
•	The user experience needs to be highly refined on the desktop and it’s enough to be merely functional on mobile
•	Some patches are required for the existing product, but the time and budget are limited



Mobile first design is a focused approach that starts with the design of for the main function of the site, then works toward higher resolutions. Also known as progressive enhancement.

The Desktop approach means designing for the utmost specifications as per design layout and the gracefully moving down to smaller resolutions. Also known as graceful degradation. 

3. What does `font-size: 62.5%` in the `html` tag do for us when using `rem` units?
Works if is the user increases their font size in their browser settings. Hard coding a 10 px font size would override this setting. So it's deference to usability using a percentage rather than a hard-coded value.

rem uses root element’s font-size instead of its parent’s font-size.

If font-size of the root element is 16px then 1 rem = 16px for all elements. If font-size is not explicitly defined in root element then 1rem will be equal to the default font-size provided by the browser (usually 16px).

4. How would you describe preprocessing to someone new to CSS?
Pre-processors have advanced features that allows code to be reusable In CSS. Using a preprocessor will increase productivity, and cut down on the amount of time it takes to code a project. 

Pre-processors have advanced features that allows code to be reusable In CSS. Using a preprocessor will increase productivity, and cut down on the amount of time it takes to code a project.  

5. What is your favorite concept in preprocessing? What is the concept that gives you the most trouble?

I like the mixins and imports. Stillneed to cement my understanding of parametric mixins


You are expected to be able to answer all these questions. Your responses contribute to your Sprint Challenge grade. Skipping this section *will* prevent you from passing this challenge.

## Project Set Up

Follow these steps to set up your project:

### Git Set up

- [ ] Create a forked copy of this project.
- [ ] Add your project manager as collaborator on Github.
- [ ] Clone your OWN version of the repository (Not Lambda's by mistake!).
- [ ] Create a new branch: git checkout -b `<firstName-lastName>`.
- [ ] Implement the project on your newly created `<firstName-lastName>` branch, committing changes regularly.
- [ ] Push commits: git push origin `<firstName-lastName>`.
 
Follow these steps for completing your project.

- [ ] Submit a Pull-Request to merge <firstName-lastName> Branch into master (student's  Repo). **Please don't merge your own pull request**
- [ ] Add your project manager as a reviewer on the pull-request
- [ ] Your project manager will count the project as complete by merging the branch back into master.
 

### Preprocessor Set up

* [ ] Verify that you have LESS installed correctly by running `lessc -v` in your terminal, if you don't get a version message back, reach out to your project manager for help.
* [ ] Open your terminal and navigate to your preprocessing project by using the `cd` command
* [ ] Once in your project's root folder, run the following command `less-watch-compiler less css index.less`
* [ ] Verify your compiler is working correctly by changing the `background-color` on the `html` selector to `red` in your `index.less` file.
* [ ] Once you see the red screen, you can delete that style and you're ready to start on the next task

## Minimum Viable Product

Your finished project must include all of the following requirements:

### Import LESS Files

* [ ] Navigate to your `index.less` file. Notice the file is blank. You have been asked to use a certain import order. That order is as follows:

```markdown
1.variables.less
2.mixins.less
3.reset.less
4.global.less
5.navigation.less
6.footer.less
7.home-page.less
```

_You will know everything is working properly when you see the styles enabled for the provided content._  

### Home Page - Desktop HTML & LESS

* [x ] Take 10 minutes to review the code that has already been provided for you. Take time to see how the home page was built.

* [x ] Add a viewport meta tag to the head of your index.html page

* [ x] [Review the provided home desktop design file](design-files/home-desktop.png). You are to build the missing navigation system and header image. You have been provided all content necessary in the [index.html file](index.html)

* [ ] Navigation Styles: Use the `navigation.less` file for styling.

* [ ] Main Content Styles: Use the `home-page.less` file for styling

* [ ] LESS Mixins: Create and use 2 different mixins to aid your styling. Use the `mixins.less` file for your mixins

* [ ] LESS Parametric Mixin: create a parametric mixin that is used to create the `sign up` button styles.

* [ ]  Use at least 2 parameters to create your button

* [ ] Create a hover state that swaps the background color and font color of the base button styles.

### Mobile Design

* [ X] Create a `@phone` variable that contains a `max-width: 500px` media query string. Use the `@phone` variable for all your nested mobile styling.

* [ ] [Review the provided home mobile design file](design-files/home-mobile.png). Match your mobile styling the best you can using the design file.

* [ ] Push your changes and create a pull request if you haven't already.

In your solution, it is essential that you follow best practices and produce clean and professional results. Schedule time to review, refine, and assess your work and perform basic professional polishing including spell-checking and grammar-checking on your work. It is better to submit a challenge that meets MVP than one that attempts too much and does not.

## Stretch Problems

After finishing your required elements, you can push your work further. These goals may or may not be things you have learned in this module but they build on the material you just studied. Time allowing, stretch your limits and see if you can deliver on the following optional goals:

* [ ] Build a page of your choosing from the navigation items. Come up with content and images that fit the theme.

* [ ] Introduce CSS animations to your site.

* [ ] Create a fixed navigation and add some opacity to the background

* [ ] Create a form that would allow someone to sign up for a Spacewalkers Magazine subscription