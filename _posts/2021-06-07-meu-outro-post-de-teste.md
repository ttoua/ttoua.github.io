---
title: Meu Outro Post de Teste
author: Toua
date: 2021-06-07 21:58:00 -0300
image:
  src: /assets/img/favicons/android-chrome-512x512.png
  alt: Toua
categories: [Teste]
tags: [novo]

---

### Lista de links ordenada

1. <https://toua.cf>
2. <https://toua.cf>
3. <https://toua.cf>
4. <https://toua.cf>
5. <https://toua.cf>
6. <https://toua.cf>

### Tabela de Links

| Toua | Número | Link Direto                |
|:-----|:-------|:---------------------------|
| Link | 1      | [Link 01](https://toua.cf) |
| Link | 2      | [Link 02](https://toua.cf) |
| Link | 3      | [Link 03](https://toua.cf) |

<a class="tag" href="https://toua.cf">Link<span class="text-muted">1</span></a>
<a class="tag" href="https://toua.cf">Link<span class="text-muted">2</span></a>
<a class="tag" href="https://toua.cf">Link<span class="text-muted">3</span></a>
<a class="tag" href="https://toua.cf">Link<span class="text-muted">4</span></a>
<a class="tag" href="https://toua.cf">Link<span class="text-muted">5</span></a>

[Link 01](https://toua.cf){: .tag}
[Link 02](https://toua.cf){: .tag}
[Link 03](https://toua.cf){: .tag}
[Link 04](https://toua.cf){: .tag}
[Link 05](https://toua.cf){: .tag}
[Link 06](https://toua.cf){: .tag}


### Video

<!--BEGIN-VIDEOJS------------------------------------------------------->

  <!--HEAD--> 
  
  <link href="https://vjs.zencdn.net/7.11.4/video-js.css" rel="stylesheet" />

  <!-- City -->
  <link
  href="https://unpkg.com/@videojs/themes@1/dist/city/index.css"
  rel="stylesheet"
  />

  <!-- If you'd like to support IE8 (for Video.js versions prior to v7) -->
  <!-- <script src="https://vjs.zencdn.net/ie8/1.1.2/videojs-ie8.min.js"></script> -->

  <!--HEAD-->

  <!--BODY-->

<!--<div style="position: absolute; inset: 0px; margin: 1.5%;">-->

<style>
  /*.figure-test { width: 100% !important; height: auto !important;}
  figcaption { font: 120% sans-serif; text-align: center;}
  .video-test { width: 100%; height: auto;}*/

.videoWrapper {
  position: relative;
  padding-bottom: 56.25%; /* 16:9 */
  height: 0;
}
.video-test {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
}

</style>  

<div class="videoWrapper">
<video
    id="my-video"
    class="video-js video-test"
    controls
    preload="auto"
    poster="https://toua.cf/assets/img/favicons/android-chrome-512x512.png"
    data-setup="{}"
  >
    <source src="https://vjs.zencdn.net/v/oceans.mp4" type="video/mp4" />
    <source src="https://vjs.zencdn.net/v/oceans.webm" type="video/webm" />
    <p class="vjs-no-js">
      To view this video please enable JavaScript, and consider upgrading to a
      web browser that
      <a href="https://videojs.com/html5-video-support/" target="_blank"
        >supports HTML5 video</a
      >
    </p>
</video>
</div>

<div class="videoWrapper">
<video
    id="vid1"
    class="video-js video-test"
    controls
    autoplay
    data-setup='{ "techOrder": ["youtube"], "sources": [{ "type": "video/youtube", "src": "https://www.youtube.com/watch?v=M3bvuAuPYH4"}] , "youtube": {"iv_load_policy": 3 , "modestbranding": 1 , ytControls": 2 } }'
  >
  </video>

  <!--<iframe class="video-js video-test" src="https://www.youtube.com/embed/PIb6AZdTr-A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>-->
</div>


  <script src="https://vjs.zencdn.net/7.11.4/video.min.js"></script>
  <script src="/assets/js/dist/youtube.js"></script>

  <!--BODY-->

 <!--END-VIDEOJS------------------------------------------------------->