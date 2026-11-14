---
type: Vehicle Generation
title: "Mazda MX-5 (ND), 2015–present"
description: "Fourth-generation MX-5 (ND), the current generation: production, dimensions, Skyactiv-G engines, RF, safety and awards."
resource: "https://en.wikipedia.org/w/index.php?title=Mazda_MX-5_(ND)&oldid=1382278464"
tags: [mazda, mx-5, miata, nd, fourth-generation]
aliases: ["ND", "ND Miata", "fourth generation", "Mk4", "MX-5 RF", "Retractable Fastback", "current MX-5"]
status: stable
stale_after: "2027-11-14T00:00:00Z"
model_code: "ND"
sources:
  - id: wp-nd
    resource: "https://en.wikipedia.org/w/index.php?title=Mazda_MX-5_(ND)&oldid=1382278464"
    title: "Wikipedia, \"Mazda MX-5 (ND)\", permanent revision 1382278464 (2026-10-27)"
x-silica:
  v: 1
  sources:
    wp-nd: { kind: http, url: "https://en.wikipedia.org/w/index.php?title=Mazda_MX-5_(ND)&oldid=1382278464" }
  facts:
    - id: overview
      at: { section: "Overview" }
      source: wp-nd
      mode: pinned
      extract: { kind: text-between, start: "Model code | ND", end: "## Overview" }
      pin: { sha256: "a44c6b9e398b671c4fda72126a5de7f86ed2aeb93c118adf8d006c2a8dc6acf7", rev: "sha256:e1a829d55fb41d71df271f5207d5dd8fcd9f6094cc6fcf9771fadcb1a335acc7", at: "2026-11-14T11:31:46Z", fact: "b0999e064009378aed63bb0ec440247ed985a65c521ee38d7e029bacec301474" }
    - id: production
      at: { section: "Production" }
      source: wp-nd
      mode: derived
      extract: { kind: text-between, start: "Production | ", end: "\n" }
    - id: model-years
      at: { section: "Model years" }
      source: wp-nd
      mode: derived
      extract: { kind: text-between, start: "Model years | ", end: "\n" }
    - id: wheelbase
      at: { section: "Wheelbase" }
      source: wp-nd
      mode: pinned
      extract: { kind: text-between, start: "Wheelbase |", end: "Length |" }
      pin: { sha256: "5222a588fb7ead579b4cca25f3cfc05ffc8956a699d372b52147c9ccab218d2a", rev: "sha256:e1a829d55fb41d71df271f5207d5dd8fcd9f6094cc6fcf9771fadcb1a335acc7", at: "2026-11-14T11:31:46Z", fact: "3de8cba2dd1f31c345151ceb9f4147d3ea4ca996760a4cd4c55ec7469feca4f4" }
    - id: length
      at: { section: "Length" }
      source: wp-nd
      mode: derived
      extract: { kind: text-between, start: "Length | ", end: "\n" }
    - id: width
      at: { section: "Width" }
      source: wp-nd
      mode: derived
      extract: { kind: text-between, start: "Width | ", end: "\n" }
    - id: height
      at: { section: "Height" }
      source: wp-nd
      mode: derived
      extract: { kind: text-between, start: "Height | ", end: "\n" }
    - id: curb-weight
      at: { section: "Curb weight" }
      source: wp-nd
      mode: pinned
      extract: { kind: text-between, start: "Curb weight |", end: "Chronology" }
      pin: { sha256: "d976e3079bc901f5f72edd08ee863987a525791edcdeaada8987a0fbddb148de", rev: "sha256:e1a829d55fb41d71df271f5207d5dd8fcd9f6094cc6fcf9771fadcb1a335acc7", at: "2026-11-14T11:31:46Z", fact: "cf84c8305d9f498b6f06cf3dd3a39fe97224a50f27863a8085986524ee8b2ec1" }
    - id: engines
      at: { section: "Engines" }
      source: wp-nd
      mode: pinned
      extract: { kind: text-between, start: "Engine |", end: "Transmission |" }
      pin: { sha256: "b109bcab8092b5d925644a91f76d98febfc553fd27d2761e5b50e96a57780a92", rev: "sha256:e1a829d55fb41d71df271f5207d5dd8fcd9f6094cc6fcf9771fadcb1a335acc7", at: "2026-11-14T11:31:46Z", fact: "28d95b5d48646de5ce3b7aec33cb0950823829e7b828182a4d118605d8dc3f24" }
    - id: transmissions
      at: { section: "Transmissions" }
      source: wp-nd
      mode: pinned
      extract: { kind: text-between, start: "Transmission |", end: "Dimensions" }
      pin: { sha256: "13d19c5d0dd49d7030bb0e5201ef06036f7582c0c10e486c7a72e52b07fe1853", rev: "sha256:e1a829d55fb41d71df271f5207d5dd8fcd9f6094cc6fcf9771fadcb1a335acc7", at: "2026-11-14T11:31:46Z", fact: "eb880086bd1fa5ea189ea163fb67ff2ab9fcc55ca3e978ad7cc57ee53eedb4a0" }
    - id: mx-5-rf
      at: { section: "MX-5 RF" }
      source: wp-nd
      mode: pinned
      extract: { kind: md-section, heading: "MX-5 RF" }
      pin: { sha256: "621b0269e460ed91ac5a644b8a83b90d30567c1ae3be74b8c0b335948c5ac58e", rev: "sha256:e1a829d55fb41d71df271f5207d5dd8fcd9f6094cc6fcf9771fadcb1a335acc7", at: "2026-11-14T11:31:46Z", fact: "30b439285024dc6524fcef31b83aea630ecb79a7b4ce9e443d320dbc682ac14d" }
    - id: european-2-0-l-withdrawal
      at: { section: "European 2.0 L withdrawal" }
      source: wp-nd
      mode: pinned
      extract: { kind: md-section, heading: "Overview" }
      pin: { sha256: "bebf0ec4eb35c8406a403ebcbeed2b186c937329dcda930bae06ad1c15b16b7f", rev: "sha256:e1a829d55fb41d71df271f5207d5dd8fcd9f6094cc6fcf9771fadcb1a335acc7", at: "2026-11-14T11:31:46Z", fact: "def6dffa89f30cb99b25e15caebb75e23a7b7f4d274b54280aab03b28697a341" }
    - id: safety
      at: { section: "Safety" }
      source: wp-nd
      mode: pinned
      extract: { kind: md-section, heading: "Safety" }
      pin: { sha256: "837fb1e3a21a425b6833c366cbae8cc588a5e86266cb211d53b9615d262124d7", rev: "sha256:e1a829d55fb41d71df271f5207d5dd8fcd9f6094cc6fcf9771fadcb1a335acc7", at: "2026-11-14T11:31:46Z", fact: "5ffd7ce62ed65f92010b9a321c48ec8261bb348ed933199aed2b52e9600b8bea" }
    - id: special-editions
      at: { section: "Special editions" }
      source: wp-nd
      mode: pinned
      extract: { kind: md-section, heading: "Special editions" }
      pin: { sha256: "44be9f08a4d4d0f186f5b5f08334c5f5d96e6800c9fda98f4d15e950ac4de67e", rev: "sha256:e1a829d55fb41d71df271f5207d5dd8fcd9f6094cc6fcf9771fadcb1a335acc7", at: "2026-11-14T11:31:46Z", fact: "4613b4b419abe6cc4b2562b147ec94e07dc6a4a3e28e21c1ddb9efea11c523b0" }
    - id: awards
      at: { section: "Awards" }
      source: wp-nd
      mode: pinned
      extract: { kind: md-section, heading: "Accolades" }
      pin: { sha256: "44a397f428d5a04b4687fb155c8090d661e65a3fdabc94a9883b96f8d75b99bf", rev: "sha256:e1a829d55fb41d71df271f5207d5dd8fcd9f6094cc6fcf9771fadcb1a335acc7", at: "2026-11-14T11:31:46Z", fact: "cd435077ecdb06267133a7ea57bc20965399c4f54c82c29af946f962dadc7b47" }
    - id: colors
      at: { section: "Colors by model year" }
    - id: model-code
      at: { field: "model_code" }
      source: wp-nd
      mode: derived
      extract: { kind: text-between, start: "Model code | ", end: "\n" }
