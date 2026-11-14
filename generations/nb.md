---
type: Vehicle Generation
title: "Mazda MX-5 (NB), 1998–2005"
description: "Second-generation MX-5 (NB): production, dimensions, engines, Mazdaspeed turbo, safety and awards."
resource: "https://en.wikipedia.org/w/index.php?title=Mazda_MX-5_(NB)&oldid=1381623005"
tags: [mazda, mx-5, miata, nb, second-generation]
aliases: ["NB", "NB Miata", "second generation", "Mk2", "Mazda Roadster", "Mazdaspeed Miata"]
status: stable
model_code: "NB"
sources:
  - id: wp-nb
    resource: "https://en.wikipedia.org/w/index.php?title=Mazda_MX-5_(NB)&oldid=1381623005"
    title: "Wikipedia, \"Mazda MX-5 (NB)\", permanent revision 1381623005 (2026-10-23)"
  - id: wp-mx5
    resource: "https://en.wikipedia.org/w/index.php?title=Mazda_MX-5&oldid=1384156481"
    title: "Wikipedia, \"Mazda MX-5\", permanent revision 1384156481 (2026-11-06)"
x-silica:
  v: 1
  sources:
    wp-nb: { kind: http, url: "https://en.wikipedia.org/w/index.php?title=Mazda_MX-5_(NB)&oldid=1381623005" }
    wp-mx5: { kind: http, url: "https://en.wikipedia.org/w/index.php?title=Mazda_MX-5&oldid=1384156481" }
  facts:
    - id: overview
      at: { section: "Overview" }
      source: wp-nb
      mode: pinned
      extract: { kind: text-between, start: "The Mazda MX-5 (NB) is the second", end: "## MX-5 10th Anniversary" }
      pin: { sha256: "ebd4cd6c3d8733ff4dc9e3a5ca1327e5a3a31e6a2fe33fbf2bf4d596173c4786", rev: "sha256:778980889258777eea626b61a1a715253cc4b66c9bc18fee54d1b2a7148fcbe8", at: "2026-11-14T11:49:25Z", fact: "e8089e9838b6880fbfcc185716cb48d63a0e83a0837cf5eb2156f1b7c429f121" }
    - id: launch-model-year-nb-article
      at: { section: "Launch model year (NB article)" }
      source: wp-nb
      mode: pinned
      extract: { kind: md-section, heading: "Overview" }
      pin: { sha256: "795a29c00a11d32b79dbf7953ee899a6feb07244b63af8e72e0527099b2084c3", rev: "sha256:778980889258777eea626b61a1a715253cc4b66c9bc18fee54d1b2a7148fcbe8", at: "2026-11-14T11:49:25Z", fact: "c30a87641d267f5a33f95f86622cdb84b5f36aae2391fa529262b9781a0888cc" }
    - id: launch-model-year-mx5-article
      at: { section: "Launch model year (MX-5 article)" }
      source: wp-mx5
      mode: pinned
      extract: { kind: md-section, heading: "Second generation – NB (1998–2005)" }
      pin: { sha256: "ff6045ce35aff9c70e49cd2417d62cbbeae49b0579140ffdb2c0e6b80b0d14c1", rev: "sha256:b96cb41d926071821490db5697fd311eccc0299e8afdf5870eae5f130f177006", at: "2026-11-14T11:49:25Z", fact: "2e4dd04241b7ad1497498e16983939ba77d970aa84af5c83932ff153ca222409" }
    - id: production
      at: { section: "Production" }
      source: wp-nb
      mode: derived
      extract: { kind: text-between, start: "Production | ", end: "\n" }
    - id: wheelbase
      at: { section: "Wheelbase" }
      source: wp-nb
      mode: derived
      extract: { kind: text-between, start: "Wheelbase | ", end: "\n" }
    - id: length
      at: { section: "Length" }
      source: wp-nb
      mode: derived
      extract: { kind: text-between, start: "Length | ", end: "\n" }
    - id: width
      at: { section: "Width" }
      source: wp-nb
      mode: derived
      extract: { kind: text-between, start: "Width | ", end: "\n" }
    - id: height
      at: { section: "Height" }
      source: wp-nb
      mode: derived
      extract: { kind: text-between, start: "Height | ", end: "\n" }
    - id: curb-weight
      at: { section: "Curb weight" }
      source: wp-nb
      mode: derived
      extract: { kind: text-between, start: "Curb weight | ", end: "\n" }
    - id: engines
      at: { section: "Engines" }
      source: wp-nb
      mode: pinned
      extract: { kind: text-between, start: "Engine |", end: "Transmission |" }
      pin: { sha256: "bae73da47b617082b1a846fbc0d059918419b1ed82c4293e94c21dc59aca8978", rev: "sha256:778980889258777eea626b61a1a715253cc4b66c9bc18fee54d1b2a7148fcbe8", at: "2026-11-14T11:49:25Z", fact: "2b41a0b09290500a2ee39e2bd18811ed232f3e921fe6101d98f63381dc118a55" }
    - id: mazdaspeed-engine-code
      at: { section: "Mazdaspeed engine code" }
      source: wp-nb
      mode: pinned
      extract: { kind: text-between, start: "Engine |", end: "## Safety" }
      pin: { sha256: "8720c0f512f34a878540b6fde8ca6eded37520466187c1164960c2c1e5c2a34a", rev: "sha256:778980889258777eea626b61a1a715253cc4b66c9bc18fee54d1b2a7148fcbe8", at: "2026-11-14T11:49:25Z", fact: "1d86dddbb47c5699a28d0c88f12701ca9b54ca5bee2a6afcdac6e7b53c0d50e9" }
    - id: transmissions
      at: { section: "Transmissions" }
      source: wp-nb
      mode: pinned
      extract: { kind: text-between, start: "Transmission |", end: "Dimensions" }
      pin: { sha256: "50db25238d7e48e961e6a095799bc4497d79d224b1dea84cdcb19491e2a449a9", rev: "sha256:778980889258777eea626b61a1a715253cc4b66c9bc18fee54d1b2a7148fcbe8", at: "2026-11-14T11:49:25Z", fact: "7b99167d365f6a570dd12af7fe7c507a34c8ac52be3d28c8804ddd10de603788" }
    - id: mazdaspeed-mx-5
      at: { section: "Mazdaspeed MX-5" }
      source: wp-nb
      mode: pinned
      extract: { kind: md-section, heading: "Mazdaspeed MX-5 (2004–2005)" }
      pin: { sha256: "5435e0c2bd01fa9c408be4023d537eb00ef3fcdb07903852ccee5bb2d05c64f3", rev: "sha256:778980889258777eea626b61a1a715253cc4b66c9bc18fee54d1b2a7148fcbe8", at: "2026-11-14T11:49:25Z", fact: "64be8664300da8d1bf39e6aa097da48a3c39755a232c1256834959431a246e71" }
    - id: safety
      at: { section: "Safety" }
      source: wp-nb
      mode: pinned
      extract: { kind: md-section, heading: "Safety" }
      pin: { sha256: "69f4a588a9cd500b0fa154dab995f4df219c85b70a005cf364d341e3728fa31b", rev: "sha256:778980889258777eea626b61a1a715253cc4b66c9bc18fee54d1b2a7148fcbe8", at: "2026-11-14T11:49:25Z", fact: "369c7cdaff72eab40f81c3b520f30fe7dec782ff82fc9b38a2ef1e5854b004b4" }
    - id: awards
      at: { section: "Awards" }
      source: wp-nb
      mode: pinned
      extract: { kind: md-section, heading: "Awards and recognition" }
      pin: { sha256: "9d1524cb949f1ce64770a89d75fa57624c91a385f3d339cb2b5a26bfd6293c57", rev: "sha256:778980889258777eea626b61a1a715253cc4b66c9bc18fee54d1b2a7148fcbe8", at: "2026-11-14T11:49:25Z", fact: "93733c85cfcd28e59375d7f8b76efcb87638cb0d5911fc93b739bb9dd6b478d5" }
    - id: colors
      at: { section: "Colors by model year" }
    - id: model-code
      at: { field: "model_code" }
      source: wp-nb
      mode: derived
      extract: { kind: text-between, start: "Model code | ", end: "\n" }
