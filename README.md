# learn-HTML-CSS-Javascript
a guide by Kenny Zhang

these three languages teaches you the basics of front-end programming
- html (hyper text markup language) tell the browser how to structure a web page
- css (cascading style sheet) describes how HTML elements are to be displayed on screen, paper, or in other media
- javascript makes web pages interactive

put simply, html is the bare bones of the human body, css is the skin that covers the bones, and javascript is the individual parts of the human body that each have their own job

[here](https://github.com/kennyszhang/resources) is a list of resources to aid you in your journey. i highly suggest freecodecamp and the odin project.

## table of contents
- [syntax-references](#syntax-references)
- [mathematical-operators](#mathematical-operators)
- [comparison-operators](#comparison-operators)
- [basics of html](#basics-of-html) WORK IN PROGRESS

## syntax-references
<img src="images/0.png">

also i suggest you look here: [w3schools javascript syntax](https://www.w3schools.com/js/js_syntax.asp)

##  mathematical-operators
the chart below are the mathematical operators used in javascript. assume a=5 and b=2

some things to keep in mind:
- the majority of programming languages uses the same basic symbols (or operators) (+ , - , * , / )

- other operators not included above depends on the programming language you are using
  - for example: modulus (or modulo) can be either `%` or `MOD`

- in programming, you also have to follow the operator rules of PEMDAS (parentheses, exponents, multiply/ divide, add/ subtract)

- you can also combine (or concatenate) strings
  - for example:

    `"hello" + " " + "world"` ==> `"hello world"` 

<img src="images/1.png">

## comparison-operators
assume x=5

some things to keep in mind:
- personally, i have never used 'strict not equal'

<img src="images/2.png">

## basics-of-html 
WORK IN PROGRESS
- html uses two things: tags and attributes

- what are tags?
  - an html tag is a reserved word surrounded by angle brackets
- for example:

  `<p> Hello World! </p>`

- most tags must be opened `<p>` and closed `</p>` in order to function
- tip: you can wrap your content with multiple tags, just make sure you close the tags correctly
- for example:

  `<strong><em> Hello World! </em></strong>`

- the `<em>` tag has to be closed inside of the `<strong>` tag

- what are attributes?
  - attributes contain additional pieces of information inside the opening tag
- for example:

  `<img src="panda.jpg">`

- the image source `src` is the attribute of the `<img>` tag
- also this is one of the few tags in html that does not have a closed tag :O

## closing notes
- i know that suggesting w3schools might not be the best choice, but their guides are easy enough to understand
  - to this day, i still reference their material and some cheatsheets because i cannot memorize everything. this is normal starting out, but once you work with the languages for a long time, you will slowly memorize the content