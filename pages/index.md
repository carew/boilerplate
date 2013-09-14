---
title: Welcome
subtitle: to your new blog
navigations: main
---

## Posts

{{ render_documents(paginate(carew.posts|reverse)) }}

## Pages

{{ render_documents(paginate(carew.pages)) }}


Or you can {{ link('tags', 'browse all tags') }}.
