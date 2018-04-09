# DynamicWebResources
<em>A collaborative collection of resources and links for New Media 3720 - The Dynamic Web</em>

<b>How to contribute:</b> This document is formatted using markdown (See the [markdown cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet))

<b>Example Repo:</b> [Spellbook of Modern Web Dev](https://github.com/dexteryy/spellbook-of-modern-webdev)

*****

### Documentation
* [Mozilla Developer Network](https://developer.mozilla.org/en-US/)
* [W3 Schools](https://www.w3schools.com/)

*****

### CSS Grid
* [A Complete Guide to Grid ](https://css-tricks.com/snippets/css/complete-guide-grid/)
* [Grid by Example](https://gridbyexample.com/learn/)
* [IE Implementation of Grid](https://rachelandrew.co.uk/archives/2016/11/26/should-i-try-to-use-the-ie-implementation-of-css-grid-layout/)

*****

### Hubs for Reading and Shop Talk
* [Smashing Magazine](https://www.smashingmagazine.com/)
* [A List Apart](http://alistapart.com/)
* [ProgrammableWeb](https://www.programmableweb.com/)

*****

### The Art of Code
<details><summary>**Groups using code for art**</summary>

* Demoscene refers to a subculture of programmers that write graphical 'demos' entirely in code such as C#, C++, and even Basic. Big in Europe.


* [Pouet Demoscene Archive](http://www.pouet.net/)
* [Conspiracy - group](http://conspiracy.hu/)
* [Conspiracy - example video](https://www.youtube.com/watch?v=20vPbH6UWIc)
</details>

*****

### Technique Code Tutorials

* [Codrops](https://tympanus.net/codrops/category/tutorials/)
* [Free Code Camp](https://guide.freecodecamp.org/javascript/tutorials)

*****

### APIS

* [Public APIs](https://github.com/abhishekbanthia/Public-APIs)
* [List of Free APIs](https://github.com/toddmotto/public-apis) 

****

### Code Snippits

###Page Loading Event
```javascript
window.onload = init;

function init() {
  // main js goes here
}
```

#### Get a random number between 0 and 9
```javascript
var x = Math.floor(Math.random() * 10);
```

#### Nice way to create elements with jquery
```javascript
//first create a variable dictating which element you're using
//this case is an image

var imagesrc = "some link or filepath to image"
var $img = $("<img>");

//you can also add attributes, id's, and classes with jq
//src is the attribute we are adding, the field that needs to be passed 
// is what you are assigning it

$img.attr("src", imagesrc);

```

#### Send data in the AJAX request

To allow the user to request a particular username or hashtag, you can pass the info to the server in the AJAX URL as a query string:
```javascript
// grab the value the user entered 
var query = document.getElementById("hashtag").value;
// append it to the AJAX request URL
xhr.open("GET", "get_tweets.php?q=" + query, true);

```
Then in get_tweets.php, you can get the query value and pass it to the $getfield value:
```php
$q = $_REQUEST["q"];
$getfield = '?q='.$q;
```

*****

### Responsive Design
* [Introduction](https://www.w3schools.com/css/css_rwd_intro.asp)
* [Media Query Examples](https://www.w3schools.com/css/css3_mediaqueries_ex.asp)
* [Font Sizing Units Explained](https://medium.com/@madhum86/css-font-sizing-pixels-vs-em-vs-rem-vs-percent-vs-viewport-units-b1485716afe7)

*****

### Web Design
[![Jen Simmons - Art Direction on the Web](http://img.youtube.com/vi/5Z7lSSMwRgo/0.jpg)](http://www.youtube.com/watch?v=5Z7lSSMwRgo)

*****

### PHP
* [A variety of helpful PHP examples](https://www.w3schools.com/php/php_examples.asp)

*****

### HTML
* [Use HTML forms to send information to the server](https://www.w3schools.com/html/html_forms.asp)
* [HTML form example](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_form_text)

*****

### WordPress
* [Child Theme Codex](https://codex.wordpress.org/Child_Themes)
* [Creating a Child Theme](https://www.elegantthemes.com/blog/resources/wordpress-child-theme-tutorial)
* [Moving your WordPress site to a host](http://www.wpbeginner.com/wp-tutorials/how-to-move-wordpress-from-local-server-to-live-site/)

*****

### All About BuddyPress
* [BuddyPress Codex](https://codex.buddypress.org/)

### Useful code for BP Activity Shortcode Plugin
* [How to add activity form to BP Activity Shortcode](https://buddypress.org/support/topic/how-to-add-activity-form-to-bp-activity-shortcode/)

*****

### Reading Assignment One Links etc. 

### Corgi Image test
![Alt text](/img/pembroke-welsh-corgi-hero.jpg)

*****



