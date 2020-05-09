# The Adventure Of The Onion

## To-Do List
- [x] Blender
- [x] Shader
- [ ] Animation
- [ ] Storyboard

## PoC
* Light and Shadow
* Mirror
* Hand
  * Hold the onion
  * Lift the onion
  * Pinch the onion
  * Catch the onion
* Onion - Rebellious and hiccups happen when he loses one leg...
  * Swim
  * Walk
  * Run
  * Dive
  * Climb
* Chameleon - Color
* Motion
  * Rotoscoping - https://www.youtube.com/watch?v=-KoSolkp5Ds
  * Motion capture
  * Keyframe animation

<p float="left">
	<img src="./storyboard/images/storyboard_1.jpeg" width=450 />
	<img src="./storyboard/images/storyboard_2.jpeg" width=450 />
</p>

## Resources
* https://www.blendswap.com/
* https://3drt.com/store/
* https://www.turbosquid.com/3d-model/alien
* https://sketchfab.com/
* https://3dwarehouse.sketchup.com/
* https://www.renderosity.com/
* https://alteredqualia.com/

## Tools
* http://www.akjava.com/demo/bvhplayer/
* https://alteredqualia.com/three/examples/webgl_road.html
* https://filterforge.com/
* https://www.verold.com/
* https://www.sketchup.com/
* https://www.posersoftware.com/
* https://www.autodesk.com/products/motionbuilder/overview
* https://github.com/stephomi/sculptgl
* https://www.shadertoy.com/

## References

### 3D file formats
* **Model formats**
	* **Wavefront OBJ** - https://en.wikipedia.org/wiki/Wavefront_.obj_file
    	* Oldest and best-supported single-model formats
    * **STL** text-based 3D printing file format - https://en.wikipedia.org/wiki/STL_%28file_format%29
    	* Used by 3D systems for rapid prototyping, manufacturing and 3D printing
		* Files can potentially be sent directly to 3D printing hardware
* **Animation formats**
    * **id Software MD2** and **MD5** character animation formats 
    	* **MD2** - http://tfc.duke.free.fr/coding/md2-specs-en.html
	  		* It supports vertex-based character animation only via morph targets
	  		* It can be converted to JSON
	  	* **MD5** - http://tfc.duke.free.fr/coding/md5-specs-en.html
	  		* It supports skinned animation and a text-based, human-readable format
	  		* It can be converted to JSON
	* **BioVision BVH** animation format for motion capture - https://research.cs.wisc.edu/graphics/Courses/cs-838-1999/Jeff/BVH.html
* **Full-featured scene formats**
	* **VRML** and **X3D** the original text-based standard for 3D on the web - https://www.web3d.org/standards
	* **COLLADA** digital asset exchange format - https://www.khronos.org/files/collada_spec_1_4.pdf
		* https://www.khronos.org/collada/wiki/OpenCOLLADA
		* It is represented in XML
	* **glTF** a new format for WebGL, OpenGL ES and OpenGL applications
		* JPEG for 3D
		* It uses JSON files to describe scene graph structure and high-level information, e.g., cameras and lights
		* It uses binary files to describe rich data, e.g., vetices, normals, colors and animation, which can be loaded directly into WebGL buffers
	* **Autodesk FBX** - https://www.autodesk.com/products/fbx/overview
		* It provides SDKs to read and write FBX in C++ and Python

### Related technologies
* **Pointer Lock API**
	* https://www.html5rocks.com/en/tutorials/pointerlock/intro/
	* https://www.w3.org/TR/pointerlock/
* **Page Visibility API**
	* https://www.w3.org/TR/page-visibility/
* **WebSocket**
	* https://code.tutsplus.com/tutorials/start-using-html5-websockets-today--net-13270
	* https://www.websocket.org/
* **WebRTC**
	* https://www.html5rocks.com/en/tutorials/webrtc/basics/
	* https://webrtc.org/
	* https://www.w3.org/TR/webrtc/
* **Web Workers**
	* https://www.w3.org/TR/workers/
	* https://developers.google.com/web/updates/2011/12/Transferable-Objects-Lightning-Fast
* **IndexedDB** and **Filesystem API**
	* https://www.w3.org/TR/IndexedDB/
	* https://www.w3.org/TR/file-system-api/
	* https://www.html5rocks.com/en/tutorials/file/filesystem/