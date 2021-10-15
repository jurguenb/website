---
description: |
  Para mí este es un espacio libre para escribir sobre cosas relacionadas con la ciencia de datos.
author: "Jurguen Bermudez"
show_post_thumbnail: false
thumbnail_left: true # for list-sidebar only
show_author_byline: false
show_post_date: true
# for listing page layout
layout: list # list, list-sidebar, list-grid

# for list-sidebar layout
sidebar: 
  title: Cosas que pienso 
  description: |
    Para mí este es un espacio libre para escribir sobre cosas no extremadamente relacionadas con mi trabajo.

  author: "Jurguen Bermudez"
  text_link_url: /index.xml
  show_sidebar_adunit: true # show ad container

# set up common front matter for all pages inside blog/
cascade:
  author: "Jurguen Bermudez"
  show_author_byline: true
  show_post_date: true
  show_comments: false # see site config to choose Disqus or Utterances
  # for single-sidebar layout
  sidebar:
    text_link_label: View recent posts
    text_link_url: /cosas_de_datos/
    show_sidebar_adunit: false # show ad container
---

** No content below YAML for the blog _index. This file provides front matter for the listing page layout and sidebar content. It is also a branch bundle, and all settings under `cascade` provide front matter for all pages inside blog/. You may still override any of these by changing them in a page's front matter.**