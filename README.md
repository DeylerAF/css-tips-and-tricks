# Flexbox and Grid Properties

## CSS flexbox properties and values

Defines the element as a flex container.

`display: flex;`
-
Defines the direction of the main axis in the flex container.

`flex-direction: row | row-reverse | column | column-reverse;`
-
Defines whether flex items are forced onto a single line or can wrap onto multiple lines.

`flex-wrap: nowrap | wrap | wrap-reverse;`
-
A shorthand for defining flex-direction and flex-wrap in a single declaration.

`flex-flow: flex-direction || flex-wrap;`
-
Defines how flex items are aligned along the main axis of the flex container.

`justify-content: flex-start | flex-end | center | space-between | space-around | space-evenly;`
-
Defines how flex items are aligned along the cross-axis of the flex container.

`align-items: flex-start | flex-end | center | baseline | stretch;`
-
Defines how flex lines are aligned along the cross-axis of the flex container when there is extra space in the flex container.

`align-content: flex-start | flex-end | center | space-between | space-around | stretch;`
-
Defines the order in which a flex item appears within the flex container.

`order: <integer>;`
-
Defines how much a flex item will grow relative to the rest of the flex items in the flex container.

`flex-grow: <number>;`
-
Defines how much a flex item will shrink relative to the rest of the flex items in the flex container.

`flex-shrink: <number>;`
-
Defines the initial size of a flex item before any remaining space is distributed.

`flex-basis: <length> | auto;`
-
A shorthand for defining flex-grow, flex-shrink, and flex-basis in a single declaration.

`flex: none | [ <'flex-grow'> <'flex-shrink'>? || <'flex-basis'> ];`
-
Defines how a single flex item is aligned along the cross-axis of the flex container.

`align-self: auto | flex-start | flex-end | center | baseline | stretch;`
-

## CSS Grid Properties and values

Defines the element as a grid container.

`display: grid | inline-grid;`
-
Defines the size of the columns in the grid.

`grid-template-columns: value | repeat(n, value) | minmax(min, max) | auto | fr;`
-
Defines the size of the rows in the grid.

`grid-template-rows: value | repeat(n, value) | minmax(min, max) | auto | fr;`
-
Defines the layout of the grid using named grid areas.

`grid-template-areas: none | value;`
-
A shorthand for defining grid-template-rows, grid-template-columns, and grid-template-areas in a single declaration.

`grid-template: none | value;`
-
Defines the size of the gap between columns in the grid.

`grid-column-gap: value;`
-
Defines the size of the gap between rows in the grid.

`grid-row-gap: value;`
-
A shorthand for defining grid-column-gap and grid-row-gap in a single declaration.

`grid-gap: value;`
-
Defines the size of the columns that are not explicitly defined in the grid.

`grid-auto-columns: value | minmax(min, max) | auto | fr;`
-
Defines the size of the rows that are not explicitly defined in the grid.

`grid-auto-rows: value | minmax(min, max) | auto | fr;`
-
Defines the direction in which the grid items are placed when they are not explicitly defined in the grid.

`grid-auto-flow: row | column | dense row | dense column;`
-
A shorthand for defining grid-template-rows, grid-template-columns, grid-template-areas, grid-auto-rows, grid-auto-columns, and grid-auto-flow in a single declaration.

`grid: none | value;`
-
Defines a grid item's size and location within the grid.

`grid-area: auto | row-start / column-start / row-end / column-end | name;`
-
Defines the starting row position of a grid item.

`grid-row-start: auto | value;`
-
Defines the starting column position of a grid item.

`grid-column-start: auto | value;`
-
Defines the ending row position of a grid item.

`grid-row-end: auto | value;`
-
Defines the ending column position of a grid item.

`grid-column-end: auto | value;`
-
Aligns grid items along the inline (row) axis.

`justify-items: start | end | center | stretch;`
-
Aligns grid items along the block (column) axis.

`align-items: start | end | center | stretch;`
-
A shorthand for align-items and justify-items in a single declaration.

`place-items: align-items / justify-items;`
-
Align grid items along the inline (row) axis when there is extra space in the grid container.

`justify-content: start | end | center | stretch | space-between | space-around | space-evenly;`
-
Align grid items along the block (column) axis when there is extra space in the grid container.

`align-content: start | end | center | stretch | space-between | space-around | space-evenly;`
-
A shorthand for align-content and justify-content in a single declaration.

`place-content: align-content / justify-content;`
-
Aligns a grid item along the inline (row) axis within its grid cell.

`justify-self: start | end | center | stretch;`
-
Aligns a grid item along the block (column) axis within its grid cell.

`align-self: start | end | center | stretch;`
-
A shorthand for align-self and justify-self in a single declaration.

`place-self: align-self / justify-self;`
-
