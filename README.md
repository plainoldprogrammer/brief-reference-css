# Brief Reference CSS
Brief reference of the CSS language.

---

#### Not show an element
```css
display: none;
```

#### Hide an element
```css
visibility: hidden;
```

#### Change the background to red color
```css
background: red;
background-color: red;
```

#### Change the text color to blue
```css
color: blue;
```

#### Center the body content
```css
body
{
  width: 600px;
  margin: 0 auto;
}
```

#### Change the background color of the body content
```css
body > *
{
  background: magenta;
}
```

#### No longer increase the width padding and width border of an element
```css
box-sizing: border-box;
```

#### Write a comment
```css
/* This is a comment */
```

#### Change the text size of a header
```css
h2 {
  font-size: 28px;
}
```

#### Select multiple HTML elements in the same CSS rule
```css
h1, h2, h3, h4, h5, h6 {
  font-family: "Helvetica", "Arial", sans-serif;
}
```

#### Change to a circle the bullet icon of a list
```css
ul {
  list-style-type: circle;
}
```

#### Change to a roman number the number of a list
```css
ol {
  list-style-type: lower-roman;
}
```

#### Remove the underline from the links
```css
a {
  text-decoration: none;
}
```

#### Strike deleted text
```css
p {
  text-decoration: line-through;	
}
```

#### Define the alignment of text
```css
p {
  text-align: left;
}
```

### Remove the bold from the headings
```css
h1, h2, h3, h4, h5, h6 {
  font-weight: normal;
}
```

#### Hightligh inline elements and color the block elements
```css
em, strong {
  background-color: #B2D6FF; /* Light blue */
}
```

#### Change the default box type from inline to blocks
```css
em, strong {
  display: block;
}
```

#### Turn back into inline box an element 
```css
em, strong {
  display: inline;
}
```

#### Add padding to the headers
```css
h1 {
  padding: 50px;
}
```

#### Add a padding on one side of an element
```css
p {
  padding-top: 20px;
  padding-bottom: 20px;
  padding-left: 10px;
  padding-right: 10px;
}
```

#### Shorthand for padding with 2 values
```css
p {
  padding: 20px 10px;
}
```

#### Shorthand for padding with 4 values
```css
p {
  paddding: 20px 0 20px 10px;
}
```

#### Adding a border around the head
```css
h1 {
  papdding: 50px;
  border: 1px solid #5D6063;
}
```

#### Drawing a border at the bottom of a heading
```css
h1 {
  border-botton: 1pm solid #5D6063;
}
```

#### Debug a box to know how is being rendered
```css
div {
  border: 1px solid red;
}
```

#### Add a margin at the bottom of a paragraph
```css
p {
  margin-bottom: 50px;
}
```

#### Add a border radius to a div
```css
div {
  border-radius: 5px;
}
```

#### Set bold font
```css
div {
  font-weight: bold;
}
```

#### Set the width of a div in pixels
```css
div {
  width: 200px;
}
```

#### Hide the elements content when is too big to fit
```css
div {
  overflow: hidden;
}
```

#### Add a scroll to a element if the content is too big to fit
```css
div {
  overflow: scroll;
}
```

#### Adjust automatically the elements content when is too big to fit
```css
div {
  overflow: auto;
}
```

#### Force the actual width of a box be 200px
```css
div {
  width: 200px;
  box-sizing: border-box;
}
```

#### Center the block in its parent element
```css
div  {
  width: 200px;
  margin: 20px auto;
}
```

#### Reset styles
```css
* {
  margin: 0;
  paddding: 0;
  box-sizing: border-box;
}
```

#### Define a CSS class selector
```css
.synopsis {
  color: #7E8184;
  font-style: italic;
}
```

#### Center a div (fixed width layout)
```
.page {
  width: 600px;
  margin: 0 auto;
}
```

#### Apply multiple classes to an element
```css
<div class="button call-to-action">
  Button
</div>
```

#### Descendant selector
```css
h1 em {
   /* some style */
}
```

#### Pseudoclasses of a link
```css
a:link {
  color: blue;
  text-decoration: none;
}

a:visited {
  color: purple;
}

a:hover {
  color: aqua;
  text-decoration: underline;
}

a:active {
  color: red;
}
```

#### Visited hover state and visited active state
```css
a:visited:hover {
  color: orange;
}

a:visited:active {
  color: red
}
```

#### Add an extra space to the last paragraph
```css
p:last-of-type {
  margin-bottom: 50px;
}
```

#### Display in italic the first paragraph
```css
p:first-of-type {
  font-style: italic;
}
```

#### Select only the first paragraph in a div (child selector)
```css
.page > p:first-of-type {
  color: #7E8184;
  font-style: italic;
}
```

#### CSS selector for id 
```css
#button-2 {
}
```

#### CSS selector for class
```css
.button-2 {
}
```

#### Select all the elements
```css
* {
}
```

#### Change all boxes to border box
```css
* {
  box-sizing: border-box;
}
```

#### Change all boxes to content box
```css
* {
  box-sizing: content-box;
}
```

#### Align block element to the left
```css
.sidebar {
  float: left;
}
```

#### Align block element to the right
```css
.sidebar {
  float: right;
}
```

#### Align block element to the center
```css
.sidebar {
  margin: 0 auto;
}
```

#### Cancel float element
```css
.sidebar {
  float: none;
}
```

#### Clear an element to appear after any floats
```css
.footer {
  clear: both;
  height: 200px;
}
```

#### Clear only the left values
```css
.footer {
  clear: right;
  height: 200px;
}
```

#### Clear only the right values
```css
.footer {
  clear: right;
  height: 200px;
}
```

