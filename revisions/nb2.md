---
type: Vehicle Revision
title: "MX-5 NB2 (facelift), model years 2001–2005"
description: "NB2 revision of the NB MX-5: facelift, engine output disagreements, Mazdaspeed MX-5 and buy-back."
tags: [mazda, mx-5, miata, nb, nb2]
aliases: ["NB2", "NB facelift", "late NB", "Mazdaspeed MX-5", "Roadster Turbo"]
status: stable
sources:
  - id: wp-nb
    resource: "https://en.wikipedia.org/w/index.php?title=Mazda_MX-5_(NB)&oldid=1381623005"
    title: "Wikipedia, \"Mazda MX-5 (NB)\", permanent revision 1381623005 (2026-10-23)"
  - id: wp-mx5
    resource: "https://en.wikipedia.org/w/index.php?title=Mazda_MX-5&oldid=1384156481"
    title: "Wikipedia, \"Mazda MX-5\", permanent revision 1384156481 (2026-11-06)"
  - id: wp-b-engine
    resource: "https://en.wikipedia.org/w/index.php?title=Mazda_B_engine&oldid=1381332751"
    title: "Wikipedia, \"Mazda B engine\", permanent revision 1381332751 (2026-10-21)"
x-silica:
  v: 1
  sources:
    wp-nb: { kind: http, url: "https://en.wikipedia.org/w/index.php?title=Mazda_MX-5_(NB)&oldid=1381623005" }
    wp-mx5: { kind: http, url: "https://en.wikipedia.org/w/index.php?title=Mazda_MX-5&oldid=1384156481" }
    wp-b-engine: { kind: http, url: "https://en.wikipedia.org/w/index.php?title=Mazda_B_engine&oldid=1381332751" }
  facts:
    - id: model-years
      at: { section: "Model years" }
      source: wp-nb
      mode: pinned
      extract: { kind: md-section, heading: "Facelift (2001)" }
      pin: { sha256: "88b8fb763112490268a97cd33f01479e81d94975076d857a9c2c33718b422ea3", rev: "sha256:778980889258777eea626b61a1a715253cc4b66c9bc18fee54d1b2a7148fcbe8", at: "2026-11-14T11:31:46Z", fact: "5e779a0712c6f6b243d4251444d5ca3ec7cee1c7584426c024de891b66237c8c" }
    - id: changes
      at: { section: "Changes" }
      source: wp-nb
      mode: pinned
      extract: { kind: md-section, heading: "Facelift (2001)" }
      pin: { sha256: "88b8fb763112490268a97cd33f01479e81d94975076d857a9c2c33718b422ea3", rev: "sha256:778980889258777eea626b61a1a715253cc4b66c9bc18fee54d1b2a7148fcbe8", at: "2026-11-14T11:31:46Z", fact: "482027f9e0d8064cdebcf1b51cb9d3d770572a68829deb5016ad07f0fd1cb052" }
    - id: engine-nb-article
      at: { section: "Engine (NB article)" }
      source: wp-nb
      mode: pinned
      extract: { kind: md-section, heading: "Facelift (2001)" }
      pin: { sha256: "88b8fb763112490268a97cd33f01479e81d94975076d857a9c2c33718b422ea3", rev: "sha256:778980889258777eea626b61a1a715253cc4b66c9bc18fee54d1b2a7148fcbe8", at: "2026-11-14T11:31:46Z", fact: "3bb775a78c84d35a8ef2efc73a360bc35c11481bbd313c8b65d9f582b24531a4" }
    - id: engine-mx5-article
      at: { section: "Engine (MX-5 article)" }
      source: wp-mx5
      mode: pinned
      extract: { kind: md-section, heading: "Second generation – NB (1998–2005)" }
      pin: { sha256: "ff6045ce35aff9c70e49cd2417d62cbbeae49b0579140ffdb2c0e6b80b0d14c1", rev: "sha256:b96cb41d926071821490db5697fd311eccc0299e8afdf5870eae5f130f177006", at: "2026-11-14T11:31:46Z", fact: "e222fa1cb415efa6b56902d4e76ad0c7cf741a23864d68a4321c8c038793e2ec" }
    - id: engine-uk-table
      at: { section: "Engine (UK table)" }
      source: wp-nb
      mode: pinned
      extract: { kind: md-section, heading: "Technical specifications (UK)" }
      pin: { sha256: "898a530d4f89ee6043a9923e358c48bb215ae881aa0e9eb87c3c3410e62ebdb3", rev: "sha256:778980889258777eea626b61a1a715253cc4b66c9bc18fee54d1b2a7148fcbe8", at: "2026-11-14T11:31:46Z", fact: "44842674cfcf37d8b933885b2cf3f1c946171a2c10d86ad39f40c5b92f121c2e" }
    - id: engine-code-b-engine-article
      at: { section: "Engine code (B engine article)" }
      source: wp-b-engine
      mode: pinned
      extract: { kind: md-section, heading: "BP-Z3" }
      pin: { sha256: "0d1d0dbf9f416def6890f08891a2a867a6b28ba9467918efc0f9c3bb917d41d6", rev: "sha256:839bdf0457d7d63505f0e4dac172dcde8ebe76503362a3426c0fa24b6ade1c0f", at: "2026-11-14T11:31:46Z", fact: "8abd65411ed9cc1059ca78be7e5e3497dadc05c76cec874b66ffab0e41e71efb" }
    - id: power-rating-buy-back
      at: { section: "Power rating buy-back" }
      source: wp-nb
      mode: pinned
      extract: { kind: md-section, heading: "Facelift (2001)" }
      pin: { sha256: "88b8fb763112490268a97cd33f01479e81d94975076d857a9c2c33718b422ea3", rev: "sha256:778980889258777eea626b61a1a715253cc4b66c9bc18fee54d1b2a7148fcbe8", at: "2026-11-14T11:31:46Z", fact: "f8cccd621bad0f755921ef57e1404bf78d0f99e314708f2b40032095f260a239" }
    - id: curb-weight
      at: { section: "Curb weight" }
      source: wp-nb
      mode: pinned
      extract: { kind: md-section, heading: "Facelift (2001)" }
      pin: { sha256: "88b8fb763112490268a97cd33f01479e81d94975076d857a9c2c33718b422ea3", rev: "sha256:778980889258777eea626b61a1a715253cc4b66c9bc18fee54d1b2a7148fcbe8", at: "2026-11-14T11:31:46Z", fact: "c3b0910487b9e660914f38ef772c9b5ebe3cf13f557df92f8239e934af9082f9" }
    - id: trims
      at: { section: "Trims" }
      source: wp-nb
      mode: pinned
      extract: { kind: md-section, heading: "Facelift (2001)" }
      pin: { sha256: "88b8fb763112490268a97cd33f01479e81d94975076d857a9c2c33718b422ea3", rev: "sha256:778980889258777eea626b61a1a715253cc4b66c9bc18fee54d1b2a7148fcbe8", at: "2026-11-14T11:31:46Z", fact: "405f8ea10b81869b0d01ee9879e6a06104fa0887beb8af57c39e7e342b9ed612" }
    - id: mazdaspeed-mx-5
      at: { section: "Mazdaspeed MX-5" }
      source: wp-nb
      mode: pinned
      extract: { kind: md-section, heading: "Mazdaspeed MX-5 (2004–2005)" }
      pin: { sha256: "5435e0c2bd01fa9c408be4023d537eb00ef3fcdb07903852ccee5bb2d05c64f3", rev: "sha256:778980889258777eea626b61a1a715253cc4b66c9bc18fee54d1b2a7148fcbe8", at: "2026-11-14T11:31:46Z", fact: "9a800426d8f7169b6104a1cf585d0d0629509d9ad02987c64bffb04b70fe37e8" }
    - id: mazdaspeed-torque-b-engine-article
      at: { section: "Mazdaspeed torque (B engine article)" }
      source: wp-b-engine
      mode: pinned
      extract: { kind: md-section, heading: "BP-4W" }
      pin: { sha256: "c84f70950c376990e62f8e889e0617d15a48ba57db98b3200cfb2a32d6992381", rev: "sha256:839bdf0457d7d63505f0e4dac172dcde8ebe76503362a3426c0fa24b6ade1c0f", at: "2026-11-14T11:31:46Z", fact: "4d11ab5e0f45a71700cba2987a0e1b0ece5ee82b8e1d78210c1d18fcb2ecf40c" }