---

# Mazda MX-5 (ND), 2015–present

## Overview

The fourth and current generation, built in Hiroshima since 4 March 2015; unveiled on 3 September 2014; US list price $24,915 to $30,065 at launch; named World Car of the Year and World Car Design of the Year on 24 March 2016. [^wp-nd]

## Production

March 2015 – present [^wp-nd]

## Model years

2016–present (North America) [^wp-nd]

## Dimensions

Infobox values, extracted verbatim from the cited revision.

### Wheelbase

2,310 mm (90.9 in). [^wp-nd]

### Length

3,915 mm (154.1 in) [^wp-nd]

### Width

1,730 mm (68.1 in) [^wp-nd]

### Height

1,235 mm (48.6 in) [^wp-nd]

## Curb weight

ND1 1.5 L manual base (S/Sport): 990 kg (2,183 lb); ND2/ND3 add 8 kg (18 lb); automatic adds 20 kg (44 lb); RF adds 50 kg (110 lb). [^wp-nd]

## Engines

1.5 L Skyactiv-G (P5-VPS) and 2.0 L Skyactiv-G (PE-VPS) DOHC I4; outputs 96 kW (129 hp; 131 PS) for the 1.5 L, and 118 kW (158 hp; 160 PS) or 135 kW (181 hp; 184 PS) for the 2.0 L. [^wp-nd]

