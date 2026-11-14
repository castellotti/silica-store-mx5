---
type: Vehicle Revision
title: "MX-5 NA1 (1.6 L), model years 1990–1993"
description: "NA1 revision of the NA MX-5: model years, engine, weight, trims and features."
tags: [mazda, mx-5, miata, na, na1]
aliases: ["NA1", "NA 1.6", "1.6 Miata", "early NA", "B6 Miata"]
status: stable
sources:
  - id: wp-na
    resource: "https://en.wikipedia.org/w/index.php?title=Mazda_MX-5_(NA)&oldid=1381587107"
    title: "Wikipedia, \"Mazda MX-5 (NA)\", permanent revision 1381587107 (2026-10-23)"
  - id: wp-mx5
    resource: "https://en.wikipedia.org/w/index.php?title=Mazda_MX-5&oldid=1384156481"
    title: "Wikipedia, \"Mazda MX-5\", permanent revision 1384156481 (2026-11-06)"
  - id: wp-b-engine
    resource: "https://en.wikipedia.org/w/index.php?title=Mazda_B_engine&oldid=1381332751"
    title: "Wikipedia, \"Mazda B engine\", permanent revision 1381332751 (2026-10-21)"
x-silica:
  v: 1
  sources:
    wp-na: { kind: http, url: "https://en.wikipedia.org/w/index.php?title=Mazda_MX-5_(NA)&oldid=1381587107" }
    wp-mx5: { kind: http, url: "https://en.wikipedia.org/w/index.php?title=Mazda_MX-5&oldid=1384156481" }
    wp-b-engine: { kind: http, url: "https://en.wikipedia.org/w/index.php?title=Mazda_B_engine&oldid=1381332751" }
  facts:
    - id: model-years
      at: { section: "Model years" }
      source: wp-na
      mode: pinned
      extract: { kind: md-section, heading: "Overview" }
      pin: { sha256: "a0d213fd056719a2f8672977f7b1a4af05febb200f8ba079a11992b9339ebd46", rev: "sha256:334b67430ffe976b0d9ef21ff9aef5af2f81844f836b567463da81d5b162351c", at: "2026-11-14T11:31:46Z", fact: "c503222135ce28842089563744213695b70823ea44a229511ecfbb548f8c5a1b" }
    - id: engine
      at: { section: "Engine" }
      source: wp-na
      mode: pinned
      extract: { kind: md-section, heading: "Overview" }
      pin: { sha256: "a0d213fd056719a2f8672977f7b1a4af05febb200f8ba079a11992b9339ebd46", rev: "sha256:334b67430ffe976b0d9ef21ff9aef5af2f81844f836b567463da81d5b162351c", at: "2026-11-14T11:31:46Z", fact: "391472786aa94e3513ab21f45b99a4c4f1c398ac851239e6790494e7935c378f" }
    - id: power-mx5-article
      at: { section: "Power (MX-5 article)" }
      source: wp-mx5
      mode: pinned
      extract: { kind: md-section, heading: "First generation – NA (1989–1997)" }
      pin: { sha256: "a57d5e15011f67f4002ba3f96cc445c70efabfc99d685b6402049b6ccae4c096", rev: "sha256:b96cb41d926071821490db5697fd311eccc0299e8afdf5870eae5f130f177006", at: "2026-11-14T11:31:46Z", fact: "e7c3741a1738f336cc954a2905786bfeaa6acab2b09dc4c43771611c1a1513ff" }
    - id: power-uk-table
      at: { section: "Power (UK table)" }
      source: wp-na
      mode: pinned
      extract: { kind: md-section, heading: "Specifications" }
      pin: { sha256: "c7d92f42deff68d8b68adc73b276ae65bb86ae7d6a62652802a80d41de662f99", rev: "sha256:334b67430ffe976b0d9ef21ff9aef5af2f81844f836b567463da81d5b162351c", at: "2026-11-14T11:31:46Z", fact: "2ddaa68344c0f15457a6e2e2e20b3b367d718ec5036428d65ef9e8d2bd432da5" }
    - id: power-b-engine-article
      at: { section: "Power (B engine article)" }
      source: wp-b-engine
      mode: pinned
      extract: { kind: md-section, heading: "B6ZE(RS)" }
      pin: { sha256: "9738e906d17cc319b690a4d28e8765b2c88eca38f0fc259bb161e9ca9a1ddee9", rev: "sha256:839bdf0457d7d63505f0e4dac172dcde8ebe76503362a3426c0fa24b6ade1c0f", at: "2026-11-14T11:31:46Z", fact: "ed26c02f8c800166f0c485d492f0c0236ee231c72a8f7bb3540d600b9993eadf" }
    - id: curb-weight-overview
      at: { section: "Curb weight (Overview text)" }
      source: wp-na
      mode: pinned
      extract: { kind: md-section, heading: "Overview" }
      pin: { sha256: "a0d213fd056719a2f8672977f7b1a4af05febb200f8ba079a11992b9339ebd46", rev: "sha256:334b67430ffe976b0d9ef21ff9aef5af2f81844f836b567463da81d5b162351c", at: "2026-11-14T11:31:46Z", fact: "565ce2f3d703e3a9fef51ac1fb7821ac87b0695e92495d74abbb4bb5c08cf49d" }
    - id: curb-weight-infobox
      at: { section: "Curb weight (infobox)" }
      source: wp-na
      mode: pinned
      extract: { kind: text-between, start: "Curb weight | ", end: "\n" }
      pin: { sha256: "b883903f9c430b131f1fb7aaa947c2730b1a9aeaaa4b7c687e77edd1dc93e400", rev: "sha256:334b67430ffe976b0d9ef21ff9aef5af2f81844f836b567463da81d5b162351c", at: "2026-11-14T11:31:46Z", fact: "2a6e710ce4f0350c21369db4a9283bb278b2bd68ca31d5d48abdd7cad81fb18b" }
    - id: weight-at-introduction
      at: { section: "Weight at introduction (MX-5 article)" }
      source: wp-mx5
      mode: pinned
      extract: { kind: md-section, heading: "Conception" }
      pin: { sha256: "bf33b1a053869ca15f5d26e36e1b6ecaf0eb47da2009a916a05e9766c073c05b", rev: "sha256:b96cb41d926071821490db5697fd311eccc0299e8afdf5870eae5f130f177006", at: "2026-11-14T11:31:46Z", fact: "64e7a0d1f975f69fcdea870eb9bcc74bbe6084ae8bea2e30ac1a2eb1db3947f1" }
    - id: performance
      at: { section: "Performance" }
      source: wp-na
      mode: pinned
      extract: { kind: md-section, heading: "Overview" }
      pin: { sha256: "a0d213fd056719a2f8672977f7b1a4af05febb200f8ba079a11992b9339ebd46", rev: "sha256:334b67430ffe976b0d9ef21ff9aef5af2f81844f836b567463da81d5b162351c", at: "2026-11-14T11:31:46Z", fact: "1352c9d565902e564768366b9e23fa99b7893ec9674eacfb20c6896b9a8f783f" }
    - id: trims
      at: { section: "Trims" }
      source: wp-na
      mode: pinned
      extract: { kind: md-section, heading: "Overview" }
      pin: { sha256: "a0d213fd056719a2f8672977f7b1a4af05febb200f8ba079a11992b9339ebd46", rev: "sha256:334b67430ffe976b0d9ef21ff9aef5af2f81844f836b567463da81d5b162351c", at: "2026-11-14T11:31:46Z", fact: "ff736e2812a5152948f24ef2f2a9677fb9f54ba334b95c568a278195d881eb46" }
    - id: features
      at: { section: "Features" }
      source: wp-mx5
      mode: pinned
      extract: { kind: md-section, heading: "First generation – NA (1989–1997)" }
      pin: { sha256: "a57d5e15011f67f4002ba3f96cc445c70efabfc99d685b6402049b6ccae4c096", rev: "sha256:b96cb41d926071821490db5697fd311eccc0299e8afdf5870eae5f130f177006", at: "2026-11-14T11:31:46Z", fact: "1d7d48768e4aaf206679b4e2f98d3027a622b5bd91f50ffd6475d615f8a3bd81" }
