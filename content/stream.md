+++
title = "Stream"
menu = "main"
weight = 100
+++

<link href="https://vjs.zencdn.net/7.21.5/video-js.css" rel="stylesheet" />
<script src="https://vjs.zencdn.net/7.21.5/video.min.js"></script>

<video
  id="hls-example"
  class="video-js vjs-default-skin vjs-big-play-centered"
  controls
  autoplay
  muted
  width="100%"
  height="480">
  <source src="https://stream.landonbjackson.dev/outside-cam/stream.m3u8" type="application/x-mpegURL" />
</video>

<script>
  var player = videojs('hls-example', {
    autoplay: true,
    muted: true,
    liveui: true
  });
  player.play();
</script>


# Currently Building:

![BearBrick](../images/case.png)
