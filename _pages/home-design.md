---
permalink: /home-design/
title: "Name to Thing"
layout: splash
classes: wide
excerpt: N2T keeps identifiers persistent, forwarding them to the best known web addresses.
header:
    overlay_color: "#0D846E"
    # overlay_filter: linear-gradient(55deg, rgba(0,119,139,1) 0%, rgba(0,119,139,1) 33%, rgba(0,163,173,1) 100%)
feature_row:
  - image_path: /assets/images/cdl-swirl.svg
    title: "Identifier Types"
    excerpt: "N2T resolves 900+ compact identifiers"
    url: "https://n2t-stg.cdlib.org/_schemes.html"
    btn_label: "All Schemes"
  - image_path: /assets/images/cdl-swirl.svg
    background: "linear-gradient(55deg, rgba(0,119,139,1) 0%, rgba(0,119,139,1) 33%, rgba(0,163,173,1) 100%)"
    title: "API"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
    url: "https://n2t-stg.cdlib.org/api#/"
    btn_label: "API Description"
  - image_path: /assets/images/cdl-swirl.svg
    title: "About N2T"
    excerpt: "The API is used to create and maintain identifiers and metadata. "
    url: "/about/"
    btn_label: "API documentation."
    
---

N2T is an identifier scheme resolver that given a provided identifier, matches it to an identifier scheme definition. Depending on the form of the request, a successful match will either redirect to the registered target or present information about the matched definition.

Identifiers take the form:

```
scheme:prefix/value
```

{% include feature_row %}

