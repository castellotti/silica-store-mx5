---
type: Award
title: "World Car Awards: Mazda MX-5"
description: "The MX-5's 2016 World Car of the Year and World Car Design of the Year wins, and its 2006 finalist place."
resource: "https://en.wikipedia.org/w/index.php?title=World_Car_Awards&oldid=1374901028"
tags: [mazda, mx-5, miata, award]
aliases: ["World Car of the Year", "WCOTY", "World Car Design of the Year", "World Car Awards"]
status: stable
sources:
  - id: wp-wca
    resource: "https://en.wikipedia.org/w/index.php?title=World_Car_Awards&oldid=1374901028"
    title: "Wikipedia, \"World Car Awards\", permanent revision 1374901028 (2026-09-14)"
  - id: wp-nd
    resource: "https://en.wikipedia.org/w/index.php?title=Mazda_MX-5_(ND)&oldid=1382278464"
    title: "Wikipedia, \"Mazda MX-5 (ND)\", permanent revision 1382278464 (2026-10-27)"
x-silica:
  v: 1
  sources:
    wp-wca: { kind: http, url: "https://en.wikipedia.org/w/index.php?title=World_Car_Awards&oldid=1374901028" }
    wp-nd: { kind: http, url: "https://en.wikipedia.org/w/index.php?title=Mazda_MX-5_(ND)&oldid=1382278464" }
  facts:
    - id: 2016-winners-table
      at: { section: "2016 winners table" }
      source: wp-wca
      mode: pinned
      extract: { kind: text-between, start: "Year[23] | World Car of the Year", end: "2017 |" }
      pin: { sha256: "e69e2de784f81be03f7299a9cbcbeebe35b8b33c9df4bcb76bc5ea6442c184f6", rev: "sha256:b3c22386df2501b53486d774deedeb7af2db0a420a529956799b96bda5a7fc34", at: "2026-11-14T11:49:25Z", fact: "b927ae15bb392e35c8d8ec1f51f65ef8790a7bf3f9c3df73c667c6e19970e49d" }
    - id: 2006-finalist
      at: { section: "2006 finalist" }
      source: wp-wca
      mode: pinned
      extract: { kind: md-section, heading: "History" }
      pin: { sha256: "ad6cfac698fd3f7e1caeac9e5c9d85bb7a81d7a91f37eafb7c6beb8487d1b4a1", rev: "sha256:b3c22386df2501b53486d774deedeb7af2db0a420a529956799b96bda5a7fc34", at: "2026-11-14T11:49:25Z", fact: "daba165b6a598307307fce78b8bdbe9f0b5aa52e7ff23d7f2dd5ce24ac8a4e1c" }
    - id: 2016-announcement
      at: { section: "2016 announcement" }
      source: wp-nd
      mode: pinned
      extract: { kind: text-between, start: "Model code | ND", end: "## Overview" }
      pin: { sha256: "a44c6b9e398b671c4fda72126a5de7f86ed2aeb93c118adf8d006c2a8dc6acf7", rev: "sha256:e1a829d55fb41d71df271f5207d5dd8fcd9f6094cc6fcf9771fadcb1a335acc7", at: "2026-11-14T11:49:25Z", fact: "6b5b9855db43a0f5d9bfa18f4fb1b98e5344f6816b0e0a6855aa660fc6bcf9c3" }
---

# World Car Awards: Mazda MX-5

## 2016 winners table

2016: the Mazda MX-5 is listed under both World Car of the Year and World Car Design of the Year. [^wp-wca]

## 2006 finalist

For 2006 the BMW 3 Series, Mazda MX-5 and Porsche Cayman were the top three finalists. [^wp-wca]

## 2016 announcement

On 24 March 2016 the MX-5 was named World Car of the Year and World Car Design of the Year at the New York International Auto Show, the second Mazda to win after the Mazda2 in 2008. [^wp-nd]

## Related

- [MX-5 (ND), 2015–present](/generations/nd.md)
- [2016 Mazda MX-5](/model-years/2016.md)
- [Car of the Year Japan](/awards/car-of-the-year-japan.md)


[^wp-wca]: Wikipedia, "World Car Awards", permanent revision 1374901028 (2026-09-14): <https://en.wikipedia.org/w/index.php?title=World_Car_Awards&oldid=1374901028>
[^wp-nd]: Wikipedia, "Mazda MX-5 (ND)", permanent revision 1382278464 (2026-10-27): <https://en.wikipedia.org/w/index.php?title=Mazda_MX-5_(ND)&oldid=1382278464>
