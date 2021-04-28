# SVG SoundCloud Vinyl Player

A Pen created on CodePen.io. Original URL: [https://codepen.io/chrisgannon/pen/VvEWQE](https://codepen.io/chrisgannon/pen/VvEWQE).

You can find an updated version [here](http://codepen.io/chrisgannon/pen/GpwqgG) with search.

***

This is tapping into the SoundCloud API and is playing a track by Arthur called [Wind Therapy](https://soundcloud.com/arthur/wind-therapy).

It's in its early stages so far but it's a fun way to interact with audio tracks. 

Currently, because of the way the API works, you have to drop the needle at the start of the record first - after that you can drop it anywhere, just like vinyl (due to the way the seek(); is working).

Things to note: iOS insists on a user interaction before it will play audio and I haven't quite sussed out why what I'm doing isn't working.

Also FireFox is having general issues with transform origins, textPath and CSS letter spacing *sigh*
