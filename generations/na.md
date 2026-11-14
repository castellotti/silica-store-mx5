---
type: Vehicle Generation
title: "Mazda MX-5 (NA), 1989–1997"
description: "First-generation MX-5 (NA): production, dimensions, engines, weights, special editions and awards."
resource: "https://en.wikipedia.org/w/index.php?title=Mazda_MX-5_(NA)&oldid=1381587107"
tags: [mazda, mx-5, miata, na, first-generation]
aliases: ["NA", "NA Miata", "first generation", "Eunos Roadster", "Mazda Miata", "Mk1", "1989 Miata"]
status: stable
model_code: "NA"
sources:
  - id: wp-na
    resource: "https://en.wikipedia.org/w/index.php?title=Mazda_MX-5_(NA)&oldid=1381587107"
    title: "Wikipedia, \"Mazda MX-5 (NA)\", permanent revision 1381587107 (2026-10-23)"
  - id: wp-mx5
    resource: "https://en.wikipedia.org/w/index.php?title=Mazda_MX-5&oldid=1384156481"
    title: "Wikipedia, \"Mazda MX-5\", permanent revision 1384156481 (2026-11-06)"
x-silica:
  v: 1
  sources:
    wp-na: { kind: http, url: "https://en.wikipedia.org/w/index.php?title=Mazda_MX-5_(NA)&oldid=1381587107" }
    wp-mx5: { kind: http, url: "https://en.wikipedia.org/w/index.php?title=Mazda_MX-5&oldid=1384156481" }
  facts:
    - id: overview
      at: { section: "Overview" }
      source: wp-na
      mode: pinned
      extract: { kind: text-between, start: "The Mazda MX-5 (NA) (sold in Japan", end: "## Special editions" }
      pin: { sha256: "1a06a8ffbefab1c3564769a527c4a6f015df2244ac936a3b7ab6d8664ec0310c", rev: "sha256:334b67430ffe976b0d9ef21ff9aef5af2f81844f836b567463da81d5b162351c", at: "2026-11-14T11:31:46Z", fact: "a104a833c5a02360c4c20bfa22455373872377e3e09f5ad401100ed853e656e6" }
    - id: production
      at: { section: "Production" }
      source: wp-na
      mode: pinned
      extract: { kind: text-between, start: "Production | ", end: "\n" }
      pin: { sha256: "2f037f6502ab3531b21da55e9d88199355339de4007593e1f4dd56289eef0e4c", rev: "sha256:334b67430ffe976b0d9ef21ff9aef5af2f81844f836b567463da81d5b162351c", at: "2026-11-14T11:31:46Z", fact: "ecfa6c8a3666cc891f3c6c5d9637cc76df2a3db04547145ea0610b09ba7d153f" }
    - id: sales-and-production-figures
      at: { section: "Sales and production figures" }
      source: wp-mx5
      mode: pinned
      extract: { kind: text-between, start: "The first generation MX-5 sold", end: "\n1990 | " }
      pin: { sha256: "3108b382ea4b93f4a025e83b770ec121617207eb249759bdf69948bfcee29112", rev: "sha256:b96cb41d926071821490db5697fd311eccc0299e8afdf5870eae5f130f177006", at: "2026-11-14T11:31:46Z", fact: "eb7b4f1c84ae0478806708f5b98477fefdfd1b84dd24355aefcbf5efc48bd3b2" }
    - id: wheelbase
      at: { section: "Wheelbase" }
      source: wp-na
      mode: derived
      extract: { kind: text-between, start: "Wheelbase | ", end: "\n" }
    - id: length
      at: { section: "Length" }
      source: wp-na
      mode: derived
      extract: { kind: text-between, start: "Length | ", end: "\n" }
    - id: width
      at: { section: "Width" }
      source: wp-na
      mode: derived
      extract: { kind: text-between, start: "Width | ", end: "\n" }
    - id: height
      at: { section: "Height" }
      source: wp-na
      mode: derived
      extract: { kind: text-between, start: "Height | ", end: "\n" }
    - id: dimension-disagreement
      at: { section: "Dimension disagreement" }
      source: wp-na
      mode: pinned
      extract: { kind: text-between, start: "Wheelbase | ", end: "## Special editions" }
      pin: { sha256: "b2f28ed4d5ef90284c78fc0eb316b88a23014f5d2114aae31474e0c1d51ff709", rev: "sha256:334b67430ffe976b0d9ef21ff9aef5af2f81844f836b567463da81d5b162351c", at: "2026-11-14T11:31:46Z", fact: "35afbd362ab0219ad3c0ca20fdb3cce2d7e8099e6c2e00604768cc06e55f1a4e" }
    - id: curb-weight
      at: { section: "Curb weight" }
      source: wp-na
      mode: pinned
      extract: { kind: text-between, start: "Wheelbase | ", end: "## Special editions" }
      pin: { sha256: "b2f28ed4d5ef90284c78fc0eb316b88a23014f5d2114aae31474e0c1d51ff709", rev: "sha256:334b67430ffe976b0d9ef21ff9aef5af2f81844f836b567463da81d5b162351c", at: "2026-11-14T11:31:46Z", fact: "cf8a2f171407819bcb4810737946ff4adccaf13d0bf8c35537a6fd417a4ad390" }
    - id: engines
      at: { section: "Engines" }
      source: wp-na
      mode: pinned
      extract: { kind: text-between, start: "Engine |", end: "Transmission |" }
      pin: { sha256: "b4b8862eb9806e5cb709f14d6711444984910db36cb02e19607d125f5b8092e7", rev: "sha256:334b67430ffe976b0d9ef21ff9aef5af2f81844f836b567463da81d5b162351c", at: "2026-11-14T11:31:46Z", fact: "80c5100ba29a21445436368c59c36239f632886a75df4e5903eaf66070651a4c" }
    - id: transmissions
      at: { section: "Transmissions" }
      source: wp-na
      mode: pinned
      extract: { kind: text-between, start: "Transmission |", end: "Dimensions" }
      pin: { sha256: "65198baae8115a2a5c5d2be7888be56012834cd35e5f66b40a01f31603a0764d", rev: "sha256:334b67430ffe976b0d9ef21ff9aef5af2f81844f836b567463da81d5b162351c", at: "2026-11-14T11:31:46Z", fact: "142c25090854e47f07752bf2f83d8304ec74c841319c7b139789cd44c70303f1" }
    - id: body-and-chassis
      at: { section: "Body and chassis" }
      source: wp-na
      mode: pinned
      extract: { kind: md-section, heading: "Overview" }
      pin: { sha256: "a0d213fd056719a2f8672977f7b1a4af05febb200f8ba079a11992b9339ebd46", rev: "sha256:334b67430ffe976b0d9ef21ff9aef5af2f81844f836b567463da81d5b162351c", at: "2026-11-14T11:31:46Z", fact: "db73e3c4f095705d66e34d7257c661346adb241330af787da0ea2ec846510896" }
    - id: special-editions
      at: { section: "Special editions" }
      source: wp-na
      mode: pinned
      extract: { kind: text-between, start: "## Special editions", end: "## Factory restoration program" }
      pin: { sha256: "fe4a8a98ad08e400a437b7115b85d38ad725f6e440b04fdf6f7324aef18d77cc", rev: "sha256:334b67430ffe976b0d9ef21ff9aef5af2f81844f836b567463da81d5b162351c", at: "2026-11-14T11:31:46Z", fact: "b2b8782a300446fb295062d0ca8b68222242ffbfe2927fe1fbb65f014b37f2de" }
    - id: factory-restoration
      at: { section: "Factory restoration" }
      source: wp-na
      mode: pinned
      extract: { kind: md-section, heading: "Factory restoration program" }
      pin: { sha256: "cf41219c758b6f7423091e9459c27e223ced4d89fe7648daaf20bbfa6ad7e3ef", rev: "sha256:334b67430ffe976b0d9ef21ff9aef5af2f81844f836b567463da81d5b162351c", at: "2026-11-14T11:31:46Z", fact: "fc7d0ee02053e1a8de69047b8a0897890675b15606f924f035d07de2bd2af39d" }
    - id: awards
      at: { section: "Awards" }
      source: wp-na
      mode: pinned
      extract: { kind: md-section, heading: "Awards and recognition" }
      pin: { sha256: "45721dadf2199c7aad9f2691d92935ea3d87ac72c7a0a20d10b8d06e1b76d0ac", rev: "sha256:334b67430ffe976b0d9ef21ff9aef5af2f81844f836b567463da81d5b162351c", at: "2026-11-14T11:31:46Z", fact: "646b0dd7edfb38fcc9f170e72d417fbaa2e8b0473c48d4bd57615d31619fabbe" }
    - id: colors
      at: { section: "Colors by model year" }
    - id: model-code
      at: { field: "model_code" }
      source: wp-na
      mode: derived
      extract: { kind: text-between, start: "Model code | ", end: "\n" }
