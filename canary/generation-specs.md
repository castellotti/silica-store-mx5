---
type: Specification Table
title: "Canary: MX-5 generation specs"
description: "Derived facts read from the store's own canary files, through file and git sources, for controlled drift testing."
tags: [mazda, mx-5, miata, canary]
aliases: ["canary", "drift test", "generation specs", "wheelbase by generation"]
status: stable
sources:
  - id: canary-specs-file
    resource: "https://github.com/castellotti/silica-store-mx5/blob/main/canary/specs.json"
    title: "Canary data file canary/specs.json (this store)"
  - id: canary-specs-git
    resource: "https://github.com/castellotti/silica-store-mx5/blob/main/canary/specs.json"
    title: "canary/specs.json in castellotti/silica-store-mx5 (main)"
  - id: canary-milestones-file
    resource: "https://github.com/castellotti/silica-store-mx5/blob/main/canary/milestones.yaml"
    title: "Canary data file canary/milestones.yaml (this store)"
  - id: canary-milestones-git
    resource: "https://github.com/castellotti/silica-store-mx5/blob/main/canary/milestones.yaml"
    title: "canary/milestones.yaml in castellotti/silica-store-mx5 (main)"
x-silica:
  v: 1
  sources:
    canary-specs-file: { kind: file, path: "canary/specs.json" }
    canary-specs-git: { kind: git, repo: "https://github.com/castellotti/silica-store-mx5", ref: main, path: "canary/specs.json" }
    canary-milestones-file: { kind: file, path: "canary/milestones.yaml" }
    canary-milestones-git: { kind: git, repo: "https://github.com/castellotti/silica-store-mx5", ref: main, path: "canary/milestones.yaml" }
  facts:
    - id: na-code
      at: { section: "NA code" }
      source: canary-specs-file
      mode: derived
      extract: { kind: json-pointer, pointer: "/generations/0/code" }
    - id: na-production
      at: { section: "NA production" }
      source: canary-specs-file
      mode: derived
      extract: { kind: json-pointer, pointer: "/generations/0/production" }
    - id: na-wheelbase-mm
      at: { section: "NA wheelbase (mm)" }
      source: canary-specs-file
      mode: derived
      extract: { kind: json-pointer, pointer: "/generations/0/wheelbase_mm" }
    - id: nb-wheelbase-mm
      at: { section: "NB wheelbase (mm)" }
      source: canary-specs-file
      mode: derived
      extract: { kind: json-pointer, pointer: "/generations/1/wheelbase_mm" }
    - id: na-engines
      at: { codeblock: { section: "NA engines", index: 0 } }
      source: canary-specs-file
      mode: derived
      extract: { kind: json-pointer, pointer: "/generations/0/engines" }
    - id: nc-wheelbase-mm
      at: { section: "NC wheelbase (mm)" }
      source: canary-specs-git
      mode: derived
      extract: { kind: json-pointer, pointer: "/generations/2/wheelbase_mm" }
    - id: nd-wheelbase-mm
      at: { section: "ND wheelbase (mm)" }
      source: canary-specs-git
      mode: derived
      extract: { kind: json-pointer, pointer: "/generations/3/wheelbase_mm" }
    - id: nd-production
      at: { section: "ND production" }
      source: canary-specs-git
      mode: derived
      extract: { kind: json-pointer, pointer: "/generations/3/production" }
    - id: one-millionth-mx-5
      at: { section: "One millionth MX-5" }
      source: canary-milestones-file
      mode: derived
      extract: { kind: json-pointer, pointer: "/milestones/2/date" }
    - id: guinness-record-units
      at: { section: "Guinness record units (2000)" }
      source: canary-milestones-git
      mode: derived
      extract: { kind: json-pointer, pointer: "/guinness_record_2000/units" }
---

# Canary: MX-5 generation specs

## NA code

NA [^canary-specs-file]

## NA production

1989–1997 [^canary-specs-file]

## NA wheelbase (mm)

2265 [^canary-specs-file]

## NB wheelbase (mm)

2270 [^canary-specs-file]

## NA engines

```json
[
  "B6ZE(RS)",
  "BP-ZE"
]
```

Source: [^canary-specs-file]

## NC wheelbase (mm)

2330 [^canary-specs-git]

## ND wheelbase (mm)

2310 [^canary-specs-git]

## ND production

2015–present [^canary-specs-git]

## One millionth MX-5

2016-04-22 [^canary-milestones-file]

## Guinness record units (2000)

531890 [^canary-milestones-git]

## Related

- [MX-5 (NA), 1989–1997](/generations/na.md)
- [MX-5 (NB), 1998–2005](/generations/nb.md)
- [MX-5 (NC), 2005–2015](/generations/nc.md)
- [MX-5 (ND), 2015–present](/generations/nd.md)
- [Mazda MX-5](/model/mx-5.md)


[^canary-specs-file]: Canary data file canary/specs.json (this store): <https://github.com/castellotti/silica-store-mx5/blob/main/canary/specs.json>
[^canary-specs-git]: canary/specs.json in castellotti/silica-store-mx5 (main): <https://github.com/castellotti/silica-store-mx5/blob/main/canary/specs.json>
[^canary-milestones-file]: Canary data file canary/milestones.yaml (this store): <https://github.com/castellotti/silica-store-mx5/blob/main/canary/milestones.yaml>
[^canary-milestones-git]: canary/milestones.yaml in castellotti/silica-store-mx5 (main): <https://github.com/castellotti/silica-store-mx5/blob/main/canary/milestones.yaml>
