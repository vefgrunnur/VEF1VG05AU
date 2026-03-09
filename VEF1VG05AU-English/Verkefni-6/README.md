# Image processing and insertion of images on a website

### Goal

Nemendur geta:

* processed images for web in [image editing program](https://www.photopea.com/)
* let images of the same size enter by screen size
* used the <picture> tag to display a large image that the browser searches for a screen size

![Octocat](github-octocat.svg)

#### Attached to the project solution are working data in a .zip file

* [Web page, style page and images] (Namsefni-6/vinnugogn.zip)

The .zip file downloads to your computer. 

- We are talking about one big picture on the front that needs to be in four different sizes.
- The picture is then uploaded to the website in the `picture` tag.
- Picture of Freystein has a background that needs to be removed and the background is made transparent (_transparent_).
- Then there are 6 pictures that are all supposed to be the same size and they are then supposed to appear after a screen size in a row, then two in a row and in one column on mobile screens.

1. **Large front view**
* The picture is saved in five sizes and the browser chooses the right size according to the width of the screen.
* Subject: <br>

```HTML
    <picture>
        <source media="(min-width:1930px)" srcset="large image 3640px width">
        <source media="(min-width:1280px)" srcset="mynd 1920px breidd">
        <source media="(min-width:960px)" srcset="mynd 1280px breidd"> 
        <source media="(min-width:768px)" srcset="mynd 960px  breidd">
        <source media="(min-width:480px)" srcset="mynd 600px breidd"> <!--mobile landscape-->
        <source media="(min-width:0px)" srcset="mynd 480px breidd"> <!--mobile portrait-->
        <img src="1280px width" alt="img tag must be included (fallback)" style="width:auto;">
    </picture>
    
```
        
* With the <picture> tag on a website it is possible to sort pictures according to the width of the screen
* [Introductory image](images/mynd1.jpg) (_note! new images are included that can be used as an intro image_)
1. **Picture with transparent (_transparent_) background**
* Clean background from photo in photo editor
* [Image with transparent background](images/image2.jpg)
1. **Images**
* 6 images are saved in the same size (500 x 500px) and their order varies on the website depending on the width of the screen
* [Images] (images/image3.jpg)

* Web images can be compressed to .jpg (kb), which is by far the most widely used on websites.
* Images in .png format can have a transparent background and ~ 25% magnification
* Images in .gif format can have a transparent background but with 0% magnification

**[Photopea](https://www.photopea.com/)** is a photo editing application (_app_) that runs in a browser.

* Myndir skornar:  _Toolbar -> Crop Tool_
* Images placed in the correct size: _Image -> Canvas size_.
* Extension for web in Photopea -> _Export -> .jpg or .png_
    
Images placed on a website should not be wider than the frame in which the image appears. 

```CSS
        img { 
            max-width:100%;
            height: auto;
        }
```

---

### Assessment 5%

- Splitting the waterfall image by screen size
- Portable (vertical): 20rem - 37.5rem
- Portable (horizontal): 37.5rem - 48rem
- Panel machines: 48rem - 80rem
- Laptops and computer monitors: 60rem +
- Images in paragraphs in the correct size and adjusted to a column
- Picture of the author with a transparent background
- All images in a separate folder (images/)

Return all work data belonging to the project to **Innu/VEFÃž1VG/Verkefni 6**.

#### Grade will be published in Inna

---

#### Myndvinnsla

* [Picture tag](https://www.w3schools.com/tags/tag_picture.asp)
* [Photopea](https://www.photopea.com/) Photo editor that runs in a browser
* [Photopea instructions](https://www.photopea.com/tuts/)
  * [How To Use Photopea 2024 (Tutorial for Beginner Designers - Youtube)](https://www.youtube.com/watch?v=JIdvvG9ZX7c)
* [Install Photopea to your device](https://www.photopea.com/tuts/install-photopea-to-your-device/)
* [Gimp](https://www.gimp.org/) 
  * Mac, Linux og PC myndvinnsluforrit
* [Myndasafn Pxhere.com](https://pxhere.com/)

#### "Dummy" myndir

* [Lorem Flickr](https://loremflickr.com/)
