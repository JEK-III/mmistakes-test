---
permalink: /home-design/
title: "Name to Thing"
layout: splash
classes: wide
excerpt: N2T keeps identifiers persistent, forwarding them to the best known web addresses.
header:
    overlay_color: rgba(0, 0, 0, 0)
    overlay_filter: linear-gradient(320deg, rgba(13,132,110,0.1) 25%, rgba(0,119,139,0.2) 94%)
    # overlay_filter: linear-gradient(55deg, rgba(0,119,139) 0, rgba(0,119,139) 0.33, rgba(0,163,173) 1.0)
    # overlay_image: /assets/images/hero/UCSD_day2-150--cropped.png
    # overlay_filter: rgba(255, 0, 0, 0.5)
feature_row:
  - image_path: /assets/images/N2T-icons_list--gradient.svg
    title: "Identifier Schemes"
    excerpt: "N2T resolves 900+ kinds of identifier, including DOIs, ARKs, and ORCIDs."
    url: "https://n2t-stg.cdlib.org/_schemes.html"
    btn_label: "See all identifier schemes"
  - image_path: /assets/images/N2T-icons_gear--gradient.svg
    title: "API"
    excerpt: "The N2T API is used to create and maintain identifiers and metadata."
    url: "https://n2t-stg.cdlib.org/api#/"
    btn_label: "API Description"
  - image_path: /assets/images/N2T-icons_uc3--gradient.svg
    title: "About N2T"
    excerpt: "The API is used to create and maintain identifiers and metadata. "
    url: "/about/"
    btn_label: "Read about N2T"
    
---

N2T.net is a kind of URL shortener for persistent identifiers, like DOIs and ORCIDs. 

When you append an identifier *name* in the form `scheme:value` to `https://n2t.net/`, N2T takes you to the digital *thing*.

Here are some examples:

```
https://n2t.net/PDB:2gc4
https://n2t.net/Taxon:9606
https://n2t.net/DOI:10.5281/ZENODO.1289856
https://n2t.net/ark:/47881/m6g15z54
https://n2t.net/IGSN:SSH000SUA
```

{% include feature_row %}

