---
pagination:
  data: collections
  size: 1
  alias: selectedTag
permalink: /tags/{{ selectedTag | noEmoji | slug }}/
layout: layouts/posts-list.njk
allPostsLabel: All posts
eleventyComputed:
  metaTitle: "{{ selectedTag | noEmoji }}"
---
