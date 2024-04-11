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

If we didn’t want div elements to be block-level elements, we would use display: inline.<br/> Flexbox, however, provides the inline-flex value for the display property, which creates flex containers that are also inline elements.<br/>


