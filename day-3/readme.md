# what is CSS grid

-> A layout system having rows and columns similar to the EXcel.

# visualization of the css grid in below image.

![CHEESE!](grid_lines.png)

1. Grid container is the entire grid container having 3 rows and 3 columns in image daigram.
2. Grid lines are the blue lines.
3. Grid cell is the one small square box.
4. Grid track is the space between 2 adjacent lines.
5. Grid item is the children of the grid container.
   where items can overlap each other. We can use z-Index to control their stacking order.
6. Grid gap are the spaces between each columns/rows.

# CSS -grid main two properties

1. grid-template-columns( Specifies the size of the columns, and how many columns in a grid layout)
2. grid-template-rows( Specifies the size of the rows, and how many rows in a grid layout)
3. row-gap
4. column-gap
5. grid-column-start (starts with specific column )
6. grid-column-end(ends with grid specific column)
7. justify-items
8. align-items
9. justify-self
10. align-self
11. place-items(to give the value of justify-items and align-items at once in grid container)
12. place-self(to give the value of justify self and align-self at once in grid items)

# justify-items and justify-self

-> justify-items works on grid container and justify-self works on grid items which values are start, end and center.
