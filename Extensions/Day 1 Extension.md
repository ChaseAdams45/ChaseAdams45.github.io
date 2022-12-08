# Day 1 Extension Materials

### Objectives:
- Learn additional advanced features of HTML
- Continue practicing skills of self-learning new topics

#### The extension material is a way students can integrate more advanced content of their choice. Do not feel required to implement all the material mentioned in this document if you don't want to add it to your portfolio site. Also studets can feel free to research other content that they would like to add as well. 

----
### Contents: 
- HTML Forms
- Interactive Images
- Tables
- Multimedia

----
### HTML Forms
With HTML, you can add forms to collect user input through single box input fields, checkboxes, radio buttons, etc. Forms use the form element, and more specifically, input elements. 

- Think about a place where you could have some user input. Do you want to take input on the user's favorites, wager on their input on various choices, etc?
1. Within your HTML file, add in one or more HTML forms. Do not worry too much about how your server will process the input
2. Try adding different types of forms! Some forms can get text as inout or you can have checkboxes as well. Below is a list of ideas and rescources.

* [HTML Forms Intro](https://www.w3schools.com/html/html_forms.asp)
* [Form Templates](https://www.w3docs.com/learn-html/html-form-templates.html)
* [More Examples (these are really good)](https://www.w3schools.com/js/js_input_examples.asp)
 
----

### Interactive Images
With HTML, you can add clickable regions into photos to take users/viewers to a certain page. You can customize this feature using maps, shapes, and styles.

- Think about a place where you could had an image that guides a user to a certain page or section.
2. Within your HTML file, add in an interactive image. Google how to mess around with the map tag and add specific requirements of shape, coordinates, and

Rescources:

* [HTML Interactive IMG Maps](https://www.w3schools.com/html/html_images_imagemap.asp)

----
### Tables
Another feature that you can add to your portfolio site are tables to allow you to arrange your data/information into rows and columns using the table, table cells, table rows, etc elements. 

![table example](https://developer.mozilla.org/en-US/docs/Learn/HTML/Tables/Basics/numbers-table.png)

3. Within your HTML file, add a table to display some of your information. Google how to mess around with sizing, # of rows and columns, styling, etc.

[HTML Tables](https://www.w3schools.com/html/html_tables.asp)

[More Tables Examples With formatting](https://www.geeksforgeeks.org/html-tables)

Below is an example of a simple table in HTML without any additional formatting.

```html
<table style="width: 100%">
  <tr>
    <th>Name</th>
    <th>Age</th>
    <th>Occupation</th>
  </tr>
  <tr>
    <th>Alex</th>
    <th>23</th>
    <th>Web Designer</th>
  </tr>
  <tr>
    <th>Rachel</th>
    <th>45</th>
    <th>Fullstack Developer</th>
  </tr>
```

----
### Multimedia
HTML allows you to add various sources of media including videos and audio files using the audio and video elements. 

4. Within your HTML file, add in videos or audios that you would like to include in your portfolio. Google how to source videos and audios, change sizing and/or add additional interactive buttons (play/pause, make bigger, make smaller, etc.)

[HTML Image Embeds](https://www.w3schools.com/html/html_images.asp)

[HTML MP4/Video Embeds](https://www.w3schools.com/html/html5_video.asp)


```html
<video width="320" height="240" controls>
  <source src="movie.mp4" type="video/mp4">
</video>
```

[HTML Audio Embeds 
(might not work in some browsers, just try it you dont have to do this one)](https://www.w3schools.com/html/html5_audio.asp)

```html
<audio controls autoplay>
  <source src="horse.ogg" type="audio/ogg">

</audio>
```

----
