## CSS Selector
###### Selects all elements with a `target` `attribute`
```css
/* tag with attribute */
td[rowspan] { 
    background-color: lightblue;
}
```
###### Selects all elements with `target="value"`
```css
.tblWrapper .fixed-table tr[headers=last] td[rowspan] {
    border-bottom: none; 
}
```
  
###### multiple class selector (contained class-name)
```html
<div class="something001"></div>
<div class="something002"></div>
<div class="something003"></div>
<div class="something004"></div>
<div class="something005"></div>
```
```css
[class^= something] {
    width: 25px;
    height: 25px;
    padding: 10px;
    margin: 10px;
    background-color: lightblue;
}
```
[Ref.] https://stackoverflow.com/questions/9836151/what-is-this-css-selector-class-span  
