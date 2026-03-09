# The HTML standard

HTML (_HyperText Markup Language_) is a language used to create hypertext. 
contains the whole number of so-called tags (_tags_) which are used to mark the vehicle
what parts of the document are where, for example what the first heading in the sentence is.

> HTML tags can be checked so that they all start with the < and end with the > tag.

All web pages start with the tag < **html** > and end with </ **html** >. 
the closing tag is a slash **/**. 
the installation. 
vefnum [https://www.w3schools.com/tags/](https://www.w3schools.com/tags/)

When a website is inspected in a browser (_right click on the mouse and select "inspector"_) the HTML code of the website is highlighted.

```HTML
<!DOCTYPE HTML>
<html lang="is">
<head>
    <meta charset="utf-8" >
<title> My first website </title>
</head>
<body>
<h1>Hello world!</h1>
</body>
</html>

```

* _&lt;!DOCTYPE HTML>_
* At the top of the HTML column is a definition of what this document is like (_Document Type Definition_). 
* Surrounding all content of the website is <html>
* &lt;head>
* Anything placed between the <head> and </head> tags affects the site but does not appear in the browser. 
* &lt;title>
* <title> displays text at the top of a tab in the web browser and also in the search bar if selected by the user
* &lt;meta>
* Character set charset=â€œutf-8" is used, among other things, for Icelandic characters
* &lt;body> 
* All content displayed in a browser goes between the <body> and </body> tags. 

When you start writing HTML code for a website, it's good to see for yourself.
a human body divided into a head <head> and a body <body>. 
are essential and form the skeleton of the web site.

> Check the above steps to place **once** on a website.

The preferred style is to use only lowercase letters in the form: <body> text </body>. 
It is necessary to have strings indented when strings are woven into another string, making overreading easier
of the cow. 
if there is a lot of space between tags or text. 
turning button has no effect.

### Fyrisagnir &lt;h1> til &lt;h6>

The HTML standard offers 7 fonts <h1> to <h6> and <p>, by default the fonts have
A certain percentage of the font size of the <body> tag.

# h1 Company

## h2 Subheading

### h3 Interpreter

#### h4 Hardening text

##### h5 Bold text

###### h6 Subtext


Body is default 1em or 16px size (_user agent_).

**<p>** tag stands for paragraph.

> The font blocks are "_block elements_" which are 100% wide and with line spacing above and below the blocks.

[Let's take a closer look at the properties of tags in project 2.](https://github.com/vefgrunnur/Vefgrunnur/tree/main/Verkefni-2)

Example:

```HTML
<!DOCTYPE HTML>
<html>
<head>
    <meta charset="utf-8">
<title> The news website <title>
</head>
<body>
<h1> Iceland habitable in 10 years </h1>
<h2>This is a subversion </h2>
<p>This is an example of a paragraph ....</p>
</body>
</html>
```

### Enumeration in list <ul>

To create a list you need to use a combination of two tags, <ul> and <li> <ul>
stands for "unordered list" or an unordered list, <li> stands for "list item" or a list
eintak.

#### Numbered list <ul>

```HTML

    <ul>
<li> January </li>
<li> February </li>
        <li> Mars </li>
<li> April </li>
<li> May </li>
    </ul >
```

If you try this example, you'll see that each item in the list gets a â—Ḉ (depill) in front of it. 
is the default symbol.

- January
- February
- mars
- April
- May

#### Numbered list <ol>

It is also possible to get a numbered list, so we use <ol> or "ordered list", so
come the numbers 1, 2, 3 and so on descending down the list <li>.

Example:

```HTML

    <ol>
<li> January </li>
<li> February </li>
        <li> Mars < /li>
<li> April </li>
<li> May </li>
    </ol >
```

January 1st
February 2
3. mars
April 4
May 5

---

### Text message

To emphasize the content of text, the HTML standard has several features.

```HTML
<strong> | <em> | <sup> | <sub> | <blockqoute> | <span>

```

#### [inline element](https://www.w3schools.com/html/html_blocks.asp)

- **<strong>** Text with emphasis (bold)
- **<em>** Italic text
- **<sup>** tag causes the text to appear <sup>above the middle line<sub>
- **<sub>** moves the text to <sub>appear below the</sub> media line
- **<span>** it is possible to style text in other ways than in the styled ways

#### [block element](https://www.w3schools.com/html/html_blocks.asp)

- **<blockqoute>** is used outside quoted text
- **<hr>** Carries to line when changing propagation material

---

### Special feature.

Some characters and symbols are reserved in HTML and it is necessary to write them in a different way in the code. 
is e.g. 
Together with the html tools.

- **<** is written `<`
- **>** is written `>`
- extra space is written ` `
- the special feature © is written `©'
- <br> tag contains 1 line space in text, goes on the next line.

> Note that <font> and <center> and other tags are deprecated HTML 4 tags. 

List of entities: http://www.w3schools.com/html/html_entities.asp

---

### Ritun

As can be seen in the code examples above, threads that are within other tags are called "nested" threads. 

```HTML
    <p>Rangt</p>
    <ul><li>Lorem ipsum dolor</li>
    <li><ol>Vel voluptate id odit </li><li>quo accusamus voluptatem</li></ol>
    <li>velit ratione, atque quas!</ul></li>

<p>Correct installation, nested and indented</p>
    <ul>
        <li>Lorem ipsum dolor</li>
        <ol>
            <li>Vel voluptate id odit </li>
            <li>quo accusamus voluptatem</li>
        </ol>
        <li>velit ratione, atque quas!</li>
    </ul>
```

---

### Bjargir

* [Project solution 1](../../)
* [Study 1](../)
* [CSS, see more coverage](stylesheet.md)
* [Colors on website](litir.md)
* [Yfirlit yfir HTML skipanir (_HTML Cheat seets_)](https://cheatsheets.shecodes.io/html)
