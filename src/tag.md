---
pagination:
  data: collections
  size: 1
  alias: selectedTag
permalink: /tags/{{ selectedTag | noEmoji | slug }}/
layout: layouts/recipes-list.njk
allRecipesLabel: Tous
eleventyComputed:
  metaTitle: "{{ selectedTag | noEmoji }}"
---
