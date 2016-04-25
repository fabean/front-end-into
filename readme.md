
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
* [html](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/html)
  * The `html` tag wraps around all of your HTML code, it generally is your second line after the doctype and last line of your HTML pages.
  * `<html> ... </html>`
* [head](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/head)
  * The `head` is everything on your page that doesn't show to the user, it is use to name the page, load the styles & describe what's happening on the page to search engines.
  * `<head> ... </head>`
* [meta](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/meta)
  * The `meta` tag goes in the `head` and is used to describe the page and help search engines and social sites know what this page is about. If you want Facebook to pull the right image when someone shares a page of your site you need to configure the metatags properly.
  * `<meta charset="utf-8">`
* [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/link)
  * The `link` tag is used to load in external css files (possibly other things too)
  * `<link href="style.css" rel="stylesheet">`
* [script](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/script)
  * `script` tag is where all your javascript goes. You generally are going to use a script tag to load an external javascript file you want to run on this page.
  * `<script src="javascript.js"></script>`
* [title](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/title)
  * this is your page `title` it's what shows in your browsers window.
  * `<title>My First Website</title>`
* [body](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/body)
  * Represents the content of an HTML document. There can be only one `<body>` element in a document.
  * `<body> ... all content goes here ... </body>`
* h1,h2,h3,h4,h5,h6
  * https://developer.mozilla.org/en-US/docs/Web/HTML/Element/h1
  * https://developer.mozilla.org/en-US/docs/Web/HTML/Element/h2
  * https://developer.mozilla.org/en-US/docs/Web/HTML/Element/h3
  * https://developer.mozilla.org/en-US/docs/Web/HTML/Element/h4
  * https://developer.mozilla.org/en-US/docs/Web/HTML/Element/h5
  * https://developer.mozilla.org/en-US/docs/Web/HTML/Element/h6
  * Heading elements implement six levels of document headings, `<h1>` is the most important and `<h6>` is the least. A heading element briefly describes the topic of the section it introduces.
  * `<h1>Page Title</h1>`
* [div](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/div)
  * generic container for flow content, which does not inherently represent anything. It can be used to group elements for styling purposes (using the class or id attributes), or because they share attribute values, such as lang. It should be used only when no other semantic element (such as `<article>` or `<nav>`) is appropriate.
  * `<div class="body-wrapper"> ... </div>`
* [span](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/span)
  * generic inline container for phrasing content, which does not inherently represent anything. It can be used to group elements for styling purposes (using the `class` or `id` attributes).
  * `<span class="description"> ... </span>`
* [section](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/section)
  * Represents a generic section of a document, i.e., a thematic grouping of content, typically with a heading. Each `<section>` should be identified, typically by including a heading (`<h1>-<h6>` element) as a child of the `<section>` element.
  * `<section class="this-section"> ... </section>`
* [article](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/article)
  * Represents a self-contained composition in a document, page, application, or site, which is intended to be independently distributable or reusable (e.g., in syndication). This could be a forum post, a magazine or newspaper article, a blog entry, an object, or any other independent item of content.
  * `<article> ... </article>`
* [footer](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/footer)
  * Represents a footer for its nearest sectioning content or sectioning root element. A footer typically contains information about the author of the section, copyright data or links to related documents.
  * `<footer> ... </footer>`
* [nav](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/nav)
  * Represents a section of a page that links to other pages or to parts within the page: a section with navigation links.
  * `<nav class="main-nav"><a href="/">Home</a> ... </nav>`
* [header](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/header)
  * Represents a group of introductory or navigational aids. It may contain some heading elements but also other elements like a logo, wrapped section's header, a search form, and so on.
  * `<header><nav>...</header>`
* [aside](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/aside)
  * epresents a section of the page with content connected tangentially to the rest, which could be considered separate from that content. These sections are often represented as sidebars or inserts.
  * `<aside class="sidebar-links"> ... </aside>`
* [button](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/button)
  * Represents a clickable button.
  * `<button>click me!</button>`
* [a](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/a)
  * defines a hyperlink to a location on the same page or any other page on the Web.
  * `<a href="https://google.com">Google</a>
  * These get used wrong a lot
    * Good
      * `To use a good search engine, you should check out <a href="https://google.com">Google.com</a>.`
    * Bad
      * `To use a good search engine, checkout out Google by <a href="https://google.com">clicking here</a>.
* [p](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/p)
  * Represents a paragraph of text.
  * `<p>paragraphs go here</p>`