---

# Mazda MX-5 (NA), 1989–1997

## Overview

The first generation, manufactured from 1989 to 1997, sold in Japan as the Eunos Roadster and in North America as the Mazda MX-5 Miata. Unveiled at the Chicago Auto Show on February 10, 1989, at $14,000. [^wp-na]

## Production

April 1989–1997; 431,506 units produced. [^wp-na]

## Sales and production figures

The MX-5 article's Overview says the first generation sold 228,961 units between 1989 and 1997, while the same article's production table gives the first generation a total production of 431,506; the article does not reconcile the two. [^wp-mx5]

## Dimensions

Infobox values, extracted verbatim from the cited revision.

### Wheelbase

2,265 mm (89.2 in) [^wp-na]

### Length

3,950 mm (155.5 in) [^wp-na]

### Width

1,675 mm (65.9 in) [^wp-na]

### Height

1,230 mm (48.4 in) [^wp-na]

## Dimension disagreement

The infobox gives length 3,950 mm and height 1,230 mm; the Overview text gives 3,970 mm (156 in) in length and 1,235 mm (48.6 in) in height. [^wp-na]

## Curb weight

Infobox: 1,002 kg (2,210 lb). Overview text: 980 kg (2,160 lb) without options, and a base weight of 990 kg (2,180 lb) after the 1994 changes. [^wp-na]

