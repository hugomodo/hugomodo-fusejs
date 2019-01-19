# HugoModo FuseJS

Adds site search functionality to Hugo sites.

## Support on Patreon
[![Patreon](https://c5.patreon.com/external/logo/become_a_patron_button.png)](https://www.patreon.com/bePatron?u=4780882)

## Support on Beerpay
Hey dude! Help me out for a couple of :beers:!

[![Beerpay](https://beerpay.io/hugomodo/hugomodo-fusejs/badge.svg?style=beer-square)](https://beerpay.io/hugomodo/hugomodo-fusejs)  [![Beerpay](https://beerpay.io/hugomodo/hugomodo-fusejs/make-wish.svg?style=flat-square)](https://beerpay.io/hugomodo/hugomodo-fusejs?focus=wish)

## Installation

Follow the usual steps for installing a HugoModo extension, then:

* Add a JSON output for `home` in your site config:

``` toml
[outputs]
  home = [
    "HTML",
    "RSS",
    "JSON"
  ]
```

* Add a content file at `content/search.md` with frontmatter:

``` yaml
---
title: Search
layout: search
---
```

* That's it! Were you expecting extra steps? Load up your site and visit `/search` to see it working.

## Roadmap

1. Searchbar partial for inclusion in templates.
