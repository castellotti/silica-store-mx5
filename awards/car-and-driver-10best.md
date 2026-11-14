---
type: Award
title: "Car and Driver 10Best: Mazda MX-5"
description: "Years the MX-5 appears on Car and Driver's 10Best list, by generation, and a count disagreement."
resource: "https://en.wikipedia.org/w/index.php?title=Mazda_MX-5&oldid=1384156481"
tags: [mazda, mx-5, miata, award]
aliases: ["10Best", "10 Best", "Ten Best", "Car and Driver"]
status: stable
sources:
  - id: wp-mx5
    resource: "https://en.wikipedia.org/w/index.php?title=Mazda_MX-5&oldid=1384156481"
    title: "Wikipedia, \"Mazda MX-5\", permanent revision 1384156481 (2026-11-06)"
  - id: wp-na
    resource: "https://en.wikipedia.org/w/index.php?title=Mazda_MX-5_(NA)&oldid=1381587107"
    title: "Wikipedia, \"Mazda MX-5 (NA)\", permanent revision 1381587107 (2026-10-23)"
  - id: wp-nb
    resource: "https://en.wikipedia.org/w/index.php?title=Mazda_MX-5_(NB)&oldid=1381623005"
    title: "Wikipedia, \"Mazda MX-5 (NB)\", permanent revision 1381623005 (2026-10-23)"
  - id: wp-nc
    resource: "https://en.wikipedia.org/w/index.php?title=Mazda_MX-5_(NC)&oldid=1381436898"
    title: "Wikipedia, \"Mazda MX-5 (NC)\", permanent revision 1381436898 (2026-10-22)"
  - id: wp-nd
    resource: "https://en.wikipedia.org/w/index.php?title=Mazda_MX-5_(ND)&oldid=1382278464"
    title: "Wikipedia, \"Mazda MX-5 (ND)\", permanent revision 1382278464 (2026-10-27)"
x-silica:
  v: 1
  sources:
    wp-mx5: { kind: http, url: "https://en.wikipedia.org/w/index.php?title=Mazda_MX-5&oldid=1384156481" }
    wp-na: { kind: http, url: "https://en.wikipedia.org/w/index.php?title=Mazda_MX-5_(NA)&oldid=1381587107" }
    wp-nb: { kind: http, url: "https://en.wikipedia.org/w/index.php?title=Mazda_MX-5_(NB)&oldid=1381623005" }
    wp-nc: { kind: http, url: "https://en.wikipedia.org/w/index.php?title=Mazda_MX-5_(NC)&oldid=1381436898" }
    wp-nd: { kind: http, url: "https://en.wikipedia.org/w/index.php?title=Mazda_MX-5_(ND)&oldid=1382278464" }
  facts:
    - id: years-listed
      at: { section: "Years listed" }
      source: wp-mx5
      mode: pinned
      extract: { kind: md-section, heading: "Awards" }
      pin: { sha256: "d6e447d1304ef62f529e37e5cc846bc531f6ebf3fb2a77533b78c1fe570ca5ee", rev: "sha256:b96cb41d926071821490db5697fd311eccc0299e8afdf5870eae5f130f177006", at: "2026-11-14T11:31:46Z", fact: "1b0f0680a79d64cbd7675ae7da2badf2789d085df8eaeb4837436d920e939b44" }
    - id: stated-count
      at: { section: "Stated count" }
      source: wp-mx5
      mode: pinned
      extract: { kind: md-section, heading: "Legacy and recognition" }
      pin: { sha256: "c78a7e69bdb00819583e7a7ced4685c66cca6511cdf4b685911dcd5af8e094ed", rev: "sha256:b96cb41d926071821490db5697fd311eccc0299e8afdf5870eae5f130f177006", at: "2026-11-14T11:31:46Z", fact: "df4b892ab6a3ed1b1d045cc6dbb4f71cc9221e2149428bab86870f3869db94f1" }
    - id: na-years
      at: { section: "NA years" }
      source: wp-na
      mode: pinned
      extract: { kind: md-section, heading: "Awards and recognition" }
      pin: { sha256: "45721dadf2199c7aad9f2691d92935ea3d87ac72c7a0a20d10b8d06e1b76d0ac", rev: "sha256:334b67430ffe976b0d9ef21ff9aef5af2f81844f836b567463da81d5b162351c", at: "2026-11-14T11:31:46Z", fact: "0d549dc1d48109e4c44ddd4be44a09bda72c9e3a3f42d4328efb75b2eb9d025c" }
    - id: nb-years
      at: { section: "NB years" }
      source: wp-nb
      mode: pinned
      extract: { kind: md-section, heading: "Awards and recognition" }
      pin: { sha256: "9d1524cb949f1ce64770a89d75fa57624c91a385f3d339cb2b5a26bfd6293c57", rev: "sha256:778980889258777eea626b61a1a715253cc4b66c9bc18fee54d1b2a7148fcbe8", at: "2026-11-14T11:31:46Z", fact: "a276752a76f579c79e7512bcfc4be2d73c471e90b455a0406ca4c60205ef0626" }
    - id: nc-years
      at: { section: "NC years" }
      source: wp-nc
      mode: pinned
      extract: { kind: md-section, heading: "Accolades" }
      pin: { sha256: "10e04bec335c16487e2205c6bea01c26f80427d64d2f3559cef831c6c1ffef44", rev: "sha256:f4725821ab6e7446faa0f56c1a7a502d19f7a842e87e55f079b17a1408bd2d31", at: "2026-11-14T11:31:46Z", fact: "108f1aba8496c36b888c5aadb1444f392df3a4e77f11ae8b7336ac3e4c58c104" }
    - id: nd-years
      at: { section: "ND years" }
      source: wp-nd
      mode: pinned
      extract: { kind: md-section, heading: "Accolades" }
      pin: { sha256: "44a397f428d5a04b4687fb155c8090d661e65a3fdabc94a9883b96f8d75b99bf", rev: "sha256:e1a829d55fb41d71df271f5207d5dd8fcd9f6094cc6fcf9771fadcb1a335acc7", at: "2026-11-14T11:31:46Z", fact: "076c736eb95cf0099824dc3612bfd3c801e761718a6adc8cb06c031f88445245" }
