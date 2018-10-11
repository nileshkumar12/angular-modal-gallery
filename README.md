<h1 align="center">
  <br>
  <img src="https://raw.githubusercontent.com/Ks89/angular-modal-gallery/700/readme-images/amg.png" alt="@ks89/angular-modal-gallery" width="200">
  <br>
  <br>
@ks89/angular-modal-gallery
  <br>
</h1>

<h3 align="center"><b>@ks89/angular-modal-gallery</b> is an Angular library (<b>SSR compatible</b>) to create image galleries.</h3>
<br>
<p align="center">
Despite its name, this library is more than for modal galleries, because I'm introducing new features every major release. In fact, It's composed by 3 main parts:</p>
<ul>
  <li><b>plain-gallery</b>: shows either a row, a column or a grid of <b>clickable thumbnails</b> using pure flexbox</li>
<li><b>modal-gallery</b>: is the core part of this project and display a <b>modal window with full screen images</b>, <b>buttons</b>, the <b>current image</b> and optionally, also navigation <b>dots</b> and <b>previews</b></li>
<li><b>carousel</b>: is the new feature introduced in 7.0.0 to show a configurable plain carousel (not modal) with auto-play and other cool features</li>
</ul>
<p><b>@ks89/angular-modal-gallery</b> supports also <b>keyboard shortcuts</b>, <b>swipe gestures</b> and <b>mouse events</b>.</p>
<br>

<p align="center">
  <a href="https://www.npmjs.com/package/@ks89/angular-modal-gallery">
    <img src="https://badge.fury.io/js/%40ks89%2Fangular-modal-gallery.svg" alt="npm@latest">
  </a>
  <a href="https://www.npmjs.com/package/@ks89/angular-modal-gallery"><img src="https://img.shields.io/npm/dw/@ks89/angular-modal-gallery.svg" alt="Downloads/week"></a>
  <a href="https://www.npmjs.com/package/@ks89/angular-modal-gallery"><img src="https://img.shields.io/npm/dm/@ks89/angular-modal-gallery.svg" alt="Downloads/month"></a>
  <a href="https://www.npmjs.com/package/@ks89/angular-modal-gallery"><img src="https://img.shields.io/npm/dy/@ks89/angular-modal-gallery.svg" alt="Downloads/year"></a>
</p>
<p align="center">
  <a href="https://travis-ci.org/Ks89/angular-modal-gallery"><img src="https://travis-ci.org/Ks89/angular-modal-gallery.svg?branch=master" alt=""></a>
  <a href="https://ci.appveyor.com/project/Ks89/angular-modal-gallery/branch/master"><img src="https://ci.appveyor.com/api/projects/status/ikp5qqr9aci2s0ae/branch/master?svg=true" alt=""></a>
  <a href="https://circleci.com/gh/Ks89/angular-modal-gallery"><img src="https://circleci.com/gh/Ks89/angular-modal-gallery.svg?style=svg" alt=""></a>
</p>
<p align="center">
  <a href="https://snyk.io/test/github/ks89/angular-modal-gallery"><img src="https://snyk.io/test/github/ks89/angular-modal-gallery/badge.svg" alt="Known Vulnerabilities"></a>
  <a href="https://david-dm.org/Ks89/angular-modal-gallery"><img src="https://david-dm.org/Ks89/angular-modal-gallery.svg" alt="david-dm Dependencies"></a>
  <a href="https://app.fossa.io/projects/git%2Bgithub.com%2FKs89%2Fangular-modal-gallery?ref=badge_shield"><img src="https://app.fossa.io/api/projects/git%2Bgithub.com%2FKs89%2Fangular-modal-gallery.svg?type=shield" alt="FOSSA Status"></a>
  <a href="https://github.com/prettier/prettier"><img src="https://img.shields.io/badge/code_style-prettier-ff69b4.svg?style=flat-square" alt="code style: prettier"></a>
  <a href="https://codeclimate.com/github/Ks89/angular-modal-gallery"><img src="https://codeclimate.com/github/Ks89/angular-modal-gallery/badges/gpa.svg" alt="Code Climate"></a>
  <a href="https://codeclimate.com/github/Ks89/angular-modal-gallery/coverage"><img src="https://codeclimate.com/github/Ks89/angular-modal-gallery/badges/coverage.svg" alt="ode Climate Coverage"></a>
  <a href="https://coveralls.io/github/Ks89/angular-modal-gallery?branch=master"><img src="https://coveralls.io/repos/github/Ks89/angular-modal-gallery/badge.svg?branch=master" alt="Coveralls Coverage"></a>
