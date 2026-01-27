+++
title = "Stream"
menu = "main"
weight = 100
+++

[![](https://markdown-videos-api.jorgenkh.no/youtube/{video_id})](https://youtu.be/{video_id})

<video id='hls-example'  class="video-js vjs-default-skin" width="400" height="300" controls>
<source type="application/x-mpegURL" src="https://3d-printer.landonbjackson.dev/3d-printer/hls/myStream.m3u8">
</video>

<script>
var player = videojs('hls-example');
player.play();
</script>