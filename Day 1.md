# Personal Webpage Day 1

###### Author(s):  Shawn E., Mitch C. 

In this project, you are going to build a personal webpage that is hosted live on the web! An example of a finished personal webpage can be found [here](https://harshharwani90.github.io/).

Today, your site is going to look very unprofessional and bland. This is because we are coding only with HTML, and haven't added any special decoration (CSS) to our project. We will stylize our webpage on Tuesday, for now focus on creating the content that you want!

In web development, the most critical aspects for reaching a solid result are **design & planning**. Over the course of today and tomorrow, you are going to build one small part of a much larger project. Each webpage that you and your teammates make are going to be links on a larger website! One example of a final project for Winter Camp is the following:

> **Climate Change Website Group Project**
> - Home/Landing Page (Teammate #1's Webpage from Monday/Tuesday). 
> - Climate Change Facts & Figures (Teammate #2's Webpage from Monday/Tuesday)
> - Videos & Photos about Climate Change (Teammate #3's Webpage from Monday/Tuesday)
> - The Climate Change Debate (Teammate #4's Webpage from Monday/Tuesday)
> - About the Team (Teammate #5's Webpage from Monday/Tuesday)
> - Interesting Articles & How to Take Action (Teammate #6's Webpage from Monday/Tuesday)

Your team can choose **any** theme for your project, it doesn't have to be climate change. Some examples student's have used before include websites about ***movies, technology, hobbies, video games, or even just portfolio pages for each of the team members to create and own their own personal websites for college applications and resume purposes***.

### Before We Start...
1. Your team should vote to identify a theme that you all want to base all of the websites around for this week. 
2. You should identify 6 webpages that your team can build based on the theme you choose.
3. Confirm with your instructor this sounds like a good path to take!


## Let's get rolling!
### Objectives
- Learn the basics of the HTML
<br>
- Build a basic webpage that your team will use in their final website.

### Create the Introduction of the Article
1.  First, head over to your `index.html` file.
<br>
2.  Next, on line 14, lets create a `h1` tag (also known as a header or heading) with the text *Hello World*, then run the project. It should look something like this (you can paste in the following)
```html
<h1>Hello World</h1>
```
3. Now, you can delete that *Hello World* and replace it with the heading of your webpage.
4. Now, let's add some basic description text. Try using a **paragraph** tag to add this.
> *Hint*: Use google to find your answer

### Miscellaneous Tools

**How to make a bulleted list.**
> 1.  Create a new heading. You can call it *Contents*
> 2. Add bullets under the heading using a **unordered list** (google it!).
   
**How to add links.**
> 1. Now lets try adding some links to the page using an *anchor* tag.


**How to divide Sections**
> 1. Let's take a step back and divide our sections using the HTML `div` element. Check it out below -- right below the "Name Here" `h1` element, we added a div. Notice how we also closed it after the end of the section following the closing `p` tag. 

    <!DOCTYPE html>
    <html>
    
    <head>
      <meta charset="utf-8">
      <meta name="viewport" content="width=device-width">
      <title>My Portfolio</title>
      <link href="style.css" rel="stylesheet" type="text/css" />
    </head>
    
    <body>
      <h1>Name Here</h1>
      <div>
          
        <p> Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore  et dolore magna aliqua. Sed pulvinar proin gravida hendrerit lectus. Diam in arcu cursus euismod quis viverra nibh cras pulvinar. Pellentesque habitant morbi tristique senectus et. Eget nulla facilisi etiam dignissim diam quis enim lobortis. Ac tortor vitae purus faucibus ornare suspendisse. Fringilla ut morbi tincidunt augue interdum velit euismod in. Et leo duis ut diam quam nulla porttitor massa. In vitae turpis massa sed elementum. Laoreet sit amet cursus sit. Habitant morbi tristique senectus et netus et. Varius duis at consectetur lorem donec massa sapien faucibus et. Consectetur adipiscing elit duis tristique sollicitudin nibh sit amet. Euismod elementum nisi quis eleifend quam adipiscing vitae proin. Sollicitudin ac orci phasellus egestas. Nulla posuere sollicitudin aliquam ultrices sagittis orci a scelerisque. Elit eget gravida cum sociis natoque. </p>
      </div>
      <h2> My Skills</h2>
        <ul>
          <li>Nunchuck Skills</li>
          <li>Bow-Hunting Skills</li>
          <li>Computer Hacking Skills</li>
        </ul>
        
    </body>
    
    </html> 
    ```
> 2. Now that we have added a div, let's give the `div` a name (also called a "class"). We will use classes heavily tomorrow to make our elements look amazing! *Note:* This class name could be anything that you would like.

```html
    ...
    <div class="about">
      <p>...</p>
    </div>
    ...
```
> 3. Now that we have put our content in a div lets get each element inside of that div a id so, later we can style our tags easier. Your code should be somthing like what is shown below.
```html
    ...
    <div class="about">
      <p id="about-text">...</p>
    </div>
    ...
```
> 4. If you have more sections, go ahead and add divs to each major section of your article as well as id's to your major elements

### We've got the basics, let's build our sites!

Ok, so by now, you should have a basic amount of text on the page. You should also have the basic tools to get started with HTML. I think it would be cruel to keep dragging you through tutorials at this point. 

You should now get started on using any combination of the code elements above to build the content your website (remember just worry about content, not style yet). If you want to find out how to add more features (tables, videos, interactive images, forms), we recommend checking out the `Day 1 Extension.md` file in the Extensions folder. 

Additionally, **please** leverage these sites heavily. They have decades of development put into them and explain many HTML concepts better than any educator could (they also give working examples).
 - [W3 Schools HTML Tutorial](https://www.w3schools.com/html/)
 - [GeeksforGeeks HTML](https://www.geeksforgeeks.org/html/)
 - [Stackoverflow](https://stackoverflow.com/questions/tagged/html)

If you run into errors or problems, **google first** then ask your instructor and teammates!

  > Last thing: if your team chooses to pursue portfolios, here is a list of impressive portfolios we recommend checking out for inspiration. 
  > <br> [Shawn Engmann's Portfolio](https://shawnengmann.com)
  > <br> [Luis Quezada's Portfolio](https://quezada.nl)
  > <br> [Hyperz#0001 Portfolio](https://hyperz.net)
  > <br> [Jack's Portfolio](http://jacekjeznach.com)
  > <br> [Tazio de Bruin's Portfolio](https://en.tazio.nl/)
