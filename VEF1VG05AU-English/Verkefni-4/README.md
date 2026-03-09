# Flexible web design (_Responsive Web Design_)
 
### Objective:

Students gain an understanding of:

* the design of a flexible web interface (_Responsive Web Design_)
* how to work with the CSS _@media_ command to change the layout of a website according to parameters

The layout of a website with many columns does not work well on small mobile screens. 

- [Code example with media (_@media & breakpoints_) ](Namsefni-4/README.md)

## 4.1 Flexible column layout, 1, 2, 4

Copy _Task 3.2_ to a new folder, e.g. 
Use the **_@media screen_** command to display different layouts depending on the screen size.

* Margin: 0 â€“ 599px,
* all columns with 100% width (_grid-template-columns:(1fr);_)
* Width: 48rem (768px - 959px)
* 2 and 4 columns with 50% width (_grid-template-columns:(1fr 1fr);_)
* Width: 60rem (960px - 1279px)
* 3 columns 33.33% width (_grid-template-columns:repeat(3, 1fr);_)
* Width: 80rem (1280px - 1599px)
* 4 columns 25% width (_grid-template-columns:repeat(4, 1fr);_)
* Width: 100rem (1600px)
* The content of the web series is centered
 

- [Sønidèmi 4.1](Namsefni-4/Dèmi41.md)

---

## 4.2 Flexible website with _"Grid-template-columns"_

Copy one website and copy it from project 3.3 and save in a new folder which you can name **project-42**.

The structure of the website is as follows

 * nav
 * header
 * main
   * article
   * section
     * aside
     * aside 

Now it's time to make the webcast flexible. 

* Margin: 0 â€“ 599px,
* all columns with 100% width (1fr)
* The table of contents contains links with _display:block_
* Dimension: 37.5rem (600px)
* Table of contents with _Flex direction: row;_
* Dimensions: 48rem (768px)
* <main> in one column (_grid-template-columns:(1fr);_)
* <article> in one column
* <section> with <aside> in two columns (_grid-template-columns:(1fr 1fr);_)
* Width: 60rem (960px)
* <main> in two columns (_grid-template-columns:(2fr 1fr);_)
* <section> with <aside> in one column (_grid-template-columns:(1fr);_)
* Dimensions: 80rem (1280px)
* The content of the web series is centered

- [Sønidèmi 4.2](Namsefni-4/Dèmi42.md)

## 4.3 Flexible website with _"Grid-template-area"_

Copy the site 4.2 and the style site and use the **"grid template area**" to organize the new site.

> The `aside' tags are taken out of the `section' tag, so that `article' and `aside' are together in the `main' tag.

To use grid area we have to name clusters that are connected to certain nodes and place them in _grid area_

| HTML tag | CSS klasi | Grid area name |
| --- | --- | --- | 
| main  | .main   | grid-area: main   |
| aside | .aside1 | grid-area: aside1 | 
| aside | .aside1 | grid-area: aside2 | 

* Margin: 0 â€“ 599px,
* table of contents is _"Flex"_ as in website 4.2
  * ```CSS
    .main {
      display: grid;
      grid-template-areas: 
      "article"
      "aside1"
      "aside2";
    }
    ```

* Dimensions: 48rem (768px)
  * ```CSS
    .main {
      display: grid;
      grid-template-areas: 
      "article article"
      "aside1 aside2";
    }
    ```

* Width: 60rem (960px)
  * ```CSS
    .main {
      display: grid;
      grid-template-areas: 
      "aside1 article article aside2";
    }
    ```
    
* Dimensions: 80rem (1280px)
  * ```CSS
    .main {
      display: grid;
      grid-template-areas: 
      "aside1 article article article aside2";
    }
    ```
* The content of the website is centered (margin:auto)

- [Sønidèmi 4.3](Namsefni-4/Dèmi43.md)

---

#### Assessment 5%

* **4.1 Columns with media**
* **4.2 Grid template columns**
* **4.3 Grid template area**
* Table of contents (nav) to be flexible with _display:flex_

### Verkefnaskil

- Put all the data of the project in a **.zip file** and submit it to project 4 in Innu

#### Grade will be published in Inna
