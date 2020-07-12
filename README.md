# Morgrave Archeology website by Dylan Lee Soon Yoong
User Centric Frontend Development Project
The purpose of this project was to create a lightweight, fully functional community web page for a board gaming group interested in Dungeons and Dragons.
## Website Hosting
The website can be assessed on [Github pages](https://dylanlee91.github.io/)

## UX
My goal was to create a community webpage for a local board gaming group. The page was designed lightweight to encourage mobile usage and relied minimally on high resolution imagery for decoration. The website was aimed at several types of visitors:
**New players**
1. Provide information on how to play the game
2. Provide information on the story of both the original setting and the community's interaction with the setting
3. Provide timing and contact information to 
4. Be a source of tools and articles for new players
**Experienced Players**
1. Be a viable source of tools and articles to keep up to date with the game
2. Disseminate information on campaign timings and code of conduct
3. Be a generally useful reference source for returning players

The website was designed to be as mobile responsive as possible, and potentially obstructive elements would disappear on mobile to facilitate easy touch navigation. Care was also taken to make sure that every link was clearly marked.

An initial planning mindmap was [created](https://app.creately.com/diagram/cxfJNlVuXj7/view).

## Features

### Existing Features
Given that the website is primarily created using bootstrap, the basic features of bootstrap are present, including
mobile responsiveness on many elements, flexbox rows and columns and so on. Bootstrap's button implementation was used, 
as well as navbar dropdown elements

### Features Left to Implement
Aside from a raft of content that is yet to be added, several design and technical aspects remain yet to be implemented.
1. Embedded iframes for youtube videos and google maps
2. Javascript implementation of appearing and disappearing elements on click
3. Embedded signup sheets either using google forms or javascript
4. Implementing social media icons and usage of icons on webpage in general
5. A cooperative carousel that is mobile responsive, alternatively a replacement element on mobile for the carousel
6. Animation in some transitions such as quick fade in and fade outs. I'd like to animated the wizard upon moseouver.

A sample of unimplemented content
* Campaign Page Content
    * [Convergence Manifesto](https://acrosseberron.com/2019/10/07/convergence-manifesto-the-complete-first-season/)
    * [Oracle of War](https://dndadventurersleague.org/storyline-seasons/oracle-of-war/)
    * Dates and times, real or fictional
* New player resources
    * https://www.dndbeyond.com/essentials
    * https://dnd.wizards.com/basics-play
* Tools
    * https://www.dmsguild.com/product/208178/DD-Adventurers-League-Players-Pack
    * https://www.dndbeyond.com/characters/builder#/
    * http://rolladvantage.com/tokenstamp/
* Helpful Youtube Channels
    * Taking20
    * WebDM
## Technologies Used
The webpage is almost entirely written with the help of Bootstrap 4 CSS and it's supporting jquery packages.
To assemble the arkhip font package, the font .ttf file was passed to https://www.fontsquirrel.com/tools/webfont-generator to generate the webkit for easier implementation.
## Testing
Testers gave positive feedback on mobile responsiveness and overall look and feel of the website. There are not many technical elements
in the submitted version of the website as of yet that are likely to break such as javascript elements or embedded websites.
Testing was primarily limited to checking presentation and link connectivity. 

To test mobile functionality, load times on mobiles were testes as well as object and link interactability. 

## Deployment
The website is currently deployed on [Github pages](https://dylanlee91.github.io/) and the repository is publicly viewable on [Github](https://github.com/DylanLee91/DylanLee91.github.io)

In order to do so, the development repository was simply renamed to the repository name compatible with github.io hosting.

In development, changes were all made in a local repository using VSCode, and tested with a live server extension. A dev branch was used to practise strict seperation between deployed branches and dev branches. Given the lack of need for collaboration in the solo project, changes were not pushed to the remote repository frequently. Many test folders containing templates or test features were cleaned up before merge with the main branch. In the future, these test pages will be reintroduced on the dev branch and not merged during deployment.


## Credits
### Content
*Some text was taken from the [wikipedia article on Eberron](https://en.wikipedia.org/wiki/Eberron)
*The website primarily refers to Dungeons and Dragons, the intellectual property of [Wizards of the Coast](https://dnd.wizards.com/)
*Ideas on how to organise pages were taken from [templates on Getbootstrap](https://getbootstrap.com/docs/4.0/examples/) and [templates on startbootstrap](https://startbootstrap.com/)

### Media
*The thumbnails were obtained from various places and are provided by [Wizards of the Coast](https://dnd.wizards.com/)
*The dancing wizard .gif was obtained from [DnDBeyond](http://dndbeyond.com)
*The background tile, Redox 01, was created by [Hendrik Lammers](https://www.hendriklammers.com/)
*The arkhip font was obtained from (https://www.1001fonts.com/arkhip-font.html)
*A font package for Roboto and Raleway was acquired from [Google](fonts.google.com)
*The map looking at a map was obtained from [Chris OCampo](http://chrisocampo1.blogspot.com/2010/06/more-random-stuff.html)
*The dwarf hitting an anvil was obtained from [Denman Rooke](https://denmanrooke.com/#the-master-blacksmith)
*The cityscape drawing was taken from [Andrei Maximov](https://www.artstation.com/andead)

### Acknowledgements
*The creators of bootstrap without which this website would not be possible
*Stackoverflow for keeping me sane
*DndBeyond for giving me the rough outline of my website
*Keith Baker for creating Eberron



