---
layout: home
title: 
---
<style>
.main-content, .page-content {
    margin: 0 !important;
    padding: 0 !important;
    width: 100vw !important;
    max-width: none !important;
}

h1 {
    display: none !important; /* Hide the repeated title since it's already in header */
}

.image-wrapper {
    width: 100vw;
    height: calc(100vh - 100px); /* Reduced from 150px to 100px for just header height */
    position: relative;
    left: 50%;
    transform: translateX(-50%);
    overflow: hidden;
    margin-top: 0 !important; /* Remove any top margin */
}

.image-wrapper img {
    width: 100%;
    height: 100%;
    object-fit: contain;
    display: block;
}

/* Hide recent posts section */
.recent-posts {
    display: none !important;
}

/* Remove any additional padding/margins */
body {
    overflow-x: hidden;
    margin: 0 !important;
    padding: 0 !important;
}
</style>

<div class="image-wrapper">
    <img src="/assets/images/MAP1.png" alt="AI Visualization">
</div>
