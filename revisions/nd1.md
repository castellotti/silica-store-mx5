---
type: Vehicle Revision
title: "MX-5 ND1, model years 2016–2018"
description: "ND1 revision of the ND MX-5: launch, engines, RF and weights."
tags: [mazda, mx-5, miata, nd, nd1]
aliases: ["ND1", "early ND", "pre-2019 ND"]
status: stable
sources:
  - id: wp-nd
    resource: "https://en.wikipedia.org/w/index.php?title=Mazda_MX-5_(ND)&oldid=1382278464"
    title: "Wikipedia, \"Mazda MX-5 (ND)\", permanent revision 1382278464 (2026-10-27)"
x-silica:
  v: 1
  sources:
    wp-nd: { kind: http, url: "https://en.wikipedia.org/w/index.php?title=Mazda_MX-5_(ND)&oldid=1382278464" }
  facts:
    - id: introduction
      at: { section: "Introduction" }
      source: wp-nd
      mode: pinned
      extract: { kind: text-between, start: "Model code | ND", end: "## Overview" }
      pin: { sha256: "a44c6b9e398b671c4fda72126a5de7f86ed2aeb93c118adf8d006c2a8dc6acf7", rev: "sha256:e1a829d55fb41d71df271f5207d5dd8fcd9f6094cc6fcf9771fadcb1a335acc7", at: "2026-11-14T11:31:46Z", fact: "0d071b1bc9c733e10b5c056e580bf74dc57fcf26fe9612c817d7f3b969887f77" }
    - id: engine
      at: { section: "Engine" }
      source: wp-nd
      mode: pinned
      extract: { kind: md-section, heading: "Overview" }
      pin: { sha256: "bebf0ec4eb35c8406a403ebcbeed2b186c937329dcda930bae06ad1c15b16b7f", rev: "sha256:e1a829d55fb41d71df271f5207d5dd8fcd9f6094cc6fcf9771fadcb1a335acc7", at: "2026-11-14T11:31:46Z", fact: "93246a2d88b0a072104a28da4e2d579bdfd16025ff0bc2992e238257d323bcd8" }
    - id: engine-european-table
      at: { section: "Engine (European specification table)" }
      source: wp-nd
      mode: pinned
      extract: { kind: text-between, start: "lighter than its predecessor", end: "## Safety" }
      pin: { sha256: "dff9f9b82ef93c0cd7422e654e3a20b8b844062d7363eef62a5128d495a96eb5", rev: "sha256:e1a829d55fb41d71df271f5207d5dd8fcd9f6094cc6fcf9771fadcb1a335acc7", at: "2026-11-14T11:31:46Z", fact: "3dfc948739159841a23266134fcd1b3730c3f77b7462563297bde494eadbc39f" }
    - id: changes
      at: { section: "Changes" }
      source: wp-nd
      mode: pinned
      extract: { kind: md-section, heading: "Overview" }
      pin: { sha256: "bebf0ec4eb35c8406a403ebcbeed2b186c937329dcda930bae06ad1c15b16b7f", rev: "sha256:e1a829d55fb41d71df271f5207d5dd8fcd9f6094cc6fcf9771fadcb1a335acc7", at: "2026-11-14T11:31:46Z", fact: "e2762bf2e906889c15f91d79a1f4c0784bc3a8245609e3b8e79c1f147cc3fe48" }
    - id: mx-5-rf
      at: { section: "MX-5 RF" }
      source: wp-nd
      mode: pinned
      extract: { kind: md-section, heading: "MX-5 RF" }
      pin: { sha256: "621b0269e460ed91ac5a644b8a83b90d30567c1ae3be74b8c0b335948c5ac58e", rev: "sha256:e1a829d55fb41d71df271f5207d5dd8fcd9f6094cc6fcf9771fadcb1a335acc7", at: "2026-11-14T11:31:46Z", fact: "0f2a10b3e25cc064a7d48ffc5e719d7bf984acfe9cd4372315fdad18fb65e665" }
    - id: curb-weight
      at: { section: "Curb weight" }
      source: wp-nd
      mode: pinned
      extract: { kind: text-between, start: "Curb weight |", end: "Chronology" }
      pin: { sha256: "d976e3079bc901f5f72edd08ee863987a525791edcdeaada8987a0fbddb148de", rev: "sha256:e1a829d55fb41d71df271f5207d5dd8fcd9f6094cc6fcf9771fadcb1a335acc7", at: "2026-11-14T11:31:46Z", fact: "bedc3729380290874006ef3c58913bf945573da75e0bbf0ba01719dbe25f7090" }
    - id: trims
      at: { section: "Trims" }
---

# MX-5 ND1, model years 2016–2018

## Introduction

Unveiled on 3 September 2014 in the United States and Spain and on 4 September 2014 in Japan; manufactured in Hiroshima since 4 March 2015. [^wp-nd]

## Engine

Skyactiv-G direct-injection petrol engines: a 1.5 L of 96 kW (129 hp; 131 PS) in base models; pre-2019 American and Canadian models use the 1,998 cc 2.0 L rated at 116 kW (155 hp; 157 PS) at 6000 rpm and 201 N⋅m (148 lb⋅ft) at 4600 rpm. [^wp-nd]

## Engine (European specification table)

2.0 L, 2015–2018: 118 kW (158 hp; 160 PS) and 200 N⋅m (148 lbf⋅ft); the Overview gives 201 N⋅m (148 lb⋅ft) for pre-2019 American and Canadian models. [^wp-nd]

## Changes

105 mm shorter and 100 kg lighter than the NC; Electric Power Assisted Steering replaced hydraulic power steering; six-speed manual or six-speed automatic; manually operated fabric roof. [^wp-nd]

## MX-5 RF

Announced in late 2016 with a rigid roof and buttresses; a full-colour circular digital gauge; 'Machine Grey Mica' paint introduced. [^wp-nd]

## Curb weight

ND1 1.5 L manual base (S/Sport): 990 kg (2,183 lb); automatic adds 20 kg (44 lb); RF adds 50 kg (110 lb). [^wp-nd]

## Trims

_Not found._

## Related

- [MX-5 (ND), 2015–present](/generations/nd.md)
- [2016 Mazda MX-5](/model-years/2016.md)
- [2017 Mazda MX-5](/model-years/2017.md)
- [2018 Mazda MX-5](/model-years/2018.md)


[^wp-nd]: Wikipedia, "Mazda MX-5 (ND)", permanent revision 1382278464 (2026-10-27): <https://en.wikipedia.org/w/index.php?title=Mazda_MX-5_(ND)&oldid=1382278464>