* [u](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/u)
  * Renders text with an underline, a line under the baseline of its content.
  * `A book worth reading is <u>The Pragmatic Programmer</u>.`
* [b](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/b)
  * Represents a span of text stylistically different from normal text, without conveying any special importance or relevance.
  * `Please only use HTML for <b>good</b>.`
* [i](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/i)
  * Represents a range of text that is set off from the normal text for some reason, for example, technical terms, foreign language phrases, or fictional character thoughts. It is typically displayed in italic type.
  * `A book worth reading is <i>The Pragmatic Programmer</i>.`
* [video](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/video)
  * Embed video content in a document. The video element contains one or more video sources. To specify a video source, use either the src attribute or the `<source>` element; the browser will choose the most suitable one.
  * 
  ```html
  <video width="480" controls poster="https://archive.org/download/WebmVp8Vorbis/webmvp8.gif" >
    <source src="https://archive.org/download/WebmVp8Vorbis/webmvp8_512kb.mp4" type="video/mp4">
    <source src="https://archive.org/download/WebmVp8Vorbis/webmvp8.ogv" type="video/ogg">
    <source src="https://archive.org/download/WebmVp8Vorbis/webmvp8.webm" type="video/webm">
    Your browser doesn't support HTML5 video tag.
  </video>
```
* [audio](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/audio)
  * Embed sound content in documents. It may contain one or more audio sources, represented using the src attribute or the `<source>` element; the browser will choose the most suitable one.
  *
  ```html
  <audio controls="controls">
    Your browser does not support the <code>audio</code> element.
    <source src="foo.wav" type="audio/wav">
  </audio>
  ```
* [form](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/form)
  * Represents a document section that contains interactive controls to submit information to a web server.
  * 
  ```html
  <form action="" method="post">
    <label for="POST-name">Name:</label>
    <input id="POST-name" type="text">
    <input type="submit" value="Save">
  </form>html
  ```
* [input](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input)
  * create interactive controls for web-based forms in order to accept data from the user. How an `<input>` works varies considerably depending on the value of its type attribute.
  * `<input type="text" value="Type here">`
* [label](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/label)
  * Represents a caption for an item in a user interface.
  * `<label>First name: <input type="text" name="fname" /></label>`
* [img](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/img)
  * Represents an image in the document.
  * `<img src="http://placekitten.com/400/300" />`
* ul,ol,li
  * https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ul
  * https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ol
  * https://developer.mozilla.org/en-US/docs/Web/HTML/Element/li
  * ordered list (1,2,3...) and unordered listed (*, *, * ...)
  *
  ```html
  <ol>
    <li>first priority</li>
    <li>second priority<li>
  </ol>
  <ul>
    <li>bullet 1</li>
    <li>bullet 2</li>
  </ul>
  ```
* table, thead, tbody, tr, td
  * https://developer.mozilla.org/en-US/docs/Web/HTML/Element/table
  * Tables have a bad rap, because they used to be used for everything. If you just use them to actually make tables of data it works out great.
  *
  ```html
    <table>
      <thead>
        <tr>
          <th>Header content 1</th>
          <th>Header content 2</th>
        </tr>
      </thead>
      <tfoot>
        <tr>
          <td>Footer content 1</td>
          <td>Footer content 2</td>
        </tr>
      </tfoot>
      <tbody>
        <tr>
          <td>Body content 1</td>
          <td>Body content 2</td>
        </tr>
      </tbody>
    </table>
  ```
* I'm sure I've missed some important HTML elements but I used all of the ones I find myself using on a weekly basis. 

##### Skills to know
* What tags are self closing?
  * `<input type="text" name="fname" />`
  * `<img src="#" />`
  * `<link ... />`
* Proper indenting of HTML
  * indenting and making your code look pretty is very important. This is a skill you should learn with HTML and it will carry over to every language you can type.
* How do you give an element an ID or a class
  * why would you do this?
    * ID
      * When you give an element an ID you can now go to yoururl.com#theIDvalue which is great for linking people to lower on the page.
      * In JavaScript grabbing an element by an ID is way faster than a class, because there can only be one ID per page so once it finds it you're done.
    * Class
      * Classes are using in CSS & JavaScript (when you need more than 1 element to be grabbed in JS) so it's good to put classes on multiple elements that share styling. For example a class of `error` could be used to outline inputs with red so you know where you messed up filling out the form.
