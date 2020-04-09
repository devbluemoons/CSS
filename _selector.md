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