</p>
<p align="center">
  <a href="https://github.com/Ks89/angular-modal-gallery"><img src="https://img.shields.io/github/release/Ks89/angular-modal-gallery.svg?style=flat-square" alt="GitHub release"></a>
  <a href="https://github.com/Ks89/angular-modal-gallery"><img src="https://img.shields.io/github/release/Ks89/angular-modal-gallery/all.svg?style=flat-square" alt="GitHub (pre-)release"></a>
</p>
<p align="center">
  <a href="https://www.paypal.me/stefanocappa"><img src="https://img.shields.io/badge/Donate-PayPal-green.svg" alt="Donate"></a>
</p>

*Do you like @ks89/angular-modal-gallery? Please, add a :star: to support this library*

<br>
<br>



## Table of Contents

1. **[Main parts](#rocket-main-parts-rocket)**
2. **[Features](#boom-features-boom)**
3. **[Installation](#package-installation-package)**
4. **[Documentation](#book-documentation-book)**
5. **[Live demo](#microphone-live-demo-microphone)**
6. **[Choose the version](#warning-choose-the-version-warning)**
7. **[News](#fire-news-fire)**
8. **[FAQS](#question-faqs-question)**
9. **[Contributing](#computer-contributing-computer)**
10. **[A big thank you to](#sparkling_heart-a-big-thank-you-to-sparkling_heart)**
11. **[License](#copyright-license-copyright)**


## :rocket: Main parts :rocket:

### Carousel

![angular-modal-gallery image](https://github.com/Ks89/angular-modal-gallery/blob/700/readme-images/carousel-full.png?raw=true)

![angular-modal-gallery image](https://github.com/Ks89/angular-modal-gallery/blob/700/readme-images/carousel-fix.png?raw=true)


### Modal Gallery

![angular-modal-gallery image](https://github.com/Ks89/angular-modal-gallery/blob/700/readme-images/modal1.png?raw=true)

![angular-modal-gallery image](https://github.com/Ks89/angular-modal-gallery/blob/700/readme-images/modal2.png?raw=true)


### Plain Gallery

![angular-modal-gallery image](https://github.com/Ks89/angular-modal-gallery/blob/700/readme-images/plain-row.png?raw=true)

![angular-modal-gallery image](https://github.com/Ks89/angular-modal-gallery/blob/700/readme-images/plain-col.png?raw=true)

![angular-modal-gallery image](https://github.com/Ks89/angular-modal-gallery/blob/700/readme-images/plain-grid.png?raw=true)

<br>

## :boom: Features :boom:
- Angular Module to import this library
- requires IE >= 11 and Angular >= 6
- works with both JIT and AOT compilers
- supports all **recommended Angular Compiler Options**
- compliant to Angular Package Format v6 specifications
- **use [Semantic versioning 2.0.0](http://semver.org/)** also known as 'semver'
- official examples with `angular-cli`, `angular-cli + material`, `SystemJS` and `angular-universal` [HERE](https://github.com/Ks89/angular-modal-gallery/tree/master/examples)
- unit testing with high % coverage
- **Server Side Rendering** support with angular-universal
- Web Accessibility features, like ARIA support and [toptal.com](https://www.toptal.com/designers/colorfilter) criteria (tested with `Sim Daltonism` for macOS)
- image **download** with buttons or keyboard shortcuts
- advanced **keyboard shortcuts** with `mousetrap` (both local and global)
- fully configurable default buttons to either close, download, navigate to an external url or delete images and so on
- support custom buttons with both pre and after hooks
- **click outside feature** to close the modal gallery clicking on the background
- configurable plain gallery
- configurable carousel
- configurable side-previews (visible only on bigger screen)
- configurable dots navigation (visible only on bigger screen)
- configurable previews (visible only on bigger screen)
- and many more... (check the official documentation [HERE](https://ks89.github.io/angular-modal-gallery-2018-v7.github.io/))

<br>

## :package: Installation :package:

- `npm install --save @ks89/angular-modal-gallery`
- `npm install --save hammerjs mousetrap`
- `npm install --save-dev @types/mousetrap @types/hammerjs`

From version @ks89/angular-modal-gallery >= 5.0.0, **font-awesome isn't a mandatory dependency**.
You can use all default features without font-awesome. For more info, check official [documentation website](https://ks89.github.io/angular-modal-gallery-2018-v7.github.io/).

<br>

## :book: **Documentation** :book:

*Image loading could be slow, because this website is hosted on Github pages*

[OFFICIAL DOCUMENTATION WEBSITE](https://ks89.github.io/angular-modal-gallery-2018-v7.github.io/)

<br>

## :microphone: **Live demo** :microphone:

[OFFICIAL LIVE DEMO](https://stackblitz.com/edit/angular-modal-gallery-v7/)

<br>

## :warning: Choose the version :warning:

|            | @ks89/angular-modal-gallery | font-awesome |
| ---------- | :---:                       | :---:        |
| AngularJS  | NOT SUPPORTED               |              |
| Angular 2  | = 3.3.5                     | &gt;= 4.0.0  |
| Angular 4  | = 5.7.1                     | optional     |
| Angular 5  | = 6.3.0                     | optional     |
| Angular 6  | &gt;= 7.0.0                 | optional     |
| Angular 7  | &gt;= 7.0.0                 | optional     |

<br>

## :fire: News :fire:

**More than 80 releases in two years**, and more to come... :)

- 10/15/2018 - 7.0.0-beta.1 - @ks89/angular-modal-gallery - [HERE](https://github.com/Ks89/angular-modal-gallery/releases)
- 10/11/2018 - 6.3.0 - angular-modal-gallery - [HERE](https://github.com/Ks89/angular-modal-gallery/releases)
- 10/09/2018 - 7.0.0-alpha.3 - @ks89/angular-modal-gallery - [HERE](https://github.com/Ks89/angular-modal-gallery/releases)
- 10/04/2018 - 7.0.0-alpha.2 - @ks89/angular-modal-gallery - [HERE](https://github.com/Ks89/angular-modal-gallery/releases)
- 09/29/2018 - 7.0.0-alpha.1 - @ks89/angular-modal-gallery - [HERE](https://github.com/Ks89/angular-modal-gallery/releases)
- 09/15/2018 - 6.2.3 - angular-modal-gallery - [HERE](https://github.com/Ks89/angular-modal-gallery/releases)
- ... (many minor 6.x.x versions)
- 06/10/2018 - 6.0.0 - @ks89/angular-modal-gallery - [HERE](https://github.com/Ks89/angular-modal-gallery/releases)
- ... (many minor 5.x.x versions)
- 02/27/2018 - 5.0.0 - angular-modal-gallery - [HERE](https://github.com/Ks89/angular-modal-gallery/releases)
- ... (many minor 4.x.x versions)
- 11/05/2017 - 4.0.0 - angular-modal-gallery - [HERE](https://github.com/Ks89/angular-modal-gallery/releases)
- ... (many minor 3.x.x versions)
- 03/20/2017 - 3.0.0 - angular-modal-gallery - [HERE](https://github.com/Ks89/angular-modal-gallery/releases)
- ... (many minor 2.x.x versions)
- 01/29/2017 - 2.0.0 - angular-modal-gallery - [HERE](https://github.com/Ks89/angular-modal-gallery/releases)

<br>

## :question: FAQS :question:

1. Question: **I have this error: `Cannot find name 'MousetrapInstance'`. What can I do?**<br>
   **Answer**: Simply run `npm i --save-dev @types/mousetrap`
2. Question: **I have this error: `Error: No provider for KeyboardService`. What can I do?**<br>
   **Answer**: You forgot to add .forRoot(), so KeyboardService will be never available as a service. Please read section "Installation" [HERE](https://ks89.github.io/angular-modal-gallery-2018-v7.github.io/gettingStarted).
   This is a common design pattern for Angular libraries. For more info check also [this issue](https://github.com/Ks89/angular-modal-gallery/issues/94).
3. Question: **How can I remove images using DELETE button without issues?**<br>
   **Answer**: **You cannot change the input image array. Instead, you should reassign it with a newer array** without the deleted element.
   In other words, **you must think in a functional way**, without changing the input array of images.
   For more information check this official demo [HERE](https://ks89.github.io/angular-modal-gallery-2018-v7.github.io/demo/buttons-strategies).

<br>

## :computer: Contributing :computer:

Check `CONTRIBUTING.md` in this repository.
To understand how to contribute to an open source project, [HERE](https://egghead.io/courses/how-to-contribute-to-an-open-source-project-on-github) you can find useful information.

Also, if you want to generate the `internal library documentation`, run `npm run docs` and open `./docs/typedoc/index.html`.

<br>

## :sparkling_heart: A big thank you to :sparkling_heart:

##### all authors of icons used in this library:
- Icons made by <a href="https://www.flaticon.com/authors/smartline" title="Smartline">Smartline</a> from <a href="https://www.flaticon.com/" title="Flaticon">www.flaticon.com</a> is licensed by <a href="http://creativecommons.org/licenses/by/3.0/" title="Creative Commons BY 3.0" target="_blank">CC 3.0 BY</a>
- Icons made by <a href="https://www.flaticon.com/authors/dave-gandy" title="Dave Gandy">Dave Gandy</a> from <a href="https://www.flaticon.com/" title="Flaticon">www.flaticon.com</a> is licensed by <a href="http://creativecommons.org/licenses/by/3.0/" title="Creative Commons BY 3.0" target="_blank">CC 3.0 BY</a>
- Icons made by <a href="http://www.freepik.com" title="Freepik">Freepik</a> from <a href="https://www.flaticon.com/" title="Flaticon">www.flaticon.com</a> is licensed by <a href="http://creativecommons.org/licenses/by/3.0/" title="Creative Commons BY 3.0" target="_blank">CC 3.0 BY</a>
- Icons made by <a href="https://www.flaticon.com/authors/those-icons" title="Those Icons">Those Icons</a> from <a href="https://www.flaticon.com/" title="Flaticon">www.flaticon.com</a> is licensed by <a href="http://creativecommons.org/licenses/by/3.0/" title="Creative Commons BY 3.0" target="_blank">CC 3.0 BY</a>
- Icons made by <a href="https://www.flaticon.com/authors/gregor-cresnar" title="Gregor Cresnar">Gregor Cresnar</a> from <a href="https://www.flaticon.com/" title="Flaticon">www.flaticon.com</a> is licensed by <a href="http://creativecommons.org/licenses/by/3.0/" title="Creative Commons BY 3.0" target="_blank">CC 3.0 BY</a>
- Icons made by <a href="https://www.flaticon.com/authors/smashicons" title="Smashicons">Smashicons</a> from <a href="https://www.flaticon.com/" title="Flaticon">www.flaticon.com</a> is licensed by <a href="http://creativecommons.org/licenses/by/3.0/" title="Creative Commons BY 3.0" target="_blank">CC 3.0 BY</a>
- Icons made by <a href="https://www.flaticon.com/authors/dario-ferrando" title="Dario Ferrando">Dario Ferrando</a> from <a href="https://www.flaticon.com/" title="Flaticon">www.flaticon.com</a> is licensed by <a href="http://creativecommons.org/licenses/by/3.0/" title="Creative Commons BY 3.0" target="_blank">CC 3.0 BY</a>

##### all authors of spinners used in this library:
- <a href="https://github.com/lukehaas">Luke Haas (@lukehaas)</a> - <a href="https://github.com/lukehaas/css-loaders">lukehaas/css-loaders</a></li>
- <a href="https://github.com/martinvd">Martin van Driel (@martinvd)</a> - <a href="https://codepen.io/martinvd/pen/xbQJom">martinvd example on codepen.io</a></li>
- <a href="https://devalchemist.com/">Devilish Alchemist</a> - <a href="https://codepen.io/devilishalchemist/pen/emOVYQ">devilishalchemist example on codepen.io</a></li>
- <a href="https://github.com/nikhil8krishnan">Nikhil Krishnan</a> - <a href="https://codepen.io/nikhil8krishnan/pen/dMEzGx">nikhil8krishnan example on codepen.io</a></li>
- <a href="https://codepen.io/WebSonata/">Anastasiya Kuligina</a> - <a href="https://codepen.io/WebSonata/pen/bRaONB">Anastasiya Kuligina example on codepen.io</a></li>

<br>

## :copyright: License :copyright:

The MIT License (MIT)

Copyright (c) 2017-2018 Stefano Cappa (Ks89)

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NON INFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

<br/>

If you like my projects you can do a free donation here [![Donate](https://img.shields.io/badge/Donate-PayPal-green.svg)](https://www.paypal.me/stefanocappa)


## FOSSA report

[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2FKs89%2Fangular-modal-gallery.svg?type=large)](https://app.fossa.io/projects/git%2Bgithub.com%2FKs89%2Fangular-modal-gallery?ref=badge_large)

<br/>

**Created by Stefano Cappa**

**[⬆ back to top](#table-of-contents)**
