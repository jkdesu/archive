---
layout: project
title: "STRUCTURE ASSISTANT: EMBEDDING STRUCTURAL INTELLIGENCE INTO EARLY DESIGN"
title_line_1: "STRUCTURE ASSISTANT:"
title_line_2: "EMBEDDING STRUCTURAL INTELLIGENCE INTO EARLY DESIGN"
title_one_line: true
author: Sara Lin
advisor: Joe Brennan
year: 2026
image: /img/2026/small-architecture-office-structure-assistant/cover.png
header_image: true
justify_content: true
links_as_buttons: true
links:
  - text: Small Architecture Office Assistant Website
    url: https://saraaaalin.github.io/Small-Architecture-Office-Assistant/
  - text: Structure Assistant Website
    url: https://saraaaalin.github.io/Small-Architecture-Office-Assistant/structure-assistant.html
---

## Project Statement

Structure Assistant is a Rhino and Grasshopper-based design tool that embeds preliminary structural guidance into early architectural workflows. The project responds to a common problem in small architecture practices, where design decisions are often made before structural expertise becomes available.

Rather than replacing structural consultants, the tool supports architects during early design by translating structural rules of thumb, span logic, material selection, product-based sizing, and visualization feedback into an interactive computational workflow.

## Motivation

In many small architecture offices, design and expertise do not happen at the same time. Architects design, send drawings to consultants, wait for feedback, and then revise the design. This delay means that many early design decisions are made without immediate structural input.

Structure Assistant explores how structural knowledge can become more present during early-stage design, especially for small firms that may not have in-house structural consultants.

<figure class="figure-caption-single-line">
  <img
    src="/img/2026/small-architecture-office-structure-assistant/timeline.png"
    alt="Traditional versus integrated workflow: consultation embedded in design." />
  <figcaption>Traditional versus integrated workflow: consultation embedded in design.</figcaption>
</figure>

## System Overview

The project is built with Rhino 8, Grasshopper, and C#. A custom Eto WebView panel provides the user interface, while Grasshopper handles geometric analysis and rule-based structural computation. The communication between the Rhino panel and Grasshopper allows selected geometry and material input to be passed into the computational definition, with results returned to the interface.

The Grasshopper definition includes span detection, beam layout generation, preliminary depth sizing, product matching, budget estimation, baking, export, and visualization logic.

<figure class="figure--column-width">
  <img
    src="/img/2026/small-architecture-office-structure-assistant/system-overview.png"
    alt="Development process: from expertise to computation to real-time feedback." />
  <figcaption>Development process: from expertise to computation to real-time feedback.</figcaption>
</figure>

## Grasshopper Backend Design Logic

The system follows a pipeline from geometric input to structural feedback:

1. Select floor and ceiling slab geometry in Rhino.
2. Detect slab dimensions and span directions.
3. Generate primary and secondary beam layouts.
4. Estimate preliminary beam depths based on material and span logic.
5. Match results to prefabricated structural products.
6. Visualize the result inside Rhino.
7. Optionally bake outputs and export results.

<video
  src="/img/2026/small-architecture-office-structure-assistant/pipeline.mp4"
  controls
  style="aspect-ratio: 16 / 9; width: 100%;">
</video>

## Plugin Rhino Interface

The tool connects a custom Rhino panel interface with a Grasshopper backend. Users select ceiling and floor slab geometry directly in Rhino, choose a material system, and receive preliminary feedback on beam layout, span direction, beam depth, product suggestions, and estimated cost range.

<video
  src="/img/2026/small-architecture-office-structure-assistant/demo.mp4"
  controls
  autoplay
  loop
  muted
  playsinline
  style="aspect-ratio: 16 / 9; width: 100%;">
</video>

## Product Layer

Along with the tool itself, I also developed a product layer: a website.

The website explains, distributes, and documents the system, making it accessible to target users. It also provides installation guidance and direct download access, so the tool can be easily adopted by people with no computational background.

<video
  src="/img/2026/small-architecture-office-structure-assistant/website-walkthrough.mp4"
  controls
  playsinline
  style="aspect-ratio: 16 / 9; width: 100%;">
</video>

## Scope of Future

Looking forward, this project is expected to expand beyond structure. The goal is to build a system where multiple forms of expertise are embedded into design workflows, including energy modeling, code compliance, zoning analysis, and environmental performance.

Instead of architects waiting for different consultants at different stages, they can interact with a system that provides layered intelligence in real time.

The future is not about replacing experts, but about making expertise continuously present during design.

<figure class="figure--column-width">
  <img
    src="/img/2026/small-architecture-office-structure-assistant/scope-of-future.png"
    alt="Multi-Consultant Assistant System: embedded design intelligence modules for structure, MEP, zoning, landscape, envelope, and sustainability." />
  <figcaption>Multi-Consultant Assistant System: embedded design intelligence across multiple domains.</figcaption>
</figure>
