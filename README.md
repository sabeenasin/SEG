# SEG
spring 2025
<!DOCTYPE html>
<html>
  <head>
    <script src="https://aframe.io/releases/1.4.0/aframe.min.js"></script>
    <title>Basic A-Frame Scene</title>
  </head>
  <body>
    <a-scene>
      <!-- Add a sky -->
      <a-sky color="#ECECEC"></a-sky>

      <!-- Add a ground -->
      <a-plane position="0 0 -4" rotation="-90 0 0" width="10" height="10" color="green"></a-plane>

      <!-- Add a box -->
      <a-box position="0 1 -3" rotation="0 45 0" color="blue"></a-box>

      <!-- Add a sphere -->
      <a-sphere position="2 1 -4" radius="1" color="red"></a-sphere>

      <!-- Add a camera -->
      <a-entity position="0 1.6 0">
        <a-camera></a-camera>
      </a-entity>
    </a-scene>
  </body>
</html>
