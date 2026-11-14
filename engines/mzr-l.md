---
type: Engine
title: "Mazda MZR L-series (L8 1.8 L, LF 2.0 L)"
description: "The MZR L-series four-cylinder engines used in the NC MX-5."
resource: "https://en.wikipedia.org/w/index.php?title=Mazda_L_engine&oldid=1385331779"
tags: [mazda, mx-5, miata, engine, l-series, mzr]
aliases: ["MZR", "LF-VE", "L8-DE", "L8-VE", "2.0 MZR", "1.8 MZR", "Duratec"]
status: stable
sources:
  - id: wp-l-engine
    resource: "https://en.wikipedia.org/w/index.php?title=Mazda_L_engine&oldid=1385331779"
    title: "Wikipedia, \"Mazda L engine\", permanent revision 1385331779 (2026-11-12)"
  - id: wp-nc
    resource: "https://en.wikipedia.org/w/index.php?title=Mazda_MX-5_(NC)&oldid=1381436898"
    title: "Wikipedia, \"Mazda MX-5 (NC)\", permanent revision 1381436898 (2026-10-22)"
x-silica:
  v: 1
  sources:
    wp-l-engine: { kind: http, url: "https://en.wikipedia.org/w/index.php?title=Mazda_L_engine&oldid=1385331779" }
    wp-nc: { kind: http, url: "https://en.wikipedia.org/w/index.php?title=Mazda_MX-5_(NC)&oldid=1381436898" }
  facts:
    - id: 1-8-l-l8
      at: { section: "1.8 L (L8)" }
      source: wp-l-engine
      mode: pinned
      extract: { kind: md-section, heading: "1.8 L (L8-DE, L8-VE)" }
      pin: { sha256: "10008d1f09849e64271bf16347cb472b92cf6a9d41a072227b28aba35a72a2bf", rev: "sha256:16a191c28f88739910cb252d7515873fd5dc0acfb5bafef88f0db0c6f6cea24a", at: "2026-11-14T11:31:46Z", fact: "b74ba40314b465a9e4c88ae9bf05ee5ef7d78f956a6f48abbd5389d71a641368" }
    - id: 2-0-l-lf
      at: { section: "2.0 L (LF)" }
      source: wp-l-engine
      mode: pinned
      extract: { kind: md-section, heading: "2.0 L (LF-DE, LF-VE, LF-VD)" }
      pin: { sha256: "c68dc1a01b7dcbefc2172ed3abe1399de47b8b925d4a7a256be22e38aa200bc5", rev: "sha256:16a191c28f88739910cb252d7515873fd5dc0acfb5bafef88f0db0c6f6cea24a", at: "2026-11-14T11:31:46Z", fact: "8a07c8d1f15b9b2b91de9d035fb2a94eb636b8b95fa79aa1d96245be3ec92b39" }
    - id: in-the-mx-5-nc-article
      at: { section: "In the MX-5 (NC article)" }
      source: wp-nc
      mode: pinned
      extract: { kind: md-section, heading: "2005—2008 (NC1)" }
      pin: { sha256: "eb5583dd773fb52a839635296607b031b5ed491267128ed8423d5f5ceffe5dc8", rev: "sha256:f4725821ab6e7446faa0f56c1a7a502d19f7a842e87e55f079b17a1408bd2d31", at: "2026-11-14T11:31:46Z", fact: "67f7b07e25ed00cb95d491037bed20331f6db097184dbc85dec1ca2e3a7314e2" }
---

# Mazda MZR L-series (L8 1.8 L, LF 2.0 L)

## 1.8 L (L8)

1,798 cc with an 83 mm bore and 83.1 mm stroke; 125 hp (92 kW) at 6000 rpm and 122 lb⋅ft (165 N⋅m) at 4250 rpm; used in the 2005-2015 Mazda MX-5 for Europe. [^wp-l-engine]

## 2.0 L (LF)

1,999 cc with a 10:1 compression ratio, 87.5 mm bore and 83.1 mm stroke; used in the 2006–2015 Roadster. [^wp-l-engine]

## In the MX-5 (NC article)

US: 2.0 L MZR LF-VE DOHC inline four-cylinder, 124 kW (166 hp) and 190 N⋅m (140 lbf⋅ft) with the 5-speed or 6-speed manual, or 118 kW (158 hp) with the optional 6-speed automatic. Europe also had a 1.8 L MZR L8-VE rated at 94 kW (126 bhp) and 167 N⋅m (123 lbf⋅ft). [^wp-nc]

## Related

- [MX-5 (NC), 2005–2015](/generations/nc.md)
- [MX-5 NC1, model years 2006–2008](/revisions/nc1.md)
- [MX-5 NC2 (2009 facelift), model years 2009–2012](/revisions/nc2.md)
- [MX-5 NC3 (2012 update), model years 2013–2015](/revisions/nc3.md)


[^wp-l-engine]: Wikipedia, "Mazda L engine", permanent revision 1385331779 (2026-11-12): <https://en.wikipedia.org/w/index.php?title=Mazda_L_engine&oldid=1385331779>
[^wp-nc]: Wikipedia, "Mazda MX-5 (NC)", permanent revision 1381436898 (2026-10-22): <https://en.wikipedia.org/w/index.php?title=Mazda_MX-5_(NC)&oldid=1381436898>
