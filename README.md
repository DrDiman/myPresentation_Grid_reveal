CSS Grid-Layout

Grid container - is the element on which display: grid is applied.

Grid items - are direct children of the grid container.
And children of the grid items are NOT grid items.

Grid Lines - are the dividing lines that make up the structure of the grid (vertical and horizontal).

Grid Track - is column or row.

Grid Cell - is a single "unit" of the grid. 

Grid Area - is total space surrounded by four grid lines. 

fraction - is a unit which represents the available space in the grid container.

The real magic of CSS Grid Layout, however, is the ability to mix flexible units and not-flexible u. 

Grid-template-columns and grid-template-rows - are CSS properties which define the line names and track sizes of the grid rows and columns.

Grid-row-gap and grid-column-gap - are CSS properties which set the size of the gap between grid rows and columns.

The grid-auto-flow - is CSS property controls how the auto-placement algorithm works.

The grid-auto-rows and The grid-auto-columns - are CSS properties which specify the size of an implicitly-created grid row or column.

Justify-content and align-content - are CSS properties which align the grid along the row axis and along the column axis.
But it can be done when all of your grid items are sized with non-flexible units like px and the total size of your grid might be less than the size of its grid container.

Justify-items and align-items - are CSS properties which align grid items along the row axis and along the column axis.

grid-template-areas - CSS property specifies named grid areas.
Instead of placing each individual item, we can define the entire layout using the grid-template-areas property. And then assign those areas to each grid item using the grid-area property.

We can give names to all of your grid lines when defining a grid.

grid-column-start,
grid-column-end,
grid-row-start,
grid-row-end,
grid-column,
and their shorthand
grid-column,
grid-row - CSS properties which determine grid item's locations within the grid by referring to specific grid lines

Grid-area - CSS property which gives the reference name to grid item from grid-template-areas property. 

Justify-self,
align-self,
and their shorthand
place-self - are CSS properties which align a grid item inside a cell along the row axis and along the column axis.

repeat() - is CSS function which defines how many times to repeat length unit.

minmax() - is CSS function which defines a size range.

fit-content() - is CSS function which clamps a given size.
