---
layout: default
title: My Favorite Foods
permalink: /food/
---

# {{ page.title }}
Below are some of my favorite dishes!

<!-- Gallery -->
<div class="gallery">
    <a target="_blank" href="full-size-image1.jpg">
      <img src="thumbnail-image1.jpg" alt="Food 1" width="600" height="400">
    </a>
    <div class="desc">Description of Food 1</div>
</div>

<div class="gallery">
    <a target="_blank" href="full-size-image2.jpg">
      <img src="thumbnail-image2.jpg" alt="Food 2" width="600" height="400">
    </a>
    <div class="desc">Description of Food 2</div>
</div>

<!-- Add more items as per your requirement -->

<!-- CSS for Gallery -->
<style>
    div.gallery {
      margin: 5px;
      border: 1px solid #ccc;
      float: left;
      width: 180px;
    }

    div.gallery:hover {
      border: 1px solid #777;
    }

    div.gallery img {
      width: 100%;
      height: auto;
    }

    div.desc {
      padding: 15px;
      text-align: center;
    }
</style>
