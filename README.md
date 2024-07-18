## threejs-toy-demo
Three JS demo using PLYLoader, Raycaster and OrbitControls

* Object is loaded from models using PLYLoader and added to the scene
* Mouse object-select is animated and enabled using Raycaster
  * Object-mouse intersection is determine using Raycaster
  * New object position is determined using mouse-pointer position
  * OrbitControls is enabled for the perspective camera and added to the renderer DOM tree

### Required THREE packages (to be added to the HTML)

```
    <script src="js/three.js"></script>
    <script src="js/OrbitControls.js"> </script>
    <script src="js/PLYLoader.js"></script>
```

