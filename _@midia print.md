
###### set output volumn when call window.print() on javaScript 

```css
/* example */

@media print {
	
	@page {
		margin: 0 !important; 
	}
	body {
		margin: 1.6cm !important;
	}
	a:after {
		content: " [" attr(href) "] ";
		text-decoration: none;
		display: inline;
	}
	a:link, a:visited {
		text-decoration: underline;
		color: #000;
	}
	body {
		margin: 0;
		box-shadow: 0;
		background: #fff; 
		height:100% !important;
		width:100% !important;
	}
	#header, #side-wrapper, .btnArea, .btnRight, .btn_info {
		display:none !important;
	}
	#contentArea {
		width:100% !important;
		padding:0px;
		background-color:#fff;
	}
	.chartFrame2 {
		border:none;
	}
	canvas {
		width:100% !important;
		display:inline-block;
	}
	.seltype01 {
		border:none;
		background:none;
	}
	.calBox2 a {
		display:none;
	}
	.calBox2 {
		width:75px !important;
	}
	a:link:after, a:visited:after {
		content:"" !important; 
	}
	input[type="text"], .calBox2 input {
		border:none !important;
		background-color:#fff;
	}
	.page_wrap {
		display:none;
	}
	.boardBox {
		min-width:100% !important;
	}
	.tblBox {
		margin-bottom:30px !important;
	}
}
```
  
참조 : https://stackoverflow.com/questions/8228088/remove-header-and-footer-from-window-print
