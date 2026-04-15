# Tenglar (_links_)

It can be very good to have links that refer to a certain part within a website. 

In HTML, this is done with the ID attribute.

```HTML
<body id =â€œtopâ€œ >Top of that</a>
```

An ID attribute that stores the actual reference to a specific location in the document. 

```HTML
<a href="#top">Top of that</a>
```

* [Example of internal links](Daemi/relative_links.html) (_relative links_)

## Hulduklasar (_pseudo-class_)

To make the browser responsive (_responsive_) there are so-called _hidden clusters_ that respond to the user's use.

```CSS
    a:link {color: #F00}
    a:visited {color: #0F0}
    a:hover {color: #F0F}
    a:active {color: #00F}
```

* ```:link``` initial color. 
* ```:visited'' another color indicates that a user has used the connection
* ```:hover'' NOTE! 
* ```:active'' works when a link is touched or selected

There are many other hidden classes used in CSS styling, and we will go into more detail about their use in the next step. 

---

### Font settings in CSS

```CSS

body {
font-family: Helvetica, sans-serif; 
    font-style: normal;      /* italic, obligue */
    font-weight: 500;     /* normal, bold, 100 - 900 */
    font-size: 1rem;          /* 16px, 1em, 100% */
line-height: 1.5;         
}

/* here all styles are combined into one command "font:"*/
body {
    font:normal 500 1rem/1.5 Helvetica, sans-serif;
    /*font-style, -weight, -size/-lineheight -family */
}


```

### Website background image

Since the majority of browser usage is on mobile screens, complex and colorful graphics should be avoided. 


```CSS

body {
    background-color: #6ff;
    background-image:url(flott-logo.svg);
background-repeat: no-repeat;     
background-position: 200px 300px; 
    background-position: center middle;
/* X horizontally: left, center, right. 
    background-attachment: fixed; /* scroll */	
}
/* all background commands in one */
body {			
	background: rgb(3,3,3) url(image.jpg) 0px -5px scroll no-repeat;
/* color, image, position X-Y, fixed, repeat -x -y */

}

```