## Engines

1,597 cc B6ZE(RS) DOHC I4; supercharged B6ZE(RS) (Mazdaspeed B-Spec); 1,839 cc BP DOHC I4; 1,995 cc BP (Mazdaspeed C-Spec). [^wp-na]

## Transmissions

5-speed M526 manual; 4-speed Jatco N4AHL and N4AEL automatics. [^wp-na]

## Body and chassis

Steel unibody with an aluminium hood; drag coefficient Cd=0.38; double wishbones on all four wheels with front and rear anti-roll bars; four-wheel disc brakes; alloy wheels with radial tires. [^wp-na]

## Special editions

US: 1991 Special Edition (British racing green), 1992 Sunburst and Black Miata, 1993 Limited Edition, M-Edition from 1994 to 1997, 1997 Special Touring Option. Japan: J Limited (1991) and J Limited II (1993). UK: 1991 Limited Edition, 1997 Monza Edition, 1998 Berkeley Limited Edition. The M2 Corporation in Japan also built limited Eunos Roadster variants. [^wp-na]

## Factory restoration

In 2018 Mazda began a factory restoration program for Eunos Roadster owners in Japan, with work certified by TÜV Rheinland; the first fully restored car, a 1992 V-Special, was unveiled on September 27, 2018. [^wp-na]

## Awards

Automobile Magazine 1990 Automobile of the Year; Car and Driver's 10Best list from 1990 to 1992; 2018 RJC Car of the Year Special Award for the restoration service; Japan Automotive Hall of Fame 2019 Special Award: Historic Car. [^wp-na]

## Colors by model year

_Not found._

## Related

- [MX-5 NA1 (1.6 L), model years 1990–1993](/revisions/na1.md)
- [MX-5 NA2 (1.8 L), model years 1994–1997](/revisions/na2.md)
- [MX-5 (NB), 1998–2005](/generations/nb.md)
- [B6ZE(RS) engine](/engines/b6ze-rs.md)
- [BP engine](/engines/bp.md)
- [1990 Mazda MX-5](/model-years/1990.md)
- [1991 Mazda MX-5](/model-years/1991.md)
- [1992 Mazda MX-5](/model-years/1992.md)
- [1993 Mazda MX-5](/model-years/1993.md)
- [1994 Mazda MX-5](/model-years/1994.md)
- [1995 Mazda MX-5](/model-years/1995.md)
- [1996 Mazda MX-5](/model-years/1996.md)
- [1997 Mazda MX-5](/model-years/1997.md)


[^wp-na]: Wikipedia, "Mazda MX-5 (NA)", permanent revision 1381587107 (2026-10-23): <https://en.wikipedia.org/w/index.php?title=Mazda_MX-5_(NA)&oldid=1381587107>
[^wp-mx5]: Wikipedia, "Mazda MX-5", permanent revision 1384156481 (2026-11-06): <https://en.wikipedia.org/w/index.php?title=Mazda_MX-5&oldid=1384156481>
