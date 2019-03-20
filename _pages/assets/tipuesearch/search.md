---
title: Search cards
description: "Search cards in this site"
permalink: /search
tipue_search_active: true
exclude_from_search: true
---

## Search cards

<link rel="stylesheet" href="{{ "/_pages/assets/tipuesearch/css/normalize.css" | relative_url }}">
<script src="{{ "/_pages/assets/js/jquery-3.3.1.min.js" | relative_url}}"></script>
<script src="{{ "/_pages/assets/tipuesearch/tipuesearch_content.js" | relative_url }}"></script>
<link rel="stylesheet" href="{{ "/_pages/assets/tipuesearch/css/tipuesearch.css" | relative_url }}">
<script src="{{ "/_pages/assets/tipuesearch/tipuesearch_set.js" | relative_url }}"></script>
<script src="{{ "/_pages/assets/tipuesearch/tipuesearch.min.js" | relative_url }}"></script>

<form action="{{ page.url | relative_url }}">
  <div class="tipue_search_left"><img src="{{ "/_pages/assets/tipuesearch/search.png" | relative_url }}" class="tipue_search_icon"></div>
  <div class="tipue_search_right"><input type="text" name="q" id="tipue_search_input" pattern=".{2,}" title="At least 2 characters" required></div>
  <div style="clear: both;"></div>
</form>

<div id="tipue_search_content"></div>

<script>
$(document).ready(function() {
  $('#tipue_search_input').tipuesearch();
});
</script>
