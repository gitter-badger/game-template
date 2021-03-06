<h1 align="center">
<a href=" https://github.com/TBosak/game-template/archive/master.zip">
<img src="https://i.ibb.co/p0hD1bD/repository-phaser-template.png" alt="repository-phaser-template" width=60% height="60%" border="0"></a><br>
Electron/Angular/Phaser Template
</h1>

[![Codacy Badge](https://api.codacy.com/project/badge/Grade/29fb4dffbab44f48bbb57bd6be67d5ca)](https://app.codacy.com/manual/TBosak/game-template?utm_source=github.com&utm_medium=referral&utm_content=TBosak/game-template&utm_campaign=Badge_Grade_Dashboard)
[![GitHub](https://img.shields.io/github/license/TBosak/game-template)](https://github.com/TBosak/game-template/blob/master/LICENSE)
[![GitHub stars](https://img.shields.io/github/stars/TBosak/game-template?style=social)](https://github.com/TBosak/game-template) [![GitHub watchers](https://img.shields.io/github/watchers/TBosak/game-template?label=Watchers&style=social)](https://github.com/TBosak/game-template) [![Twitter URL](https://img.shields.io/twitter/url?style=social&url=https%3A%2F%2Fgithub.com%2FTBosak%2Fgame-template)](https://twitter.com/intent/tweet?text=Wow:&url=https%3A%2F%2Fgithub.com%2FTBosak%2Fgame-template)

This is an Angular project template with Phaser nested inside, set up to run with Electron.

### Cross-Platform & Responsive
The template should run on any desktop operating system.  

Flexbox integration allows for extremely responsive design elements.  

Angular and Phaser can be easily decoupled from Electron to allow for mobile deployment with a different framework.  


### Easy to Build
Build with HTML, CSS, and Typescript  

---

## Getting Started


### Prerequisites
[Node.js and Angular CLI](https://angular.io/guide/setup-local)  
(you shouldn’t need to go past step 1)  
[Electron](https://www.electronjs.org/docs/tutorial/installation)


### Running
In order to run, make sure to open two separate terminals targeting the project path and do the following:  

1. ```npm install electron -g``` to install electron globally & set path.  

2. ```npm install``` to ensure that all dependencies are installed.  

3. ```ng serve``` in one terminal to start Angular app.  

4. ```npm run electron``` in the other terminal to start Electron interface  

---

## To Do  
* Setting up config(s) to point at correct hosting environment(s) for the project in Electron's main.js  

* Correctly exposing index.html to Electron as Angular runs (this has proven difficult to do in one run-script as you cannot chain commands with 'ng serve') - fixing this may fix item 1, as there will be no reference needed to host location.  

* Need to make use of this template to find pain points between frameworks and correct them before they occur in use of the template, to optimize ease of implementation.  

* Need to hide Electron toolbar, or bind to a boolean for end-user(developer).  

* Need to turn template into an installable package.  

* Add implementation example images and videos to README

---

## Built With

* [Angular](https://angular.io/) – The web framework used.  

* [Phaser]( https://phaser.io/) – The game framework used.  

* [Electron]( https://www.electronjs.org/) – The software framework used.  

* [NodeJS](https://nodejs.org/en/) – The Javascript framework and package manager used.  

* [Flexbox](https://github.com/angular/flex-layout) – The web layout model used.

## Authors

* **Tim Barani** - *Initial work* - [TBosak]( https://github.com/TBosak)

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.
