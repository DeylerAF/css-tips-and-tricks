# CSS Grid Properties and values

CSS Grid is a powerful tool for creating complex and flexible layouts. Here are the properties you can use to customize your grid:

## Display

- `display: grid | inline-grid;`
    - Defines the element as a grid container.

## Grid Template

- `grid-template-columns: value | repeat(n, value) | minmax(min, max) | auto | fr;`
    - Defines the size of the columns in the grid.
- `grid-template-rows: value | repeat(n, value) | minmax(min, max) | auto | fr;`
    - Defines the size of the rows in the grid.
- `grid-template-areas: none | value;`
    - Defines the layout of the grid using named grid areas.
- `grid-template: none | value;`
    - A shorthand for defining grid-template-rows, grid-template-columns, and grid-template-areas in a single declaration.

## Grid Gaps

- `grid-column-gap: value;`
    - Defines the size of the gap between columns in the grid.
- `grid-row-gap: value;`
    - Defines the size of the gap between rows in the grid.
- `grid-gap: value;`
    - A shorthand for defining grid-column-gap and grid-row-gap in a single declaration.

## Grid Auto

- `grid-auto-columns: value | minmax(min, max) | auto | fr;`
    - Defines the size of the columns that are not explicitly defined in the grid.
- `grid-auto-rows: value | minmax(min, max) | auto | fr;`
    - Defines the size of the rows that are not explicitly defined in the grid.
- `grid-auto-flow: row | column | dense row | dense column;`
    - Defines the direction in which the grid items are placed when they are not explicitly defined in the grid.
- `grid: none | value;`
    - A shorthand for defining grid-template-rows, grid-template-columns, grid-template-areas, grid-auto-rows, grid-auto-columns, and grid-auto-flow in a single declaration.

## Grid Items

- `grid-area: auto | row-start / column-start / row-end / column-end | name;`
    - Defines a grid item's size and location within the grid.
- `grid-row-start: auto | value;`
    - Defines the starting row position of a grid item.
- `grid-column-start: auto | value;`
    - Defines the starting column position of a grid item.
- `grid-row-end: auto | value;`
    - Defines the ending row position of a grid item.
- `grid-column-end: auto | value;`
    - Defines the ending column position of a grid item.

## Alignment

- `justify-items: start | end | center | stretch;`
    - Aligns grid items along the inline (row) axis.
- `align-items: start | end | center | stretch;`
    - Aligns grid items along the block (column) axis.
- `place-items: align-items / justify-items;`
    - A shorthand for align-items and justify-items in a single declaration.
- `justify-content: start | end | center | stretch | space-between | space-around | space-evenly;`
    - Aligns grid items along the inline (row) axis when there is extra space in the grid container.
- `align-content: start | end | center | stretch | space-between | space-around | space-evenly;`
    - Aligns grid items along the block (column) axis when there is extra space in the grid container.
- `place-content: align-content / justify-content;`
    - A shorthand for align-content and justify-content in a single declaration.
- `justify-self: start | end | center | stretch;`
    - Aligns a grid item along the inline (row) axis within its grid cell.
- `align-self: start | end | center | stretch;`
    - Aligns a grid item along the block (column) axis within its grid cell.
- `place-self: align-self / justify-self;`
    - A shorthand for align-self and justify-self in a single declaration.

Use these properties and values to create beautiful and responsive layouts with CSS Grid.

The code above lists the properties that can be used to customize CSS Grid layouts. The properties are grouped into several categories, including Display, Grid Template, Grid Gaps, Grid Auto, Grid Items, and Alignment.

The Display category includes the `display` property, which defines an element as a grid container. The Grid Template category includes properties that define the size of the columns and rows in the grid, as well as the layout of the grid using named grid areas. The Grid Gaps category includes properties that define the size of the gap between columns and rows in the grid.

The Grid Auto category includes properties that define the size of the columns and rows that are not explicitly defined in the grid, as well as the direction in which grid items are placed when they are not explicitly defined in the grid. The Grid Items category includes properties that define a grid item's size and location within the grid.

Finally, the Alignment category includes properties that align grid items along the inline (row) and block (column) axes, as well as properties that align a grid item within its grid cell.

By using these properties and values, developers can create beautiful and responsive layouts with CSS Grid.
