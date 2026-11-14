---
type: Vehicle Revision
title: "MX-5 NB1 (pre-facelift), 1998–2000"
description: "NB1 revision of the NB MX-5: launch, BP-4W engine, features and the 10th Anniversary Model."
tags: [mazda, mx-5, miata, nb, nb1]
aliases: ["NB1", "early NB", "pre-facelift NB", "10AE"]
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
    - id: model-years-nb-article
      at: { section: "Model years (NB article)" }
      source: wp-nb
      mode: pinned
      extract: { kind: md-section, heading: "Overview" }
      pin: { sha256: "795a29c00a11d32b79dbf7953ee899a6feb07244b63af8e72e0527099b2084c3", rev: "sha256:778980889258777eea626b61a1a715253cc4b66c9bc18fee54d1b2a7148fcbe8", at: "2026-11-14T11:31:46Z", fact: "c30a87641d267f5a33f95f86622cdb84b5f36aae2391fa529262b9781a0888cc" }
    - id: model-years-mx5-article
      at: { section: "Model years (MX-5 article)" }
      source: wp-mx5
      mode: pinned
      extract: { kind: md-section, heading: "Second generation – NB (1998–2005)" }
      pin: { sha256: "ff6045ce35aff9c70e49cd2417d62cbbeae49b0579140ffdb2c0e6b80b0d14c1", rev: "sha256:b96cb41d926071821490db5697fd311eccc0299e8afdf5870eae5f130f177006", at: "2026-11-14T11:31:46Z", fact: "3d8a4d4a8dab068798c0ec32513672be83d0cb6b9bc913c849300505338b5a0b" }
    - id: engine
      at: { section: "Engine" }
      source: wp-nb
      mode: pinned
      extract: { kind: md-section, heading: "Overview" }
      pin: { sha256: "795a29c00a11d32b79dbf7953ee899a6feb07244b63af8e72e0527099b2084c3", rev: "sha256:778980889258777eea626b61a1a715253cc4b66c9bc18fee54d1b2a7148fcbe8", at: "2026-11-14T11:31:46Z", fact: "a01098808236ceea8ff34af5337926869a90acc105dd923398541aed7f0adf8b" }
    - id: output-uk-table
      at: { section: "Output (UK table)" }
      source: wp-nb
      mode: pinned
      extract: { kind: md-section, heading: "Technical specifications (UK)" }
      pin: { sha256: "898a530d4f89ee6043a9923e358c48bb215ae881aa0e9eb87c3c3410e62ebdb3", rev: "sha256:778980889258777eea626b61a1a715253cc4b66c9bc18fee54d1b2a7148fcbe8", at: "2026-11-14T11:31:46Z", fact: "3761084abc6916c338fb13800f329266d309ab8d9a7a509d8bff2435c889c119" }
    - id: output-b-engine-article
      at: { section: "Output (B engine article)" }
      source: wp-b-engine
      mode: pinned
      extract: { kind: md-section, heading: "BP-4W" }
      pin: { sha256: "c84f70950c376990e62f8e889e0617d15a48ba57db98b3200cfb2a32d6992381", rev: "sha256:839bdf0457d7d63505f0e4dac172dcde8ebe76503362a3426c0fa24b6ade1c0f", at: "2026-11-14T11:31:46Z", fact: "81e5b5629a8620622d473d6f10c9ea3637251a28aa4164ddc4562dd2d9e0f26b" }
    - id: performance
      at: { section: "Performance" }
      source: wp-nb
      mode: pinned
      extract: { kind: md-section, heading: "Overview" }
      pin: { sha256: "795a29c00a11d32b79dbf7953ee899a6feb07244b63af8e72e0527099b2084c3", rev: "sha256:778980889258777eea626b61a1a715253cc4b66c9bc18fee54d1b2a7148fcbe8", at: "2026-11-14T11:31:46Z", fact: "0f4e3b499818a57c28a55414cc48d11e80702e970d43c7e3d747fb4531690e69" }
    - id: features
      at: { section: "Features" }
      source: wp-nb
      mode: pinned
      extract: { kind: md-section, heading: "Overview" }
      pin: { sha256: "795a29c00a11d32b79dbf7953ee899a6feb07244b63af8e72e0527099b2084c3", rev: "sha256:778980889258777eea626b61a1a715253cc4b66c9bc18fee54d1b2a7148fcbe8", at: "2026-11-14T11:31:46Z", fact: "da88ac149716edf34a004d9111764e382a43e1bfa9a994774518d7e90e173f1b" }
    - id: 10th-anniversary-model
      at: { section: "10th Anniversary Model" }
      source: wp-nb
      mode: pinned
      extract: { kind: md-section, heading: "MX-5 10th Anniversary Model (1999)" }
      pin: { sha256: "8476f321ef66f02df85790dbdf122525b2609780df1c23871532d4f0ee22866f", rev: "sha256:778980889258777eea626b61a1a715253cc4b66c9bc18fee54d1b2a7148fcbe8", at: "2026-11-14T11:31:46Z", fact: "ea1e6c9fe9404da43f0149d24a3f99826d2dc422be7baa3c5ac7d00963d5f38b" }
