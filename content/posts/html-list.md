---
title: "Interactive HTML Visualizations"
date: 2025-01-30
type: post
---

## Data Products (Fragility Curves)

Click on any item below to load the HTML content.

- [Brick Masonry Residential (South Pacific Tsunami 2009)](#brick-masonry)
- [Chilean Tsunami 2010](#chilean-tsunami)

<div id="brick-masonry" style="display:none;">
    <iframe src="/html/Brick_masonry.html" width="100%" height="600px"></iframe>
</div>

<div id="chilean-tsunami" style="display:none;">
    <iframe src="/html/Chilean_Tsunami.html" width="100%" height="600px"></iframe>
</div>

<script>
function showContent(id) {
    document.getElementById('brick-masonry').style.display = 'none';
    document.getElementById('chilean-tsunami').style.display = 'none';
    document.getElementById(id).style.display = 'block';
}

document.querySelector('a[href="#brick-masonry"]').addEventListener('click', function() {
    showContent('brick-masonry');
});

document.querySelector('a[href="#chilean-tsunami"]').addEventListener('click', function() {
    showContent('chilean-tsunami');
});
</script>
