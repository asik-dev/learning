**CSS**

**Working with boxes**

Every element in CSS is interpreted as a BOX.

a. Content -\&gt; Padding -\&gt; Border -\&gt; Margin

Except Margin all the attributes are related to the element.

**Margin**

By default body has a margin of 8px around, that&#39;s why we see a white box around.

Margin Collapsing (if two element are next to each other then the margin between them is collapsed to save from too much distance)

**Shorthand property**

1. Combine values of multiple values into a single property.
2. Order doesn&#39;t matter in the multiple values for a shorthand property
3. Margin values are interpreted as top, right, bottom and left.(like clock) E.g {margin: 2px 5px 10px 12px }
4. if only we specify 2 values, then top and bottom takes one and the right and left takes the other. E.g {margin: 2px 5px}
5. margin with one value to use for all sides. E.g {margin:20px}

**Width and Height Parameters**

1. Block level elements take full available Height/width by default E.g (div etc unlike \&lt;anchor tag)
2. padding and border&#39;s width and height always add up to the element&#39;s size
3. By default box sizing is content-box, we can change to border-box
4. use box-sizing to border-box and declare it in \*root{} so that its applied across all elements

**Display property**

1. we can use inline, block, inline-block and none.

1. in CSS make sure that there&#39;s a space after all the operators

**pseudo classes and pseudo elements**

1. pseudo classes ; defines the style of a special state of an element

syntax = classname:state\_name

E.g = classname:hover

1. pseudo elements ; defines the style of specific part of an element

syntax = classname::state\_name

E.g = classname::element\_name

**Grouping of 2 rules for pseudo classes**

Use comma to group 2 classes,

e.g

.class1, .class3 {

color:red

}

properties worth remembering

a. color

b. background-color

c. display

d. Padding

e. Border

f. Margin

g. width

h. Height

**Box model is the core concept of CSS.**

**Pseudo classes and elements are important.**

CSS classes