---

# MX-5 NB1 (pre-facelift), 1998–2000

## Model years

Sources disagree on the NB's first model year; both are recorded.

### Model years (NB article)

Released in February 1998 for the 1998 model year. [^wp-nb]

### Model years (MX-5 article)

Sold beginning in 1998 for the 1999 model year; changed in 2001 (NB2). [^wp-mx5]

## Engine

BP-4W 1.8 L: compression raised from 9.0:1 to 9.5:1 and Mazda's Variable Intake Control System added; 104.4 kW (140.0 bhp) and 157 N⋅m (116 lbf⋅ft). The 1.6 L (98 cu in) B6 engine remained available in Europe and Japan. [^wp-nb]

## Output disagreement

Sources give different figures for the BP-4W.

### Output (UK table)

UK 1.8i, 1998–2001: 100 kW (140 bhp) @ 6,500 and 161 N⋅m (119 ft⋅lbf) @ 5,000. [^wp-nb]

### Output (B engine article)

BP-4W: initially 140 hp at 6500 rpm and 119 lb·ft at 5000 rpm. [^wp-b-engine]

## Performance

The base-model NB reached 62 mph in 7.8 s and had a top speed of 130 mph. [^wp-nb]

## Features

Fixed headlamps replaced the retractable units; glass rear window with defogger; optional hinged wind deflector; anti-lock braking system optional; 14-inch or 15-inch alloy wheels depending on trim; Cd=0.36. [^wp-nb]

## 10th Anniversary Model

7,500 units for 1999 in Sapphire Blue Mica (Innocent Blue in Japan), with a 6-speed manual, Bilstein shock absorbers, a Torsen limited-slip differential and 15 inch polished wheels; MSRP $26,875. [^wp-nb]

## Related

- [MX-5 (NB), 1998–2005](/generations/nb.md)
- [1998 Mazda MX-5](/model-years/1998.md)
- [1999 Mazda MX-5](/model-years/1999.md)
- [2000 Mazda MX-5](/model-years/2000.md)


[^wp-nb]: Wikipedia, "Mazda MX-5 (NB)", permanent revision 1381623005 (2026-10-23): <https://en.wikipedia.org/w/index.php?title=Mazda_MX-5_(NB)&oldid=1381623005>
[^wp-mx5]: Wikipedia, "Mazda MX-5", permanent revision 1384156481 (2026-11-06): <https://en.wikipedia.org/w/index.php?title=Mazda_MX-5&oldid=1384156481>
[^wp-b-engine]: Wikipedia, "Mazda B engine", permanent revision 1381332751 (2026-10-21): <https://en.wikipedia.org/w/index.php?title=Mazda_B_engine&oldid=1381332751>
