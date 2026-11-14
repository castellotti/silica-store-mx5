---
type: Vehicle Revision
title: "MX-5 NA2 (1.8 L), model years 1994–1997"
description: "NA2 revision of the NA MX-5: model years, 1.8 L engine, weight and the R Package."
tags: [mazda, mx-5, miata, na, na2]
aliases: ["NA2", "NA 1.8", "1.8 NA", "late NA", "BP Miata"]
status: stable
sources:
  - id: wp-na
    resource: "https://en.wikipedia.org/w/index.php?title=Mazda_MX-5_(NA)&oldid=1381587107"
    title: "Wikipedia, \"Mazda MX-5 (NA)\", permanent revision 1381587107 (2026-10-23)"
  - id: wp-b-engine
    resource: "https://en.wikipedia.org/w/index.php?title=Mazda_B_engine&oldid=1381332751"
    title: "Wikipedia, \"Mazda B engine\", permanent revision 1381332751 (2026-10-21)"
x-silica:
  v: 1
  sources:
    wp-na: { kind: http, url: "https://en.wikipedia.org/w/index.php?title=Mazda_MX-5_(NA)&oldid=1381587107" }
    wp-b-engine: { kind: http, url: "https://en.wikipedia.org/w/index.php?title=Mazda_B_engine&oldid=1381332751" }
  facts:
    - id: model-years
      at: { section: "Model years" }
      source: wp-na
      mode: pinned
      extract: { kind: md-section, heading: "Overview" }
      pin: { sha256: "a0d213fd056719a2f8672977f7b1a4af05febb200f8ba079a11992b9339ebd46", rev: "sha256:334b67430ffe976b0d9ef21ff9aef5af2f81844f836b567463da81d5b162351c", at: "2026-11-14T11:31:46Z", fact: "a3e329fc79c0e628efac20a778699093007f8597e2e80ac939132e7649a912c3" }
    - id: changes
      at: { section: "Changes" }
      source: wp-na
      mode: pinned
      extract: { kind: md-section, heading: "Overview" }
      pin: { sha256: "a0d213fd056719a2f8672977f7b1a4af05febb200f8ba079a11992b9339ebd46", rev: "sha256:334b67430ffe976b0d9ef21ff9aef5af2f81844f836b567463da81d5b162351c", at: "2026-11-14T11:31:46Z", fact: "f3ea044ebadd78a3f61f8ba35ffcb0305bffa56dc97ec8d35fdcb9877c37ae9c" }
    - id: engine
      at: { section: "Engine" }
      source: wp-na
      mode: pinned
      extract: { kind: md-section, heading: "Overview" }
      pin: { sha256: "a0d213fd056719a2f8672977f7b1a4af05febb200f8ba079a11992b9339ebd46", rev: "sha256:334b67430ffe976b0d9ef21ff9aef5af2f81844f836b567463da81d5b162351c", at: "2026-11-14T11:31:46Z", fact: "55b21fa9675f3e1e1badfbd8d635830c3ad233e5083a7f729c2afada439f2130" }
    - id: torque-uk-table
      at: { section: "Torque rpm (UK table)" }
      source: wp-na
      mode: pinned
      extract: { kind: md-section, heading: "Specifications" }
      pin: { sha256: "c7d92f42deff68d8b68adc73b276ae65bb86ae7d6a62652802a80d41de662f99", rev: "sha256:334b67430ffe976b0d9ef21ff9aef5af2f81844f836b567463da81d5b162351c", at: "2026-11-14T11:31:46Z", fact: "17f9748cc78f19f5a6859a4fdb13418643bd0fe0d0e7846b0ab28b91944f1625" }
    - id: europe-1-6-na-article
      at: { section: "European 1.6 L (NA article)" }
      source: wp-na
      mode: pinned
      extract: { kind: md-section, heading: "Overview" }
      pin: { sha256: "a0d213fd056719a2f8672977f7b1a4af05febb200f8ba079a11992b9339ebd46", rev: "sha256:334b67430ffe976b0d9ef21ff9aef5af2f81844f836b567463da81d5b162351c", at: "2026-11-14T11:31:46Z", fact: "a19412528ce7e84474253f7a8106ceaa7384f090bdcd4b834ae64c63dc647782" }
    - id: europe-1-6-uk-table
      at: { section: "European 1.6 L (UK table)" }
      source: wp-na
      mode: pinned
      extract: { kind: md-section, heading: "Specifications" }
      pin: { sha256: "c7d92f42deff68d8b68adc73b276ae65bb86ae7d6a62652802a80d41de662f99", rev: "sha256:334b67430ffe976b0d9ef21ff9aef5af2f81844f836b567463da81d5b162351c", at: "2026-11-14T11:31:46Z", fact: "81c3c81bc1588935404cd0357f84744b2345f6aa594cbaba2e808d7b26867177" }
    - id: europe-1-6-b-engine-article
      at: { section: "European 1.6 L (B engine article)" }
      source: wp-b-engine
      mode: pinned
      extract: { kind: md-section, heading: "B6ZE(RS)" }
      pin: { sha256: "9738e906d17cc319b690a4d28e8765b2c88eca38f0fc259bb161e9ca9a1ddee9", rev: "sha256:839bdf0457d7d63505f0e4dac172dcde8ebe76503362a3426c0fa24b6ade1c0f", at: "2026-11-14T11:31:46Z", fact: "06dba7f410f56f5fc64b8357aff2cfaf83839b20bdffe583f44d444707088116" }
    - id: curb-weight
      at: { section: "Curb weight" }
      source: wp-na
      mode: pinned
      extract: { kind: md-section, heading: "Overview" }
      pin: { sha256: "a0d213fd056719a2f8672977f7b1a4af05febb200f8ba079a11992b9339ebd46", rev: "sha256:334b67430ffe976b0d9ef21ff9aef5af2f81844f836b567463da81d5b162351c", at: "2026-11-14T11:31:46Z", fact: "d9df45f84f95ca110fdb151daabd16de590a1d6b4f9c729d8d2e3b79631ccf1c" }
    - id: trims
      at: { section: "Trims" }
      source: wp-na
      mode: pinned
      extract: { kind: md-section, heading: "Overview" }
      pin: { sha256: "a0d213fd056719a2f8672977f7b1a4af05febb200f8ba079a11992b9339ebd46", rev: "sha256:334b67430ffe976b0d9ef21ff9aef5af2f81844f836b567463da81d5b162351c", at: "2026-11-14T11:31:46Z", fact: "965ffd159ece09bd18bd17a7d2f98be332bae233909cdf2dfb6154faaa5a2dfe" }
