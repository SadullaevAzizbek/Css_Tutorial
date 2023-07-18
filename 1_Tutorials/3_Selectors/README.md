# Css Selectors

### A Css selector selects the Html elements you want to style

## The Css Element selector

### The element selector selects Html elements based on the element name

### Here, all p elements on page will be center-aligned, with a red text color
p {
  text-align: center;
  color: red;
}
## The Css id selector
### The id selector uses the id attribute of an Html element to select a specific element
### To select an element with a specific id, write a hash(#) character, followed by the id of the element
### The Css rule below will be appied to the Html element with id="para1"
#para1 {
  text-align: center;
  color: red;
}
## The Css Class Selctor
### The Class selector selects Html elements with a specific class attribute
### To select elements with a specific class, write a period (.) charactor, followed by the class name
### In this example all Html elements with class="center" will be red and center align
.center {
  text-align: center;
  color: red;
}