---

# Mazda MX-5 (NB), 1998–2005

## Overview

The second generation, manufactured from 1998 until 2005. Fixed headlamps replaced the NA's retractable units, which no longer passed pedestrian safety tests; drag coefficient Cd=0.36; US prices started at $19,770. [^wp-nb]

## Launch model year

Sources disagree on the NB's first model year; both are recorded.

### Launch model year (NB article)

Released in February 1998 for the 1998 model year. [^wp-nb]

### Launch model year (MX-5 article)

Unveiled in 1997 and sold beginning in 1998 for the 1999 model year. [^wp-mx5]

## Production

January 1998 – 2005 [^wp-nb]

## Dimensions

Infobox values from the cited revision. Single values are derived (copied verbatim); a row with a citation marker or several values is pinned instead.

### Wheelbase

2,270 mm (89.4 in) [^wp-nb]

### Length

3,940–3,950 mm (155.1–155.5 in) [^wp-nb]

### Width

1,680 mm (66.1 in) [^wp-nb]

### Height

1,220–1,230 mm (48.0–48.4 in) [^wp-nb]

## Curb weight

1,065 kg (2,348 lb) [^wp-nb]

## Engines

1.6 L B6-ZE (Europe and Japan); 1.8 L BP-5A (Japan), BP-4W and BP-Z3; BPT turbocharged 1.8 L (Mazdaspeed). [^wp-nb]

