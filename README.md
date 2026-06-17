# Tri-Leg Tutorial Webpage

This repository contains a lightweight GitHub Pages webpage for presenting the **Tri-Leg Tutorial** video.

The page is designed to host a local MP4 file directly inside the repository, allowing the tutorial video to be played through a standard HTML5 video player. A fallback button is also provided for opening the original CUHK Stream / SharePoint video link when needed.

## Project Purpose

Microsoft Stream and SharePoint video links may not work reliably when embedded into external websites such as GitHub Pages, because they often require institutional login and may block iframe embedding.

To avoid this issue, this project uses a local MP4 playback solution:

```html
<video controls>
  <source src="assets/videos/tutorial_trileg.mp4" type="video/mp4">
</video>
