---
type: Engine
title: "Mazda BP 1.8 L (BP-ZE, BP-4W, BP-Z3)"
description: "The 1.8 L BP inline-four family used in the NA from 1994, the NB and the Mazdaspeed MX-5."
resource: "https://en.wikipedia.org/w/index.php?title=Mazda_B_engine&oldid=1381332751"
tags: [mazda, mx-5, miata, engine, b-series]
aliases: ["BP", "BP-ZE", "BP-4W", "BP-Z3", "BP-VE", "BPT", "1.8 L", "1800"]
status: stable
sources:
  - id: wp-b-engine
    resource: "https://en.wikipedia.org/w/index.php?title=Mazda_B_engine&oldid=1381332751"
    title: "Wikipedia, \"Mazda B engine\", permanent revision 1381332751 (2026-10-21)"
x-silica:
  v: 1
  sources:
    wp-b-engine: { kind: http, url: "https://en.wikipedia.org/w/index.php?title=Mazda_B_engine&oldid=1381332751" }
  facts:
    - id: mx-5-applications
      at: { section: "MX-5 applications" }
      source: wp-b-engine
      mode: pinned
      extract: { kind: md-section, heading: "BP" }
      pin: { sha256: "d79c2d2f175c1c73ab6caff8fa36c671cb577ab7692c0af693c428381c38adc8", rev: "sha256:839bdf0457d7d63505f0e4dac172dcde8ebe76503362a3426c0fa24b6ade1c0f", at: "2026-11-14T11:31:46Z", fact: "b40e4001af205eb1340282e3e87fab591cfd26afdc317f8e09162ae2ecaaad59" }
    - id: bp-4w
      at: { section: "BP-4W" }
      source: wp-b-engine
      mode: pinned
      extract: { kind: md-section, heading: "BP-4W" }
      pin: { sha256: "c84f70950c376990e62f8e889e0617d15a48ba57db98b3200cfb2a32d6992381", rev: "sha256:839bdf0457d7d63505f0e4dac172dcde8ebe76503362a3426c0fa24b6ade1c0f", at: "2026-11-14T11:31:46Z", fact: "ff14b7e682ed89d15066c401f73a235087d91a1e087ccc3e67cfa2032cef4e7c" }
    - id: bp-z3
      at: { section: "BP-Z3" }
      source: wp-b-engine
      mode: pinned
      extract: { kind: md-section, heading: "BP-Z3" }
      pin: { sha256: "0d1d0dbf9f416def6890f08891a2a867a6b28ba9467918efc0f9c3bb917d41d6", rev: "sha256:839bdf0457d7d63505f0e4dac172dcde8ebe76503362a3426c0fa24b6ade1c0f", at: "2026-11-14T11:31:46Z", fact: "e2849d3fd404f05082361640d925eb2c7f6c9f998eb4affc09ed6173cb111a50" }
    - id: mazdaspeed-turbo
      at: { section: "Mazdaspeed turbo" }
      source: wp-b-engine
      mode: pinned
      extract: { kind: md-section, heading: "BP-4W" }
      pin: { sha256: "c84f70950c376990e62f8e889e0617d15a48ba57db98b3200cfb2a32d6992381", rev: "sha256:839bdf0457d7d63505f0e4dac172dcde8ebe76503362a3426c0fa24b6ade1c0f", at: "2026-11-14T11:31:46Z", fact: "e0eefa7dc2396a7d47aa3550843d0c29ccd52722d1670a2182ce17b68ba6376f" }
---

# Mazda BP 1.8 L (BP-ZE, BP-4W, BP-Z3)

## MX-5 applications

1994–1997 Mazda MX-5/Miata (no VICS until 1999); BP-4W in the 1998–2000 MX-5 and the 2004–2005 Mazdaspeed MX-5; BP-Z3 in the 2001+ Miata. [^wp-b-engine]

## BP-4W

Replaced the dual cam angle sensor with two Hall Effect units, improved the intake ports and switched to solid lifters; initially 140 hp at 6500 rpm and 119 lb·ft at 5000 rpm. [^wp-b-engine]

## BP-Z3

Introduced in 2001, also called BP-VE: 1.8 L (1,839 cc) with S-VT variable valve timing on the intake side and a Variable Tumble Control System (VTCS) instead of VICS. [^wp-b-engine]

## Mazdaspeed turbo

The 2004–2005 Mazdaspeed MX-5 turbo is based on the BP-4W and produces 178 bhp (180 PS; 133 kW) at 6000 rpm and 226 N⋅m; 166 lbf⋅ft at 4500 rpm, with a 9.5:1 compression ratio. [^wp-b-engine]

## Related

- [MX-5 (NA), 1989–1997](/generations/na.md)
- [MX-5 (NB), 1998–2005](/generations/nb.md)
- [MX-5 NA2 (1.8 L), model years 1994–1997](/revisions/na2.md)
- [MX-5 NB1 (pre-facelift), 1998–2000](/revisions/nb1.md)
- [MX-5 NB2 (facelift), model years 2001–2005](/revisions/nb2.md)


[^wp-b-engine]: Wikipedia, "Mazda B engine", permanent revision 1381332751 (2026-10-21): <https://en.wikipedia.org/w/index.php?title=Mazda_B_engine&oldid=1381332751>
