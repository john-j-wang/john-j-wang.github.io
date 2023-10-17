---
layout: default
title: Food Gallery
permalink: /food/
---

# {{ page.title }}

<div class="gallery">
    <a target="_blank" href='images/chess.png'>
        <img src='images/chess.png' alt="Description 1" />
    </a>
    <div class="desc">Description 1</div>
</div>

<div class="gallery">
    <a target="_blank" href='images/chess.png'>
        <img src='images/chess.png' alt="Description 2" />
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
