---
type: Engine
title: "Mazda Skyactiv-G 1.5 L and 2.0 L in the MX-5"
description: "The Skyactiv-G P5-VPS 1.5 L and PE-VPS 2.0 L engines of the ND MX-5."
resource: "https://en.wikipedia.org/w/index.php?title=Mazda_MX-5_(ND)&oldid=1382278464"
tags: [mazda, mx-5, miata, engine, skyactiv]
aliases: ["Skyactiv-G", "Skyactiv", "P5-VPS", "PE-VPS", "1.5 Skyactiv", "2.0 Skyactiv"]
status: stable
sources:
  - id: wp-nd
    resource: "https://en.wikipedia.org/w/index.php?title=Mazda_MX-5_(ND)&oldid=1382278464"
    title: "Wikipedia, \"Mazda MX-5 (ND)\", permanent revision 1382278464 (2026-10-27)"
  - id: wp-cup
    resource: "https://en.wikipedia.org/w/index.php?title=Mazda_MX-5_Cup&oldid=1385048255"
    title: "Wikipedia, \"Mazda MX-5 Cup\", permanent revision 1385048255 (2026-11-11)"
x-silica:
  v: 1
  sources:
    wp-nd: { kind: http, url: "https://en.wikipedia.org/w/index.php?title=Mazda_MX-5_(ND)&oldid=1382278464" }
    wp-cup: { kind: http, url: "https://en.wikipedia.org/w/index.php?title=Mazda_MX-5_Cup&oldid=1385048255" }
  facts:
    - id: variants
      at: { section: "Variants" }
      source: wp-nd
      mode: pinned
      extract: { kind: text-between, start: "Engine |", end: "Power output |" }
      pin: { sha256: "43b5d609e5b343084657156d6ffb1cd7063e0cd7249915f0f0ed8bcecd129683", rev: "sha256:e1a829d55fb41d71df271f5207d5dd8fcd9f6094cc6fcf9771fadcb1a335acc7", at: "2026-11-14T11:49:25Z", fact: "2fa018b10961f8b0d1a5daaf1a05f2a6f02d01e918f5cf7d69d0664e004f4c62" }
    - id: specification-table
      at: { section: "Specification table" }
      source: wp-nd
      mode: pinned
      extract: { kind: md-section, heading: "Specifications" }
      pin: { sha256: "4e5bdeeca57d2e67a4163a5a351d9c597a4147b7ca91cb14ac98e37294435e92", rev: "sha256:e1a829d55fb41d71df271f5207d5dd8fcd9f6094cc6fcf9771fadcb1a335acc7", at: "2026-11-14T11:49:25Z", fact: "9b2976b1948541271f768768ae2bd7527f1971f349e51d726728c512ad771041" }
    - id: 2018-revision
      at: { section: "2018 revision" }
      source: wp-nd
      mode: pinned
      extract: { kind: md-section, heading: "2018 update" }
      pin: { sha256: "f27ec33fa84f1d99a0013b96d08473c3358d7733e47ddca3d191cf0b64579aec", rev: "sha256:e1a829d55fb41d71df271f5207d5dd8fcd9f6094cc6fcf9771fadcb1a335acc7", at: "2026-11-14T11:49:25Z", fact: "049b67c3a65bb697875d1f8cc0c71917b78bd147b6cef689689bb04db0bd96e3" }
    - id: 12r-engine
      at: { section: "12R engine" }
      source: wp-nd
      mode: pinned
      extract: { kind: md-section, heading: "Mazda Spirit Racing Roadster 12R" }
      pin: { sha256: "6bbe2d29d4b862e4e11ff3efca5fb6d32c51a1c387f44c2bce1df0e500c95e38", rev: "sha256:e1a829d55fb41d71df271f5207d5dd8fcd9f6094cc6fcf9771fadcb1a335acc7", at: "2026-11-14T11:49:25Z", fact: "0e0c61d8bc3937a66389f1a87c8d7f17644eb24e9287603881b3c1c62380bd07" }
    - id: in-the-mx-5-cup
      at: { section: "In the MX-5 Cup" }
      source: wp-cup
      mode: pinned
      extract: { kind: md-section, heading: "2016–present" }
      pin: { sha256: "fc3ffd48a8eb31ac4d4a7be3c917df7bd2fb964b861ae1927f18e5264597c9fa", rev: "sha256:40fe23051a8cb7a4140c850fd875a14ac3a84e8ff9c1122c184b6fb8d89d3575", at: "2026-11-14T11:49:25Z", fact: "6565c58ea5f5734ea88a0acca54ea86f42135e703ac82a1c83be0e7a648e78b8" }
---

# Mazda Skyactiv-G 1.5 L and 2.0 L in the MX-5

## Variants

1.5 L Skyactiv-G (P5-VPS) and 2.0 L Skyactiv-G (PE-VPS), both DOHC I4. [^wp-nd]

## Specification table

1.5 L: 1,496 cc, 96 kW (129 hp; 131 PS), 150 N⋅m. 2.0 L: 1,998 cc, 118 kW (158 hp; 160 PS) and 200 N⋅m (2015–2018), then 135 kW (181 hp; 184 PS) and 205 N⋅m (2019–). [^wp-nd]

## 2018 revision

For the 2019 model year the 2.0-litre was revised to 135 kW (181 hp; 184 PS) and 205 N⋅m (151 lb⋅ft), with the redline increased to 7,500 rpm. [^wp-nd]

## 12R engine

The Spirit Racing Roadster 12R's 2.0-litre Skyactiv-G delivers 197 hp (147 kW; 200 PS) at 7,000 rpm and 159 lb⋅ft (216 N⋅m) at 4,000 rpm, with a revised intake system and lightweight pistons. [^wp-nd]

## In the MX-5 Cup

MX-5 Cup cars since 2016 use the 2.0 L Skyactiv-G (PE-VPS) I4. [^wp-cup]

## Related

- [MX-5 (ND), 2015–present](/generations/nd.md)
- [MX-5 ND1, model years 2016–2018](/revisions/nd1.md)
- [MX-5 ND2 (2018 update), model years 2019–2023](/revisions/nd2.md)
- [MX-5 ND3 (2024 update), model years 2024–present](/revisions/nd3.md)


[^wp-nd]: Wikipedia, "Mazda MX-5 (ND)", permanent revision 1382278464 (2026-10-27): <https://en.wikipedia.org/w/index.php?title=Mazda_MX-5_(ND)&oldid=1382278464>
[^wp-cup]: Wikipedia, "Mazda MX-5 Cup", permanent revision 1385048255 (2026-11-11): <https://en.wikipedia.org/w/index.php?title=Mazda_MX-5_Cup&oldid=1385048255>
