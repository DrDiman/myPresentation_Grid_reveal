CSS Grid-Layout

Agenda.

Browser support.

  CSS Grid is well supported in most desktop and mobile browsers except Internet Explorar and Opera Mini, in IE you need to add prefix -  ms-.

Terminology.
  
  Grid container - is the element on which display: grid is applied.

  Grid items - are direct children of the grid container.
  And children of the grid items are NOT grid items.

  Grid Lines - are the dividing lines that make up the structure of the grid (vertical and horizontal).

  Grid Track - is a column or a row.

  Grid Cell - is a single "unit" of the grid. 

  Grid Area - is total space surrounded by four grid lines.


  Fraction - is a flexible unit which represents the available space in the grid container.
  The real magic of CSS Grid Layout is the ability to mix flexible units and not-flexible units. 

Properties for the grid container.

  Grid-template-columns and grid-template-rows - are CSS properties which define the names of the grid lines and the track sizes.

  Grid-row-gap and grid-column-gap - are CSS properties which set the size of the gap between grid rows and columns.

  Grid-auto-flow - is a CSS property controls how the auto-placement algorithm works.

  Grid-auto-rows and grid-auto-columns - are CSS properties which specify the size of an implicitly-created grid row or column.

  Justify-content and align-content - are CSS properties which align the grid along the row axis and along the column axis.
  But it can be done when all of your grid items are sized with non-flexible units like px and the total size of your grid might be less than the size of its grid container.

  Justify-items and align-items - are CSS properties which align grid items along the row axis and along the column axis.

  Grid-template-areas - is a CSS property which sets names for the grid areas.
  Instead of placing each individual item, we can define the entire layout using the grid-template-areas property. And then assign those areas to each grid item using the grid-area property.

Properties for the grid items.

  grid-column-start,
  grid-column-end,
  grid-row-start,
  grid-row-end,
  grid-column,
  and their shorthands:
  grid-column,
  grid-row - are CSS properties which determine grid item's locations within the grid by referring to specific grid lines.

  Grid-area - is a CSS property which gives the reference name to grid item from grid-template-areas property. 

  Justify-self,
  align-self,
  and their shorthand:
  place-self - are CSS properties which align a grid item inside a cell along the row axis and along the column axis.
  
Useful CSS functions.
  
  repeat() - is a CSS function which defines how many times to repeat length unit.

  minmax() - is a CSS function which defines a size range.

  fit-content() - is a CSS function which clamps a given size.

Useful links.
