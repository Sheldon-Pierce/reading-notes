[Home](../README.md)

## Flexbox

The Flexible Box Layout Model (flexbox) is a layout model designed for one-dimensional content. It excels at taking a bunch of items which have different sizes, and returning the best layout for those items.

The key to understanding flexbox is to understand the concept of a main axis and a cross axis. The main axis is the one set by your flex-direction property. If that is row your main axis is along the row, if it is column your main axis is along the column.

You should be cautious when using any properties that reorder the visual display away from how things are ordered in the HTML document, as it can negatively impact accessibility. The row-reverse and column-reverse values are a good example of this. The reordering only happens for the visual order, not the logical order. This is important to understand as the logical order is the order that a screen reader will read out the content, and anyone navigating using the keyboard will follow.

Deciding on when to use either Flexbox or float will come down to practice and figuring out what method is best to creating better flow in the document. 

## Things I want to know more about