---
type: Vehicle Model
title: "Mazda MX-5"
description: "The Mazda MX-5 two-seat roadster: names, generations, production milestones and awards."
resource: "https://en.wikipedia.org/w/index.php?title=Mazda_MX-5&oldid=1384156481"
tags: [mazda, mx-5, miata, roadster]
aliases: ["Miata", "MX-5 Miata", "Mazda Miata", "Mazda Roadster", "Eunos Roadster", "MX5", "Roadster"]
status: stable
sources:
  - id: wp-mx5
    resource: "https://en.wikipedia.org/w/index.php?title=Mazda_MX-5&oldid=1384156481"
    title: "Wikipedia, \"Mazda MX-5\", permanent revision 1384156481 (2026-11-06)"
x-silica:
  v: 1
  sources:
    wp-mx5: { kind: http, url: "https://en.wikipedia.org/w/index.php?title=Mazda_MX-5&oldid=1384156481" }
  facts:
    - id: names
      at: { section: "Names" }
      source: wp-mx5
      mode: pinned
      extract: { kind: text-between, start: "Also called |", end: "Production |" }
      pin: { sha256: "3f3c2891260c0687e52cb71c671cf375cbc24a027b7ae401ca11b038c25cf0bf", rev: "sha256:b96cb41d926071821490db5697fd311eccc0299e8afdf5870eae5f130f177006", at: "2026-11-14T11:31:46Z", fact: "6d7fc9c3e28b7984942bff373adebcdef6fa7d3fda3328ba886c6abfb0a83c21" }
    - id: generations
      at: { section: "Generations" }
      source: wp-mx5
      mode: pinned
      extract: { kind: text-between, start: "Each generation is identified", end: "More than one million" }
      pin: { sha256: "b74914956ccb13c18ee9e307beddc7ed1dd5284c6c07e57e6608843de28119a6", rev: "sha256:b96cb41d926071821490db5697fd311eccc0299e8afdf5870eae5f130f177006", at: "2026-11-14T11:31:46Z", fact: "43a3881f59a803492eb606ef9d94eaafc0f1fc61f3b68097b85656f9a18894fe" }
    - id: overview
      at: { section: "Overview" }
      source: wp-mx5
      mode: pinned
      extract: { kind: md-section, heading: "Overview" }
      pin: { sha256: "7cdbbbe3f000ab0b77efc3c97576c65599eaf0a2d971dcf226d7d2c168e2c98d", rev: "sha256:b96cb41d926071821490db5697fd311eccc0299e8afdf5870eae5f130f177006", at: "2026-11-14T11:31:46Z", fact: "3eb0a3f03e9abe59fb6b351695371ffcc9351564bd93340e547f33103e5f8066" }
    - id: production-milestones
      at: { section: "Production milestones" }
      source: wp-mx5
      mode: pinned
      extract: { kind: md-section, heading: "Production numbers and details" }
      pin: { sha256: "c45ef12562f84fed1bd98d447976e017c0390d91921803d8f802d306831cb54c", rev: "sha256:b96cb41d926071821490db5697fd311eccc0299e8afdf5870eae5f130f177006", at: "2026-11-14T11:31:46Z", fact: "26739d12a16f608ca2edefaf835762c31340e445b6f2e89a1ad00acf9619467e" }
    - id: production-by-generation
      at: { section: "Production by generation" }
      source: wp-mx5
      mode: pinned
      extract: { kind: md-section, heading: "Production numbers and details" }
      pin: { sha256: "c45ef12562f84fed1bd98d447976e017c0390d91921803d8f802d306831cb54c", rev: "sha256:b96cb41d926071821490db5697fd311eccc0299e8afdf5870eae5f130f177006", at: "2026-11-14T11:31:46Z", fact: "2fc086f5c450ba598e61b4b792479822576a110adbf05792acba38a82f5627aa" }
    - id: awards
      at: { section: "Awards" }
      source: wp-mx5
      mode: pinned
      extract: { kind: md-section, heading: "Awards" }
      pin: { sha256: "d6e447d1304ef62f529e37e5cc846bc531f6ebf3fb2a77533b78c1fe570ca5ee", rev: "sha256:b96cb41d926071821490db5697fd311eccc0299e8afdf5870eae5f130f177006", at: "2026-11-14T11:31:46Z", fact: "3abf9387516e7e89f249306ea4188379636b7ec922ad857c2f1c23d781f69902" }
    - id: recognition
      at: { section: "Recognition" }
      source: wp-mx5
      mode: pinned
      extract: { kind: md-section, heading: "Legacy and recognition" }
      pin: { sha256: "c78a7e69bdb00819583e7a7ced4685c66cca6511cdf4b685911dcd5af8e094ed", rev: "sha256:b96cb41d926071821490db5697fd311eccc0299e8afdf5870eae5f130f177006", at: "2026-11-14T11:31:46Z", fact: "79913ea76fa27b96bc93bfde4eaf769a5597758eb32d91ffba787d94483946b3" }
    - id: ten-best-count
      at: { section: "Car and Driver 10Best count" }
      source: wp-mx5
      mode: pinned
      extract: { kind: md-section, heading: "Legacy and recognition" }
      pin: { sha256: "c78a7e69bdb00819583e7a7ced4685c66cca6511cdf4b685911dcd5af8e094ed", rev: "sha256:b96cb41d926071821490db5697fd311eccc0299e8afdf5870eae5f130f177006", at: "2026-11-14T11:31:46Z", fact: "232e113b66495dfe3f0a29cd7e12be83e2aec4e9bd3a7c0caea3ff72b5ac4e75" }
    - id: total-sales
      at: { section: "Total sales to date" }
