Frontend Setup Steps
====================

Description
-----------

The list of steps I most often use to create the basic scaffolding for a new Frontend project.


Prerequisites
-------------

 - [node (& npm)](https://nodejs.org/)
 - [git](http://git-scm.com/)
 - [chrome](https://www.google.com/chrome/)

One-Time Steps
--------------

 1. Install globally the [karma](https://github.com/karma-runner/karma/) CLI: `npm install -g karma-cli`

Per-Project Steps
-----------------

 1. `mkdir <project-folder>` to create a new project folder
 2. `cd <project-folder>` to enter the project folder
 3. `git init` to initialize git
 4. `npm init` to initialize npm
 5. `npm install karma --save-dev` to install [karma](https://github.com/karma-runner/karma/)
 6. `npm install karma-jasmine karma-chrome-launcher --save-dev` to install the basic karma plugins
