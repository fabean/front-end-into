
# Job Path Requirements

## Frontend Developer

A Frontend developer is such a broad term and can mean so many different things. I'm going to simplify it and just call it 1 of 2 things. A frontend developer is someone who writes code and the end user looking at the site will see or use. For my two different types of frontend developers I'm saying there is one who is into design and making pretty things, then there is the other who wants to make functional things with cool functionality. I'm going to call those frontend-designer & frontend-functional until I come up with better terms. I would highly suggest learning all the technologies required with being a frontend developer but everyone is different but the more you know the more valiable you are to your company.

### Resources
* [mdn](https://developer.mozilla.org) This will be the best documentation of every web technology out there. Don't use w3schools they're terrible compaired to mdn.
* [codepen](http://codepen.io) CodePen is a frontend developer playground. It's a great place to see what is possible with HTML, CSS & JavaScript and to learn.
* [Bento](https://bento.io/) an online learning resource
* [Codecademy](https://www.codecademy.com/) another online learning resource
* Podcasts
  * [Shoptalk Show](http://shoptalkshow.com/) A podcast about web design, development and UX.
  * [Javascript Jabber](http://javascriptjabber.com/) A podcast all about Javascript
  * [The Big Web Show](http://5by5.tv/bigwebshow) A podcast about all things web hosted by Jeffrey Zeldman
  * [The Web Ahead](http://5by5.tv/webahead) A weekly podcast about changing technologies and the future of the web
  * [SassCast](http://sasscast.podbean.com/) A podcast all about the Sass preprocessor.
  * [CDNify](https://itunes.apple.com/us/podcast/cdnify/id786191888?mt=2) The CDNify podcast covers all things tech, startup, web performance and acceleration.
  * [The Non Breaking Space Show](http://goodstuff.fm/nbsp)
* [frontend-dev-bookmarks](https://github.com/dypsilon/frontend-dev-bookmarks) This is a very overwhelming large maintained list of great places to get resources as a frontend developer.

### Shared knowledge of both types

Regardless of what path you want to take you will need to know HTML. HTML (HyperText Markup Language) is the building block & structure for every site out there. It's the language that broswers read and know how you've laid out your content on what is a header, image, text, and button (also more). It's a very simple language and shouldn't take you that long to get your head wrapped around how to do things.

#### Knowledge

* You will need to know every HTML tag and what it does, and where it goes in the HTML

##### HTML Elements

* [mdn](https://developer.mozilla.org/en-US/docs/Web/HTML)
  * [Every HTML Element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element)
* Doctype
  * doctype is a required tag that's what tells the browser what type of document it's looking at so it knows how to render the page.
  * `<!DOCTYPE html>`
* html
  * The `html` tag wraps around all of your HTML code, it generally is your second line after the doctype and last line of your HTML pages.
  * `<html> ... </html>`
* head
  * The `head` is everything on your page that doesn't show to the user, it is use to name the page, load the styles & describe what's happening on the page to search engines.
  * `<head> ... </head>`
* meta
  * The `meta` tag goes in the `head` and is used to describe the page and help search engines and social sites know what this page is about. If you want Facebook to pull the right image when someone shares a page of your site you need to configure the metatags properly.
  * `<meta charset="utf-8">`
* link
  * The `link` tag is used to load in external css files (possibly other things too)
  * `<link href="style.css" rel="stylesheet">`
* script
  * `script` tag is where all your javascript goes. You generally are going to use a script tag to load an external javascript file you want to run on this page.
  * `<script src="javascript.js"></script>`
* title
  * this is your page `title` it's what shows in your browsers window.
  * `<title>My First Website</title>`
* body
  * Represents the content of an HTML document. There can be only one `<body>` element in a document.
  * `<body> ... all content goes here ... </body>`
* h1,h2,h3,h4,h5,h6
  * Heading elements implement six levels of document headings, `<h1>` is the most important and `<h6>` is the least. A heading element briefly describes the topic of the section it introduces.
  * `<h1>Page Title</h1>`
* div
  * generic container for flow content, which does not inherently represent anything. It can be used to group elements for styling purposes (using the class or id attributes), or because they share attribute values, such as lang. It should be used only when no other semantic element (such as `<article>` or `<nav>`) is appropriate.
  * `<div class="body-wrapper"> ... </div>`
* span
  * generic inline container for phrasing content, which does not inherently represent anything. It can be used to group elements for styling purposes (using the `class` or `id` attributes).
  * `<span class="description"> ... </span>`
* section
  * 
* article
* footer
* nav
* header
* aside
* button
* a
* p
* u
* b
* i
* video
* audio
* form
* input
* label
* img
* ul,ol,li
* table, thead, tbody, tr, td

##### Skills to know
* What tags are self closing?
* Proper indenting of HTML
* How do you give an element an ID or a class
  * why would you do this?
* How to give elements attributes
  * examples are `disabled`


##### Skills to show you have knowledge

* Make the browser window say your site's name `<title>`
* Link to an external css & javascript file
* Be able to build proper structure to make an HTML grid with content in it
```html
<div class="row">
  <div class="left column">
    <h1>Some cool title</h1>
    <p>Some paragraph content goes here...</p>
  </div>
  <div class="right column">
    <img src="http://placekitten.com/400/350" />
  </div>
</div>
```
* make a form that submits to a seperate page
```html
<form post="/form-submit.php">
  <label>
    First Name
    <input name="fname" type="text" /> 
  </label>
  <label>
    Last Name
    <input name="lname" type="text" /> 
  </label>
  <label>
    Email
    <input name="email" type="email" /> 
  </label>
  <input type="submit" value="submit" />
</form>
```

### Frontend Designer
The frontend designer is someone so cares about to the site looks and feels to the users. The language used to make websites styled properly is called CSS (Cascading Style Sheets). CSS is a hard one because it's easy to learn and use and get results, but hard to master and do things the right way every time.

#### Things to help
* You should use a linter to help know when you write bad CSS
  * [Stylint](https://github.com/stylelint/stylelint)
  * Here is our config:
```
"extends": [
  "stylelint-config-standard",
],
"plugins": [
  "stylelint-statement-max-nesting-depth",
],
"rules": {
  "statement-max-nesting-depth": [3, { countAtRules: false }],
  "string-quotes": "single",
  "selector-no-id": true,
  "color-hex-case": "lower",
  "number-leading-zero": "never",
  "property-no-vendor-prefix": true,
  "declaration-bang-space-after": "never",
  "declaration-bang-space-before": "always",
  "declaration-colon-space-after": "always",
  "declaration-no-important": true,
  "selector-combinator-space-after": "always",
  "selector-combinator-space-before": "always",
  "selector-pseudo-element-colon-notation": "single",
  "rule-nested-empty-line-before": "always",
  "declaration-block-properties-order": "alphabetical"
}
```

#### Knowledge
* You will want to know what a preprocessor is and how to use one
* Every common propery and what it does / when to use it
  * animation
  * background
  * border
  * bottom
  * box-sizing
  * box-shadow
  * clip
  * color
  * content
  * cursor
  * display
  * flex
  * float
  * font
  * height
  * justify-content
  * left
  * letter-spacing
  * line-height
  * list-style
  * margin
  * max-height
  * max-width
  * min-height
  * min-width
  * object-fit
  * order
  * outline
  * overflow
  * padding
  * right
  * text-align
  * text-decoration
  * text-shadown
  * text-transform
  * top
  * transform
  * vertical-align
  * width
  * z-index
* Know what box model is and be albe to describe it
* know how to make simple animations
* know what HEX codes are and what is different between them and HSLA, rgba
* px vs em vs rem
* What is responsive design
* What is mobile first and why do people do that?
* media queries
* floats, when to use them
* know how to make grids with & without flexbox
* Why don't you style with IDs
* SMACSS - what problem does it solve
  * need quick bullets on that
* Know  about nesting depth and why it's bad to nest too much
* Use linter to learn faster

##### Skills to show you have knowledge


### Frontend Functional

## Backend Developer




// pasted in stuff

Front end

3 main technologies
- HTML (hypertext markup language)
- css (cascading style sheets)
- javascript

You MUST know html as everything on the internet eventually becomes html, but you can then focus on css or javascript depending on what you ultimately want to do.

If you want to make pretty websites go html & css, if you want to make function websites with cool features learn html & javascript. I suggest leaning and being an expert at all 3 and that ultimately will make you more valuable but everyone is different. (edited)

Josh Fabean [18:41] 
Here are all the things you need to know own about html.

* HTML,Head,title,body what they are and what goes in them. 
* How to link to external css & javascript files. 
* what does proper HTML actually look like
* how to give things IDs and classes, and why?
* how to give things attributes 'disabled' or whatever
* every tag and what it does
* identifying proper structure of elements to make styling easier and not have chaps
* header tags how they're used and when to use them. 
* when to use tables (the answer is sometimes)
* meta tags what they do
* create a form and have it submit
* button vs a

Josh Fabean [18:47] 
Css

* You will want to know what a preprocessor is, why they exist and how to use them. (How they will go away/ change a lot in future because browsers are awesome)
* every part of your code (this is an attribute, a selector...)
* every common selector and what it does
* box model
* animations
* hex codes, HSLA, RGBA....
* rem em px
* responsive design / mobile first
* media queries
* floats
* grids & flex box 
* why not use IDS
* read SMACSS book / get bullet points
* architecture or good format
* using a litter / style lint and how that will make you better
* debugging sites to find problems

[18:50] 
Also since I'll be showing sass talk about variables, mixing, nesting all that stuff.

[18:53] 
Javascript

* what it is and why it exists
* drawing lines and circles in canvas
* doing math
* scoping 
* es5 vs new
* babel
* build tools
* frameworks
* Ajax requests
* loops
* array | objects
* if else
* api
* taking to Mongo server
* l defining variables
* functions 
* global variables
* node vs javascript
*

[18:54] 
Linting

