# Brief Reference CSS
Brief reference of the CSS language.

---

#### Not show an element
```
display: none;
```

#### Hide an element
```
visibility: hidden;
```

#### Change the background to red color
```
background: red;
background-color: red;
```

#### Change the text color to blue
```
color: blue;
```

#### Center the body content
```
body
{
  width: 600px;
  margin: 0 auto;
}
```

#### Change the background color of the body content
```
body > *
{
  background: magenta;
}
```

#### No longer increase the width padding and width border of an element
```
box-sizing: border-box;
```

#### Write a comment
```
/* This is a comment */
```

#### Change the text size of a header
```
h2 {
  font-size: 28px;
}
```

#### Select multiple HTML elements in the same CSS rule
```
h1, h2, h3, h4, h5, h6 {
  font-family: "Helvetica", "Arial", sans-serif;
}
```

#### Change to a circle the bullet icon of a list
```
ul {
  list-style-type: circle;
}
```

#### Change to a roman number the number of a list
```
ol {
  list-style-type: lower-roman;
}
```

#### Remove the underline from the links
```
a {
  text-decoration: none;
}
```

#### Strike deleted text
```
p {
  text-decoration: line-through;	
}
```

#### Define the alignment of text
```
p {
  text-align: left;
}
```

### Remove the bold from the headings
```
h1, h2, h3, h4, h5, h6 {
  font-weight: normal;
}
```

#### Hightligh inline elements and color the block elements
```
em, strong {
  background-color: #B2D6FF; /* Light blue */
}
```

#### Change the default box type from inline to blocks
```
em, strong {
  display: block;
}
```

#### Turn back into inline box an element 
```
em, strong {
  display: inline;
}
```

#### Add padding to the headers
```
h1 {
  padding: 50px;
}
```

#### Add a padding on one side of an element
```
p {
  padding-top: 20px;
  padding-bottom: 20px;
  padding-left: 10px;
  padding-right: 10px;
}
```

#### Shorthand for padding with 2 values
```
p {
  padding: 20px 10px;
}
```

#### Shorthand for padding with 4 values
```
p {
  paddding: 20px 0 20px 10px;
}
```

#### Adding a border around the head
```
h1 {
  papdding: 50px;
  border: 1px solid #5D6063;
}
```

#### Drawing a border at the bottom of a heading
```
h1 {
  border-botton: 1pm solid #5D6063;
}
```

#### Debug a box to know how is being rendered
```
div {
  border: 1px solid red;
}
```

#### Add a margin at the bottom of a paragraph
```
p {
  margin-bottom: 50px;
}
```

#### Add a border radius to a div
```
div {
  border-radius: 5px;
}
```

#### Set bold font
```
div {
  font-weight: bold;
}
```

#### Set the width of a div in pixels
```
div {
  width: 200px;
}
```

#### Hide the elements content when is too big to fit
```
div {
  overflow: hidden;
}
```

#### Add a scroll to a element if the content is too big to fit
```
div {
  overflow: scroll;
}
```

#### Adjust automatically the elements content when is too big to fit
```
div {
  overflow: auto;
}
```

#### Force the actual width of a box be 200px
```
div {
  width: 200px;
  box-sizing: border-box;
}
```

#### Center the block in its parent element
```
div  {
  width: 200px;
  margin: 20px auto;
}
```
