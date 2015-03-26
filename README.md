#jquery-checkem
It simplifies the parent-child relationship and selects appropriate checkboxes.

[DEMO](http://lancevo.github.io/jquery-checkem/)

#usage

```js
$('form').checkem()
```


### Select All Checkbox

Define select all checkboxes using attribute `data-checkem="all"`

```html
<input type="checkbox" name="allitems" data-checkem="all"> Check All
```


### Nested Checkbox

Define parent input's name in child input attribute `data-checkem-parent` 

```html
<input type="checkbox" name="parentitem"> Parent Item <br>
   <input type="checkbox" name="childitem1" data-checkem-parent="parentitem"> Child item 1
   <input type="checkbox" name="childitem2" data-checkem-parent="parentitem"> Child item 2
```
