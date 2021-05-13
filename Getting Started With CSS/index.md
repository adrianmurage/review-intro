# GETTING STARTED WITH CSS

CSS is an abbreviation for cascading style sheets. It is a style language used in expressing the display of a document  written in a markup language like HTML. Alongside HTML and Javascript, CSS is a foundation technology in the worldwide web.
## Functions of CSS
CSS aids users carry out the presentation of web pages and adjust their presentation to different types of gadgets such as large screens or small screens. CSS also helps users apply elements consistently throughout the site pages such that lists and headings look alike throughout the site pages.
## CSS Properties and How to Use Them
### 1.Changing The Color of A Text
It is done by merely adding the suitable CSS selector and specifying the color property and value wanted. Users can use CSS selectors to style elements by adding the **style** element to your code like this;
```CSS
<style>
 h2{
     color: red;
 }
 </style>
 ```
 This will change all the header2 to the color red.
 The CSS selector can be incorporated in HTML like this;
 ```HTML
 <h2 style="color: red;">Properties of CSS</h2>
 ```
### 2.Using Class to Style Elements
 A class is declared by adding a fullstop(.) accompanied by the class name in a style block.Then followed by a declaration block({}) which contains the property to style the element for example color.Here is an example;
 ```CSS
 <style>
   .red-text{
       color: red;
   }
 </style>
 ```
 In this example,.red-text is the class declaration.A class declaration can be used to style multiple elements.
One can create a class in HTML element like this;
```HTML
<h2 class= "red-text">Properties of CSS</h2>
```
### 3.Changing the Font Size and Font Family of an Element
In order to change the font size of an element,the **font-size** element is introduced like this;
```CSS
h2{
    font-size: 15px;
}
```
Say for example one wants to change the font-size of a paragraph to 17px within the style element it will be like;
```CSS
<style>
p{
    font-size: 17px;
}
</style>
```
In order to change the font name of an element,the **font-name** element is introduced like this;
```CSS
<style>
 p{
     font-family: Helvetica;
 }
</style>
```
### 4.Sizing Images
CSS uses a property known as **width** to size elements by the help of class declarations such as **.smaller-width** and **.larger-image** like this;
```CSS
<style>
 .smaller-image{
     width: 120px;
 }
 </style>
```
This should also be incorporated into your HTML element like this;
```HTML
<img class= "smaller-image">
```
### 5.Using an Id Attribute to Style an Element
An Id attribute can be set in HTML like this;
```HTML
<h2 id= "Properties-of-CSS"> 
```
Using CSS  can style Id attributes. However, Id attributes are only applicable to one element. An Id attribute has a higher dominance than a class declaration , therefore, prioritized if they collide. Introducing an Id attribute of Properties-of-CSS and giving it a background color of black will be like this;
```CSS
<style>
 #Properties-of-CSS{
     background-color: black;
 }
 </style>
 ```

### 6.Using HEX and RGB Colors to Color Elements
Hex is the short name for hexadecimal code. Hex code uses six hexadecimal numbers to specify colors in CSS. Some Hex values of different colors according to [Simmons](http://web.simmons.edu/) are;
- black    #000000

- maroon   #800000

- yellow   #FFFF00

- purple   #800080

representing color in hex code will be like;
```CSS
<style>
   p{
   color: #800080;
   }
</style>
```
But since it is hard to remember hex code,one can shorten it.This are examples from [freshersnow](https://tutorials.freshersnow.com/css/css-colors/);
- black  #000

- red    #F00

- cyan   #0FF

RGB stands for red, green,and blue. It is another way of representing colors in CSS. Each value of RGB could have a value from between 0 to 100% or 0 to 255. A value of 0 means none of the colors was used while a value of 255 or 100% means all of that color was used.
The color black would result from all values(red,green and blue) being 0 while the color white would result from all values being a 100%.Some of RGB values according to [rapidtables](https://www.rapidtables.com/web/color/RGB_Color.html) are as follows;
- black  rgb(0,0,0)

- red    rgb(255,0,0)

- gray   rgb(128,128,128)

RGB values can be styled in CSS as follows;
```CSS
 <style>
    p{
     color: rgb(128,128,128);
    }
</style>
```

### 7.Styling HTML Using CSS
  let us create a HTML element and style it with CSS;
  ```HTML
  <!DOCTYPE html>
  <html>
  <h1>Getting Started With CSS</h1>
  <style>
   body{
       color: black;
       background-color: blue;
       font-family: monospace;
       font-size: 16px;
   }
   </style>
   </html>
   ```
   These are just seven properties to get you started with CSS but there is a lot more to learn. You can learn it from here [CSS.](https://webplatform.github.io/docs/css)

### References
   1.[FreecodeCamp](https://www.freecodecamp.org/)

   2.[Wikipedia](https://en.wikipedia.org/wiki/CSS)

   3.[rapidtables](https://www.rapidtables.com/web/color/RGB_Color.html)


