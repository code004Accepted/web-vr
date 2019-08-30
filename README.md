# Web VR

This is a copy of a complete web-VR web page.

Learn more at https://aframe.io/.

Try it at https://code004accepted.github.io/web-vr.

Source Code:

```html

<html>
  <head>
    <script src="https://aframe.io/releases/0.8.0/aframe.min.js"></script>
    <script src="https://npmcdn.com/aframe-animation-component@3.0.1"></script>
    <script src="https://npmcdn.com/aframe-event-set-component@3.0.1"></script>
    <title>VR test</title>
  </head>
  <body>
    <center><font color="red" size="8">VR-test&nbsp;is&nbsp;loading...</font></center>
    <a-scene>

      <a-text value="Welcome to VR test!" color="#FFC65D"
         position="-2 1 -3" scale="3 3 3"></a-text>

      <a-text value="Example Text" color="#FFFFFF"
         position="-62.5 50 -150" scale="100 100 100"></a-text>

      <a-box position="5 3.25 -3" rotation="0 45 0" color="#4CC3D9">
        <a-animation attribute="rotation" from="0 45 0" to="0 360 0" repeat="indefinite" direction="alternate"></a-animation>
      </a-box>
      <a-box position="5 3.25 -4" rotation="0 45 0" color="#4CC3D9">
        <a-animation attribute="rotation" from="0 45 0" to="0 360 0" repeat="indefinite" direction="alternate"></a-animation>
      </a-box>
      <a-box position="5 3.25 -5" rotation="0 45 0" color="#4CC3D9">
        <a-animation attribute="rotation" from="0 45 0" to="0 360 0" repeat="indefinite" direction="alternate"></a-animation>
      </a-box>
      <a-box position="5 3.25 -6" rotation="0 45 0" color="#4CC3D9">
        <a-animation attribute="rotation" from="0 45 0" to="0 360 0" repeat="indefinite" direction="alternate"></a-animation>
      </a-box>
      <a-box position="5 3.25 -7" rotation="0 45 0" color="#4CC3D9">
        <a-animation attribute="rotation" from="0 45 0" to="0 360 0" repeat="indefinite" direction="alternate"></a-animation>
      </a-box>
      <a-box position="4 3.25 -3" rotation="0 45 0" color="#4CC3D9">
        <a-animation attribute="rotation" from="0 45 0" to="0 360 0" repeat="indefinite" direction="alternate"></a-animation>
      </a-box>
      <a-box position="4 3.25 -4" rotation="0 45 0" color="#4CC3D9">
        <a-animation attribute="rotation" from="0 45 0" to="0 360 0" repeat="indefinite" direction="alternate"></a-animation>
      </a-box>
      <a-box position="4 3.25 -5" rotation="0 45 0" color="#4CC3D9">
        <a-animation attribute="rotation" from="0 45 0" to="0 360 0" repeat="indefinite" direction="alternate"></a-animation>
      </a-box>
      <a-box position="4 3.25 -6" rotation="0 45 0" color="#4CC3D9">
        <a-animation attribute="rotation" from="0 45 0" to="0 360 0" repeat="indefinite" direction="alternate"></a-animation>
      </a-box>
      <a-box position="4 3.25 -7" rotation="0 45 0" color="#4CC3D9">
        <a-animation attribute="rotation" from="0 45 0" to="0 360 0" repeat="indefinite" direction="alternate"></a-animation>
      </a-box>
      <a-box position="3 3.25 -3" rotation="0 45 0" color="#4CC3D9">
        <a-animation attribute="rotation" from="0 45 0" to="0 360 0" repeat="indefinite" direction="alternate"></a-animation>
      </a-box>
      <a-box position="3 3.25 -4" rotation="0 45 0" color="#4CC3D9">
        <a-animation attribute="rotation" from="0 45 0" to="0 360 0" repeat="indefinite" direction="alternate"></a-animation>
      </a-box>
      <a-box position="3 3.25 -5" rotation="0 45 0" color="#4CC3D9">
        <a-animation attribute="rotation" from="0 45 0" to="0 360 0" repeat="indefinite" direction="alternate"></a-animation>
      </a-box>
      <a-box position="3 3.25 -6" rotation="0 45 0" color="#4CC3D9">
        <a-animation attribute="rotation" from="0 45 0" to="0 360 0" repeat="indefinite" direction="alternate"></a-animation>
      </a-box>
      <a-box position="3 3.25 -7" rotation="0 45 0" color="#4CC3D9">
        <a-animation attribute="rotation" from="0 45 0" to="0 360 0" repeat="indefinite" direction="alternate"></a-animation>
      </a-box>
      <a-box position="2 3.25 -3" rotation="0 45 0" color="#4CC3D9">
        <a-animation attribute="rotation" from="0 45 0" to="0 360 0" repeat="indefinite" direction="alternate"></a-animation>
      </a-box>
      <a-box position="2 3.25 -4" rotation="0 45 0" color="#4CC3D9">
        <a-animation attribute="rotation" from="0 45 0" to="0 360 0" repeat="indefinite" direction="alternate"></a-animation>
      </a-box>
      <a-box position="2 3.25 -5" rotation="0 45 0" color="#4CC3D9">
        <a-animation attribute="rotation" from="0 45 0" to="0 360 0" repeat="indefinite" direction="alternate"></a-animation>
      </a-box>
      <a-box position="2 3.25 -6" rotation="0 45 0" color="#4CC3D9">
        <a-animation attribute="rotation" from="0 45 0" to="0 360 0" repeat="indefinite" direction="alternate"></a-animation>
      </a-box>
      <a-box position="2 3.25 -7" rotation="0 45 0" color="#4CC3D9">
        <a-animation attribute="rotation" from="0 45 0" to="0 360 0" repeat="indefinite" direction="alternate"></a-animation>
      </a-box>
      <a-box position="1 3.25 -3" rotation="0 45 0" color="#4CC3D9">
        <a-animation attribute="rotation" from="0 45 0" to="0 360 0" repeat="indefinite" direction="alternate"></a-animation>
      </a-box>
      <a-box position="1 3.25 -4" rotation="0 45 0" color="#4CC3D9">
        <a-animation attribute="rotation" from="0 45 0" to="0 360 0" repeat="indefinite" direction="alternate"></a-animation>
      </a-box>
      <a-box position="1 3.25 -5" rotation="0 45 0" color="#4CC3D9">
        <a-animation attribute="rotation" from="0 45 0" to="0 360 0" repeat="indefinite" direction="alternate"></a-animation>
      </a-box>
      <a-box position="1 3.25 -6" rotation="0 45 0" color="#4CC3D9">
        <a-animation attribute="rotation" from="0 45 0" to="0 360 0" repeat="indefinite" direction="alternate"></a-animation>
      </a-box>
      <a-box position="1 3.25 -7" rotation="0 45 0" color="#4CC3D9">
        <a-animation attribute="rotation" from="0 45 0" to="0 360 0" repeat="indefinite" direction="alternate"></a-animation>
      </a-box>
      <a-box position="0 3.25 -3" rotation="0 45 0" color="#4CC3D9">
        <a-animation attribute="rotation" from="0 45 0" to="0 360 0" repeat="indefinite" direction="alternate"></a-animation>
      </a-box>
      <a-box position="0 3.25 -4" rotation="0 45 0" color="#4CC3D9">
        <a-animation attribute="rotation" from="0 45 0" to="0 360 0" repeat="indefinite" direction="alternate"></a-animation>
      </a-box>
      <a-box position="0 3.25 -5" rotation="0 45 0" color="#4CC3D9">
        <a-animation attribute="rotation" from="0 45 0" to="0 360 0" repeat="indefinite" direction="alternate"></a-animation>
      </a-box>
      <a-box position="0 3.25 -6" rotation="0 45 0" color="#4CC3D9">
        <a-animation attribute="rotation" from="0 45 0" to="0 360 0" repeat="indefinite" direction="alternate"></a-animation>
      </a-box>
      <a-box position="0 3.25 -7" rotation="0 45 0" color="#4CC3D9">
        <a-animation attribute="rotation" from="0 45 0" to="0 360 0" repeat="indefinite" direction="alternate"></a-animation>
      </a-box>
      <a-box position="-1 3.25 -3" rotation="0 45 0" color="#4CC3D9">
        <a-animation attribute="rotation" from="0 45 0" to="0 360 0" repeat="indefinite" direction="alternate"></a-animation>
      </a-box>
      <a-box position="-1 3.25 -4" rotation="0 45 0" color="#4CC3D9">
        <a-animation attribute="rotation" from="0 45 0" to="0 360 0" repeat="indefinite" direction="alternate"></a-animation>
      </a-box>
      <a-box position="-1 3.25 -5" rotation="0 45 0" color="#4CC3D9">
        <a-animation attribute="rotation" from="0 45 0" to="0 360 0" repeat="indefinite" direction="alternate"></a-animation>
      </a-box>
      <a-box position="-1 3.25 -6" rotation="0 45 0" color="#4CC3D9">
        <a-animation attribute="rotation" from="0 45 0" to="0 360 0" repeat="indefinite" direction="alternate"></a-animation>
      </a-box>
      <a-box position="-1 3.25 -7" rotation="0 45 0" color="#4CC3D9">
        <a-animation attribute="rotation" from="0 45 0" to="0 360 0" repeat="indefinite" direction="alternate"></a-animation>
      </a-box>
      <a-box position="-2 3.25 -3" rotation="0 45 0" color="#4CC3D9">
        <a-animation attribute="rotation" from="0 45 0" to="0 360 0" repeat="indefinite" direction="alternate"></a-animation>
      </a-box>
      <a-box position="-2 3.25 -4" rotation="0 45 0" color="#4CC3D9">
        <a-animation attribute="rotation" from="0 45 0" to="0 360 0" repeat="indefinite" direction="alternate"></a-animation>
      </a-box>
      <a-box position="-2 3.25 -5" rotation="0 45 0" color="#4CC3D9">
        <a-animation attribute="rotation" from="0 45 0" to="0 360 0" repeat="indefinite" direction="alternate"></a-animation>
      </a-box>
      <a-box position="-2 3.25 -6" rotation="0 45 0" color="#4CC3D9">
        <a-animation attribute="rotation" from="0 45 0" to="0 360 0" repeat="indefinite" direction="alternate"></a-animation>
      </a-box>
      <a-box position="-2 3.25 -7" rotation="0 45 0" color="#4CC3D9">
        <a-animation attribute="rotation" from="0 45 0" to="0 360 0" repeat="indefinite" direction="alternate"></a-animation>
      </a-box>
      <a-box position="-3 3.25 -3" rotation="0 45 0" color="#4CC3D9">
        <a-animation attribute="rotation" from="0 45 0" to="0 360 0" repeat="indefinite" direction="alternate"></a-animation>
      </a-box>
      <a-box position="-3 3.25 -4" rotation="0 45 0" color="#4CC3D9">
        <a-animation attribute="rotation" from="0 45 0" to="0 360 0" repeat="indefinite" direction="alternate"></a-animation>
      </a-box>
      <a-box position="-3 3.25 -5" rotation="0 45 0" color="#4CC3D9">
        <a-animation attribute="rotation" from="0 45 0" to="0 360 0" repeat="indefinite" direction="alternate"></a-animation>
      </a-box>
      <a-box position="-3 3.25 -6" rotation="0 45 0" color="#4CC3D9">
        <a-animation attribute="rotation" from="0 45 0" to="0 360 0" repeat="indefinite" direction="alternate"></a-animation>
      </a-box>
      <a-box position="-3 3.25 -7" rotation="0 45 0" color="#4CC3D9">
        <a-animation attribute="rotation" from="0 45 0" to="0 360 0" repeat="indefinite" direction="alternate"></a-animation>
      </a-box>

      <a-sphere position="-1 15 100" rotation="0 220 0" radius="30" src="./caidan-yellow.jpg"></a-sphere>
      <a-sphere position="1 200 -300" radius="150" src="./very-big-ball.jpg"></a-sphere>
      <a-sphere position="-1 1.25 -5" radius="1.25" src="./welcome-purple.jpg"></a-sphere>
      <a-sphere position="1 1.25 -5" radius="1.25" src="./welcome-blue(with yellow words).jpg"></a-sphere>
      <a-sphere position="3 1.25 -5" radius="1.25" src="./welcome-purple.jpg"></a-sphere>

      <a-cylinder position="1 1 -3" radius="0.5" height="3.5" color="#FFC65D">
        <a-animation attribute="height" from="3.5" to="0" repeat="indefinite" direction="alternate"></a-animation>
      </a-cylinder>
      <a-cylinder position="2 1 -3" radius="0.5" height="3.5" color="#FFC65D">
        <a-animation attribute="height" from="3.5" to="0" repeat="indefinite" direction="alternate"></a-animation>
      </a-cylinder>
      <a-cylinder position="3 1 -3" radius="0.5" height="3.5" color="#FFC65D">
        <a-animation attribute="height" from="3.5" to="0" repeat="indefinite" direction="alternate"></a-animation>
      </a-cylinder>
      <a-cylinder position="4 1 -3" radius="0.5" height="3.5" color="#FFC65D">
        <a-animation attribute="height" from="3.5" to="0" repeat="indefinite" direction="alternate"></a-animation>
      </a-cylinder>
      <a-cylinder position="5 1 -3" radius="0.5" height="3.5" color="#FFC65D">
        <a-animation attribute="height" from="3.5" to="0" repeat="indefinite" direction="alternate"></a-animation>
      </a-cylinder>
      <a-cylinder position="5 1 -4" radius="0.5" height="3.5" color="#FFC65D">
        <a-animation attribute="height" from="3.5" to="0" repeat="indefinite" direction="alternate"></a-animation>
      </a-cylinder>
      <a-cylinder position="5 1 -5" radius="0.5" height="3.5" color="#FFC65D">
        <a-animation attribute="height" from="3.5" to="0" repeat="indefinite" direction="alternate"></a-animation>
      </a-cylinder>
      <a-cylinder position="5 1 -6" radius="0.5" height="3.5" color="#FFC65D">
        <a-animation attribute="height" from="3.5" to="0" repeat="indefinite" direction="alternate"></a-animation>
      </a-cylinder>
      <a-cylinder position="5 1 -7" radius="0.5" height="3.5" color="#FFC65D">
        <a-animation attribute="height" from="3.5" to="0" repeat="indefinite" direction="alternate"></a-animation>
      </a-cylinder>
      <a-cylinder position="4 1 -7" radius="0.5" height="3.5" color="#FFC65D">
        <a-animation attribute="height" from="3.5" to="0" repeat="indefinite" direction="alternate"></a-animation>
      </a-cylinder>
      <a-cylinder position="3 1 -7" radius="0.5" height="3.5" color="#FFC65D">
        <a-animation attribute="height" from="3.5" to="0" repeat="indefinite" direction="alternate"></a-animation>
      </a-cylinder>
      <a-cylinder position="2 1 -7" radius="0.5" height="3.5" color="#FFC65D">
        <a-animation attribute="height" from="3.5" to="0" repeat="indefinite" direction="alternate"></a-animation>
      </a-cylinder>
      <a-cylinder position="1 1 -7" radius="0.5" height="3.5" color="#FFC65D">
        <a-animation attribute="height" from="3.5" to="0" repeat="indefinite" direction="alternate"></a-animation>
      </a-cylinder>
      <a-cylinder position="0 1 -7" radius="0.5" height="3.5" color="#FFC65D">
        <a-animation attribute="height" from="3.5" to="0" repeat="indefinite" direction="alternate"></a-animation>
      </a-cylinder>
      <a-cylinder position="-1 1 -7" radius="0.5" height="3.5" color="#FFC65D">
        <a-animation attribute="height" from="3.5" to="0" repeat="indefinite" direction="alternate"></a-animation>
      </a-cylinder>
      <a-cylinder position="-2 1 -7" radius="0.5" height="3.5" color="#FFC65D">
        <a-animation attribute="height" from="3.5" to="0" repeat="indefinite" direction="alternate"></a-animation>
      </a-cylinder>
      <a-cylinder position="-3 1 -7" radius="0.5" height="3.5" color="#FFC65D">
        <a-animation attribute="height" from="3.5" to="0" repeat="indefinite" direction="alternate"></a-animation>
      </a-cylinder>
      <a-cylinder position="-3 1 -6" radius="0.5" height="3.5" color="#FFC65D">
        <a-animation attribute="height" from="3.5" to="0" repeat="indefinite" direction="alternate"></a-animation>
      </a-cylinder>
      <a-cylinder position="-3 1 -5" radius="0.5" height="3.5" color="#FFC65D">
        <a-animation attribute="height" from="3.5" to="0" repeat="indefinite" direction="alternate"></a-animation>
      </a-cylinder>
      <a-cylinder position="-3 1 -4" radius="0.5" height="3.5" color="#FFC65D">
        <a-animation attribute="height" from="3.5" to="0" repeat="indefinite" direction="alternate"></a-animation>
      </a-cylinder>
      <a-cylinder position="-3 1 -3" radius="0.5" height="3.5" color="#FFC65D">
        <a-animation attribute="height" from="3.5" to="0" repeat="indefinite" direction="alternate"></a-animation>
      </a-cylinder>
      <a-cylinder position="-2 1 -3" radius="0.5" height="3.5" color="#FFC65D">
        <a-animation attribute="height" from="3.5" to="0" repeat="indefinite" direction="alternate"></a-animation>
      </a-cylinder>
      <a-cylinder position="-1 1 -3" radius="0.5" height="3.5" color="#FFC65D">
        <a-animation attribute="height" from="3.5" to="0" repeat="indefinite" direction="alternate"></a-animation>
      </a-cylinder>
      <a-cylinder position="0 1 -3" radius="0.5" height="3.5" color="#FFC65D">
        <a-animation attribute="height" from="3.5" to="0" repeat="indefinite" direction="alternate"></a-animation>
      </a-cylinder>


      <a-plane position="0 0 -4" rotation="-90 0 0" width="1000" height="1000" color="#00EC00"></a-plane>
      <a-sky src="./welcome-blue(with yellow words).jpg"></a-sky>
      <a-light
        type="directional"
        color="#FFF"
        intensity="0.5"
        position="1 1 1">
      </a-light>
      <a-light
        type="ambient"
        color="#FFF">
      </a-light>
    </a-scene>
  </body>
</html>
```
