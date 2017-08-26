# Skin-video-js-5.20.3
New skin-video-js-5.20.3

<img src="https://raw.githubusercontent.com/maluklo/Skin-video-js-5.20.3/master/video-js-5.20.3.png">
### Quick Start

```html
<link href="video-js-5.20.3/video-js.css" rel="stylesheet">
<script src="video-js-5.20.3/video.js"></script>

<video id="player" 
class="video-js" 
controls preload="none" 
width="960" 
height="400" 
poster="video-js-5.20.3/oceans.png" 
data-setup="{}">
<source src="http://vjs.zencdn.net/v/oceans.mp4" type="video/mp4">
<source src="http://vjs.zencdn.net/v/oceans.webm" type="video/webm">
<source src="http://vjs.zencdn.net/v/oceans.ogv" type="video/ogg">
</video>
```
### Or

```html
<link href="video-js-5.20.3/video-js.css" rel="stylesheet">
<script src="video-js-5.20.3/video.js"></script>

<video id="player" class="video-js"></video>
<script>
var Player = videojs("player", { 
"controls": true, 
"autoplay": false, 
"preload": "auto" ,
"poster": "video-js-5.20.3/oceans.png",
"width": 960,
"height": 400,
sources: [
{ src: 'https://vjs.zencdn.net/v/oceans.mp4', type: 'video/mp4'},
{ src: 'https://vjs.zencdn.net/v/oceans.webm', type: 'video/webm'},
{ src: 'https://vjs.zencdn.net/v/oceans.ogv', type: 'video/ogg'}
],
});
</script>
```
