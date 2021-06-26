### Image in HTML **(Adding & manipulate)**

<p class='six'><b>To add an image into the page you need to use this syntax</b></p>

<p class='zero'>HTML Images Syntax
The HTML img tag is used to embed an image in a web page.

Images are not technically inserted into a web page; images are linked to web pages. The img tag creates a holding space for the referenced image.

The img tag is empty, it contains attributes only, and does not have a closing tag.

The img tag has two required attributes:

src - Specifies the path to the image
alt - Specifies an alternate text for the image</p>

<p class='nine'>
<b>You will also often see an image element use two other attributes that specify its size:height This specifies the height of the image in pixels.width This specifies the width of the image in pixels also you align the image and put it to the right or left</b></p>


<img src="https://cdn.pixabay.com/photo/2015/04/23/22/00/tree-736885__480.jpg" alt="tree" style="width:500px;height:500px;align='right'"><img src="https://www.wikihow.com/images/thumb/d/dc/Insert-Images-with-HTML-Step-5-Version-5.jpg/v4-460px-Insert-Images-with-HTML-Step-5-Version-5.jpg" alt="screen" style="width:500px;height:500px;align='left'">







### Now let's talk about the extensions in iamges & the differance between them

**There are 3 commonly used format for images & they represent around 95% of images on websites**
## JPEG & PNG & GIF and ther is a huge differences between them 

### JPEG is a lossy compression specification that takes advantage of human perception , JPEG images are best suited for photographs and paintings of natural scenes where the variations in colour and intensity are smooth. However, if an image contains text or lines, where a sharp contrast between adjacent pixels is desired to highlight the proper shape, this lossy compression technique does not yield good results.

### PNG is a lossless image format No data is lost during compression and no compression artefacts are introduced in the image. For this reason, a PNG image would retain higher quality than an image than JPEG and would look a lot sharper, it would also occupy more space on the disk. This makes it unsuitable for storing or transferring high-resolution digital photographs but a great choice for images with text, logos and shapes with sharp edges.

### GIF is also a lossless image format GIF images are now mainly used only if the image contains animations.

<img src="https://thumbs.gfycat.com/CheerySeparateGoldeneye-size_restricted.gif" alt="Computer man" style="width:500px;height:500px;">
<img src="https://i.chzbgr.com/full/12191237/hFD0E9B81/internet-the-cover-gif-is-of-a-cat-feverishly-typing-away-on-a-laptop-keyboard-as-would-a-puppet" alt="Computer man" style="width:500px;height:500px;">


# colors in CSS
<p class='five'><b>Color can really bring your pages to life and make it attractive to the user such as the screen you are watching&</b></p><p class='seven'><b>notify that we can change the color of the background and the text it self</b></p>




<!DOCTYPE html>
<html>
<head>
 <title>Color</title>
 <style type="text/css">
 body {
 background-color: silver;
 color: white;
 padding: 20px;
 font-family: Arial, Verdana, sans-serif;}
 h1 {
 background-color: #ffffff;
 background-color: hsla(0,100%,100%,0.5);
 color: #64645A;
 padding: inherit;}
 p {
 padding: 5px;
 margin: 0px;}
 p.zero {
 background-color: rgb(238,62,128);}
 p.one {
 background-color: rgb(244,90,139);}
 p.two {
 background-color: rgb(243,106,152);}
 p.three {
 background-color: rgb(244,123,166);}
 p.four {
 background-color: rgb(245,140,178);}
 p.five {
 background-color: rgb(246,159,192);}
 p.six {
 background-color: rgb(245,176,204);}
 p.seven {
 background-color: rgb(0,187,136);}
 p.eight {
 background-color: rgb(140,202,242);}
 p.nine {
 background-color: rgb(114,193,240);}
 