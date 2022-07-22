MY READIND NOTES 8

My reading note for today will be aboout modeling, CSS, CSS layout and flexbox.

1. Learn CSS - Flexbox

* When a flex container wraps it creates multiple flex lines. In terms of space distribution, each line acts like a new flex container. 
Therefore if you are wrapping rows, it is not possible to get something in row 2 to line up with something above it in row 1. 
This is what is meant by flexbox being one-dimensional. You can control alignment in one axis, a row or a column, not both together as we can do in grid.
"Quoting from the reading material"

* The main axis and the cross axis #
The key to understanding flexbox is to understand the concept of a main axis and a cross axis. The main axis is the one set by your flex-direction property. 
If that is row your main axis is along the row, if it is column your main axis is along the column.
"Quoting from the reading material"


Flex items move as a group on the main axis. Remember: we've got a bunch of things and we are trying to get the best layout for them as a group.

The cross axis runs in the other direction to the main axis, so if flex-direction is row the cross axis runs along the column.

You can do two things on the cross axis. You can move the items individually or as a group so they align against each other and the flex container. 
Also, if you have wrapped flex lines, you can treat those lines as a group in order to control how space is assigned to those lines. 
You will see how this all works in practice throughout this guide, for now just keep in mind that the main axis follows your flex-direction.
"Quoting from the reading material"

2. CSS Layout - Flexbox

* Why Flexbox?
For a long time, the only reliable cross-browser compatible tools available for creating CSS layouts were features like floats and positioning. These work, but in some ways they're also limiting and frustrating.

The following simple layout designs are either difficult or impossible to achieve with such tools in any kind of convenient, flexible way:

- Vertically centering a block of content inside its parent.
- Making all the children of a container take up an equal amount of the available width/height, regardless of how much width/height is available.
- Making all columns in a multiple-column layout adopt the same height even if they contain a different amount of content.
As you'll see in subsequent sections, flexbox makes a lot of layout tasks much easier. 
"Quoting from the reading material"

* Float
Originally for floating images inside blocks of text, the float property became one of the most commonly used tools for creating multiple column layouts on webpages. 
With the advent of flexbox and grid it's now returned to its original purpose, as this article explains.
"Quoting from the reading material"


For live access to my page, please visit the following link: https://github.com/timothee2022
