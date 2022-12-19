---
title: Search
permalink: /search/index.html
description: "Ask, and it will be given you. Seek, and you will find."
layout: page
---

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
