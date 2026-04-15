# Flexible design

### ViÃ°miÃ° (_Breakpoints_) - "_Mobile up_"

```CSS

/* First come styles that apply to all document sizes, such as 
body {
	font-family: sans-serif;
	background-color: lightblue;
	color: darkblue;
}
/* Mobile horizontal, Mobile Horisontal */
@media only screen and (min-width: 37.5rem) { /* min-width= screens that are larger than 600px */
	  body {
		background-color: blue;
		color:white;
	  }
} 
/* tablet */
@media only screen and (min-width: 48rem) { /* screens larger than 768px */
	  body {
		background-color: black;
		color: lime;
	  }
}
/* Laptop, laptop */
@media only screen and (min-width: 60rem) { /* screens larger than 960px */
	  body {
		background-color: red;
		color: yellow;
	  }
}
/* Computer screen */
@media only screen and (min-width: 80rem) { /* screens larger than 1280px */
	body {
		max-width: 80rem; 
margin: 0 auto;  
	}
}

``` 

### Grid zoning

- https://bok.vefforritun.is/18.skalanlegir
- https://bok.vefforritun.is/21.grid#20.4.2

