HTML is used to structure of the page.
CSS is used for styling of the page.

---

CSS was introduced : 1996
CSS-1 : 1996
CSS-2 : 1998
CSS-3 : In Still in Development (Dont say u know CSS-3)
Note : There will never be CSS-4 version
bcoz: Rather than focusing on different version of the CSS, CSS Team decided to split up the
independent modules. For ex- modules which focus on animation, modules which focus on color, etc..

---

3 Methods for adding CSS:

1)Inline CSS
2)Internal CSS
3)External CSS

---

1. Inline CSS : Directly in the html element (Strictly NO!)
2. Internal CSS : Using <style> tags within the documen
3. External CSS : Linking an external .css file

---

font-family: Arial, Helvetica, sans-serif;
font-size: 12px;
font-weight: bold;

-> Shortcut of above style script is :
font: bold 12px Arial, Helvetica, sans-serif;

---

id-> should be unique,
class-> Reusbable component (Not unique)

---

Target :
Class -> . (dot)
id -> #
element -> As it is the element name

---

Difference between Margin and Padding :
check margin.PNG

content -> Any text content inside p, div tag
border => Is the border of that p, div tag
padding -> Space inside of the border
margin -> Space outside of the border

---

We can apply margin :

div{
margin-top : 5px;
margin-bottom: 5px;
margin-right : 10px;
margin-left : 10px;
}

shorthand notation :

div{
margin : 5px 10px 5px 10px;
}

margin : margin-top margin-right margin-bottom margin-left;

Remeber : top right bottom left

-> If top and bottom margin are same and left and right margin are same (More shorthand notation):

div{
margin : 5px 10px;
}

margin : margin-top&bottom margin-right&left

-> If all the sides are equal then

div {
margin : 5px;
}

margin : margin-top&bottom&right&left

[Same format with padding]

---
