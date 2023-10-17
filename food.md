---
layout: default
title: Food Gallery
permalink: /food/
---

# {{ page.title }}

<div class="gallery">
    <a target="_blank" href='/contact-me'>
        <img src='images/chess.png' alt="Fish Cheeks (NoHo, New York)" />
    </a>
    <div class="desc">Description 1</div>
</div>

<div class="gallery">
    <a target="_blank" href='/contact-me'>
        <img src='images/chess.png' alt="Frankie's 457 (Carroll Gardens, Brooklyn)" />
    </a>
    <div class="desc">Description 2</div>
</div>

<!-- Repeat for more items -->

<style>
    .gallery {
        margin: 5px; /* Adjusts the space around the gallery item */
        border: 1px solid #ccc; /* A light grey border around the gallery items */
        float: left; /* This makes the gallery items sit side by side */
        width: 100px; /* <-- Adjusted width of the gallery items. Change this value to find your preferred size */
    }
    
    .gallery:hover {
        border: 1px solid #777; /* A slightly darker grey border on hover for a subtle effect */
    }
    
    .gallery img {
        width: 100%;  /* Makes sure the image scales to the width of its container */
        height: auto;  /* Ensures the image's aspect ratio is maintained */
    }
    
    .desc {
        padding: 15px; /* Space between image and the description */
        text-align: center; /* Centers the text horizontally */
    }
</style>
