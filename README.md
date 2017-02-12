# overlay.js
My own JS library for an alternative alert.

## Usage
**Step 1:** Add this to your HTML file:
```HTML
<script type="text/javascript" src="https://rawgit.com/Greenscreener/overlay.js/master/overlay.js"> </script>
```
**Step 2:** Use the `Overlay` class to create an overlay:
```javascript
var someVariable = new Overlay("image url", miliseconds, "text");
```
(you can also do that using Chrome DevTools Console.)

The overlays are timed by the miliseconds parameter, but you can remove them earlier by typing o1.remove() in the DevTools console (or in your JS program.) 
## Examples
```javascript
o1 = new Overlay("https://raw.githubusercontent.com/Greenscreener/overlay.js/master/yes.png",3000,"<h2> Everything's good </h2>  Nice!")
```
```javascript
o1 = new Overlay("https://raw.githubusercontent.com/Greenscreener/overlay.js/master/no.png",3000,"<h2> You messed up </h2> This is just an example (everything's good.)")
```
(o1 is the name of the variable the overlay's data is stored in => you can change it to anything you want.)
