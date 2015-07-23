JiSlider
========

Simple Image Slider - jQuery Plugin
-----------------------------------

JiSlider is a simple jQuery Plugin to create a Image Slider. You can modify settings to make the slider for your taste. It has been tested on Safari 8, Chrome 44, Firefox 38.

[View demo](http://jiyong.unifox.kr/file/html/JiSlider.html)

Simple Usage
------------

```html
<!DOCTYPE html>
<html>
  <head>
    <link rel="stylesheet" href="/path/to/JiSlider.css">
  </head>
  <body>
    <div id="JiSlider" class="JiSlider">
      <ul>
        <li>
          <img src="img1.jpg">
        </li>
        <li>
          <img src="img2.jpg">
        </li>
        <li>
          <img src="img3.jpg">
        </li>
      </ul>
    </div>
    <script src="/path/to/jquery.min.js"></script>
    <script src="/path/to/JiSlider.js"></script>
    <script>
      $(window).load(function () {
        $('#JiSlider').JiSlider();
      });
    </script>
  </body>
</html>
```

Custom Settings
---------------

Passing a associative array in JiSlider method you can change JiSlider the way you like!  
You can modify:
  + auto
    + This value represents whether the animation will be automatic or not.
    + Default value: **true**
    + Boolean
  + start
    + This value represents start slide.
    + Default value: **1**
    + Number
  + time
    + This value represents animation time.
    + Default value: **600**
    + Number in milliseconds
  + stay
    + This value represents stay time in between animations.
    + Default value: **3000**
    + Number in millisecons
  + controller
    + This value represents where the controller will appear or not
    + Default value: **true**
    + Boolean
  + color
    + This value represents color of controller.
    + Default value: **#fff**
    + hexcode value
  + easing
    + This value represents easing of animation.
    + Default value: **ease**
    + CSS Transition easing property
  + reverse
    + This value represents whether animation direction will be reversed or not
    + Default value: **false**
    + Boolean

Sample Usage
------------

```javascript
$('#JiSlider').JiSlider({
  color: '#fff',
  start: 3,
  reverse: true,
});
```