* How to give elements attributes
  * examples are `disabled`
  * https://developer.mozilla.org/en-US/docs/Web/HTML/Attributes


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
* You should use a linter to help know when you write bad CSS. This runs when you save and lets you know all the mistakes you made. The hard thing about CSS is your code could run just fine but that doesn't mean it's good or right.
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
  * What is it?
    * A preprocessor is a program that takes one type of data and converts it to another type of data.
    * So in CSS you write in a preprocess language, which gives you some sort of functionality that the final language does not support but you feel like is benificial.
  * Why do they exist?
    * CSS is a pretty dumb language, and isn't efficient. So someone came up with the idea to add features that would make CSS better, made a different language, but since browsers only understand CSS it converts it to CSS when it's done.
  * [Sass](http://sass-lang.com/) is probably the most popular preproccessor out there
    * **Features:**
      * **Variables:** Do you use the same color of blue all over your site? Why not just use a variable of `$blue` instead of trying to remember the six digit hex code everytime. Then what if later your designer says you used the wrong color blue, now you only need to change that variable once instead of doing a find and replace across the whole project which could be thousands of lines of CSS.
      * **Nesting:** To me this is the best reason to use Sass even if you use no other feature. In CSS you have to say `.container { background: red; } .container .child { background: green; }`. That's annoying because you have to repeat yourself in Sass you write
      ```sass
        .container {
          background: red;

          .child {
            background: green;
          }
        }
      ```
      Isn't that nicer? Yes, yes it is.
      * **Multiple Files:** In CSS you *can* have multiple files but then you have to include all of those in your HTML document which is sort of lame. In Sass you can make as many files as you want, then in compile them all down to just one file and compress it to amke the browser happy but it still makes sense to you.
      * There are tons of features, and I suggest reading the docs and playing around but to me those three listed are more than enough to make the jump and learn the rest later.
* Every common propery and what it does / when to use it
  * [animation](https://developer.mozilla.org/en-US/docs/Web/CSS/animation)
    * This is the shorthand to define what animation an element is using. This is used to make elements move around the page.
    * [hamburger menu](http://codepen.io/fabean/pen/XXegoQ)
    * [loading spinner](http://codepen.io/fabean/pen/LEBdmp)
  * [background](https://developer.mozilla.org/en-US/docs/Web/CSS/background)
    * Shorthand for all the different things you can do to an elements background. Most common usages including changing the background color, or putting an image in the background of something.
  * [border](https://developer.mozilla.org/en-US/docs/Web/CSS/border)
    * Setting the border of an element. Used to give something a border...
  * [border-radius](https://developer.mozilla.org/en-US/docs/Web/CSS/border-radius)
    * Want something with rounded corners? this is your friend for all you web 2.0 people
  * [bottom](https://developer.mozilla.org/en-US/docs/Web/CSS/bottom)
    * participates in specifying the position of positioned elements.
  * [box-sizing](https://developer.mozilla.org/en-US/docs/Web/CSS/box-sizing)
    * property is used to alter the default CSS box model used to calculate width and height of the elements. It is possible to use this property to emulate the behavior of browsers that do not correctly support the CSS box model specification.
    * This is actually hard to understand, but it's very useful. I'll give you an example.
      * You define the width of an element as 100px wide. But you also added a padding to this element of 10px, so how wide is your element? 120px wide, WHAT!? That's the default behavior of the box model. Well here comes the use of your little new best friend `box-sizing: border-box;` This makes it so if you define the width of 100px it will always be 100px no matter what padding, border, or whatever you add to your element.
  * [box-shadow](https://developer.mozilla.org/en-US/docs/Web/CSS/box-shadow)
    * Property describes one or more shadow effects as a comma-separated list. It enables you to cast a drop shadow from the frame of almost any element.
  * [clip-path](https://developer.mozilla.org/en-US/docs/Web/CSS/clip-path)
    * prevents a portion of an element from getting displayed by defining a clipping region to be displayed i.e, only a specific region of the element is displayed.
    * Basically to make really cool designs in CSS you use this
    * [github logo in CSS](http://codepen.io/chreeswright/pen/grXpjL)
  * [color](https://developer.mozilla.org/en-US/docs/Web/CSS/color)
    * sets the foreground color of an element's text content, and its decorations. It doesn't affect any other characteristic of the element; it should really be called text-color and would have been named so, save for historical reasons and its appearance in CSS Level 1.
  * [content](https://developer.mozilla.org/en-US/docs/Web/CSS/content)
    * CSS property is used with the ::before and ::after pseudo-elements to generate content in an element.
    * You can get super crazy with :before & :after like my [Mario in CSS](http://codepen.io/fabean/pen/XJNpbd?editors=0100)
  * [cursor](https://developer.mozilla.org/en-US/docs/Web/CSS/cursor)
    * property specifies the mouse cursor displayed when the mouse pointer is over an element.
    * Want to make it so the moust looks like an element is clickable? this is how we do it.
  * [display](https://developer.mozilla.org/en-US/docs/Web/CSS/display)
    * CSS property specifies the type of rendering box used for an element. In HTML, default display property values are taken from behaviors described in the HTML specifications or from the browser/user default stylesheet.
    * Display inline elements go left & right, display block go up & down.
  * [flex](https://developer.mozilla.org/en-US/docs/Web/CSS/flex)
    * Just read this [guide to flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
    * Flexbox is the savior to CSS
  * [float](https://developer.mozilla.org/en-US/docs/Web/CSS/float)
    * specifies that an element should be taken from the normal flow and placed along the left or right side of its container, where text and inline elements will wrap around it.
    * Useful to get text to wrap around an image or an older way to make grids (now people use `display: inline-block;` at least last I heard they did)
  * [font](https://developer.mozilla.org/en-US/docs/Web/CSS/font)
    * shorthand property for setting font-style, font-variant, font-weight, font-size, line-height and font-family, or a way to set the element's font to a system font, using specific keywords.
  * [height](https://developer.mozilla.org/en-US/docs/Web/CSS/height<Paste>)
    * Specifies the height of the content area of an element. The content area is inside the padding, border, and margin of the element.
  * [justify-content](https://developer.mozilla.org/en-US/docs/Web/CSS/justify-content)
    * property defines how the browser distributes space between and around flex items along the main-axis of their container.
  * [left](https://developer.mozilla.org/en-US/docs/Web/CSS/left)
    * specifies part of the position of positioned elements.
  * [letter-spacing](https://developer.mozilla.org/en-US/docs/Web/CSS/letter-spacing)
    * specifies spacing behavior between text characters.
  * [line-height](https://developer.mozilla.org/en-US/docs/Web/CSS/line-height)
    * On block level elements, the line-height property specifies the minimum height of line boxes within the element.
    * On non-replaced inline elements, line-height specifies the height that is used to calculate line box height. On replaced inline elements such as buttons or other input elements, line-height has no effect.
    * Mostly used to change the space between lines of text.
  * [list-style](https://developer.mozilla.org/en-US/docs/Web/CSS/list-style)
    * shorthand property for setting list-style-type, list-style-image and list-style-position.
    * Mostly used when people make a menu a `ul` but you don't want bullet points `list-style: none;`
  * [margin](https://developer.mozilla.org/en-US/docs/Web/CSS/margin)
    * Sets the margin for all four sides.
    * It's the space around the element.
  * [max-height](https://developer.mozilla.org/en-US/docs/Web/CSS/max-height)
    * used to set the maximum height of an element. It prevents the used value of the height property from becoming larger than the value specified for max-height.
    * I don't really use this that much, but it's a common thing. Height as you will learn is weird on the web.
  * [max-width](https://developer.mozilla.org/en-US/docs/Web/CSS/max-width)
    * used to set the maximum width of a given element. It prevents the used value of the width property from becoming larger than the value specified for max-width.
    * I use this a lot more than `max-height` but mostly on "we don't want our website getting any wider than 1440px wide" `.row { max-width: 1440px; }`
  * [min-height](https://developer.mozilla.org/en-US/docs/Web/CSS/min-height)
    * used to set the minimum height of a given element. It prevents the used value of the height property from becoming smaller than the value specified for min-height.
  * [min-width](https://developer.mozilla.org/en-US/docs/Web/CSS/min-width)
    * used to set the minimum width of a given element. It prevents the used value of the width property from becoming smaller than the value specified for min-width.
  * [object-fit](https://developer.mozilla.org/en-US/docs/Web/CSS/object-fit)
    * specifies how the contents of a replaced element should be fitted to the box established by its used height and width.
    * used when you're using an actual `<img>` as a background image and need to make it fit whatever it's container with without skewing the dimensions.
  * [order](https://developer.mozilla.org/en-US/docs/Web/CSS/order)
    * specifies the order used to lay out flex items in their flex container. Elements are laid out in the ascending order of the order value. Elements with the same order value are laid out in the order in which they appear in the source code.
  * [outline](https://developer.mozilla.org/en-US/docs/Web/CSS/outline)
    * shorthand property for setting one or more of the individual outline properties outline-style, outline-width and outline-color in a single declaration. In most cases the use of this shortcut is preferable and more convenient.
    * I don't think I've ever used this.
  * [overflow](https://developer.mozilla.org/en-US/docs/Web/CSS/overflow)
    * specifies whether to clip content, render scrollbars or just display content when it overflows its block level container.
    * Very useful if you have floated content, put `overflow: hidden;` on the wrapper and it will kill all the floats and keep your page happy.
  * [padding](https://developer.mozilla.org/en-US/docs/Web/CSS/padding)
    * Sets the padding space on all sides of an element. The padding area is the space between the content of the element and its border. Negative values are not allowed.
    * Padding is inside the element, so if you don't want your text touching the edge of your box you need padding.
  * [position](https://developer.mozilla.org/en-US/docs/Web/CSS/position)
    * chooses alternative rules for positioning elements, designed to be useful for scripted animation effects.
    * By default things are `position: static`.
    * **All `position: absolute` elements top,left,right,bottom is measured of their closest parent element with `position: relative` that's important to remember!**
    * `position: fixed` is measured off the whole window, it's how you get elements to scroll around the page with you
      * Also how you make modals, but by reading this you're taking an oath to not create modals!
  * [right](https://developer.mozilla.org/en-US/docs/Web/CSS/right)
    * specifies part of the position of positioned elements.
    * Important for absolutely positioned elements.
  * [text-align](https://developer.mozilla.org/en-US/docs/Web/CSS/text-align)
    * describes how inline content like text is aligned in its parent block element. text-align does not control the alignment of block elements, only their inline content.
    * You use this to center text: `text-align: center;`
  * [text-decoration](https://developer.mozilla.org/en-US/docs/Web/CSS/text-decoration)
    * used to set the text formatting to underline, overline, line-through or blink. Underline and overline decorations are positioned under the text, line-through over it.
    * need your `<a>` to not be underlined? `text-decoration: none;`
  * [text-shadow](https://developer.mozilla.org/en-US/docs/Web/CSS/text-shadow)
    * adds shadows to text. It accepts a comma-separated list of shadows to be applied to the text and text-decorations of the element.
    * Web 2.0 FTW!
  * [text-transform](https://developer.mozilla.org/en-US/docs/Web/CSS/text-transform)
    * specifies how to capitalize an element's text. It can be used to make text appear in all-uppercase or all-lowercase, or with each word capitalized.
    * Use this to capitalize all your menu links instead of actually writing them out in all caps, no need to shout on the internet.
  * [top](https://developer.mozilla.org/en-US/docs/Web/CSS/top)
    * specifies part of the position of positioned elements. It has no effect on non-positioned elements.
  * [transform](https://developer.mozilla.org/en-US/docs/Web/CSS/transform)
    * lets you modify the coordinate space of the CSS visual formatting model. Using it, elements can be translated, rotated, scaled, and skewed.
    * if you're animating something left, right, up or down it's better to use `transform: translate(10px 50px)` than left,right... because sub-pixel rendering and GPU optimization.
      * The things you learn the more you do this...
    * Lets you rotate things! `transform: rotate(360deg);`
  * [transition](https://developer.mozilla.org/en-US/docs/Web/CSS/transition)
    * shorthand property for transition-property, transition-duration, transition-timing-function, and transition-delay. It enables you to define the transition between two states of an element. Different states may be defined using pseudo-classes like :hover or :active or dynamically set using JavaScript.
    * What when someone hovers your button it fades to a darker color? `transition: background 300ms ease;` will accomplish that for you.
  * [vertical-align](https://developer.mozilla.org/en-US/docs/Web/CSS/vertical-align)
    * specifies the vertical alignment of an inline or table-cell box.
    * This never actually works the way or when you want it to.
  * [width](https://developer.mozilla.org/en-US/docs/Web/CSS/width)
    * specifies the width of the content area of an element. The content area is inside the padding, border, and margin of the element.
  * [z-index](https://developer.mozilla.org/en-US/docs/Web/CSS/z-index)
    * specifies the z-order of an element and its descendants. When elements overlap, z-order determines which one covers the other. An element with a larger z-index generally covers an element with a lower one.
    * please don't just jump to `z-index: 9999999;` have standards please
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

