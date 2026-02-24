# Jeremy Shaki Birthday Site

> A fun birthday celebration website for Jeremy Shaki featuring a fullscreen video background, autoplay music, and interactive tooltip messages from friends.

![Status](https://img.shields.io/badge/status-archived-lightgrey)
![HTML](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

## Live Demo

[https://izzydoesizzy.github.io/jeremyshaki](https://izzydoesizzy.github.io/jeremyshaki)

## Overview

A playful birthday tribute page built as a surprise for Jeremy Shaki. When visitors load the page, they are greeted with a fullscreen looping video background, background music (Kirby theme), and scattered doge-meme-style text phrases. Each phrase is a clickable tooltip that reveals a personal birthday message from a different friend -- Sumi, Rachel, Amy, Emma, Wallace, Kristin, Chriscelle, Topaz, Izzy, Chris, and Juan.

## Features

- Fullscreen autoplay looping video background (`<video>` element with poster fallback)
- Autoplay background music with OGG and MP3 source fallbacks, set to low volume
- Doge-meme-inspired text layout with scattered, colorful phrases
- Interactive tooltips powered by Tooltipster -- hover over any phrase to read a personal birthday message
- jQuery-based tooltip initialization
- Custom punk-inspired and standard CSS styling

## Screenshots

<!-- ![Screenshot](screenshot.png) -->

## Tech Stack

- HTML5 (video and audio elements)
- CSS3 (custom punk.css + style.css)
- jQuery 1.10
- Tooltipster (tooltip library)
- Hosted on GitHub Pages

## Getting Started

### Run Locally

No build step required:

1. **Clone the repository**
   ```bash
   git clone https://github.com/izzydoesizzy/jeremyshaki.git
   cd jeremyshaki
   ```

2. **Open in browser**
   ```bash
   open index.html
   # or use a local server:
   npx serve .
   ```

### Deploy to GitHub Pages

1. Push to the `gh-pages` branch
2. Go to Settings > Pages > Source: Deploy from branch
3. Site live at `https://izzydoesizzy.github.io/jeremyshaki`

## Project Structure

```
jeremyshaki/
├── index.html              # Main page with video, audio, and tooltips
├── style.css               # Primary stylesheet
├── punk.css                # Additional punk-inspired styles
├── jeremyshaki2.mp4        # Background video
├── kirbymusic2.mp3         # Background music (MP3)
├── kirbymusic2.ogg         # Background music (OGG)
├── music.ogg               # Additional audio file
├── tooltipster-master/     # Tooltipster tooltip library
├── license.txt             # License file
└── README.txt              # Original readme
```

## Tags

`fun-project`

## Created

2017-01

## Status

Legacy -- This was a one-time birthday surprise site from January 2017.

## Author

**Izzy Piyale-Sheard** -- [@izzydoesizzy](https://github.com/izzydoesizzy)
