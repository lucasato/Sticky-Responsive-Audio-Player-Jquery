# Sticky & Inline Responsive HTML5 Audio Player with jQuery


![demo](https://user-images.githubusercontent.com/8246622/29740949-0829b9f2-8a63-11e7-90d0-c5f9be724d11.png)
![demo2](https://user-images.githubusercontent.com/8246622/29741176-87d86c9e-8a67-11e7-8dab-6c0352c78c3c.png)

## Prerequisites

jQuery 1.3+
## Demo

[LIVE DEMO](http://www.tiendasdigitales.net/github/stickyaudioplayerjquery/)

## Quick start

Include CSS And JS Files

1. Include Files:
```html
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script>
<link rel="stylesheet" href="css/stickyaudioplayerjquery.min.css">
<script src="js/stickyaudioplayerjquery.min.js"></script>
```

2. Scope

```js
 var player; // declare it outside to use methods after
 $(document).ready(function()
  {
  player = $.stickyAudioPlayer(
    {
      url:'http://tiendasdigitales.net/github/stickyaudioplayerjquery/bensound-goinghigher.mp3',
      position:'bottom',
      text:'Bensound - Going Higher - Music: http://www.bensound.com',
      image:'http://tiendasdigitales.net/github/stickyaudioplayerjquery/images/cover.png',
      maxWidth:1000
     }
   );
 });
```
**METHODS**
```html
player.changeAudio('myfile.mp3','song text','mycover.png'); Replace current song
player.setVolume(100);	Change Player volume from 0 to 100
player.mute();	Mute audio
player.unmute();	Unmute Audio
player.pause();	
player.stop();	
player.play();	
player.show();	Open Sticky Player (not valid for inline position)
player.hide();	Hide Sticky Player (not valid for inline position)
player.remove();	Remove audio player from the DOM
```

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.

## Authors

* **Lucas G. Martinez** - *Initial work* - [Lucasato](https://github.com/lucasato)

See also the list of [contributors](https://github.com/lucasato/Sticky-Responsive-Audio-Player-Jquery/graphs/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