---

# MX-5 NA2 (1.8 L), model years 1994–1997

## Model years

From the freshening for the 1994 model year until the NA was phased out after the 1997 model year; 400 Berkeley models were sold only in the UK in 1998. [^wp-na]

## Changes

1994 freshening: 1,839 cc BP-ZE engine, dual airbags in a redesigned dashboard, a Mazda badge on the front fascia in the US, a Torsen limited-slip differential in some markets, and chassis bracing for side-impact standards, including a track bar between the seatbelt towers. [^wp-na]

## Engine

1,839 cc BP-ZE: 96 kW (129 bhp) at 6,500 rpm and 149 N⋅m (110 lbf⋅ft) at 5,500 rpm, raised to 99 kW (133 bhp) and 155 N⋅m (114 lbf⋅ft) for the 1996 model year. [^wp-na]

## Torque rpm (UK table)

UK 1.8i, 1994–1995: 95 kW (128 hp) @ 6,500 and 149 N⋅m (110 ft⋅lbf) @ 5,000, a lower torque rpm than the Overview text gives. [^wp-na]

## European 1.6 L

Sources give slightly different outputs for the detuned European 1.6 L sold alongside the 1.8 L.

### European 1.6 L (NA article)

In Europe the 1.6 L continued as a lower-cost option, detuned to 66 kW (89 bhp). [^wp-na]

### European 1.6 L (UK table)

UK 1.6i, 1994–1998: 66 kW (88 hp). [^wp-na]

### European 1.6 L (B engine article)

Later European version (1994–1997): 90 hp (66 kW) at 6,500 rpm and 129 N⋅m (95 lb⋅ft) at 5,500 rpm. [^wp-b-engine]

## Curb weight

Base weight 990 kg (2,180 lb) after the 1994 changes. [^wp-na]

## Trims

US: the base model with the A Package, B Package and C Package continued; the R Package, introduced in 1994, added Bilstein shocks, stiffer sway bars, retuned springs, underbody spoilers and a Torsen LSD, and was not available with power steering, leather or an automatic transmission. Annual special editions were formalized as M Editions. [^wp-na]

## Related

- [MX-5 (NA), 1989–1997](/generations/na.md)
- [1994 Mazda MX-5](/model-years/1994.md)
- [1995 Mazda MX-5](/model-years/1995.md)
- [1996 Mazda MX-5](/model-years/1996.md)
- [1997 Mazda MX-5](/model-years/1997.md)


[^wp-na]: Wikipedia, "Mazda MX-5 (NA)", permanent revision 1381587107 (2026-10-23): <https://en.wikipedia.org/w/index.php?title=Mazda_MX-5_(NA)&oldid=1381587107>
[^wp-b-engine]: Wikipedia, "Mazda B engine", permanent revision 1381332751 (2026-10-21): <https://en.wikipedia.org/w/index.php?title=Mazda_B_engine&oldid=1381332751>
