# Learn to Code - Intro to CSS

Brought to you by Galvanize. Learn more about the way we teach code at [galvanize.com](galvanize.com).

## Overview

The goal of this brief course is to provide you with a fun introduction to the world of web development, focusing on CSS. We will explore a variety of ways to build CSS features, and if we have time, we'll explore some CSS3 as well.

#### Here's what we'll be doing:

* Setting up our computers for web development
* Setting up your HTML with CSS
* Basic CSS syntax and features
* Advanced CSS features
* Playing around in the sandbox

**This course presumes some knowledge of HTML.** If you need to review, check out [our course](https://github.com/GalvanizeOpenSource/learn-to-code-intro-html/) at the link below.

_Learn To Code HTML_: [https://github.com/GalvanizeOpenSource/learn-to-code-intro-html/](https://github.com/GalvanizeOpenSource/learn-to-code-intro-html/)

#### Before you begin, a quick gut check:

* This course is for absolute beginners
* Feel free to move ahead
* Help others when you can
* Be patient and nice
* You will get through it!

#### What web coding is (really)?

Recipes to give to your computer to “cook” up some awesome things for you online

## Setting up your computer

(Brace yourself...)

#### Please set up the following:

* A web browser to see what we're working on as others see it (Recommend Google Chrome: chrome.google.com)
* A text editor to modify your files (Recommend the Atom text editor: Atom.io)
* Download the tutorial files on this page within the zip file

####  Download the file for this class:

1. Go to https://github.com/GalvanizeOpenSource/Learn-To-Code-Intro-CSS
2. Click on the button on the right-hand side that says "Download ZIP"
3. Go to your downloads folder and double click on the .zip file to unzip it
4. From Atom: File > open, select the folder and then click "Open"
5. From Atom: If the file tree does not appear on the left hand View > Toggle Tree View -- this will show you the entire folder within Atom
6. Open up the file in your browser -- 
  a. index.html
  b. style.css

#### Alternative: Use CodePen to code for this course

1. Go to this link: [https://codepen.io/leepngo/pen/KgrLNw](https://codepen.io/leepngo/pen/KgrLNw).
2. You will be taken to a page where you can simulate the coding experience.
3. Focus on the windows called "HTML" and "CSS". We'll work mostly in that one. Feel free to minimize the "JS" window.

**Patience!** Setting up your computer takes time and can be tricky, especially across platforms.

Once you're ready, you can move onto the next lesson.

## Overview of CSS

#### What Does CSS Stand for?

* _Cascading_ - prioritizing certain values over others
* _Style_ - focusing on layout, colors, fonts, etc.
* _Sheet_ - another name for the file we use here
The internet used to be ugly. Enter CSS - a consolidated way to make it prettier.

#### Three primary objects:

* _Elements_: e.g. h1, div, body, a - default HTML (already reviewed)
* _Classes_: everything that starts with a “.”
* _IDs_: everything that starts with a “#”

#### Elements

We're going to start you off with a prepared HTML page that looks like this.

```html
<html>
  <head>
    <title>
      Hello! Learn to Code CSS with us!
    </title>
  </head>
  <body>
    <header>This is a header. Make it look better.</header>
    <h1>This is a vertical navigation bar.</h1>
    <nav>
      <ul>
        <li>Header</li>
        <li>Text #1</li> 
        <li>Text #2</li> 
        <li>Footer</li> 
      </ul>  
    </nav>
    <div>
      This is a wall of text. What can you do to make it more visually appealing in this webpage? Right now, it sure could use a little style.
    </div>  
    <h1>This is a horizontal navigation bar.</h1>
    <nav>
      <a>Header</a> | <a>Text #1</a> | <a>Text #2</a> | <a>Footer</a>
    </nav> 
    <div>
      This is a wall of text. Can you make it look like the last wall of text without having to write too much code?
    </div>
    <div>Can you change some of the words in this text to the same color? What if you wanted to change them to a different color? How would you do that? 
    <footer>This is a footer. Make it look better.</footer>
  </body>  
</html>
```

If you don't remember HTML, now is a good time to review the [HTML course](https://github.com/GalvanizeOpenSource/learn-to-code-intro-html/).

We'll be adding CSS classes and IDs into this HTML, but first, an overview of the syntax.

#### Syntax of CSS:

```css
h1 {  // this is either an element, class, or ID
    font-size: 24px; // syntax is name: value;
    font-weight: bold;
    color: #000000; // hexadecimal, RGB, etc.
}
```
Space doesn’t matter, but “onion” rules apply

#### What are Classes?

Classes are attributes something to multiple elements on a page noted with a “.” symbol in CSS.

HTML:
```html
 
<a class=”ninja”>Lee Ngo</a>
```

CSS:
```css
.ninja { 
    color: black; margin: 10px; 
}
```

Classes are used to change or affect multiple items in an HTML document at once

e.g. everything with class=”ninja” should have the same attributes

## LET'S CODE!

**Remember:**

* Coding can be hard - be patient!
* Work in pairs! Even the pros do it
* Ask for help - we’re in a school!

 


#### What are IDs?

IDs are attributes that are used only on one element ONLY and noted with a “#” symbol in CSS e.g.

HTML:
```html
<a id=”leesName”>Lee Ngo</a>
```

CSS: 
```css
#leesName { 
    color: white; 
}
```

IDs are used to direct functions to unique elements in the HTML so that there’s no confusion

e.g clicking to a specific part of page

In tandem, you can do a lot with HTML & CSS! Let's give it a shot!



