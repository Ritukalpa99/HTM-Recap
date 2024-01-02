# HTML 
HTML Survival guide

# Chapter 1 - Start here
Every page starts with opening and closing `html` tags and everything else on the page goes between those tags.
html pages have 2 main area :
- one area contains data that in not seen on the page but is considered to be meta-data about the page : it is the `head` area
- The next area is the part the everybody sees in the browser. It's the `body` element

`h1` is the biggest heading, with `h6`being the smallest

`<html lang="en">` : language attribute  
`<meta charset="UTF-8">` : meta tag  
`<!DOCTYPE html>` : doctype declaration needed to every html file.

# Chapter 2 - Head elements
- `<meta>` tags will be picked up by search engines.  
- Adding a favicon. `<link rel="icon" href="path" type="image/x-icon">`
- - `rel` stands for relate/relation; how does this relate to the webpage ? It's an icon.
- - `href` : referencing a resource
- - `type`: What type of resource is this.  
- `head` is the area where we'll link `css` and `js` files and other resources we pull from web.

# Chapter 3 - Text Basics
- Whitespace collapsing : We can have many whitespace in between text, but it won't be displayed in the webpage.  
- `block` level element : Every element starts on a new line.  
- `html entity` : Suppose we need to use less than, greater than, or even whitespaces in our html.
- - html entity start with `&`
- - `&nbsp;` - creates space
- - `&lt;` - less than
- `<abbr title="Mozilla Developer Network">MDN</abbr>` : For abbreviations (Not available for screen readers).
- `<address>` tag
