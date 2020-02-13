## css global variable
  
###### declare in main css file
```css
:root {
  --header-height: 50px;
  --sidebar-width: 200px;
}
```
  
###### how to use
```css
header {
  height: var(--header-height)
}
nav {
  width: calc(100% - var(--sidebar-width));
}
```
