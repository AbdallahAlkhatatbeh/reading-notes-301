## EJS

What is EJS?
What is the "E" for? "Embedded?" Could be. How about "Effective," "Elegant," or just "Easy"? EJS is a simple templating language that lets you generate HTML markup with plain JavaScript. No religiousness about how to organize things. No reinvention of iteration and control-flow. It's just plain JavaScript. 


 
Use plain JavaScript
We love JavaScript. It's a totally friendly language. All templating languages grow to be Turing-complete. Just cut out the middle-man, and use JS!

Fast development time
Don't waste time and attention figuring out arcane new syntax because 'elegance' — or how to preprocess your data so it will actually render right.

Simple syntax
JavaScript code in simple, straightforward scriptlet tags. Just write JavaScript that emits the HTML you want, and get the job done!

Speedy execution
We all know how fast V8 and the other JavaScript runtimes have gotten. EJS caches the intermediate JS functions for fast execution.

Easy debugging
It's easy to debug EJS errors: your errors are plain JavaScript exceptions, with template line-numbers included.

Active development
EJS has a large community of active users, and the library is under active development. We're happy to answer your questions or give you help. 



### Features
Fast compilation and rendering
Simple template tags: <% %>
Custom delimiters (e.g., use <? ?> instead of <% %>)
Includes
Both server JS and browser support
Static caching of intermediate JavaScript
Static caching of templates
Complies with the Express view system



Install
It's easy to install EJS with NPM.

$ npm install ejs
Use
Pass EJS a template string and some data. BOOM, you've got some HTML.

let ejs = require('ejs'),
    people = ['geddy', 'neil', 'alex'],
    html = ejs.render('<%= people.join(", "); %>', {people: people});
Browser support
Download a browser build from the latest release, and use it in a script tag.

<script src="ejs.js"></script>
<script>
  let people = ['geddy', 'neil', 'alex'],
      html = ejs.render('<%= people.join(", "); %>', {people: people});
</script> 



## the end 