---
layout: '../../layouts/ProjectLayout.astro'
title: "Audio & Godot Project"
description: "A demonstration of using native HTML for media."
---

### The Mix
Native HTML audio players are lightweight and supported by every browser. Just drop your `.mp3` into the `public/audio/` folder.

<audio controls style="width: 100%; border-radius: 8px;">
  <source src="/audio/mix-01.mp3" type="audio/mpeg">
  Your browser does not support the audio element.
</audio>

### The Game Embed
If you export a WebGL build to itch.io, they give you an iframe. You can paste it directly into your Markdown.

<iframe 
  frameborder="0" 
  src="https://itch.io/embed/123456" 
  width="100%" 
  height="400">
</iframe>