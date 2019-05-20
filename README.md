# flexbox
Flexbox tutorial.


### Hi there.

In a perfect world of browser support, the reason you'd choose to use flexbox is because you want to lay a collection of items out in one direction or another. As you lay out your items you want to control the dimensions of the items in that one dimension, or control the spacing between items. These are the uses that flexbox was designed for. You can read more about the difference between flexbox and CSS Grid Layout in Relationship of Flexbox to other layout methods, where we discuss how flexbox fits into the overall picture of CSS Layout.

In reality we also often use Flexbox for jobs that might be better done by Grid Layout, as a fallback for Grid, and also in order to get alignment capabilities. This is something that may well change once Box Alignment is implemented in Block Layout. In this guide I look at some of the typical things you might use flexbox for today.

## Lets get started

### display: flex
###### display: flex => place the several contents in horizontal way.

### flex-direction
###### flex-direction: row/column => lay the contents in row or column.

### justify-content: flex-start/flex-end/center/space-around/space-evenly.
###### justify-content: flex-start => put the contents to left side.
 ###### justify-content: flex-end => put the contents to the right side.
 ###### justify-content: center => put the contents to the center.
###### justify-content: space-around/spaceevenly => fit the contents to the screen putting space among them.
### margin-left: auto
###### put the content to the right
### responsive: flex
###### flex: 1 => allocate contents in equil size and responsive. If you give the attrabute ony for one of them then given content will be responsive the others stay fixed.

### align-item: flex-start/end/center
###### put the contents to top, center and end.
### flex-wrap: wrap/nowrap
###### Wrapping => if attrabute is wrap then it allows wrapping the contents, if it is nowrap then the size be fixed, even if you give size large that doesnt effect.

### flex-grow/shrink/basis
###### flex-basis => deterime the max size to shrink
###### flex-grow: 0/1 => like col-sm-12 destrabution
###### flex-shrink => shrinking px

### order
###### order: positive number puts the content to the end of the all contents. negative number puts to the begining of the all contents.