---

# MX-5 NA1 (1.6 L), model years 1990–1993

## Model years

First generation (NA), 1.6 L period. The NA was delivered from May 1989 as a 1990 model in the US and Canada; the 1.8 L engine arrived for the 1994 model year. [^wp-na]

## Engine

B6ZE(RS) 1.6 L, DOHC inline four-cylinder: 86 kW (115 bhp) at 6,500 rpm and 136 N⋅m (100 lbf⋅ft) at 5,500 rpm with the manual; tuned to 78.5 kW (105 bhp) at 6500 rpm with the optional automatic. [^wp-na]

## Power output

Sources disagree on the 1.6 L's output; each figure is recorded with its source.

### Power (MX-5 article)

1.6 L (98 cu in) straight-four making 116 horsepower. [^wp-mx5]

### Power (UK table)

UK 1.6i, 1990–1993: 85 kW (114 hp) @ 6,500 and 136 N⋅m (100 ft⋅lbf) @ 5,500; redline 7,200 rpm. [^wp-na]

### Power (B engine article)

B6ZE(RS) (US and European, 1990–1993): 9.4:1 compression ratio, 115 hp (85 kW) at 6,500 rpm and 136 N⋅m (100 lb⋅ft) at 5,500 rpm. [^wp-b-engine]

