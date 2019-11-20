# Floats
* Initially, never intended to layout whole web pages. Generally, a layout hack.
* Features rows and cells.
* Rows clear the floats on the cells.
* Ordering of the code determines how things are displayed on the screen. Some minor rearrangement is possible.
* Major disadvantage: equal column heights.

* Rearrange the columns using attribute selector.
  * Rather than selecting an html tag, create a class.
  * For any html element with the attribute of class, use a wildcard `class*=` to select every `col-`
  * Can also be used to select all `href` links such that you can add images to indicate a link brings the user off site, plus many other uses.

* Practice:
  * Create a 4-column floated grid with the given starter file.
  * Include 2 breakpoints and 3 layouts (`desktop`,`tablet`,`phone`)
  * Consider how to equalize the columns so they wrap without breaking
  * Consider reordering row 3 at tablet and phone size.
