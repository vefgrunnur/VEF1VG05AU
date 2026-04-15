# Style - _Cascading style sheet_ (CSS)

When the HTML standard was designed, it was mostly intended to allow text documents to be shared between Internet-connected computers. 

When the artificial world got up to speed with the use of the Internet and its real possibilities began to come to light, it became clear very early on that the HTML standard just wasn't enough to meet the increased appearance requirements.

Cascading Style Sheets contain special formats used to define the transformation and appearance of HTML files. 

* It is much easier to update the look of an entire website than ever before
Appearance-related rules are held in one or a few shelters.
* CSS offers more complete control over the appearance of documents.
* CSS offers features that improve the accessibility of document content for people with disabilities.
* CSS can be used to distinguish different layouts of the same content (HTML) for e.g.
print job or laptop and refer to a different CSS file for each one
media.

The World Wide Web Consortium standards committee, which oversees the HTML standard, decided to make small improvements to the standard instead of changing it and possibly losing it to nonsense. 

See more at [http://www.w3.org/Style/CSS/](http://www.w3.org/Style/CSS/)


There are many ways to style an HTML website.

* <body> Wrapping (Inline)
Styles placed in HTML style are only valid for the type that the styles are in.
* <head> Local
Styles placed in the header, valid for all HTML documents.
* <link> Global
Styles are placed in another document as a style sheet and has the extension .css - all
Web sites linked to the style site have the same features and appearance.
Comparison: Covers **â€“** Standing **â€“** Worth

Wrapped styles take precedence over static styles and static styles over variable styles. 

* The browser first reads into the computer's RAM what is related to the filter, such as images and styles, then commands from the <head> section above and then the configuration placed inside the <body> tag above, all together.

### Our connection (_global_)

The strength of stylesheets lies in being able to create styles in a separate document which is then linked to each HTML element that should be placed under the same layout or layout. 

To be able to use the styles in the CSS document, we need to put a <link> tag in the HTML document that refers to the CSS document. 

#### &lt;!DOCTYPE HTML>

```HTML
    <html>
    <head>
        <meta charset="utf-8">
<title>Our (e. global) connection</title>
        <link href="styles.css" rel="stylesheet">
    </head>

```

**href=â€¨styles.cssâ€¨** is the path to the file styles.css (have HTML and CSS files in the same folder). 

```CSS
h1 { color:red; 
are in red color */
```

> /* */ delimits comments in a CSS document. 

> &lt;!-- --> gegnir sama hlutverki innan HTML skjals.

### Sins:

These two files must be in the same folder, style.css and index.html so
the connection <link> works between them.

In a CSS document that I name styles.css, I write the following style

```CSS
p {color:red;} /* All paragraphs <p> have red text*/
```

In an HTML document called e.g. 

```HTML
<!DOCTYPE HTML>
<html>
    <head>
        <meta charset="UTF-8">
<title>Example no. 
        <link href="styles.css" rel="stylesheet">
    </head>
    <body>
<h1>Prediction</h1>
<p>This text in a paragraph will be red<p>
    </body>
</html>
```

How do I set different fonts?

```CSS
    body {font-family: sans-serif}
    h3 {font-family: courier}
    .serif {font-family: serif}
```

```HTML
<body>
<h1>All fonts on the web series are sans-serif</h1>
<h3>Intermediate company in Courier</h3>
<p>Paragraph</p>
<p class="serif">Another paragraph with serif font</p>
</body>
```
How do I determine the font size?

```CSS
    h1 {font-size: 2rem}
    h2 {font-size:130%}
    p {font-size:16px}
```

How do I measure font appearance?

```CSS
    h1 {font-style:italic}
    h2 {font-style:normal}
    p {font-style:oblique}
```
How do I put spaces between characters?

```CSS
    h1 {letter-spacing:3px}
    h4 {letter-spacing:0.5em}
```
How do I choose a font?

```CSS
    p.normal {font-weight:normal}
    p.thick {font-weight:bold}
p.thicker {font-weight:900} /* scale from 100 to 900. 400 = normal */
```

An example of how clusters are placed in an HTML document

```HTML
<body>
    <p class="normal">This is a normal paragraph</p>
    <p class="thick">This is a thick paragraph</p>
    <p class="thicker">This is a thicker paragraph</p>
</body>
```
How to make links (_links_) interactive

```CSS
  a:link {color:red; text-decoration:underline;}
  a:visited {color:brown; text-decoration:none;}
  a:hover {color:orange; text-decoration:none;}
  a:active {color:pink; text-decoration:underline;}
```

How do I align text?

```CSS
    h1 {text-align:center}
    h2 {text-align:left}
    h3 {text-align:right}
```

How do I handle text in different ways?

```CSS
    h1 {text-decoration:overline}
    h2 {text-decoration:line-through}
    h3 {text-decoration:underline}
    a {text-decoration:none}
```

How do I insert text?

```CSS
    p {text-indent:2rem}
```
How do I measure the appearance of letters (text)?

```CSS
    p {text-transform:uppercase}
    p {text-transform:lowercase}
    p {text-transform:capitalize}

```

---

### Bjargir

* [Project solution 1](../../)
* [Study 1](../)
* [HTML, see more details](README.md)
* [Colors on website](litir.md)
* [Yfirlit yfir CSS skipanir (_CSS Cheat seets_)](https://cheatsheets.shecodes.io/css)
