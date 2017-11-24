# CSS Grid
An HTML, JS, and CSS website that utilizes CSS Grid 

The main objective of this site is so that I can get familiar laying out responsive pages without using frameworks like Twitter's Bootstrap (sorry guys), while guiding users through some of the CSS Grid concepts.

CSS Grid features are compatible with most modern browsers and give us an opportunity to avoid all of the common hacks seen to make site be laid out a certain way.

The best part of it all is that no libraries, or frameworks needed.

I will most likely have to use [@media](https://devdocs.io/css/@media) queries.

## Grid Properties

I am going to attempt to use all of the properties of CSS Grid in this site while describing them. As soon as these properties are featured in the site I will check them off. All of the definitions come from [CSS-Tricks](https://css-tricks.com/snippets/css/complete-guide-grid/), [MDN](https://mozilladevelopers.github.io/playground/css-grid/), and this great [video](https://www.youtube.com/watch?v=txZq7Laz7_4)

First lets start with the checklist:
- [ ] display: grid, inline-grid, subgrid
    The element on which display: grid is applied. It's the direct parent of all the grid items. In this example container is the grid container.

    grid - generates a block-level grid
    inline-grid - generates an inline-level grid
    subgrid - if your grid container is itself a grid item (i.e. nested grids), you can use this property to indicate that you want the sizes of its rows/columns to be taken from its parent rather than specifying its own.

    One thing to note that wasn't clear to me when I first started using CSS Grid, is that when you select a column or row.
    You are selecting the Grid Line...

    i.e. - when you define grid-column: 3; you are selecting the third line, not the third column.
------------


    ```
  #garden {
    display: grid;
    grid-template-columns: 20% 20% 20% 20% 20%;
    grid-template-rows: 20% 20% 20% 20% 20%;
  }

  #water-1 {
    grid-area: 1 / 4 / 6 / 5;
  }

  #water-2 {
    grid-area: 2/3 / 5/6;
}

  #other-sample {
    grid-template-columns: 50px 1fr 1fr 1fr 50px;
  }
```


If grid items aren't explicitly placed with grid-area, grid-column, grid-row, etc., they are automatically placed according to their order in the source code. We can override this using the order property, which is one of the advantages of grid over table-based layout.

By default, all grid items have an order of 0, but this can be set to any positive or negative value, similar to z-index.

grid-template is a shorthand property that combines grid-template-rows and grid-template-columns.

For example, grid-template: 50% 50% / 200px; will create a grid with two rows that are 50% each, and one column that is 200 pixels wide.


CSS Grid Final Excercise
https://i.gyazo.com/a06cd2e4e94f13641864c1372d5a40f0.png

This is for later ^^^^^ overlapping



-------------

Then the grid can be composed of:
- [ ] grid item
    The children (e.g. direct descendants) of the grid container.

- [ ] grid line
    The dividing lines that make up the structure of the grid. They can be either vertical ("column grid lines") or horizontal ("row grid lines") and reside on either side of a row or column.

- [ ] grid track
    The space between two adjacent grid lines. You can think of them like the columns or rows of the grid

- [ ] grid cell
    The space between two adjacent row and two adjacent column grid lines. It's a single "unit" of the grid.

- [ ] grid area
    The total space surrounded by four grid lines. A grid area may be comprised of any number of grid cells.

Grid Properties:
- [ ] grid-template-columns:

- [ ] grid-template-rows:    px, pt, em, fr, %, repeat({amt}, size)

- [ ] grid-template-areas:   <name>

- [ ] grid-auto-columns:     px, pt, em, fr, %

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
- v0.02 - Created html file, css file, and intro content.
- v0.021 - Small changes to css grid layout