---

# MX-5 NB2 (facelift), model years 2001–2005

## Model years

The facelift was released for the 2001 model year, announced in a press release of July 18, 2000. [^wp-nb]

## Changes

fog lamps made standard, projector low beams with separate high beams, clear rear turn signals, a redesigned center console, white faced and red backlit gauges and more supportive seats; top models added 16-inch wheels with low-profile tires, larger brakes, a limited-slip differential, a 6-speed manual and Bilstein suspension. The body gained 16% in bending rigidity and 22% in torsional rigidity. [^wp-nb]

## Engine output

Sources disagree on the NB2's engine code and output; each figure is recorded.

### Engine (NB article)

BP6D 1.8 L, with variable valve timing on the intake camshaft: 107 kW (143 bhp) in the US; 113 kW (152 bhp) in Japan, the UK and Australia. [^wp-nb]

### Engine (MX-5 article)

Variable-valve timing for the 1.8-liter engine, which made 106 kW (142 hp). [^wp-mx5]

### Engine (UK table)

UK 1.8i, 2001–2005: BP-Z3, 109 kW (146 bhp) @ 6,500 and 168 N⋅m (124 ft⋅lbf) @ 5,000. [^wp-nb]

### Engine code (B engine article)

The BP-Z3 (also called BP-VE), introduced in 2001, has S-VT variable valve timing on the intake side. [^wp-b-engine]