#### Recognize the height of any floated element in a div
```css
.page {
  overflow: hidden;
}

<div class="page">
  <div class="sidebar">Sidebar</div>
  <div class="content">Content</div>
</div>
```

#### Turn one HTML element into a flex container
```css
.menu-container {
  display: flex;
}
```

#### Define the horizontal alignment of the items of a flexbox
```css
.menu-container {
  display: flexbox;
  justify-content: center;
}
```

#### Align vertically the content of a flex container
```css
.header {
  align-items: center;
}
```

#### Force items  that don't fit to getbBumped down to the next row
```css
.photo-grid {
  /* ... */
  flex-wrap: wrap;
}
```

#### Change the direction of a container from row to column
```css
.photo-grid {
  flex-direction: column;
}
```

#### Set the direction of a container to row
```css
.photo-grid {
  flex-direction: row;
}
```

#### Reverse the order of everything
```css
.photo-grid {
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
  flex-direction: row-reverse;
}
```

#### Change the order of a flex item
```css
.photo-grid {
  order: 1;
}
```

#### Align a flex item individually
```css
.social,
.subscribe {
  alight-left: flex-end;
}
```

#### Tell the flex items to stretch to match the width of their parent content
```css
.footer-item {
  flex: 1;
}
```

#### Make a flex item to be fixed width
```css
.footer-one,
.footer-three {
  flex: initial;
  width: 300px;
}
```

#### Eats up all the extra space in a flex container
```css
.signup {
  margin-left: auto;
}
```

#### Create a flex container
```css
display: flex;
```

#### Make a relative positioning an element
```css
.item-relative {
  position: relative;
}
```

#### Make an absolute positioning an element
```css
.item-absolute {
  position: absolute;
}
```

#### Make a fixed positioning an element
```css
.item-fixed {
  position: fixed;
}
```

#### Make a list appear an horizontal menu
```css
.menu > li {
  display: inline;
}

.menu > li:last-of-type {
  margin-right: 0;
}
```

#### Child selector
```css
.menu > li {
   display: inline;
}
```

#### Descendant selector
```css
.information p {
  background-color: gray;
}
```

#### Increment the z-index
```css
.dropdown > span {
  z-index: 2;
  position: relative;
}
```

#### Set the cursor as pointer
```css
.dropdown > span {
  cursor: pointer;
}
```

#### Change the background color depending on the screen size
```css
@media only screen and (max-width: 500px) {
  body {
    background-color: #F09A9D;
  }
}

@media only screen and (min-width: 501px) and (max-width: 960px) {
  body {
    background-color: #F5CF8E;
  }
}

@media only screen and (min-width: 961px) {
  body {
    background-color: #B2D6FF;
  }
}
```

#### Cap the width of the illustration to its inherent width
```css
<div class="section content">
  <img class="illustration" src="images/illustration.svg" style="max-width: 500px">
</div>
```

#### Make the semantic elements behave like divs In legacy browsers
```css
section, article, aside, footer, header, nav {
  display: block;
}
```

#### Attribute selector
```css
.form-row input[type="text"] {
}
```

#### Apply a theme color for chrome in android
```css
<meta name="theme-color" content="#db5945"/>
```

#### Disable the resize in a text area
```css
textarea {
  resize: none;
}
```

#### Include a web font
```css
@font-face {
  font-family: "Roboto";
  src: url("Roboto-Light-webfont.woff") format("woff");
}
```

#### Verify that the bold and italic faces really are being synthesized
```css
em, strong {
  font-synthesis: none;
}
```

#### Include multiple font face of the same font family (the right way)
```css
@font-face {
  font-family: "Roboto";
  src: url("Roboto-Light-webfont-woff") format("woff");
  font-style:  normal;
  font-weight: 300;
}

@font-face {
  font-family: "Roboto";
  src: url("Roboto-LightItalic-webfont.woff") format("woff");
  font-style: italic;
  font-weight: 300;
}

@font-face {
  font-family: "Roboto";
  src: url("Roboto-Bold-webfont.woff") format("woff");
  font-style: normal;
  font-weight: 700;
}
```

#### Paragraph indentation
```css
.paragraph-indent p {
  text-indent: 1em;
  margin-bottom: 0;
}

.paragraph-indent p:first-of-type {
  text-indent: 0;
}

NOTE:	Never use indents and margins. Use only only at the time.
```

#### Align the text to the left
```css
.left {
  text-align: left;
}
```

#### Center the text
```css
.center {
  text-align: center;
}
```

#### Justify the text
 ```css
 .jusutify {
  text-align: justify;
}
```

#### Align horizontal and vertical the text inside a div
```css
.button {
  widht: 80px;
  height: 80px;
  text-align: center;
  line-height: 80px;
}

NOTE:	The properties "width" and "line-height" should bethe same.
```

#### Change the background color depending on the window size
```css
@media (max-width: 640px) {
  body {
    background-color: blue;
  }
}

@media (min-width: 641px) {
  body {
    background-color: red;
  }
}
```

#### Global selector
```css
* {
}
```

#### Reset all the styles
```css
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
```

#### Remove the background of an input
```css
.some-class {
  background: none;
}

<input type="number" class="some-class" />
```

#### Making an element semi transparent
```css
.the-element {
  opacity: 50%;
}
```

#### Define a custom property at document level
```css
:root {
  --color-primary: #5ec576;
}

NOTE:  ":root" is equivalent to the "documentProperty" in JavaScript.
```

#### Select an h1 heading with a paragraphm element that inmmediately follows it
```css
h1:has(+ p) {
  background-color: yellow;
}
```

#### Truncate text and show ellipsis
```css
.text
{
  white-space: nowrap;
  overflow: hidden;
  text-overflow: ellipsis;
  width: 100px;
}
```
