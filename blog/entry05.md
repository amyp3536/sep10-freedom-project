# Entry 5
##### 04/20/26

### Content
For my freedom project, we had the opportunity to incorporate a tool in our website. I have choosen the tool A-frame. A-frame is a web framework that is able to create 3D and virtual reality scenes just with the use of HTML. I choose this tool because I thought it would be intresting to have something interactive and visual for my project. When I began tinkering with A-frame I began looking at the website to understand the basics and tried it on my own. So far I have learned the positioning, Viewing the options of an entity,adding background, scenery, and material.
# Tinker 1
Viewing the options of entitys, Aframe has many, so viewing and seeing the structure will help understand the concept better. By doing this I will tinker with each entity to see what each one does. I tinkerred with given code. 
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

# Tinker 2 
Have a better understanding of the positioning with the coordinate. Understanding the relevance of x,y,z. By doing this, I will tinker with pre-made code to see how (x,y,z) works. 
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
<img width="1366" height="768" alt="Screenshot 2026-04-19 12 57 44 AM" src="https://github.com/user-attachments/assets/8e183439-5b91-43df-8d57-61f3f98ae4d9" />
# Tinker 3
Adding background and a scenery. With Aframe, it allows texture, material applied, 360 video. By doing this I will look at videos and guides to help create a background. Creating this with given code.

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
<img width="1366" height="768" alt="Screenshot 2026-04-19 12 26 05 AM" src="https://github.com/user-attachments/assets/73ed2e3c-26e7-42ce-8018-2922d887dc70" />

# Skills
* Learned the posioning in Aframe
* Continued expanding my knowlege of entitys
* Adding texture to shapes
* 
[Previous](entry04.md) | [Next](entry06.md)

[Home](../README.md)