## Power rating buy-back

Mazda's early US catalogues quoted the Japanese and Australian power figure; Mazda offered to buy back the 2001 cars, and owners who kept them were offered an apology and free servicing for the warranty period. [^wp-nb]

## Curb weight

1,065 kg (2,348 lb) with the minimum of options (2001 model). [^wp-nb]

## Trims

US (2003): base, Shinsen Version (SV) and LS. Miata Club Sport (2003): 50 units for the SCCA. UK: top models designated 'Sport'. [^wp-nb]

## Mazdaspeed MX-5

Mazdaspeed MX-5: IHI RHF5 turbocharged BP-4W producing 133 kW (178 bhp) at 6,000 rpm and 226 N⋅m (167 lbf⋅ft) at 4,500 rpm, with a front-mounted air-to-air intercooler. Built for the 2004 and 2005 model years. [^wp-nb]

## Mazdaspeed torque (B engine article)

The B engine article gives the Mazdaspeed engine 226 N⋅m; 166 lbf⋅ft at 4500 rpm; the NB article gives a different torque figure. [^wp-b-engine]

## Related

- [MX-5 (NB), 1998–2005](/generations/nb.md)
- [2001 Mazda MX-5](/model-years/2001.md)
- [2002 Mazda MX-5](/model-years/2002.md)
- [2003 Mazda MX-5](/model-years/2003.md)
- [2004 Mazda MX-5](/model-years/2004.md)
- [2005 Mazda MX-5](/model-years/2005.md)


[^wp-nb]: Wikipedia, "Mazda MX-5 (NB)", permanent revision 1381623005 (2026-10-23): <https://en.wikipedia.org/w/index.php?title=Mazda_MX-5_(NB)&oldid=1381623005>
[^wp-mx5]: Wikipedia, "Mazda MX-5", permanent revision 1384156481 (2026-11-06): <https://en.wikipedia.org/w/index.php?title=Mazda_MX-5&oldid=1384156481>
[^wp-b-engine]: Wikipedia, "Mazda B engine", permanent revision 1381332751 (2026-10-21): <https://en.wikipedia.org/w/index.php?title=Mazda_B_engine&oldid=1381332751>
