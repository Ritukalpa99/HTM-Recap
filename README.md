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

