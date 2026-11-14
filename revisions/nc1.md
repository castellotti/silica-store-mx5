---
type: Vehicle Revision
title: "MX-5 NC1, model years 2006–2008"
description: "NC1 revision of the NC MX-5: launch phase: engines, chassis, PRHT and special editions."
tags: [mazda, mx-5, miata, nc, nc1]
aliases: ["NC1", "early NC", "pre-facelift NC"]
status: stable
sources:
  - id: wp-nc
    resource: "https://en.wikipedia.org/w/index.php?title=Mazda_MX-5_(NC)&oldid=1381436898"
    title: "Wikipedia, \"Mazda MX-5 (NC)\", permanent revision 1381436898 (2026-10-22)"
x-silica:
  v: 1
  sources:
    wp-nc: { kind: http, url: "https://en.wikipedia.org/w/index.php?title=Mazda_MX-5_(NC)&oldid=1381436898" }
  facts:
    - id: model-years
      at: { section: "Model years" }
      source: wp-nc
      mode: pinned
      extract: { kind: text-between, start: "Model years |", end: "## 2009 facelift (NC2)" }
      pin: { sha256: "53a865d0a20c31ff4f5d7ba50603ef19b5d4f90e53808ceadc6d572c920651ef", rev: "sha256:dee0e9956663fb8260f2f41bb55994564bf060b51af210ed156f5bf0c6589418", at: "2026-11-14T11:49:25Z", fact: "6fd5bc9f1688f2d652cd5537e9d044591fca8a80998d7296237b0967bc3917c8" }
    - id: design
      at: { section: "Design" }
      source: wp-nc
      mode: pinned
      extract: { kind: md-section, heading: "2005—2008 (NC1)" }
      pin: { sha256: "eb5583dd773fb52a839635296607b031b5ed491267128ed8423d5f5ceffe5dc8", rev: "sha256:dee0e9956663fb8260f2f41bb55994564bf060b51af210ed156f5bf0c6589418", at: "2026-11-14T11:49:25Z", fact: "e58c3bb3cc87bc35d2e0b5df224a0e77d92f413b1da2799e29f2b8edb424fb5b" }
    - id: engine
      at: { section: "Engine" }
      source: wp-nc
      mode: pinned
      extract: { kind: md-section, heading: "2005—2008 (NC1)" }
      pin: { sha256: "eb5583dd773fb52a839635296607b031b5ed491267128ed8423d5f5ceffe5dc8", rev: "sha256:dee0e9956663fb8260f2f41bb55994564bf060b51af210ed156f5bf0c6589418", at: "2026-11-14T11:49:25Z", fact: "67f7b07e25ed00cb95d491037bed20331f6db097184dbc85dec1ca2e3a7314e2" }
    - id: features
      at: { section: "Features" }
      source: wp-nc
      mode: pinned
      extract: { kind: md-section, heading: "2005—2008 (NC1)" }
      pin: { sha256: "eb5583dd773fb52a839635296607b031b5ed491267128ed8423d5f5ceffe5dc8", rev: "sha256:dee0e9956663fb8260f2f41bb55994564bf060b51af210ed156f5bf0c6589418", at: "2026-11-14T11:49:25Z", fact: "6ba359c9c639e3f9f78e480f5fca9802e840c1f9bff82a5429a5495dee1c3065" }
    - id: power-retractable-hard-top
      at: { section: "Power Retractable Hard Top" }
      source: wp-nc
      mode: pinned
      extract: { kind: md-section, heading: "Power Retractable Hard Top" }
      pin: { sha256: "c7994c4bc04331bb18b4079d5a70451a253a24c09b44f3c9b0cdd77665a40102", rev: "sha256:dee0e9956663fb8260f2f41bb55994564bf060b51af210ed156f5bf0c6589418", at: "2026-11-14T11:49:25Z", fact: "1ca68dce5a6df81bbabc22699cc5ef9a1643b3074a963ac10ea7856b490744e9" }
    - id: trims
      at: { section: "Trims" }
      source: wp-nc
      mode: pinned
      extract: { kind: md-section, heading: "Transmissions" }
      pin: { sha256: "108f8b4426d163e09fc1f36a1ee431c61f734b8f9a1a4cf604b8a0546b8a2334", rev: "sha256:dee0e9956663fb8260f2f41bb55994564bf060b51af210ed156f5bf0c6589418", at: "2026-11-14T11:49:25Z", fact: "4f488403648e0032703b862ab2f61267cae3118ca4ddf33584e81f3043f2129d" }
    - id: special-editions
      at: { section: "Special editions" }
      source: wp-nc
      mode: pinned
      extract: { kind: md-section, heading: "Special editions (2005—2008)" }
      pin: { sha256: "5e063b137e5e1aa00f8d34c87202d13de4665a1a27fa1521bdd40c4f1903af63", rev: "sha256:dee0e9956663fb8260f2f41bb55994564bf060b51af210ed156f5bf0c6589418", at: "2026-11-14T11:49:25Z", fact: "6d6b09b064c3d0c7abbc4f4da9baf80ebfe4859e3ad731c9d88d120273bd2fba" }
---

# MX-5 NC1, model years 2006–2008

## Model years

Third generation (NC), first phase (NC1). Model years 2006–2015 (North America) for the generation. [^wp-nc]

## Design

Exterior by Yasushi Nakamuta, previewed by the 2003 Mazda Ibuki concept; chief designer Moray Callum; no components reused from the NB except some turn signal lights and differential internals. [^wp-nc]

## Engine

US: 2.0 L MZR LF-VE DOHC inline four-cylinder, 124 kW (166 hp) and 190 N⋅m (140 lbf⋅ft) with the 5-speed or 6-speed manual, or 118 kW (158 hp) with the optional 6-speed automatic. Europe also had a 1.8 L MZR L8-VE rated at 94 kW (126 bhp) and 167 N⋅m (123 lbf⋅ft). [^wp-nc]

## Features

Front wishbone and rear multilink suspension shared with the Mazda RX-8; traction control and stability control; optional 6-speed automatic with paddle shifters; skidpad 0.90g (Car and Driver). [^wp-nc]

## Power Retractable Hard Top

Debuted in July 2006; first deliveries in late August 2006; adds 36 kg (79 lb) to a comparably equipped soft-top. [^wp-nc]

## Trims

US trims named for the NC generation include SV, Sport and Grand Touring; Canada: GX, GS and GT. [^wp-nc]

## Special editions

3rd Generation Limited (3,500 worldwide), MS-R Package (2007), 2008 Special Edition in Icy Blue, MX-5 Niseko (Europe, 2008). [^wp-nc]

## Related

- [MX-5 (NC), 2005–2015](/generations/nc.md)
- [2006 Mazda MX-5](/model-years/2006.md)
- [2007 Mazda MX-5](/model-years/2007.md)
- [2008 Mazda MX-5](/model-years/2008.md)


[^wp-nc]: Wikipedia, "Mazda MX-5 (NC)", permanent revision 1381436898 (2026-10-22): <https://en.wikipedia.org/w/index.php?title=Mazda_MX-5_(NC)&oldid=1381436898>
