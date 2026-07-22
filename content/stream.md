+++
title = "Stream"
menu = "main"
weight = 100
+++

<link href="https://vjs.zencdn.net/7.21.5/video-js.css" rel="stylesheet" />
<script src="https://vjs.zencdn.net/7.21.5/video.min.js"></script>

<style>
  .video-container {
    width: 100%;
    max-width: 960px;
  }
</style>

<div class="video-container">
  <video
    id="hls-example"
    class="video-js vjs-default-skin vjs-big-play-centered vjs-16-9"
    controls
    autoplay
    muted
    preload="auto">
    <source src="https://stream.landonbjackson.dev/printer-cam/stream.m3u8" type="application/x-mpegURL" />
  </video>
</div>

<script>
  var player = videojs('hls-example', {
    autoplay: true,
    muted: true,
    liveui: true,
    fluid: true
  });
  player.play();
</script>

# Currently Building:

<!-- ![BearBrick](../images/wisblock.jpg) -->
