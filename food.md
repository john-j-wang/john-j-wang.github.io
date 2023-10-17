---
layout: default
title: Food Gallery
permalink: /food/
---

# {{ page.title }}

<div class="gallery">
    <a target="_blank" href="/path/to/image1-full.jpg">
        <img src="/path/to/image1-thumbnail.jpg" alt="Description 1" />
    </a>
    <div class="desc">Description 1</div>
</div>

<div class="gallery">
    <a target="_blank" href="/path/to/image2-full.jpg">
        <img src="/path/to/image2-thumbnail.jpg" alt="Description 2" />
    </a>
    <div class="desc">Description 2</div>
</div>

<!-- Repeat for more items -->

<style>
    .gallery {
        margin: 5px;
        border: 1px solid #ccc;
        float: left;
        width: 180px;
    }
    
    .gallery:hover {
        border: 1px solid #777;
    }
    
    .gallery img {
        width: 100%;
        height: auto;
    }
    
    .desc {
        padding: 15px;
        text-align: center;
    }
</style>
