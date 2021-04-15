# Day 4
___
### Section 4 of [Web Dev Course by Dr. Angela Yu](https://www.udemy.com/course/the-complete-web-development-bootcamp)
___

#### Introduction to CSS

##### [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)

Cascading style sheets is a stylesheet language by which we describe the presentation of HTML and XML documents.

[seanhalpin.design](https://seanhalpin.design) Inspiration for design.

##### Inline CSS

Inline css in general use to change styling attributes of a particular tag .

```HTML
<p style="color:red;">
```
[color MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/color_value)
[color code](colorhunt.co)

##### Internal CSS

This implementation of CSS is used when we want to iplement styling changes in a page.It's place in head section of the HTML Page.

```HTML
<style>
body { background-color : #69bfbf ; }
hr  { background-color : white ;
      border-style : none ;
      height : 2px ;
      border-style : none ;
      border-top-style : dotted ;
}
</style>
```
##### External CSS

External CSS is use to add same styling on multiple webpages and for easy debuging.

```html
<head>
<link rel="stylesheet" href="css/style.css">
</head>
```


[Default css](https://www.w3schools.com/cssref/css_default_values.asp) here is the default css used by browser.

##### how to debug CSS Code 

press F12 to open developer tols, in console tab you are most likely to see the error of code.

in frist problem the path was actually changed to root path by adding / in href.

in second problem the external css style was override by inline css which is logically not a bug .

##### priority of CSS
 
 ###### inline > internal > external

 inline css could override the internal css for same selectors property and internal css could do same with external css.

 ##### Anatomy of CSS Syntex
  
  This Syntex is applied for internal and external css only.

  ###### Selector { Property : value ;}

  selector is who you want to perform styling on Property is what is going to be affected and value decides how it is going to be affected.

##### [emojipedia](https://emojipedia.org/)

 A website to find emoji for keyword.

 ##### Class Vs Id 

 ###### Class
class can  multiple for the same name. sigle property could have multiple class name by just adding space. more commonly used.

```html
. class_name { property}
```


###### Id 

Id is used to specific selector which is unique in it's own more like a primary key used in sql there could be only for particular selector and it must be unique.
note :- it's rarely used developers.

```html
# Id_name { Property : value ; }
```

##### [Pseudo classes](https://www.w3schools.com/css/css_pseudo_classes.asp)

:hover was used as an example to change background-color of image when mouse is hovered on image.



