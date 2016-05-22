# Angular2/Phaser Seed Project

### What Am I?!
Want to make a game with the amazing Phaser engine and Angular 2?  Well look no further!
  - Download or clone this repo.
  - npm install
  - npm start

Should load the default Angular2 quickstart page, initiate a preload, and then present the Phaser logo.

### Usage
```javascript
<phaser (phaser)="phaserLink1($event)" [settings]="{file:'node_modules/phaser/build/phaser.min.js'}"></phaser>
```

### Version
1.1.2

### Updates
 - v1.1.2 - Eliminated jankiness when using Macbook touchpads and touchscreens.

### Live Demo 
[Check it out](https://allenroyston.herokuapp.com/access/ng-parallax/index.html "Title")


### Dependencies
- None!  (Other than AngularJS).

### NPM / Bower
<code>
npm install ng-parallax --save-dev
</code>
<br>
<code>
bower install ng-simple-parallax --save
</code>

### Installation
Include the module in your scripts.<br>
<code>
&lt;script src="./js/ngParallax.min.js"&gt; &lt;script&gt;
</code>

Add ngParallax in your apps dependencies.<br> 
<code>
var app = angular.module('myApp', ['ngParallax']);
</code>


### Parameters
<code>
&lt;div ng-parallax pattern="'imageLocation'" speed="[0-3]" reverse="[true/false]"&gt; &lt; /div&gt; 
</code>
<br><br>
speed: 0-3              (slowest to fastest)<br>

<ul>
 <li>Setting the speed at 0 will lock the image in place.</li>
 <li> ... unless it's iOS, in which case the image will act as a static image and scroll naturally.</li>
 <li>Using negative numbers reverses the direction.</li>  
 <li>The speed is directly related to the image size, so tinker with your speed to get the right effect.</li>
</ul>


License
----

MIT - go nuts y'all.
