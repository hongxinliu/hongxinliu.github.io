---
layout: post
title: 像我这样的人
subtitle: 第一首翻唱试麦
description: 第一首翻唱试麦
image: http://qhge22hn5.hn-bkt.clouddn.com/bamboo.jpeg
category: 音乐
tags: 
  - 翻唱
  - 毛不易
  - Cover
author: hongxinliu
---

{% raw %}
<div class="audio">
  <audio id="audio-ones-like-me" controls loop preload="auto">
    <source src="http://qhge22hn5.hn-bkt.clouddn.com/ones-like-me.mp3" type="audio/mpeg">
  </audio>
  <div id="lyrics-ones-like-me">
  </div>
  <script type="module">
    import RabbitLyrics from "/assets/js/rabbit-lyrics.js";
    $.get("http://qhge22hn5.hn-bkt.clouddn.com/ones-like-me.lrc", function(data, status) {
      $("#lyrics-ones-like-me").append(data);
      new RabbitLyrics({
        element: document.getElementById("lyrics-ones-like-me"),
        mediaElement: document.getElementById("audio-ones-like-me")
      });
    });
  </script>
</div>
{% endraw %}
