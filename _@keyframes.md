###### @keyframes, -webkit-keyframes
```css
/** fade effect **/
@-webkit-keyframes fade-in {
	0%   {opacity: 0;}
	100% {opacity: 1;}
}
@keyframes fade-in {
	0%   {opacity: 0;}
	100% {opacity: 1;}
}
.fadeIn {
	-moz-animation   : fade-in 700ms;
	-webkit-animation: fade-in 700ms;
	animation        : fade-in 700ms;
}

@-webkit-keyframes fade-out {
	0%   {opacity: 1;}
	100% {opacity: 0;}
}
@keyframes fade-out {
	0%   {opacity: 1;}
	100% {opacity: 0;}
}
.fadeOut {
	-moz-animation   : fade-out 700ms;
	-webkit-animation: fade-out 700ms;
	animation        : fade-out 700ms;
}
```
