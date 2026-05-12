---
layout: project
title: "HAI, A Garment Intelligence System"
author: Chelsea Hai
year: 2026
image: /img/2026/hai-a-garment-intelligence-system/main-image.jpg
links:
  - text: Website
    url: https://chelseahai.github.io/review_proposal/
---

![HAI project main image.](/img/2026/hai-a-garment-intelligence-system/main-image.jpg)

This page mirrors the **review_proposal** documentation: the same narrative, media, and structure as the live site. The embedded view below is the full interactive experience (layout, scroll, and pipeline diagram). Under it, the same content is reproduced as static text, images, and videos so it remains readable even if embedding is blocked.

## Interactive documentation (full site)

<iframe
  src="https://chelseahai.github.io/review_proposal/"
  title="HAI — Garment intelligence system documentation"
  loading="lazy"
  referrerpolicy="strict-origin-when-cross-origin"
  style="border: 0; width: 100%; min-height: 90vh; aspect-ratio: unset;">
</iframe>

If the preview does not load, [open the full documentation in a new tab](https://chelseahai.github.io/review_proposal/).

---

## Intro

> "Every garment is a brand new start."

**A system that listens, computes, and translates human context into what we wear.**

Human Context + Computational System = Fabricated Garment + Adaptive Experience

---

## Theme

**Q: What is the context this project begins with?**

A: Fashion, or ready-to-wear garments are built on many decisions, while people and environments are changing all the time. This system recognizes that difference, and tries to propose an alternative relationship.

**Q: How does the system involve the wearer?**

A: The wearer's physical body and daily context become the beginning of the design logic, so each garment iteration reflects the life it was made for.

**Q: How is data used here?**

A: Data acts as a design material, environmental, spatial, bodily, and emotional inputs collectively shape the garment form.

**Q: How does this system reinterpret garment function?**

A: Function becomes responsive rather than assigned. The hope is to bring function, aesthetic, and fabrication of the garment as one process.

**Q: Why 3D printing?**

A: It replaces the finality of cut fabric, allowing material to be formed, used, recycled, reclaimed, and reformed, without waste. Material circularity and on-demand fabrication can both contribute to a more sustainable industry.

**Q: What does this mean culturally?**

A: It shifts fashion away from hierarchy to a shared authorship between experience, environment, and design.

**Q: And what does this system propose for the future of wear?**

A: A circular, computational process where garments continually evolve alongside the people who live in them.

---

## Pipeline (static reference)

The live site includes an interactive tech pipeline map (React). Below is the same **pipeline map** graphic used on the site.

![Pipeline map.](/img/2026/hai-a-garment-intelligence-system/pipeline-map.jpg)

---

## The body input

**THE BODY INPUT**

The system offers two solutions, 3D scanning the body or simply put in your measurements.

![Body measurement.](/img/2026/hai-a-garment-intelligence-system/measureurself.gif)

![Body measurements.](/img/2026/hai-a-garment-intelligence-system/8measurements.gif)

#### Measure yourself for

- Upper Bust **78**
- Bust **80**
- Under Bust **74**
- Waist **60**
- Upper Hip **78**
- Hip **90**
- B to W **13**
- W to H **20**

The data forms a live parametric model that updates in real time.

![Body geometry.](/img/2026/hai-a-garment-intelligence-system/bodygeometry.gif)

This step establishes the baseline geometry for garment generation.

---

## The context input

**THE CONTEXT INPUT**

Simply answer the question

**"What are you doing for today?"**

The system reads your context, processes it, pulls the relevant data, and calculates what you need to wear for that day.

<video src="/img/2026/hai-a-garment-intelligence-system/videos/talking01_04.mp4" controls muted playsinline loop style="aspect-ratio: 16 / 9; width: 100%;"></video>

![Text analysis.](/img/2026/hai-a-garment-intelligence-system/text-analysis.jpg)

**Fit**

`Fit = 1 - [0.30 × temp_norm - 0.25 × activity_norm + 0.15 × (1 - comfort_pref_norm) + 0.20 × containment_norm + 0.10 × spatial_norm]`

**Mesh**

`Mesh = 0.35 × temp_norm + 0.25 × (1 - activity_norm) + 0.20 × formality_norm + 0.20 × aesthetic_norm`

**Thickness**

`Thickness = 0.50 × temp_norm + 0.25 × wind_norm + 0.25 × exposure_norm`

**Airflow**

`Airflow = 1 - [0.35 × temp_norm + 0.25 × humidity_norm + 0.25 × activity_norm - 0.15 × outdoor_norm]`

**Support**

`Support = 0.35 × demand_norm + 0.25 × stability_norm + 0.25 × formality_norm + 0.15 × wind_norm`

Example parameter readouts (first block): Fit **0.73**, Mesh **0.42**, Thickness **0.89**, Airflow **0.15**, Support **0.67**.

<video src="/img/2026/hai-a-garment-intelligence-system/videos/talking02_01.mp4" controls muted playsinline loop style="aspect-ratio: 16 / 9; width: 100%;"></video>

Second block: Fit **0.31**, Mesh **0.58**, Thickness **0.94**, Airflow **0.26**, Support **0.81**.

<video src="/img/2026/hai-a-garment-intelligence-system/videos/talking03_03.mp4" controls muted playsinline loop style="aspect-ratio: 16 / 9; width: 100%;"></video>

Third block: Fit **0.52**, Mesh **0.19**, Thickness **0.76**, Airflow **0.38**, Support **0.64**.

<video src="/img/2026/hai-a-garment-intelligence-system/videos/talking04.mp4" controls muted playsinline loop style="aspect-ratio: 16 / 9; width: 100%;"></video>

Fourth block: Fit **0.47**, Mesh **0.83**, Thickness **0.29**, Airflow **0.56**, Support **0.92**.

---

## The garment generation

**THE GARMENT GENERATION**

<video src="/img/2026/hai-a-garment-intelligence-system/garment-logic.mov" controls muted playsinline loop style="aspect-ratio: 16 / 9; width: 100%;"></video>

![Garment generation.](/img/2026/hai-a-garment-intelligence-system/garment-generation-01.jpg)

<video src="/img/2026/hai-a-garment-intelligence-system/garment-generations.mp4" controls muted playsinline loop style="aspect-ratio: 16 / 9; width: 100%;"></video>

---

## The fabrication

**THE FABRICATION**

The generated geometry compiles into print-ready code.

Printed in flexible TPU, each layer follows the parametric form exactly.

Localized fabrication compresses the lifecycle, no global shipping, no mass storage, no distance between maker and wearer.

Shorter cycles, smaller footprint, stronger connection.

**Data → Geometry → Code → Print → Wear**

![Fabrication 01.](/img/2026/hai-a-garment-intelligence-system/fab-01.jpg)

![Fabrication 02 (test prints).](/img/2026/hai-a-garment-intelligence-system/fab-02.jpg)

*Additional fabrication sequence video appears on the [live documentation site](https://chelseahai.github.io/review_proposal/) (`Sequence 02.mp4` in the source project).*

---

## Impact

Each garment is generated from the context of life itself: weather, movement, emotion, intent, and more. It's not fashion reacting to trend, but form reacting to existence.

Instead of searching for identity, the wearer creates it. Instead of fitting into a system, the system fits around them.

The body becomes the designer. The garment becomes the record.

### Picture grid

![Picture 2.](/img/2026/hai-a-garment-intelligence-system/pictures/P02.jpg)

![Picture 29.](/img/2026/hai-a-garment-intelligence-system/pictures/P29.jpg)

![Picture 1.](/img/2026/hai-a-garment-intelligence-system/pictures/P01.jpg)

![Picture 10.](/img/2026/hai-a-garment-intelligence-system/pictures/P10.jpg)

![Picture 9.](/img/2026/hai-a-garment-intelligence-system/pictures/P09.jpg)

![Picture 13.](/img/2026/hai-a-garment-intelligence-system/pictures/P13.jpg)

![Picture 4.](/img/2026/hai-a-garment-intelligence-system/pictures/P04.jpg)

![Picture 15.](/img/2026/hai-a-garment-intelligence-system/pictures/P15.jpg)

![Picture 19.](/img/2026/hai-a-garment-intelligence-system/pictures/P19.jpg)

![Picture 21.](/img/2026/hai-a-garment-intelligence-system/pictures/P21.jpg)

![Picture 16.](/img/2026/hai-a-garment-intelligence-system/pictures/P16.jpg)

![Picture 6.](/img/2026/hai-a-garment-intelligence-system/pictures/P06.jpg)

![Picture 23.](/img/2026/hai-a-garment-intelligence-system/pictures/P23.jpg)

![Picture 22.](/img/2026/hai-a-garment-intelligence-system/pictures/P22.jpg)

![Picture 11.](/img/2026/hai-a-garment-intelligence-system/pictures/P11.jpg)

![Picture 20.](/img/2026/hai-a-garment-intelligence-system/pictures/P20.jpg)

![Picture 26.](/img/2026/hai-a-garment-intelligence-system/pictures/P26.jpg)

![Picture 5.](/img/2026/hai-a-garment-intelligence-system/pictures/P05.jpg)

![Picture 17.](/img/2026/hai-a-garment-intelligence-system/pictures/P17.jpg)

![Picture 3.](/img/2026/hai-a-garment-intelligence-system/pictures/P03.jpg)

![Picture 8.](/img/2026/hai-a-garment-intelligence-system/pictures/P08.jpg)

![Picture 7.](/img/2026/hai-a-garment-intelligence-system/pictures/P07.jpg)

![Picture 14.](/img/2026/hai-a-garment-intelligence-system/pictures/P14.jpg)

![Picture 28.](/img/2026/hai-a-garment-intelligence-system/pictures/P28.jpg)

![Picture 18.](/img/2026/hai-a-garment-intelligence-system/pictures/P18.jpg)

![Picture 12.](/img/2026/hai-a-garment-intelligence-system/pictures/P12.jpg)

![Picture 24.](/img/2026/hai-a-garment-intelligence-system/pictures/P24.JPG)

![Picture 25.](/img/2026/hai-a-garment-intelligence-system/pictures/P25.jpg)

![Picture 27.](/img/2026/hai-a-garment-intelligence-system/pictures/P27.jpg)

![Picture 30.](/img/2026/hai-a-garment-intelligence-system/pictures/P30.jpg)

---

## Closing

It doesn't tell someone else's story.  
It listens to yours.
