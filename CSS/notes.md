# CSS Flexbox

### **justify-content property**

aligns items horizontally and accepts the following values:

- _flex-start:_ Items align to the left side of the container.
- _flex-end:_ Items align to the right side of the container.
- _center:_ Items align at the center of the container.
- _space-between:_ Items display with equal spacing between them.
- _space-around:_ Items display with equal spacing around them.

### **align-items**

aligns items vertically and accepts the following values:

- _flex-start:_ Items align to the top of the container.
- _flex-end:_ Items align to the bottom of the container.
- _center:_ Items align at the vertical center of the container.
- _baseline:_ Items display at the baseline of the container.
- _stretch:_ Items are stretched to fit the container.

### **flex-direction**

defines the direction items are placed in the container, and accepts the following values:

- _row:_ Items are placed the same as the text direction.
- _row-reverse:_ Items are placed opposite to the text direction.
- _column:_ Items are placed top to bottom.
- _column-reverse:_ Items are placed bottom to top.

### **order**

By default, items have a value of 0, but we can use this property to also set it to a positive or negative integer value (-2, -1, 0, 1, 2).

### **align-self**

This property accepts the same values as align-items and its value for the specific item.

### **flex-wrap**

- _nowrap:_ Every item is fit to a single line.
- _wrap:_ Items wrap around to additional lines.
- _wrap-reverse:_ Items wrap around to additional lines in reverse.

### **flex-flow**

The two properties **flex-direction** and **flex-wrap** are used so often together that the shorthand property flex-flow was created to combine them. This shorthand property accepts the value of one of the two properties separated by a space.

For example, you can use flex-flow: row wrap to set rows and wrap them.

### **align-content**

align-content determines the spacing between lines, while align-items determines how the items as a whole are aligned within the container. When there is only one line, align-content has no effect.

set how multiple lines are spaced apart from each other. This property takes the following values:

- _flex-start:_ Lines are packed at the top of the container.
- _flex-end:_ Lines are packed at the bottom of the container.
- _center:_ Lines are packed at the vertical center of the container.
- _space-between:_ Lines display with equal spacing between them.
- _space-around:_ Lines display with equal spacing around them.
- _stretch:_ Lines are stretched to fit the container.

# CSS Layout

## The Position Property

The position property specifies the type of positioning method used for an element.

There are five different position values:

1. static
2. relative
3. fixed
4. absolute
5. sticky

Elements are then positioned using the top, bottom, left, and right properties. However, these properties will not work unless the position property is set first. They also work differently depending on the position value.

## position: static;

HTML elements are positioned static by default.

Static positioned elements are not affected by the top, bottom, left, and right properties.

An element with position: static; is not positioned in any special way; it is always positioned according to the normal flow of the page:

## position: relative;

An element with position: relative; is positioned relative to its normal position.

Setting the top, right, bottom, and left properties of a relatively-positioned element will cause it to be adjusted away from its normal position. Other content will not be adjusted to fit into any gap left by the element.

## position: fixed;

An element with position: fixed; is positioned relative to the viewport, which means it always stays in the same place even if the page is scrolled. The top, right, bottom, and left properties are used to position the element.

A fixed element does not leave a gap in the page where it would normally have been located.

## position: absolute;

An element with position: absolute; is positioned relative to the nearest positioned ancestor (instead of positioned relative to the viewport, like fixed).

However; if an absolute positioned element has no positioned ancestors, it uses the document body, and moves along with page scrolling.

Note: A "positioned" element is one whose position is anything except static.

## position: sticky;

An element with position: sticky; is positioned based on the user's scroll position.

A sticky element toggles between relative and fixed, depending on the scroll position. It is positioned relative until a given offset position is met in the viewport - then it "sticks" in place (like position:fixed).

## Overlapping Elements

When elements are positioned, they can overlap other elements.

The z-index property specifies the stack order of an element (which element should be placed in front of, or behind, the others).

An element can have a positive or negative stack order.

## All CSS Positioning Properties

### Property Description

- _**bottom:**_ Sets the bottom margin edge for a positioned box
- _**clip:**_ Clips an absolutely positioned element
- _**left:**_ Sets the left margin edge for a positioned box
- _**position:**_ Specifies the type of positioning for an element
- _**right:**_ Sets the right margin edge for a positioned box
- _**top:**_ Sets the top margin edge for a positioned box
- _**z-index:**_ Sets the stack order of an element

# BEM Naming Syntax

**Block**

- a standalone entity that is meaningful on its own

- class="card"

**Element**

- a part of a block that has no standalone meaning and is semantically tied to its block

- class="card\_\_picture"
- class="card\_\_title"
- class="card\_\_description"
- class="card\_\_button"

**Modifier**

- a flag on a block or element. Use them to change appearance or behaviour

- class="card**button card**button--active"

### _**designate element with block class name + 2 underscores**_

### _**designate modifier with element and block class name + 2 dashes and space after first class name**_
