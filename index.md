---
okf_version: "0.2"
---

# Mazda MX-5 knowledge store

A [Silica](https://github.com/castellotti/silica) knowledge store about the Mazda MX-5 ("Miata", "Roadster",
"Eunos Roadster"): each generation (NA, NB, NC, ND), each North American model year from 1990 to 2026,
and the revisions within each generation (NA1–ND3).

Every fact names its source, and Silica can fetch that source again and check the fact in code. The
sources are permanent revisions of English Wikipedia articles (`oldid` links that never change), plus
this store's own canary files. Facts are short statements in our own words, or values copied exactly
from the source. Where sources disagree, both figures are recorded, each with its own source, rather
than one being chosen. A section that reads _Not found._ is a known gap, waiting to be researched.
Colors and recalls are the largest gaps, because the cited articles do not cover them.

## Contents

* [Model](model/index.md) - the MX-5 as a whole, and a glossary of codes
* [Generations](generations/index.md) - NA, NB, NC and ND
* [Revisions](revisions/index.md) - NA1, NA2, NB1, NB2, NC1, NC2, NC3, ND1, ND2, ND3
* [Model years](model-years/index.md) - 1990 to 2026
* [Engines](engines/index.md) - B6ZE(RS), BP, MZR L-series, Skyactiv-G
* [Awards](awards/index.md) - Car of the Year Japan, World Car Awards, Car and Driver 10Best
* [Related](related/index.md) - Fiat 124 Spider, MX-5 Cup
* [Canary](canary/index.md) - controllable sources for drift testing

## Canary sources

`canary/specs.json` and `canary/milestones.yaml` hold small, *correct* extracts of values cited
elsewhere in this store (wheelbases, production years, engine codes and production milestones).
[Canary: MX-5 generation specs](canary/generation-specs.md) derives facts from them in two ways:
through `file` sources (the working tree) and through `git` sources (the same files on `main` of
`https://github.com/castellotti/silica-store-mx5`).

To test drift, change one value in a canary file and run
`silica verify canary/generation-specs#na-wheelbase-mm`. The verifier should report `drifted`,
with the new value attached. Restore the file afterwards. For a `git` fact, the change has to be
on `main` before the verifier sees it. The canary data must stay true: it is a source we control,
not invented content.

## Conventions

* Model years are North American unless a fact says otherwise. A magazine list year (such as a
  10Best year) is recorded as published.
* NA1/NA2 is this store's own label for the 1.6 L and 1.8 L NA (see the
  [glossary](model/glossary.md)). The other revision codes come from the cited articles.
