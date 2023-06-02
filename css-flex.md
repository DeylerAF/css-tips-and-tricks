# CSS flexbox properties and values

## Container

- `display: flex;`
    - Defines the element as a flex container.
- `flex-direction: row | row-reverse | column | column-reverse;`
    - Defines the direction of the main axis in the flex container.
- `flex-wrap: nowrap | wrap | wrap-reverse;`
    - Defines whether flex items are forced onto a single line or can wrap onto multiple lines.
- `flex-flow: flex-direction || flex-wrap;`
    - A shorthand for defining flex-direction and flex-wrap in a single declaration.
- `justify-content: flex-start | flex-end | center | space-between | space-around | space-evenly;`
    - Defines how flex items are aligned along the main axis of the flex container.
- `align-items: flex-start | flex-end | center | baseline | stretch;`
    - Defines how flex items are aligned along the cross axis of the flex container.
- `align-content: flex-start | flex-end | center | space-between | space-around | stretch;`
    - Defines how flex lines are aligned along the cross axis of the flex container when there is extra space in the flex container.

## Flex Items

- `order: <integer>;`
    - Defines the order in which a flex item appears within the flex container.
- `flex-grow: <number>;`
    - Defines how much a flex item will grow relative to the rest of the flex items in the flex container.
- `flex-shrink: <number>;`
    - Defines how much a flex item will shrink relative to the rest of the flex items in the flex container.
- `flex-basis: <length> | auto;`
    - Defines the initial size of a flex item before any remaining space is distributed.
- `flex: none | [ <'flex-grow'> <'flex-shrink'>? || <'flex-basis'> ];`
    - A shorthand for defining flex-grow, flex-shrink, and flex-basis in a single declaration.
- `align-self: auto | flex-start | flex-end | center | baseline | stretch;`
    - Defines how a single flex item is aligned along the cross axis of the flex container.

By using these properties and values, developers can create flexible and responsive layouts with CSS flexbox. Let me know if you have any other questions!
