# Day 2 Extension Materials

### Objectives
- Learn additional features of CSS and bootstrap
- Continue practicing self-learning skills

#### The extension material is a way students can integrate more advanced content of their choice. Feel free to choose which materials you want to add into your site, or even explore other options not included within this document. 

----
## CSS Guide
### CSS Contents: 
- Animations/Transitions
- Image Masking
- On Hover
- Transformations
- Shadows
- Scroll Snapping
- Resources

----
### Animations/Transitions
CSS Animations allows elements to change style over time by specifying the properties and the keyframes. CSS Transitions allow you to change property values over a certain duration of time. 
- Think about a place where you could implement an animation or a transition. Is there a certain element you want to pop out? A header? An image?
1. Add an animtaion or a transition to your website.

* [Mozilla Animations](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Animations/Using_CSS_animations)
* [W3Schools Animations](https://www.w3schools.com/css/css3_animations.asp)
* [W3Schools Transitions](https://www.w3schools.com/css/css3_transitions.asp)




Here is an example of a square that transitions from red to yellow over the course of four seconds. Note that with animations, the element goes back to its default value after the animation has run. 
```css
@keyframes example {
  from {background-color: red;}
  to {background-color: yellow;}
}

div {
  width: 100px;
  height: 100px;
  background-color: red;
  animation-name: example;
  animation-duration: 4s;
}
```


You can also play around with speed curves of an animation:

![Animation Gif](/assets/speed-curves.gif/)

----
### Image Masking
With image masking, you can create a layer over images to partially or fully mask portions of the element. With this feature, you can overlay two images over each other, crop an image into a certain shape or fade out an image. 
- Do you have any use case for this feature within your portfolio site?
2. Implement image masking into your website.

* [Mozilla Image Masking](https://developer.mozilla.org/en-US/docs/Web/CSS/mask-image)
* [W3Schools Image Masking](https://www.w3schools.com/CSSref/css3_pr_mask-image.php)

----
### On Hover
This is a feature of CSS that allows you to change a property of an element when you hover your mouse over it. Paired with transformations or transitions, you can zoom into an image, rotate, translate, etc. 
- Think about where you could implement this feature onto your portfolio site. Which transformation or transition do you want to pair this feature with? Is there another element you could change on hover instead?
3. Implement an on hover feature to your portfolio site. Try to mess around with different transformations.
  
* [CSS Zoom Hover](https://www.w3schools.com/howto/howto_css_zoom_hover.asp)

* [2D Transformations](https://www.w3schools.com/css/css3_2dtransforms.asp)

Here is the example code for zooming into a square on hover. Within the zoom class, the code specifies the size and time constraints while the zoom.hover section specifies the transformation. Note, if you are enlargening something, keep it within the size contraints of the webpage.

```css
<style>
.zoom {
  padding: 50px;
  background-color: green;
  transition: transform .2s;
  width: 200px;
  height: 200px;
  margin: 0 auto;
}

.zoom:hover {
  transform: scale(1.5); 
}
</style>

<div class="zoom"></div>
```
Here is what it shows up as. Be creative! (Maybe use it in a button?)

![html hover](/assets/hover-element.gif)


----
### Transformations (3D and 2D)
CSS allows you to add both 3D and 2D transformations to images and texts. These transformations include translation, rotation, scale (X, Y, Z) and skew. Oftentimes, this feature is paired with On Hover, or to slightly alter an image. 
- Is there an image that you would like to size up/down, rotate, etc?
4. Implement some transformations to your portfolio. Examine the difference between 
* [2D Transformations](https://www.w3schools.com/css/css3_2dtransforms.asp)
* [3D Transformations](https://www.w3schools.com/css/css3_3dtransforms.asp
)

Here are some examples of 2D transformations to fuel your inspiration/ideas!

![2D Transformations](https://lenadesign.org/wp-content/uploads/2021/06/CSS-2d-transforms.gif)

----
### Shadows
Another feature of CSS includes shadows, which you can apply to both texts and images. You can mess around with size, blur, layering, and borders. A box-shadow is another subcategory within this feature. 
- This feature could definitely be used to highlight a header, title/subtitle or an image.
5. Implement some shadows into your portfolio. Try to mess around with adding multiple colors, blur and box-shadows.
* [CSS Shadow Effects](https://www.w3schools.com/css/css3_shadows.asp)
* [CSS Shadow Box](https://www.w3schools.com/css/css3_shadows_box.asp)

Here is an example of a CSS box shadow that adds a shadow to the content in the bottom right. 

![Sample Box Shadow](https://www.webfx.com/wp-content/uploads/2021/10/0457-04-offset-box-shadow-example-01.png)

----
### Scroll Snapping 
This is a great feature to implement especially if you have clear-cut sections within your project. With this feature, you will "snap" to the next container of your project in a single scroll. 
- Do you have your portfolio site divided into clear sections/categories? Would scroll snap make it easier to understand your content?

This is an example of what scroll snapping would do to scrolling.

###### Below is a set of elements with normal scroll. (**without** scroll snapping)
![normal](/assets/smooth-scroll.gif)

_____

###### Below is a set of elements **with** scroll snapping. Notice how the elements "snap" into place.

![snap](/assets/scroll-snap.gif)


6. Implement scroll snapping into your portfolio site. Think about the snap-type and snap-padding along with other elements. of this feature.
* [Scroll Snapping Basic Concepts](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Scroll_Snap/Basic_concepts)
* [Scroll Snapping](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Scroll_Snap)

----
### Additional Resources
#### This is a place where we provide more resources that you can explore to gain a more detailed understanding of CSS and to brainstorm other advanced features that you would like to add into your portfolio site. 

#### **W3Schools CSS Guide:** 
- W3Schools provides a thorough yet easily understandable guide into CSS and variety of its features and properties. It's a great place to start to dive deeper into CSS and brainstorm features to add into your portfolio site.
* [W3School CSS](https://www.w3schools.com/css/)

#### **Mozilla Developer:**
- Mozilla Developer, similar to W3Schools, provides a comprehensive guide into CSS. Another place with extensive material where you can find many additional components to integrate into your portfolio site.
* [Mozilla CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)

----
## Bootstrap Guide
### Bootstrap Contents: 
- Fluid containers
- Nested rows
- Push and Pull
- Offsets
- Resources

----
### Fluid Containers
With this feature of bootstrap, you can extend a container across the full screen without any whitespace or offset. However, these containers can still be customized to add a little bit of whitespace if your portfolio would need some. 
#### Example of a Fluid Container
![Fluid Containers](https://d585tldpucybw.cloudfront.net/sfimages/default-source/blogs/older-content/tdn/container-fluid.jpg)

#### Customized Fluid Container
![Fluid Container with Customized Whitespaces](https://d585tldpucybw.cloudfront.net/sfimages/default-source/blogs/older-content/tdn/container-fluid-custom.jpg)
- Would fluid containers add more flexibility to your portfolio? Would it be better to have less whitespace on the margins? 

1. Change your containers to fluid containers within your portfolio website. 

* [Bootstrap Fluid Containers](https://getbootstrap.com/docs/5.0/layout/containers/)

----
### Nested Rows
Columns and rows are an essential part of Bootstrap grids. Rows can be infinitely nested, which means that we have limitless control over how to divide up the grid. One use case for nested rows is social media UI.
![Nested Rows Example](https://d585tldpucybw.cloudfront.net/sfimages/default-source/blogs/older-content/tdn/fully-nested-row.jpg)

2. Implement nested rows into your portfolio site. This feature can help build part of the layout of your site so be sure to mess around with various properties. 

* [Bootstrap Gridview](https://getbootstrap.com/docs/4.0/layout/grid/)

----
### Push and Pull
This feature of bootstrap allows you to have an alternative view of images and texts. The main functionality of this feature is to reduce the complexity
#### Example of Large Push and Pull Layout
![Push and Pull Large Scale Image](https://d585tldpucybw.cloudfront.net/sfimages/default-source/blogs/older-content/tdn/alternating-items.png)
- Is there any place on your portfolio site where adding an alternative text and image layout would reduce the complexity of your code? 
3. Implement this feature into your portfolio website. Mess around with this feature at a large and small scale. 
* [Bootstrap Push and Pull](https://getfishtank.ca/blog/bootstrap-3-column-reordering-using-push-and-pull)

----
### Offsets
This feature of bootstrap allows you to change the alignment of content by adding whitespace without adding in another container/content element. One of the common use cases with this feature is to horizontally center an element.
#### Offset Center Alignment
![Offset Example Image](https://d585tldpucybw.cloudfront.net/sfimages/default-source/blogs/older-content/tdn/offsets.png)
- Is there any place where you would rather right or center align a container?
4. Implement offsets into your portfolio site.
* [Bootstrap Gridview](https://getbootstrap.com/docs/4.0/layout/grid/)
* [Bootstrap Offset](https://css3menu.com/web-design/bootstrap-offset-property-980.html)

----
