## Portfolio Site Day 2 - Part 1 
###### Author(s):  R. Tang, S. Dave, Mitch

### Objectives

- Learn how to integrate CSS into a website
- Learn how to alter the font, color, size, and change of the spacing/alignment of various elements. 
- Master Inline CSS basics
  
_____


### Lesson
1. First, find your `styles.css` file on the sidebar to your left.
   
> If you don't have a CSS file, make one by clicking the *Add File* button at the top of the NavBar.

![a](asc-gif.gif)

2. CSS is based on classes that HTML elements can be assigned to.

________

* Inline CSS is another way to add CSS to HTML.
  * This isnt the best way to write CSS for a number of reasons:
  * We like to organize things, so CSS is typically written in a seperate file
  * Instead of writing long CSS code on each element, we can just make a **_class_** of CSS styles that we can assign to HTML elements.

Here's a short exanmple just so that you know what it is:


_____

Below is the syntax to make a class called r_text with red text, a font size of 15 pixels and a left padding of 40.

```css
.r_text{
  color: red;
  padding-left: 40;
  font-size: 15px;
}
```

- Now go into your CSS file and make a class for your text. Don't worry about fonts - we will get into that later.
  
_____


3. After writing that class, we need to tell the HTML file where to go to find the CSS file. The syntax will look something like this:



```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>this is a title</title>


    
<!-- this like of code links the css file to the HTML.
    it's typically found at the end of the head element. -->
    <link rel="stylesheet" href="style.css"> 
<!-- you will have to change the styles.css to the name of your filename or the path to your css file. -->
    
  
  </head>
  <body>
	<script src="index.js"></script>

<p> hello world</p>
    
  </body>
</html>
```



* Now do this yourself with your files!
  * (hint: you may need to replace the names with your file names)

____

4. Now that we have the files linked, we just have to assign the HTML elements a CSS class. Below is the syntax with an element with and without a CSS class assigned to it. 



```html

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>HTML 5 Boilerplate</title>
    <link rel="stylesheet" href="style.css">
  </head>
  <body>
	<script src="index.js"></script>

<p> this text is text without CSS styling, it does not have a class assigned to it.</p>

<hr>

<p class = "r_text"> this text does have some styling, it's red and it has a 40 pixel padding.</p>
    
  </body>
</html>

```


* Now go to your CSS file and write some classes to style text with your preferred colors!
* Remember to assign your HTML elements classes too, or else your CSS styling won't show up.
* Just play around with the color and font size properties for now.


### The CSS Box Model

_____


* Every element in HTML has a border, padding and margin properties. Some just may not be visible.
* This is called the box model for CSS. Essentially, every HTML element has these outer layers that you are able to adjust the values of to make it look nicer.

![Box model diagram](https://upload.wikimedia.org/wikipedia/commons/7/7a/Boxmodell-detail.png)

>The text that you're reading right now probably has a value for the left padding or margin set, because it has a space on the left.

A lot of websites use the box model to make their text look prettier, though it is not requiered.

_____


5. Now go back to your css file and add some borders or margins to your classes!
* We encourage you to play around ; there is no right answer, just explore how these properties work!

Below is an example:



```css
/* below is a class for aqua text with some paddings */

.aqua-text {
  color: aqua;
  font-size: 20px;
  padding-left: 35px;
  margin-bottom: 30px;
  
}
```



```html
<!-- i'm going to not include the boilerplate code here for sake of space, but you guys should have boilerplate code here -->

<body>
  <p class="aqua-text"> this text is aqua in color and it is part of a css class! </p>
</body>
```

## Inline CSS


* To add inline CSS, you don't have to add any new files to the document. You will be making changes directly in your HTML file.
* Inline CSS allows you to make changes to specific elements.
  * For example, if you want to change the size of just one live of text but you don't want to create a whole class, you wouold use inline CSS.

```html

<p style="font-size: 43px; color: red;"> This text has inline css styling! </p>

```

* Try to add inline HTML to a couple of your elements!
* You dont have to keep them, you can just delete them when youre done (this is just so you know how to add inline CSS)
----
### Color: 
* Colors are specified using predefined color names, RGB, HEX, HSL, RGBA, HSLA values.
```CSS
<h1 style = "color: yellow;"> This makes the color of this header yellow. </h1>
```
1. Google how to add color using three of the six methods specified. Next, attempt to add color to different elements of your website (Title, headers, text, background, etc.). Some questions to fuel your research...
* Which elements do I want to change the color of?
* Can I add multiple colors to one element?
* How can I change the opacity, brightness, saturation of the color? 
* Are there any resources can help me generate the color I want to use?
____
### Text: 
* There are a lot of text properties that you can play around with including alignment, spacing, font, borders, etc.
```CSS
<h1 style = "font-family: verdana; font-size: 300%; border: 2px solid;"> This sized-up text will have verdana font and a thin solid border. </h1>
```
2. Research into the various text properties available through CSS. Attempt to change the spacing, alignment, font, size of your texts within your website. Some questions to guide your search...
* How can I make my text left-aligned, center-aligned or right-aligned?
* How can I add spacing between my words? Letters? 
____
### Background/Borders
* With CSS, you can add color, images, and various effects to your website background (as a whole, and/or within elements).
```CSS
<div style = "background-image: url('cat.jpg');"> </div>
```
* This line of code will set a cat photo as the background image.
3. Research into the various background effects that you can add and attempt integrating 2-3 unique properties. Some questions to keep in mind...
* Do I want the background image to be static or dynamic?
* How can I combine multiple properties? (For example color and images)
----
### Advanced Elements
* Although we have gone over some of the basics within CSS (color, images, background, etc.), there are additional elements that you can add into your website.
4. Research into other CSS properties and integrate 2-3 into your website. 
----
* After playing around with this stuff, show off your work to everyone!


## Enjoy your lunch break everyone!

----

