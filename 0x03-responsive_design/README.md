Responsive design

Overview
Before talking about media-queries, the backbone of responsive web design. Some basic elements are crucial and actually already implemented in our code. But it’s important to know about these in case you want to add responsive web design to an existing website.

Viewport
The viewport is a meta seen in our first HTML advanced module. The width=device-width forces mobile browsers to adopt their real viewport width.

Code example
<head>
  <meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
</head>
Box-sizing
Code example
*, *:before, *:after {
  box-sizing: border-box;
}

RESOURCES
[Responsive web design] (https://intranet.hbtn.io/concepts/185)
[The building blocks of responsive design - Progressive web apps | MDN] (https://intranet.hbtn.io/rltoken/xunPO8dNZy0mJpq8vbUMRA)
[Apragmatic guide to designing and building responsive web applications | developerlife.com] (https://intranet.hbtn.io/rltoken/rs5zCrDpRaU6LD13-rG2yg)
[Understanding the difference between mobile-first, adaptive and responsive design] (https://intranet.hbtn.io/rltoken/7W08yfp6vBGFlgoqZZc7eQ)
[LukeW | Mobile First] (https://intranet.hbtn.io/rltoken/AMTqHMY4OeGET3nOdRH2uQ)
[Media Queries | A collection of inspirational websites using media queries and responsive web design] (https://intranet.hbtn.io/rltoken/bk52ihWug_pe0QUghl99aQ)
[Responsive Design Newsletter] (https://intranet.hbtn.io/rltoken/1k39DhswkQfzN7L4N7pO7w)

TASKS
https://intranet.alxswe.com/projects/1194#task-11374

0. Fix the hero banner
1. Make the container flexible
2. Fix layout issues
3. Generate images with responsive breakpoints
4. Create the mobile icon and hide the menu
5. Hamburger!
6. Add the behavior based on menu-btn state
7. Make the font size responsive
8. Improve the "Works" section
9. Improve the "Footer" section
10. Fix the top header background
11. Make the article page responsive


Learning Objectives
At the end of this project, you are expected to be able to explain to anyone, without the help of Google:

Mobile-first design

Media-queries

Sizes to use for responsive web design

How to make a website responsive

The differences between responsive and adaptive design

CSS units that are used to make elements flexible


Requirements

Allowed editors: vi, vim, emacs

A README.md at the root of the project directory is mandatory

HTML and CSS have been rendered on Chrome 78 or more.
