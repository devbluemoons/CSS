## position
[Ref.] https://developer.mozilla.org/ko/docs/Web/CSS/position
  
###### sticky
```css
thead th {
	z-index: 100;
	background: #ddebf5; 
	font-weight: bold; 
	position: sticky;
	top: 0;
}
```
  
###### set border for sticky thead 
```css
th:before {
	content:'';
	position:absolute;
	left: 0;
	top: 0;
	width:100%;
	border-top:1px solid #7d9aae;
}

th:after {
	content:'';
	position:absolute;
	left: 0;
	bottom: 0;
	width:100%;
	border-bottom:1px solid #C2D2DF;
}
```
