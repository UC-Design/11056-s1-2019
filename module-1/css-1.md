# Module 1: HTML5 and CSS

## CSS 1: CSS Fundamentals



## Introduction

- We will create a CSS file
- Save it in the correct location
- Link to it from our HTML page
- Write some basic styles



## Key points

The link to your stylesheet should look like:

```
<link rel="stylesheet" href="assets/css/styles.css">
```

The file should be saved in the css folder, which is inside the assets folder

All file names and folder names are in **lowercase** and **no spaces**

Code is available in GitHub




## CSS reset


We will apply a CSS reset to our document



## But why?

Each browser has different default styles built in, but they aren't consistent

As Chris Coyier (of CSS Tricks) [explains](https://css-tricks.com/reboot-resets-reasoning/):

>the whole idea of a CSS reset is to deal with styling inconsistencies across browsers. For example, just now I popped a `<button>` onto a page with no other styling whatsoever. Chrome applies `padding: 2px 6px 3px;` - Firefox applies `padding: 0 8px;`. A CSS reset would apply new padding to that element, so that all browsers are consistent about what they apply. 


## Two main options

Eric Meyer’s reset:
[http://meyerweb.com/eric/tools/css/reset/](http://meyerweb.com/eric/tools/css/reset/)

Normalize.css:
[http://necolas.github.io/normalize.css/](http://necolas.github.io/normalize.css/)


# CSS fundamentals


## Introduction

- Why is it called CSS?
- Basic syntax 
- Targeting elements
- Basic properties


## Why CSS?

Stands for: Cascading Style Sheets  
- Styles cascade from the top to the bottom
- Styles added later can override ones from the top

Works internally as well  
- If you include the same property twice, the latter one will be used


## Syntax
<img src="images/css-1-1.png" alt="Syntax" height="500px;">


## Syntax

<img src="images/css-1-2.png" alt="Syntax" height="500px;">                    




