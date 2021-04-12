# Day 3
___
### Section 3 of [Web Dev Course by Dr. Angela Yu](https://www.udemy.com/course/the-complete-web-development-bootcamp)
___

Today i got introduced to intermediate level of HTML so let's begin with today learnings.

####Table

Table is an HTML element , the reason of it's existance is that it help in organising layout of other element of HTML.

```html
<table>
<tr> <!--table row-->
<td></td> <!--table data-->
<td></td>
</tr>
</table>
```
Table element of HTML have 3 parts in it's foundation Which are Header, Body & Footer.

```html
<thead>
<tr>
<th></th>
<th></th>
</tr>
</thead>

<tbody>
<tr>
<th></th>
<td></td>
</tr>
</tbody>
<!-- important thing to note here is that thead could work without the <thead></thead> tag 
as most of browser used today's are smart enough to understand the usage without proper syntax.-->
```
[tbody](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/tbody)
Also learned about some attribute such as cell spacing and border Created a Nested table for code challenge as well.

####Form

Form element of HTML use to submit some information.
```html
<form class="" action="index.html" method="post">
<label> any text : </label>
<input type="text" name ="" value="">
<--attribute  type can be used to get desired result.
 we can change it's value to password,email,file,submit,date,radio,range,number .... and so on.-->

```

[form:attributes](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/form#attributes)