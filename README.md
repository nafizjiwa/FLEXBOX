# FLEXBOX
Explain flexbox and its components.

Flexbox a tool that simplifies how to position elements and change postions especially if there are positioning issues. <br/>
Two components of flexbox are flex containers and flex itms.<br/>
A flex container is an element on a page that contains flex items. <br/>
All direct child elements of a flex container are flex items.<br/>
Flexbox has properties some are appied to flex containers while others are for flex items.<br/>
To designate an ELEMENT as a flex container, set the element’s display property to flex or inline-flex. <br/>
```elementName {```<br/>
```        display: flex/ in-line; ```<br/>
```}```<br/>
Flex container properties specify how its children behave. <br/>
Flexbox flex container and flex item properties:
<ol>
  <li>justify-content</li>
  <li>align-items</li>
  <li>flex-grow</li>
  <li>flex-shrink</li>
  <li>flex-basis</li>
  <li>flex</li>
  <li>flex-wrap</li>
  <li>align-content</li>
  <li>flex-direction</li>
  <li>flex-flow</li>
</ol>

![image](https://github.com/nafizjiwa/FLEXBOX/assets/56348190/da7657ba-4170-464a-aa20-29cb9d0fe680)<br/>

A div with the declaration display: flex; will remain block level — no other elements will appear on the same line as it.<br/>

However, it will change the behavior of its child elements. Child elements will not begin on new lines.

If we dodn’t want div elements to be block-level elements<br/>
Use 
display: inline.<br/> 
Flexbox, however, provides the inline-flex value for the display property, which creates flex containers that are also inline elements.<br/>

display: flex, children will be positioned next to each other. Makes an element into a flex container but remains block level so no other elements in same line<br/>
display: inline we want multiple flex containers to display inline with each other and not block level<br/>
justify-content position the items left or right, along the container main axis. <br/>
align-items - align flex items (single row) vertically within the containers cross axis of the parent container. The cross axis stretches from top to bottom of the container.<br/>
flex-grow — is declared on flex items. Specify if items should grow to fill a container which item grows more or less than other items<br/>
flex-shrink property can be used to specify which elements will shrink and in what proportions.<br/>
Flex-grow or shrink don’t’ affect margins.<br/>
Default value of flex-shrink is 1. flex-grow is 0.<br/>
flex-basis allows us to specify the WIDTH of an item before it stretches or shrinks.<br/>
flex property specifies how elements stretch and shrink and allow declare flex-grow, flex-shrink, and flex-basis all in one line.<br/>
Flex : flex-grow, flex-shrink, and flex-basis;<br/>
flex-wrap declared on flex containers to allow flex items move to next line and not have content shrink to fit its container. flex-wrap: wrap/wrap-reverse/nowrap;<br/>
align-content declared on flex containers, with multiple rows of content and space the rows from top to bottom<br/>

flex containers have two axes: a main axis and a cross axis.<br/>
Main axis positions flex items with properties:<br/>
1.	justify-content
2.	flex-wrap
3.	flex-grow
4.	flex-shrink<br/>
Cross axis positions flex items with properties:<br/>
1.	align-items
2.	align-content<br/>
The axis can interchange by using:<br/>
flex-direction: column;<br/>
It accepts 4 values:<br/>
flex-direction: row/row-reverse/column/column-reverse;<br/>
flex direction is declared on flex-containers and tells how elements are ordered either horizontally (side by side), or vertically (top to bottom) and in reverse.<br/>
flex-flow declared on flex container allow flex-wrap and flex-direction properties in one line.<br/>
flex-flow : flex-wrap Value, flex-direction Value; <br/>



