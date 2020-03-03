
###### set output volumn when call window.print() on javaScript 

```css
/* example */

@media print {
	
	a:after {
		content: " [" attr(href) "] ";text-decoration: none;display: inline;
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
	#header, #side-wrapper, .titleBox .loadBox, .btnArea, .btnRight, .btn_info {
		display:none;
	}
	#contentArea {
		width:100% !important;padding:0px;background-color:#fff;
	}
	.chartFrame2 {
		border:none;
	}
	canvas {
		width:100% !important;display:inline-block;
	}
	.seltype01 {
		border:none;background:none;
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
		border:none !important;background-color:#fff;
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
	#policy #TYPE_1 {
		width:50%;
	}
}
```
