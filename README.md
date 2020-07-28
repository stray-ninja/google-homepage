As an assignment for the odin project, I'm trying to build a replica of Google.com

What I've learned:

How to add a favicon to the browser tab
-> in the <head> put <link rel="icon" href="image.jpeg">

searchbar position
-> change display to block, so that it occupies it's own row
-> buttons jump to next row
-> change margin to auto, to align horizontally

inline-blocks vertical alignment
-> inline-blocks can be vertically aligned, using the vertical-align: property
-> enter value middle, if items should be centered, vertically

float order follows html flow
-> to position the navbar items, i used the float property
-> items floated to the right, turned out to be placed the other way round than expected
-> turns out if items are floated in a specific direction, items higher in the markup will be floated first, than the next item and so on

switched from float positioning to two separate boxes, first one absolutely positioned, second one flexbox
-> trying to omit issue with not evenly centered items in the right box (app icon)

app icon can still not perfectly aligned horizontally with the text items, same goes for googleuser-img
-> workaround: 1. align-items: center - to base items on one line
               2. from there, each item - vertically-align: center
               3. separately align googleuser and appicon with vertically-align: length



