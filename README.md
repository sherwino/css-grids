# CSS Grid
An HTML and CSS static site that utilizes CSS Grid

The main objective of this site is to get familiar laying out responsive pages without using JavaScript or frameworks like Twitter's Bootstrap.

CSS Grid are compatible with most modern browsers and give us an opportunity to avoid all of the common hacks seen today.

## Grid Properties

When creating this site I am going to attempt to use all of the properties of CSS Grid. As soon as these properties are featured in the site I will check them off. All of the definitions come from [https://css-tricks.com/snippets/css/complete-guide-grid/]

First it starts with:
- [ ] display: grid, inline-grid, subgrid
- The element on which display: grid is applied. It's the direct parent of all the grid items. In this example container is the grid container.

    grid - generates a block-level grid
    inline-grid - generates an inline-level grid
    subgrid - if your grid container is itself a grid item (i.e. nested grids), you can use this property to indicate that you want the sizes of its rows/columns to be taken from its parent rather than specifying its own.

Then the grid can be composed of:
- [ ] grid item
- The children (e.g. direct descendants) of the grid container.

- [ ] grid line
- The dividing lines that make up the structure of the grid. They can be either vertical ("column grid lines") or horizontal ("row grid lines") and reside on either side of a row or column.

- [ ] grid track
- The space between two adjacent grid lines. You can think of them like the columns or rows of the grid

- [ ] grid cell
- The space between two adjacent row and two adjacent column grid lines. It's a single "unit" of the grid.

- [ ] grid area
- The total space surrounded by four grid lines. A grid area may be comprised of any number of grid cells.

Grid Properties:
- [ ] grid-template-columns:

- [ ] grid-template-rows:    px, pt, em, fr, %, repeat({amt}, size)

- [ ] grid-template-areas:   <name>

- [ ] grid-auto-columns:     px, pt, em, fr, %
-
- [ ] grid-auto-rows:        px, pt, em, fr, %

- [ ] grid-auto-flow:        px, pt, em, fr, %

- [ ] grid-column-gap:       px, pt, em, fr, %

- [ ] grid-row-gap:          px, pt, em, fr, %

- [ ] justify-items:         start, center, end, stretch (default)

- [ ] justify-self:         start, center, end, stretch (default)

- [ ] align-items:           start, center, end, stretch (default)

- [ ] align-self:            start, center, end, stretch (default)


## The Site

To best way to demonstrate the power of the CSS Grid right now is by making a long single page layout so that you can scroll your little heart out. The site is going to be hosted in GitHub Pages.

What I am not certain about is what kind of content I am going to put on it. Possibly an informational site about one of my many interest.



## Change Log
- v0.01 - Initial Commit / Readme