## Mazdaspeed engine code

The infobox lists the Mazdaspeed engine as a turbocharged BPT, while the Mazdaspeed MX-5 section describes it as a turbocharged variant of the BP-4W. [^wp-nb]

## Transmissions

5-speed manual; 4-speed Aisin 03-72LE automatic; 6-speed Aisin AZ6 manual. [^wp-nb]

## Mazdaspeed MX-5

Turbocharged (IHI RHF5) BP-4W: 133 kW (178 bhp) at 6,000 rpm and 226 N⋅m (167 lbf⋅ft) at 4,500 rpm; 5,428 built for the US (4,000 in 2004 and 1,428 in 2005); sold in Australia as the MX-5 SE. [^wp-nb]

## Safety

Euro NCAP (2002): 4 out of 5 stars for adult protection and 1 out of 4 stars for pedestrian protection. ANCAP also tested the 2000 model. [^wp-nb]

## Awards

Car and Driver's 10Best list from 1998 to 1999 and 2001. [^wp-nb]

## Colors by model year

_Not found._

## Related

- [MX-5 NB1 (pre-facelift), 1998–2000](/revisions/nb1.md)
- [MX-5 NB2 (facelift), model years 2001–2005](/revisions/nb2.md)
- [MX-5 (NA), 1989–1997](/generations/na.md)
- [MX-5 (NC), 2005–2015](/generations/nc.md)
- [BP engine](/engines/bp.md)
- [1998 Mazda MX-5](/model-years/1998.md)
- [1999 Mazda MX-5](/model-years/1999.md)
- [2000 Mazda MX-5](/model-years/2000.md)
- [2001 Mazda MX-5](/model-years/2001.md)
- [2002 Mazda MX-5](/model-years/2002.md)
- [2003 Mazda MX-5](/model-years/2003.md)
- [2004 Mazda MX-5](/model-years/2004.md)
- [2005 Mazda MX-5](/model-years/2005.md)


[^wp-nb]: Wikipedia, "Mazda MX-5 (NB)", permanent revision 1381623005 (2026-10-23): <https://en.wikipedia.org/w/index.php?title=Mazda_MX-5_(NB)&oldid=1381623005>
[^wp-mx5]: Wikipedia, "Mazda MX-5", permanent revision 1384156481 (2026-11-06): <https://en.wikipedia.org/w/index.php?title=Mazda_MX-5&oldid=1384156481>
