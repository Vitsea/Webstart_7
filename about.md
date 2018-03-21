---
layout: page
title: About
sidebar_link: true
---

<p class="message">
  Hey there! This page is included as an example. Feel free to customize it
  for your own use upon downloading. Carry on!
</p>

To make pages show up in the sidebar, add `sidebar_link: true` to the front
matter.
<div class="embed-responsive embed-responsive-16by9">
  <iframe width="360" height="640" src="https://www.youtube.com/watch?v=zcSqH6ZCmtU/embed/l2Of1-d5E5o?controls=0&amp;" frameborder="0" allowfullscreen></iframe>
</div>

This post tests YouTube video embeds.

Simply wrap embeds with a `<div>` element and the appropriate classes:

```html
<!-- 16:9 aspect ratio -->
<div class="embed-responsive embed-responsive-16by9">
  <iframe class="embed-responsive-item" src="..."></iframe>
</div>

<!-- 4:3 aspect ratio -->
<div class="embed-responsive embed-responsive-4by3">
  <iframe class="embed-responsive-item" src="..."></iframe>
</div>
```