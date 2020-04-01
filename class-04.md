## Responsive Web Design and Regular Expressions

### Grid  

- Properties for the Parent
(Grid Container)
display
Defines the element as a grid container and establishes a new grid formatting context for its contents.

Values:

grid – generates a block-level grid
inline-grid – generates an inline-level grid
.container {
  display: grid | inline-grid;
}

- Properties for the Children
(Grid Items)
grid-column-start
grid-column-end
grid-row-start
grid-row-end
Determines a grid item’s location within the grid by referring to specific grid lines. grid-column-start/grid-row-start is the line where the item begins, and grid-column-end/grid-row-end is the line where the item ends.

Values:

<line> – can be a number to refer to a numbered grid line, or a name to refer to a named grid line
span <number> – the item will span across the provided number of grid tracks
span <name> – the item will span across until it hits the next line with the provided name
auto – indicates auto-placement, an automatic span, or a default span of one
.item {
  grid-column-start: <number> | <name> | span <number> | span <name> | auto;
  grid-column-end: <number> | <name> | span <number> | span <name> | auto;
  grid-row-start: <number> | <name> | span <number> | span <name> | auto;
  grid-row-end: <number> | <name> | span <number> | span <name> | auto;
}


## the end 