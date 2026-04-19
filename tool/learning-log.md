# Tool Learning Log

## Tool: **A-frame**

---

### 03/20/26:
**Me tinkering with the given code:**
```HTML
   <a-scene>
      <a-box position="0 -2 -3" rotation="0 45 0" color="orange"></a-box>
      <a-box position="0 2.5 -4" rotation="0 90 0" color="pink"></a-box>
      <a-sphere position="0 1 -5" radius="1.5" color="white"></a-sphere>
      <a-sphere position="-1 1 -4" radius=".7" color="purple"></a-sphere>
      <a-sphere position="1 1.3 -3" radius=".4" color="lightblue"></a-cylinder>
      <a-plane position="0 0 -4" rotation="-90 0 0" width="5" height="4" color="gray"></a-plane>
      <a-sky color="black"></a-sky>
    </a-scene>
```
<img width="1365" height="767" alt="Screenshot 2026-03-23 9 18 46 AM" src="https://github.com/user-attachments/assets/f0d2c225-1442-4732-918b-9b830650c371" />

### 3/23/26:
I have been learning how to create shapes, understand the basics, the positions, trying to figure out how to use the **VR feature**. The positions are confusing but still getting the uses of how it positions. 
```HTML
<a-scene>
  <a-assets>
    <audio id="click-sound" src="https://cdn.aframe.io/360-image-gallery-boilerplate/audio/click.ogg"></audio>

    <!-- Images. -->
    <img id="city" src="https://cdn.aframe.io/360-image-gallery-boilerplate/img/city.jpg">
    <img id="city-thumb" src="https://cdn.aframe.io/360-image-gallery-boilerplate/img/thumb-city.jpg">
    <img id="cubes" src="https://cdn.aframe.io/360-image-gallery-boilerplate/img/cubes.jpg">
    <img id="cubes-thumb" src="https://cdn.aframe.io/360-image-gallery-boilerplate/img/thumb-cubes.jpg">
    <img id="sechelt" src="https://cdn.aframe.io/360-image-gallery-boilerplate/img/sechelt.jpg">
    <img id="sechelt-thumb" src="https://cdn.aframe.io/360-image-gallery-boilerplate/img/thumb-sechelt.jpg">
  </a-assets>

  <!-- 360-degree image. -->
  <a-sky id="image-360" radius="10" src="#city"></a-sky>

  <!-- Link template we will build. -->
  <a-entity class="link"></a-entity>

  <!-- Camera + Cursor. -->
  <a-camera>
    <a-cursor
      id="cursor"
      animation__click="property: scale; from: 0.1 0.1 0.1; to: 1 1 1; easing: easeInCubic; dur: 150; startEvents: click"
      animation__clickreset="property: scale; to: 0.1 0.1 0.1; dur: 1; startEvents: animationcomplete__click"
      animation__fusing="property: scale; from: 1 1 1; to: 0.1 0.1 0.1; easing: easeInCubic; dur: 150; startEvents: fusing"></a-cursor>
  </a-camera>
</a-scene>
```
# 4/15/26 --> Timeline
# Wednesday
* Viewing the options of an entity, Aframe has many, so viewing ans seeing the structure will help understand the concept better. By doing this i will tinker with each entity to see what each one does.
```HTML
<html>
  <head>
    <script src="https://aframe.io/releases/1.7.1/aframe.min.js"></script>
  </head>
  <body>
    <a-scene>
      <a-sky color="#a8dadc"></a-sky>
      <a-plane position="0 0 -5" rotation="-90 0 0" width="10" height="10" color="#6a994e"></a-plane>
      <a-box position="0 1 -5" width="2" height="2" depth="2" color="#ffe6a7"></a-box>
      <a-cone position="0 2.5 -5" radius-bottom="1.5" height="1" color="#8B0000"></a-cone>
      <a-box position="0 0.5 -3.9" width="0.5" height="1" depth="0.1" color="#5e503f"></a-box>
      <a-box position="-0.7 1.2 -3.9" width="0.4" height="0.4" depth="0.1" color="#a8dadc"></a-box>
    </a-scene>
  </body>
</html>
```
<img width="1366" height="768" alt="Screenshot 2026-04-18 11 44 31 PM" src="https://github.com/user-attachments/assets/8e5fcade-4b3a-479a-9c9a-bab3a85e3c41" />

# Thursday
* Have a better understanding of the positioning with the coordinate. Understanding the relevance of x,y,z. By doing this, I will tinker with pre-made code to see how (x,y,z) works.
```HTML
<html>
  <head>
    <script src="https://aframe.io/releases/1.7.1/aframe.min.js"></script>
  </head>
  <body>
    <a-scene>
      <a-box position="0 1 -3" rotation="0 45 0" color="lightblue"></a-box>
      <a-sphere position="-2 1 -3" radius="1.25" color="pink"></a-sphere>
      <a-cylinder position="2 1 -3" radius="0.5" height="1.5" color="lightgray"></a-cylinder>
      <a-box position="0 3 -3" rotation="0 45 0" color="lightyellow"></a-box>
      <a-sphere position="0 1 -6" radius="1.25" color="purple"></a-sphere>
      <a-sky color="#ECECEC"></a-sky>
    </a-scene>
  </body>
</html>
```

# Friday
* How to add background and a scenery. With Aframe, it allows texture, material applied, 360 video. By doing this I will look at videos and guides to help create a background. 
```HTML
<html>
  <head>
    <script src="https://aframe.io/releases/1.7.1/aframe.min.js"></script>
  </head>
  <body>
    <a-scene>
      <a-box position="0 1 -2" color="lightgray" metalness="0.5" roughness="0.5"></a-box>
      <a-plane position="0 0 -5" rotation="-90 0 0" width="15" height="15" color="lightblue"></a-plne>
      <a-sky color="#ECECEC"></a-sky>
    </a-scene>
  </body>
</html>
```
<!-- 
* Links you used today (websites, videos, etc)
* Things you tried, progress you made, etc
* Challenges, a-ha moments, etc
* Questions you still have
* What you're going to try next
-->
