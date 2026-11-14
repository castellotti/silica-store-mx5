---
type: Vehicle Generation
title: "Mazda MX-5 (NC), 2005–2015"
description: "Third-generation MX-5 (NC): production, dimensions, MZR engines, PRHT hardtop and awards."
resource: "https://en.wikipedia.org/w/index.php?title=Mazda_MX-5_(NC)&oldid=1381436898"
tags: [mazda, mx-5, miata, nc, third-generation]
aliases: ["NC", "NC Miata", "third generation", "Mk3", "PRHT", "Power Retractable Hard Top", "Roadster Coupé"]
status: stable
model_code: "NC"
sources:
  - id: wp-nc
    resource: "https://en.wikipedia.org/w/index.php?title=Mazda_MX-5_(NC)&oldid=1381436898"
    title: "Wikipedia, \"Mazda MX-5 (NC)\", permanent revision 1381436898 (2026-10-22)"
x-silica:
  v: 1
  sources:
    wp-nc: { kind: http, url: "https://en.wikipedia.org/w/index.php?title=Mazda_MX-5_(NC)&oldid=1381436898" }
  facts:
    - id: overview
      at: { section: "Overview" }
      source: wp-nc
      mode: pinned
      extract: { kind: text-between, start: "The Mazda MX-5 (NC) is the third", end: "## 2005—2008 (NC1)" }
      pin: { sha256: "5f5125af2ed9e3a40fb205c45b047f74e5c7c8286c4c517ee525cf65bd6fe6ae", rev: "sha256:dee0e9956663fb8260f2f41bb55994564bf060b51af210ed156f5bf0c6589418", at: "2026-11-14T11:49:25Z", fact: "8c2d2ddaf15ec85a9cf1e5ebbc3e0fc95e6ced2659285abafa422f0f4fba73ea" }
    - id: production
      at: { section: "Production" }
      source: wp-nc
      mode: derived
      extract: { kind: text-between, start: "Production | ", end: "\n" }
    - id: model-years
      at: { section: "Model years" }
      source: wp-nc
      mode: derived
      extract: { kind: text-between, start: "Model years | ", end: "\n" }
    - id: wheelbase
      at: { section: "Wheelbase" }
      source: wp-nc
      mode: derived
      extract: { kind: text-between, start: "Wheelbase | ", end: "\n" }
    - id: length
      at: { section: "Length" }
      source: wp-nc
      mode: pinned
      extract: { kind: text-between, start: "Length |", end: "Width |" }
      pin: { sha256: "3373fdf020d35f81360192d2fc35ee0adea59b9aee8a779426f46c876bae0680", rev: "sha256:dee0e9956663fb8260f2f41bb55994564bf060b51af210ed156f5bf0c6589418", at: "2026-11-14T11:49:25Z", fact: "a5f757e783e36c03008fe769a68e47171d11fdeebd8b734592d35adeb77493c3" }
    - id: width
      at: { section: "Width" }
      source: wp-nc
      mode: derived
      extract: { kind: text-between, start: "Width | ", end: "\n" }
    - id: height
      at: { section: "Height" }
      source: wp-nc
      mode: pinned
      extract: { kind: text-between, start: "Height |", end: "Curb weight |" }
      pin: { sha256: "d4583f0cba55b3c9feb7f7076eb3d4f8420f6d2c528350a75f04244e621ba6ad", rev: "sha256:dee0e9956663fb8260f2f41bb55994564bf060b51af210ed156f5bf0c6589418", at: "2026-11-14T11:49:25Z", fact: "e6f55d6cef3a34995f102b2098e3fbac97949a27ad7c14b4dc8d4a772199fb41" }
    - id: curb-weight
      at: { section: "Curb weight" }
      source: wp-nc
      mode: pinned
      extract: { kind: text-between, start: "Curb weight |", end: "Chronology" }
      pin: { sha256: "4bca1626587573431c2e6e1dfa16c9a0e52e99d74ca441dced64922578515552", rev: "sha256:dee0e9956663fb8260f2f41bb55994564bf060b51af210ed156f5bf0c6589418", at: "2026-11-14T11:49:25Z", fact: "7ab21ce6b8b381a6b340bfb812a2a7c234b5d796ea6abf5f3b66be47c1c49679" }
    - id: hardtop-weight-disagreement
      at: { section: "Hardtop weight disagreement" }
      source: wp-nc
      mode: pinned
      extract: { kind: text-between, start: "Curb weight |", end: "### Special editions (2005—2008)" }
      pin: { sha256: "78daa9be2afc71107c1eb6eee47ebf9a289572e569c3211789036478a8490345", rev: "sha256:dee0e9956663fb8260f2f41bb55994564bf060b51af210ed156f5bf0c6589418", at: "2026-11-14T11:49:25Z", fact: "04260a5a774143c6681cca6d8b592e9f0383eeefff0cba8cdc8f63d3a7a6e9c8" }
    - id: engines
      at: { section: "Engines" }
      source: wp-nc
      mode: pinned
      extract: { kind: text-between, start: "Engine |", end: "Transmission |" }
      pin: { sha256: "4dd28186200007f5725e89c382721254e11a3291e6b0c716f808f70a166e4983", rev: "sha256:dee0e9956663fb8260f2f41bb55994564bf060b51af210ed156f5bf0c6589418", at: "2026-11-14T11:49:25Z", fact: "5bf91b4c54a0458ef4ab199b168d71ea2759ff8210b61f4312bd038bae7394b0" }
    - id: european-1-8-l-engine-code
      at: { section: "European 1.8 L engine code" }
      source: wp-nc
      mode: pinned
      extract: { kind: text-between, start: "Engine |", end: "## Transmissions" }
      pin: { sha256: "d8367e3ec0fd2031fc8154f5493b3f5ec5a64103af7cd448da6adbc0aecc4780", rev: "sha256:dee0e9956663fb8260f2f41bb55994564bf060b51af210ed156f5bf0c6589418", at: "2026-11-14T11:49:25Z", fact: "c587e40fcb8162dd56e8ab6aa64dd6cfabc7ac41f44a998b707aa397ee5c7dcc" }
    - id: transmissions
      at: { section: "Transmissions" }
      source: wp-nc
      mode: pinned
      extract: { kind: text-between, start: "Transmission |", end: "Dimensions" }
      pin: { sha256: "c8f70e395b850c45f7e2967a2b95a4222132b7e2a9b05abdbf5876c7ada016f6", rev: "sha256:dee0e9956663fb8260f2f41bb55994564bf060b51af210ed156f5bf0c6589418", at: "2026-11-14T11:49:25Z", fact: "e3591275214a0e9243b930ad1db0c9b6bb62eeeb3ae002b7ad4bda7a80febc7a" }
    - id: power-retractable-hard-top
      at: { section: "Power Retractable Hard Top" }
      source: wp-nc
      mode: pinned
      extract: { kind: md-section, heading: "Power Retractable Hard Top" }
      pin: { sha256: "c7994c4bc04331bb18b4079d5a70451a253a24c09b44f3c9b0cdd77665a40102", rev: "sha256:dee0e9956663fb8260f2f41bb55994564bf060b51af210ed156f5bf0c6589418", at: "2026-11-14T11:49:25Z", fact: "abb4cb3f00a27124310614b92a429e80facc0a41b1c38ff194e8f985f37f06e4" }
    - id: awards
      at: { section: "Awards" }
      source: wp-nc
      mode: pinned
      extract: { kind: md-section, heading: "Accolades" }
      pin: { sha256: "10e04bec335c16487e2205c6bea01c26f80427d64d2f3559cef831c6c1ffef44", rev: "sha256:dee0e9956663fb8260f2f41bb55994564bf060b51af210ed156f5bf0c6589418", at: "2026-11-14T11:49:25Z", fact: "117b1c6780c096a842e9010ba12a708a29a53437420e0b669b2a90e69e9f6887" }
    - id: colors
      at: { section: "Colors by model year" }
    - id: model-code
      at: { field: "model_code" }
      source: wp-nc
      mode: derived
      extract: { kind: text-between, start: "Model code | ", end: "\n" }
