---
title: About
permalink: /about/index.html
description: About this starter
layout: page
youtube: true
---

Based on the companion website of Andy Bell's talk 'Be the browser’s mentor, not its micromanager'.
An approach that promotes modern CSS with methodologies, fluid type & space, flexible Layouts and Progressive Enhancement.

This starter exists to hopefully spread the use of this _excellent_ workflow. To work with it efficiently you should be familiar with [cube.fyi](https://cube.fyi/), [utopia.fyi](https://utopia.fyi/) and [every-layout.dev](https://every-layout.dev/).

- Find out more on https://buildexcellentwebsit.es/.
- Remix the original: https://glitch.com/edit/#!/remix/build-excellent-websites

Edit your preferences (colors, fonts, fluid text sizes etc.) in `src/assets/css/design-tokens`.

## Watch the talk

{% youtube '5uhIiI9Ld5M', 'Andy Bell – Be the browser’s mentor, not its micromanager' %}


<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@algolia/algoliasearch-netlify-frontend@1/dist/algoliasearchNetlify.css" />
<script type="text/javascript" src="https://cdn.jsdelivr.net/npm/@algolia/algoliasearch-netlify-frontend@1/dist/algoliasearchNetlify.js"></script>
<script type="text/javascript">
  algoliasearchNetlify({
    appId: '1C3WFOU8W0',
    apiKey: '32512f48afa78f08379b398322d5df6f',
    siteId: '004e3c2e-eb8e-439d-b4a4-a27bbe12cfec',
    branch: 'main',
    selector: 'div#search',
  });
</script>
<div id="search"></div>
