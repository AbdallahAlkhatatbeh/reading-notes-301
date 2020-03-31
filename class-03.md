 ## Javascript Templating Language and Engine— Mustache.js with Node and Express
 


 ### Javascript Templating
Javascript templating is a fast and efficient technique to render client-side view templates with Javascript by using a JSON data source. The template is HTML markup, with added templating tags that will either insert variables or run programming logic.
The template engine then replaces variables and instances declared in a template file with actual values at runtime, and convert the template into an HTML file sent to the client.

### Mustache
 Mustache is a logic-less template syntax. It can be used for HTML, config files, source code — anything. It works by expanding tags in a template using values provided in a hash or object. 

Mustache.render(“Hello, {{name}}”, { name: “Sherlynn” });
// returns: Hello, Sherlynn  

## Flexbox 
- Properties for the Parent
(flex container)
display
This defines a flex container; inline or block depending on the given value. It enables a flex context for all its direct children.

.container {
  display: flex; /* or inline-flex */
}
Note that CSS columns have no effect on a flex container.

- Properties for the Children
(flex items)
order
Diagram showing flexbox order. A container with the items being 1 1 1 2 3, -1 1 2 5, and 2 2 99.
By default, flex items are laid out in the source order. However, the order property controls the order in which they appear in the flex container.

.item {
  order: <integer>; /* default is 0 */
} 

 by using the justify-content property, which aligns items horizontally and accepts the following values:
 flex-start: Items align to the left side of the container.
flex-end: Items align to the right side of the container.
center: Items align at the center of the container.
space-between: Items display with equal spacing between them.
space-around: Items display with equal spacing around them.



## the end