---

# Mazda MX-5 (NC), 2005–2015

## Overview

The third generation, manufactured from 2005 to 2015; the first MX-5 with a retractable hardtop, which can fold or deploy in 12 seconds without reducing trunk space. [^wp-nc]

## Production

2005–2015 [^wp-nc]

## Model years

2006–2015 (North America) [^wp-nc]

## Dimensions

Infobox values from the cited revision. Single values are derived (copied verbatim); a row with a citation marker or several values is pinned instead.

### Wheelbase

2,330 mm (91.7 in) [^wp-nc]

### Length

4,000 mm (157.5 in) soft-top; 4,020 mm (158.3 in) PRHT. [^wp-nc]

### Width

1,720 mm (67.7 in) [^wp-nc]

### Height

1,240 mm (48.8 in) soft-top; 1,255 mm (49.4 in) PRHT. [^wp-nc]

## Curb weight

1,110 kg (2,450 lb) soft-top; 1,153 kg (2,542 lb) PRHT. [^wp-nc]

## Hardtop weight disagreement

The infobox gives 1,110 kg for the soft-top and 1,153 kg for the PRHT, while the PRHT section says the hardtop adds 36 kg (79 lb) to a comparably equipped soft-top; the infobox difference does not match the stated figure. [^wp-nc]