## Transmissions

6-speed Skyactiv-MT manual; 6-speed Skyactiv-Drive automatic. [^wp-nd]

## MX-5 RF

The Retractable Fastback, announced in late 2016, has a rigid roof and buttresses; it introduced the 'Machine Grey Mica' paint colour, and a 500-car Launch Edition in the UK was priced at £28,995. [^wp-nd]

## European 2.0 L withdrawal

In 2024 the 2.0 L model was discontinued in Europe due to stricter emissions regulations; it remains on sale in the UK until January 2027. [^wp-nd]

## Safety

Euro NCAP (2015): 4 out of 5 stars; adult occupant 84%, child occupant 80%, pedestrian 93%, safety assist 64%. ANCAP (2016): side impact 16/16 and pole 2/2. [^wp-nd]

## Special editions

Icon (UK, 2016, 600 cars); Levanto (2016 one-off); Z-Sport (2018); Yamamoto Signature (Italy, 2018); 30th Anniversary Edition (2019, 3,000 worldwide); Eunos Edition (France, 2020, 110 units); 100th Anniversary (2020); MCP 25th Anniversary Edition (Philippines, 2022); Flat Out Edition (Poland, 2024); Spirit Racing Roadster 12R (Japan, 200 to be made). [^wp-nd]

## Awards

Car of the Year Japan Award 2015–2016; 2016 World Car of the Year and World Car Design of the Year; Car and Driver's 10Best list from 2016 to 2019; Red Dot Best of the Best Award: Product Design 2017; Car and Driver 2024 Editor's Choice: Affordable Sports Car. [^wp-nd]

## Colors by model year

_Not found._

## Related

- [MX-5 ND1, model years 2016–2018](/revisions/nd1.md)
- [MX-5 ND2 (2018 update), model years 2019–2023](/revisions/nd2.md)
- [MX-5 ND3 (2024 update), model years 2024–present](/revisions/nd3.md)
- [MX-5 (NC), 2005–2015](/generations/nc.md)
- [Skyactiv-G engines](/engines/skyactiv-g.md)
- [Fiat 124 Spider](/related/fiat-124-spider.md)
- [2016 Mazda MX-5](/model-years/2016.md)
- [2017 Mazda MX-5](/model-years/2017.md)
- [2018 Mazda MX-5](/model-years/2018.md)
- [2019 Mazda MX-5](/model-years/2019.md)
- [2020 Mazda MX-5](/model-years/2020.md)
- [2021 Mazda MX-5](/model-years/2021.md)
- [2022 Mazda MX-5](/model-years/2022.md)
- [2023 Mazda MX-5](/model-years/2023.md)
- [2024 Mazda MX-5](/model-years/2024.md)
- [2025 Mazda MX-5](/model-years/2025.md)
- [2026 Mazda MX-5](/model-years/2026.md)


[^wp-nd]: Wikipedia, "Mazda MX-5 (ND)", permanent revision 1382278464 (2026-10-27): <https://en.wikipedia.org/w/index.php?title=Mazda_MX-5_(ND)&oldid=1382278464>