## Weight

Sources give different weights for the early NA; each is recorded with its source.

### Curb weight (Overview text)

980 kg (2,160 lb) without options. [^wp-na]

### Curb weight (infobox)

1,002 kg (2,210 lb). [^wp-na]

### Weight at introduction (MX-5 article)

By 1989 the MX-5 weighed just 940 kg (2,070 lb). [^wp-mx5]

## Performance

Mazda reported 0-60 mph in 8.6 seconds and a top speed of 116.8 mph for the 1990 NA; Car and Driver (September 1989) measured 9.2 seconds. [^wp-na]

## Trims

US (the source gives no breakdown by year): a basic base model ($13,995 at launch, manual windows, steel wheels, no air conditioning or power steering); the A Package added power steering, a leather-wrapped steering wheel, alloy wheels and a cassette stereo; the B Package added power windows, cruise control and headrest speakers; the C Package added a tan interior and top with leather seats. [^wp-na]

## Features

Pop-up headlights (unique to the NA); base models had no power steering, air conditioning or sound system and used steel wheels; a five-speed manual was standard with a four-speed automatic optional. [^wp-mx5]

## Related

- [MX-5 (NA), 1989–1997](/generations/na.md)
- [1990 Mazda MX-5](/model-years/1990.md)
- [1991 Mazda MX-5](/model-years/1991.md)
- [1992 Mazda MX-5](/model-years/1992.md)
- [1993 Mazda MX-5](/model-years/1993.md)


[^wp-na]: Wikipedia, "Mazda MX-5 (NA)", permanent revision 1381587107 (2026-10-23): <https://en.wikipedia.org/w/index.php?title=Mazda_MX-5_(NA)&oldid=1381587107>
[^wp-mx5]: Wikipedia, "Mazda MX-5", permanent revision 1384156481 (2026-11-06): <https://en.wikipedia.org/w/index.php?title=Mazda_MX-5&oldid=1384156481>
[^wp-b-engine]: Wikipedia, "Mazda B engine", permanent revision 1381332751 (2026-10-21): <https://en.wikipedia.org/w/index.php?title=Mazda_B_engine&oldid=1381332751>