## Engines

MZR L8-DE 1.8 L, DOHC I4 (Europe), 126 hp (94 kW); MZR LF-VE 2.0 L, DOHC I4, 167 hp (125 kW). [^wp-nc]

## European 1.8 L engine code

The infobox and the UK specification table call the European 1.8 L engine the MZR L8-DE, while the NC1 section text calls it the MZR L8-VE. [^wp-nc]

## Transmissions

5-speed manual; 6-speed Aisin AZ6 manual; 6-speed SJ6A-EL Activematic automatic. [^wp-nc]

## Power Retractable Hard Top

Debuted in July 2006: a two-piece polycarbonate folding hardtop designed by Webasto that takes 12 seconds to raise or lower; first deliveries in late August 2006. Named MX-5 Roadster Coupé in Europe. [^wp-nc]

## Awards

2005-2006 Car of the Year Japan Award; Car and Driver's 10Best list from 2006 to 2013; 2006 World Car of the Year finalist; 2012 Autocar Indonesia Reader's Choice Award, Favorite Convertible; What Car? Magazine 2014 Used Car of the Year - Best Fun Car. [^wp-nc]

## Colors by model year

_Not found._

## Related

- [MX-5 NC1, model years 2006–2008](/revisions/nc1.md)
- [MX-5 NC2 (2009 facelift), model years 2009–2012](/revisions/nc2.md)
- [MX-5 NC3 (2012 update), model years 2013–2015](/revisions/nc3.md)
- [MX-5 (NB), 1998–2005](/generations/nb.md)
- [MX-5 (ND), 2015–present](/generations/nd.md)
- [MZR L-series engines](/engines/mzr-l.md)
- [2006 Mazda MX-5](/model-years/2006.md)
- [2007 Mazda MX-5](/model-years/2007.md)
- [2008 Mazda MX-5](/model-years/2008.md)
- [2009 Mazda MX-5](/model-years/2009.md)
- [2010 Mazda MX-5](/model-years/2010.md)
- [2011 Mazda MX-5](/model-years/2011.md)
- [2012 Mazda MX-5](/model-years/2012.md)
- [2013 Mazda MX-5](/model-years/2013.md)
- [2014 Mazda MX-5](/model-years/2014.md)
- [2015 Mazda MX-5](/model-years/2015.md)


[^wp-nc]: Wikipedia, "Mazda MX-5 (NC)", permanent revision 1381436898 (2026-10-22): <https://en.wikipedia.org/w/index.php?title=Mazda_MX-5_(NC)&oldid=1381436898>
