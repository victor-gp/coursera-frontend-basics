# Coursera - Frontend Basics

My solutions to the [coding assignments](https://github.com/jhu-ep-coursera/fullstack-course4/tree/master/assignments) of the Coursera course [HTML, CSS, and Javascript for Web Developers](https://www.coursera.org/learn/html-css-javascript-for-web-developers), by Yaakov Chaikin.

The code for each assignment is available on its solution subfolder, along with a copy of the instructions for the assignment.

This repo is deployed to GitHub Pages, you can see how the solutions look in the following links:

- [Assignment 2](https://victor-gp.github.io/coursera-frontend-basics/module-2-solution/index.html) : a responsive webpage without Bootstrap
- [Assignment 3](https://victor-gp.github.io/coursera-frontend-basics/module-3-solution/index.html) : barebones of a responsive webpage with Bootstrap
- [Assignment 3 Optional](https://victor-gp.github.io/coursera-frontend-basics/module-3-optional/index.html) : a responsive webpage with Bootstrap
- [Assignment 4](https://victor-gp.github.io/coursera-frontend-basics/module-4-solution/index.html) : a simple Javascript program
- [Assignment 5](https://victor-gp.github.io/coursera-frontend-basics/module-5-solution/index.html) : navigation (content re-render) for an SPA

## Usage

You can run Assignments 2-4 by opening the solution's `index.html` on your browser.

Assignment 5 is a bit more tricky because it makes AJAX requests to local files. [Your browser may not support that](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/set_up_a_local_testing_server#The_problem_with_testing_local_files) so you'll need to fire up a local server. There are many ways to do that. For instance, Python includes an http server in its standard library (see previous link).

I used [Browsersync](https://browsersync.io/) while I was debugging. You can run it with [npx](https://www.npmjs.com/package/npx) like this:

```
$ npx browser-sync start --server "module-5-solution/" --files "module-5-solution/"
```
