CSS

#Working with boxes
Every element in CSS is interpreted as a BOX.
a. Content -> Padding -> Border -> Margin
Except Margin all the attributes are related to the element.

##Margin
By default body has a margin of 8px around, that's why we see a white box around.
Margin Collapsing (if two element are next to each other then the margin between them is collapsed to save from too much distance)

##Shorthand property
Combine values of multiple values into a single property.
Order doesn't matter in the multiple values for a shorthand property

Margin values are interpreted as top, right, bottom and left.(like clock) E.g {margin: 2px 5px 10px 12px }
if only we specify 2 values, then top and bottom takes one and the right and left takes the other. E.g {margin: 2px 5px}
margin with one value to use for all sides. E.g {margin:20px}

#width and Height Parameters
Block level elements take full available Height/width by default E.g (div etc unlike <anchor tag)

padding and border's width and height always add up to the element's size

By default box sizing is content-box, we can change to border-box

use box-sizing to border-box and declare it in *root{} so that its applied across all elements

#display property

we can use inline, block, inline-block and none.

in CSS make sure that there's a space after all the operators

#pseudo classes and pseudo elements

pseudo classes ; defines the style of a special state of an element
syntax = classname:state_name
E.g = classname:hover


pseudo elements ; defines the style of specific part of an element
syntax = classname::state_name
E.g = classname::element_name


#Grouping of 2 rules for pseudo classes

Use comma to group 2 classes,

e.g
.class1, .class3 {
  color:red
}

#properties worth remembering

a. color
b. background-color
c. display
d. Padding
e. Border
f. Margin
g. width
h. Height

Box model is the core concept of CSS.
Pseudo classes and elements are important.

#CSS classes