---

# Mazda MX-5

## Names

Sold as the Mazda Roadster, and earlier the Eunos Roadster, in Japan, and as the Mazda MX-5 Miata in North America. [^wp-mx5]

## Generations

Each generation has a two-letter code: first generation NA, then NB launched in 1998, NC in 2005 and ND in 2015. [^wp-mx5]

## Overview

Introduced in February 1989 at the Chicago Auto Show; unibody construction with a curb weight under 1,100 kg (2,500 lb), a Powerplant Frame (PPF) truss joining engine and differential, and an approximate 50:50 front/rear weight balance. [^wp-mx5]

## Production milestones

In 2000 the Guinness Book of World Records declared it the best-selling two-seat sports car, at 531,890 units. Milestone cars followed on November 9, 1992, February 8, 1999, in March 2004, January 2007 and February 2011; the one millionth was produced on April 22, 2016. [^wp-mx5]

## Production by generation

Production table totals: first generation (NA) 431,506; second generation (NB) 290,123; third generation (NC) 231,632; all calendar years 1,089,697. [^wp-mx5]

## Awards

Automobile Magazine 1990 Automobile of the Year; Car and Driver 10Best list 1990-1992, 1998-1999, 2001, 2006-2013 and 2016-2019; Car of the Year Japan Award 2005-2006 and 2015-2016; 2016 World Car of the Year and World Car Design of the Year; Red Dot Best of the Best Award: Product Design 2017; Car and Driver 2024 Editor's Choice: Affordable Sports Car. [^wp-mx5]

## Recognition

Wheels Magazine's Car of the Year for 1989, 2005 and 2016; 2005 Australian Car of the Year; Grassroots Motorsports (December 2009) named it the most important sports car of the previous 25 years. [^wp-mx5]

## Car and Driver 10Best count

The article says the MX-5 made Car and Driver's 10 Best list 17 times, while its awards list gives the years 1990-1992, 1998-1999, 2001, 2006-2013 and 2016-2019; the stated count and the listed years do not agree. [^wp-mx5]

## Total sales to date

_Not found._

## Related

- [MX-5 (NA), 1989–1997](/generations/na.md)
- [MX-5 (NB), 1998–2005](/generations/nb.md)
- [MX-5 (NC), 2005–2015](/generations/nc.md)
- [MX-5 (ND), 2015–present](/generations/nd.md)
- [Glossary of MX-5 codes](/model/glossary.md)
- [Model years](/model-years/index.md)
- [Awards](/awards/index.md)


[^wp-mx5]: Wikipedia, "Mazda MX-5", permanent revision 1384156481 (2026-11-06): <https://en.wikipedia.org/w/index.php?title=Mazda_MX-5&oldid=1384156481>
