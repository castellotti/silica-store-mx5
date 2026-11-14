---
type: Vehicle Revision
title: "MX-5 ND2 (2018 update), model years 2019–2023"
description: "ND2 revision of the ND MX-5: 2019 engine update, trims, fuel economy and the 2022 change."
tags: [mazda, mx-5, miata, nd, nd2]
aliases: ["ND2", "2019 update", "2018 update", "GT-S"]
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
    - id: introduction-and-changes
      at: { section: "Introduction and changes" }
      source: wp-nd
      mode: pinned
      extract: { kind: md-section, heading: "2018 update" }
      pin: { sha256: "f27ec33fa84f1d99a0013b96d08473c3358d7733e47ddca3d191cf0b64579aec", rev: "sha256:e1a829d55fb41d71df271f5207d5dd8fcd9f6094cc6fcf9771fadcb1a335acc7", at: "2026-11-14T11:49:25Z", fact: "79ade14591db32968839718746b34e1a2748b0ecc2a3fc507303ae7b2ff024c2" }
    - id: engine
      at: { section: "Engine" }
      source: wp-nd
      mode: pinned
      extract: { kind: md-section, heading: "2018 update" }
      pin: { sha256: "f27ec33fa84f1d99a0013b96d08473c3358d7733e47ddca3d191cf0b64579aec", rev: "sha256:e1a829d55fb41d71df271f5207d5dd8fcd9f6094cc6fcf9771fadcb1a335acc7", at: "2026-11-14T11:49:25Z", fact: "a388e38b2bda628f7c3b57553b85a0171496acc3753b64809c360ccc19a391bf" }
    - id: trims
      at: { section: "Trims" }
      source: wp-nd
      mode: pinned
      extract: { kind: md-section, heading: "2018 update" }
      pin: { sha256: "f27ec33fa84f1d99a0013b96d08473c3358d7733e47ddca3d191cf0b64579aec", rev: "sha256:e1a829d55fb41d71df271f5207d5dd8fcd9f6094cc6fcf9771fadcb1a335acc7", at: "2026-11-14T11:49:25Z", fact: "23369d037c6794f15c9083b2ab3b86c6f5efb163fa3a841dc3561a7ae294ad37" }
    - id: fuel-economy
      at: { section: "Fuel economy" }
      source: wp-nd
      mode: pinned
      extract: { kind: md-section, heading: "2018 update" }
      pin: { sha256: "f27ec33fa84f1d99a0013b96d08473c3358d7733e47ddca3d191cf0b64579aec", rev: "sha256:e1a829d55fb41d71df271f5207d5dd8fcd9f6094cc6fcf9771fadcb1a335acc7", at: "2026-11-14T11:49:25Z", fact: "a1ded75c1c3f36a350db7ccf6f97e0404f19642d551353bcba5e46f041cc37a5" }
    - id: 2022-change
      at: { section: "2022 change" }
      source: wp-nd
      mode: pinned
      extract: { kind: md-section, heading: "2021 update" }
      pin: { sha256: "f450cb44b88df2ecdb15564e2cc3c9424b0403a0997c31d67eac38937f8ce3d3", rev: "sha256:e1a829d55fb41d71df271f5207d5dd8fcd9f6094cc6fcf9771fadcb1a335acc7", at: "2026-11-14T11:49:25Z", fact: "50af8b3d0f1bc6e8622bac80d5a79ecd1e7ce895105ed09b1c76cdcff979f3f0" }
    - id: mx-5-cup-car
      at: { section: "MX-5 Cup car" }
      source: wp-cup
      mode: pinned
      extract: { kind: md-section, heading: "2016–present" }
      pin: { sha256: "fc3ffd48a8eb31ac4d4a7be3c917df7bd2fb964b861ae1927f18e5264597c9fa", rev: "sha256:40fe23051a8cb7a4140c850fd875a14ac3a84e8ff9c1122c184b6fb8d89d3575", at: "2026-11-14T11:49:25Z", fact: "c1e192b391203899495fc58a6729e116d8018d3cca5f739e76b4bee9a68bd552" }
    - id: curb-weight
      at: { section: "Curb weight" }
      source: wp-nd
      mode: pinned
      extract: { kind: text-between, start: "Curb weight |", end: "Chronology" }
      pin: { sha256: "d976e3079bc901f5f72edd08ee863987a525791edcdeaada8987a0fbddb148de", rev: "sha256:e1a829d55fb41d71df271f5207d5dd8fcd9f6094cc6fcf9771fadcb1a335acc7", at: "2026-11-14T11:49:25Z", fact: "6dd99dabeb258e2b633fed9ffef01f2ee215ca5c304c73c3946bce5a30560ab3" }
---

# MX-5 ND2 (2018 update), model years 2019–2023

## Introduction and changes

Introduced in late 2018 for the 2019 model year. Telescoping steering column, standard reverse camera, reworked door opening mechanism, revised seat controls and redesigned cupholders; burgundy soft top and black 17-inch wheels; dual-mass flywheel. [^wp-nd]

## Engine

2.0 L revised to 135 kW (181 hp; 184 PS) and 205 N⋅m (151 lb⋅ft), redline 7,500 rpm, with a dual-mass flywheel; in North America the ratings are at 7,000 rpm and 4000 rpm. [^wp-nd]

## Trims

US: Sport, Club and Grand Touring (Canada: GS, GS-P and GT); a GT-S trim was introduced in 2019 and its features became standard on the GT in 2020. [^wp-nd]

## Fuel economy

Claimed (North America, 2.0 L): manual 9.0 L/100 km (26.1 mpg‑US) city and 7.0 L/100 km (33.6 mpg‑US) highway; automatic 9.0 L/100 km (26.1 mpg‑US) city and 6.6 L/100 km (35.6 mpg‑US) highway. [^wp-nd]

## 2022 change

Mazda said in December 2021 that the 2022 MX-5 would brake the inner rear wheel to improve steering and body roll during hard cornering. [^wp-nd]

## MX-5 Cup car

The MX-5 Cup used ND1 cars from 2016 to 2018 and added an updated ND2 class in 2019, with a Bosch ECU, a 7,500rpm limit and 181 horsepower. [^wp-cup]

## Curb weight

The infobox base figure is for the 1.5 L manual (S/Sport), not the engine of American and Canadian models: ND2/ND3 add 8 kg (18 lb) to the ND1 base of 990 kg (2,183 lb); automatic adds 20 kg (44 lb); RF adds 50 kg (110 lb). [^wp-nd]

## Related

- [MX-5 (ND), 2015–present](/generations/nd.md)
- [2019 Mazda MX-5](/model-years/2019.md)
- [2020 Mazda MX-5](/model-years/2020.md)
- [2021 Mazda MX-5](/model-years/2021.md)
- [2022 Mazda MX-5](/model-years/2022.md)
- [2023 Mazda MX-5](/model-years/2023.md)


[^wp-nd]: Wikipedia, "Mazda MX-5 (ND)", permanent revision 1382278464 (2026-10-27): <https://en.wikipedia.org/w/index.php?title=Mazda_MX-5_(ND)&oldid=1382278464>
[^wp-cup]: Wikipedia, "Mazda MX-5 Cup", permanent revision 1385048255 (2026-11-11): <https://en.wikipedia.org/w/index.php?title=Mazda_MX-5_Cup&oldid=1385048255>
