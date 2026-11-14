---
type: Engine
title: "Mazda B6ZE(RS) 1.6 L"
description: "The 1.6 L B6ZE(RS) inline-four developed for the MX-5 (NA, and NB in Europe and Japan)."
resource: "https://en.wikipedia.org/w/index.php?title=Mazda_B_engine&oldid=1381332751"
tags: [mazda, mx-5, miata, engine, b-series]
aliases: ["B6ZE(RS)", "B6ZE", "B6-ZE", "B6", "1.6 L", "1600"]
status: stable
sources:
  - id: wp-b-engine
    resource: "https://en.wikipedia.org/w/index.php?title=Mazda_B_engine&oldid=1381332751"
    title: "Wikipedia, \"Mazda B engine\", permanent revision 1381332751 (2026-10-21)"
  - id: wp-na
    resource: "https://en.wikipedia.org/w/index.php?title=Mazda_MX-5_(NA)&oldid=1381587107"
    title: "Wikipedia, \"Mazda MX-5 (NA)\", permanent revision 1381587107 (2026-10-23)"
x-silica:
  v: 1
  sources:
    wp-b-engine: { kind: http, url: "https://en.wikipedia.org/w/index.php?title=Mazda_B_engine&oldid=1381332751" }
    wp-na: { kind: http, url: "https://en.wikipedia.org/w/index.php?title=Mazda_MX-5_(NA)&oldid=1381587107" }
  facts:
    - id: specification
      at: { section: "Specification" }
      source: wp-b-engine
      mode: pinned
      extract: { kind: md-section, heading: "B6ZE(RS)" }
      pin: { sha256: "9738e906d17cc319b690a4d28e8765b2c88eca38f0fc259bb161e9ca9a1ddee9", rev: "sha256:839bdf0457d7d63505f0e4dac172dcde8ebe76503362a3426c0fa24b6ade1c0f", at: "2026-11-14T11:49:25Z", fact: "2d75a29afa0d19af7d199e49950e55399ea7b11f281f187a011ece2688907314" }
    - id: outputs-by-market
      at: { section: "Outputs by market" }
      source: wp-b-engine
      mode: pinned
      extract: { kind: md-section, heading: "B6ZE(RS)" }
      pin: { sha256: "9738e906d17cc319b690a4d28e8765b2c88eca38f0fc259bb161e9ca9a1ddee9", rev: "sha256:839bdf0457d7d63505f0e4dac172dcde8ebe76503362a3426c0fa24b6ade1c0f", at: "2026-11-14T11:49:25Z", fact: "d2712e96ac5b82e1c94d6c3e2cec2b7ca082c6cbf41896a2886c0e675de2a5aa" }
    - id: in-the-mx-5-na-article
      at: { section: "In the MX-5 (NA article)" }
      source: wp-na
      mode: pinned
      extract: { kind: md-section, heading: "Overview" }
      pin: { sha256: "a0d213fd056719a2f8672977f7b1a4af05febb200f8ba079a11992b9339ebd46", rev: "sha256:bda638195825802a57d650a56f5093c6bfd926047ae11a7e963501beeccc6c3c", at: "2026-11-14T11:49:25Z", fact: "4e132d3230720ebb28d3edb2c3bc0ca8a05af77cdd390e4c67a52fe97243c135" }
---

# Mazda B6ZE(RS) 1.6 L

## Specification

1.6 L (1,597 cc), DOHC 16-valve alloy head, lightened crankshaft and flywheel allowing a 7,200 rpm redline, and an aluminum sump with cooling fins; developed for the Miata (1989–05). [^wp-b-engine]

## Outputs by market

US and European (1990–1993): 115 hp (85 kW) at 6,500 rpm and 136 N⋅m (100 lb⋅ft) at 5,500 rpm. Later European (1994–1997): 90 hp (66 kW). 1998 to 2005: 110 hp (81 kW). Japanese: 120 hp (88 kW); after 1998 power was increased to 125 hp (92 kW). [^wp-b-engine]

## In the MX-5 (NA article)

Codenamed B6ZE(RS), the engine was designed for the MX-5, with electronic fuel injection using a vane-type air flow meter and a camshaft angle sensor instead of a distributor. [^wp-na]

## Related

- [MX-5 (NA), 1989–1997](/generations/na.md)
- [MX-5 NA1 (1.6 L), model years 1990–1993](/revisions/na1.md)
- [BP engine](/engines/bp.md)


[^wp-b-engine]: Wikipedia, "Mazda B engine", permanent revision 1381332751 (2026-10-21): <https://en.wikipedia.org/w/index.php?title=Mazda_B_engine&oldid=1381332751>
[^wp-na]: Wikipedia, "Mazda MX-5 (NA)", permanent revision 1381587107 (2026-10-23): <https://en.wikipedia.org/w/index.php?title=Mazda_MX-5_(NA)&oldid=1381587107>
