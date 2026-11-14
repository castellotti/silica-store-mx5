---
type: Vehicle Model
title: "Fiat 124 Spider (2016) and Abarth 124 Spider"
description: "The ND-based Fiat and Abarth 124 Spider built by Mazda in Hiroshima."
resource: "https://en.wikipedia.org/w/index.php?title=Fiat_124_Spider_(2016)&oldid=1364893234"
tags: [mazda, mx-5, miata, fiat, abarth, nd]
aliases: ["Fiat 124 Spider", "Abarth 124 Spider", "124 Spider", "Fiata", "Type 348"]
status: stable
sources:
  - id: wp-fiat-124
    resource: "https://en.wikipedia.org/w/index.php?title=Fiat_124_Spider_(2016)&oldid=1364893234"
    title: "Wikipedia, \"Fiat 124 Spider (2016)\", permanent revision 1364893234 (2026-07-19)"
  - id: wp-nd
    resource: "https://en.wikipedia.org/w/index.php?title=Mazda_MX-5_(ND)&oldid=1382278464"
    title: "Wikipedia, \"Mazda MX-5 (ND)\", permanent revision 1382278464 (2026-10-27)"
x-silica:
  v: 1
  sources:
    wp-fiat-124: { kind: http, url: "https://en.wikipedia.org/w/index.php?title=Fiat_124_Spider_(2016)&oldid=1364893234" }
    wp-nd: { kind: http, url: "https://en.wikipedia.org/w/index.php?title=Mazda_MX-5_(ND)&oldid=1382278464" }
  facts:
    - id: overview
      at: { section: "Overview" }
      source: wp-fiat-124
      mode: pinned
      extract: { kind: text-between, start: "Related | Mazda MX-5 (ND)", end: "## Background" }
      pin: { sha256: "9b816930adf4d0015e115eee6e26a00245c2ca568749654363af0bba302151f6", rev: "sha256:788dd2b43fd58bfdfbf6544ac68575a56a437395a23a054c32672da6b2e4d26f", at: "2026-11-14T11:49:25Z", fact: "2be9eb749b275e6d61b8d19b2c95ff71e499fd601a59bd08e88b0fa1cdb42c8f" }
    - id: engine-fiat-article
      at: { section: "Engine (Fiat article)" }
      source: wp-fiat-124
      mode: pinned
      extract: { kind: md-section, heading: "Specifications" }
      pin: { sha256: "075fec71d7f3ed61ff17354ae3b28a31153b958d961710abe5c3c88d6236ed44", rev: "sha256:788dd2b43fd58bfdfbf6544ac68575a56a437395a23a054c32672da6b2e4d26f", at: "2026-11-14T11:49:25Z", fact: "407cfad09751638de92a3df041ef5ed9f27f77c588f779bd66a0e1dedd78b0ce" }
    - id: engine-nd-article
      at: { section: "Engine (ND article)" }
      source: wp-nd
      mode: pinned
      extract: { kind: md-section, heading: "Cooperation with Fiat Chrysler" }
      pin: { sha256: "e94d90fe28731a447d25b286462acddaffecc0d6ebbff64e153bd3a3be6db57d", rev: "sha256:e1a829d55fb41d71df271f5207d5dd8fcd9f6094cc6fcf9771fadcb1a335acc7", at: "2026-11-14T11:49:25Z", fact: "e52235cb47b3dfb6f4ec73a27e54bc418dd6b854f10a7d4bccc9273db48eb387" }
    - id: origin
      at: { section: "Origin" }
      source: wp-nd
      mode: pinned
      extract: { kind: md-section, heading: "Cooperation with Fiat Chrysler" }
      pin: { sha256: "e94d90fe28731a447d25b286462acddaffecc0d6ebbff64e153bd3a3be6db57d", rev: "sha256:e1a829d55fb41d71df271f5207d5dd8fcd9f6094cc6fcf9771fadcb1a335acc7", at: "2026-11-14T11:49:25Z", fact: "7a43d89eefa3c914ebee7d3ab86e0d88b9ae4ca23337b6705293c9f9e08eae73" }
---

# Fiat 124 Spider (2016) and Abarth 124 Spider

## Overview

The Fiat 124 Spider (Type 348) was made by Mazda and sold by Fiat from 2016 until 2019, based on the fourth-generation MX-5 and built alongside it in Hiroshima; it was sold in North America for the 2017 to 2020 model years and just over 41,000 were produced. [^wp-fiat-124]

## Engine output

The two articles give different outputs for the Fiat engine.

### Engine (Fiat article)

1.4 litre FIRE Multiair turbocharged inline-four: 140 PS (103 kW; 138 hp) and 240 N⋅m in European specification, 160 hp (117 kW) and 184 lb⋅ft (249 N⋅m) in North American specification. [^wp-fiat-124]

### Engine (ND article)

A 1.4 litre turbocharged engine with 127 kW (170 hp). [^wp-nd]

## Origin

A joint venture with Alfa Romeo on a rear-wheel drive platform was announced in 2012 and cancelled in 2014; FCA then announced the Fiat 124 Spider and Abarth 124 Spider on the Mazda ND platform. [^wp-nd]

## Related

- [MX-5 (ND), 2015–present](/generations/nd.md)
- [MX-5 ND1, model years 2016–2018](/revisions/nd1.md)


[^wp-fiat-124]: Wikipedia, "Fiat 124 Spider (2016)", permanent revision 1364893234 (2026-07-19): <https://en.wikipedia.org/w/index.php?title=Fiat_124_Spider_(2016)&oldid=1364893234>
[^wp-nd]: Wikipedia, "Mazda MX-5 (ND)", permanent revision 1382278464 (2026-10-27): <https://en.wikipedia.org/w/index.php?title=Mazda_MX-5_(ND)&oldid=1382278464>