---

# Car and Driver 10Best: Mazda MX-5

## Years listed

Car and Driver's 10Best list from 1990-1992, 1998-1999, 2001, 2006-2013 and 2016-2019. [^wp-mx5]

## Stated count

The MX-5 article says the MX-5 has made the 10 Best list 17 times, which does not match the years in its own awards list. [^wp-mx5]

## NA years

10Best list from 1990 to 1992. [^wp-na]

## NB years

10Best list from 1998 to 1999 and 2001. [^wp-nb]

## NC years

10Best list from 2006 to 2013. [^wp-nc]

## ND years

10Best list from 2016 to 2019. [^wp-nd]

## Related

- [MX-5 (NA), 1989–1997](/generations/na.md)
- [MX-5 (NB), 1998–2005](/generations/nb.md)
- [MX-5 (NC), 2005–2015](/generations/nc.md)
- [MX-5 (ND), 2015–present](/generations/nd.md)


[^wp-mx5]: Wikipedia, "Mazda MX-5", permanent revision 1384156481 (2026-11-06): <https://en.wikipedia.org/w/index.php?title=Mazda_MX-5&oldid=1384156481>
[^wp-na]: Wikipedia, "Mazda MX-5 (NA)", permanent revision 1381587107 (2026-10-23): <https://en.wikipedia.org/w/index.php?title=Mazda_MX-5_(NA)&oldid=1381587107>
[^wp-nb]: Wikipedia, "Mazda MX-5 (NB)", permanent revision 1381623005 (2026-10-23): <https://en.wikipedia.org/w/index.php?title=Mazda_MX-5_(NB)&oldid=1381623005>
[^wp-nc]: Wikipedia, "Mazda MX-5 (NC)", permanent revision 1381436898 (2026-10-22): <https://en.wikipedia.org/w/index.php?title=Mazda_MX-5_(NC)&oldid=1381436898>
[^wp-nd]: Wikipedia, "Mazda MX-5 (ND)", permanent revision 1382278464 (2026-10-27): <https://en.wikipedia.org/w/index.php?title=Mazda_MX-5_(ND)&oldid=1382278464>
