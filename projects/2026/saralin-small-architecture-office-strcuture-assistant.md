---
layout: project
title: "Structure Assistant: Embedding Structural Intelligence into Early Design"
author: Sara Lin
advisor: Joe Brennan
year: 2026
image: /img/2026/small-architecture-office-structure-assistant/cover.jpg
links:
    -text: Small Architecture Office Assistant Website
        url:https://saraaaalin.github.io/Small-Architecture-Office-Assistant/
    -text: Structure Assistant Website
        url:https://saraaaalin.github.io/Small-Architecture-Office-Assistant/structure-assistant.html
---

## Project Statement

Structure Assistant is a Rhino and Grasshopper-based design tool that embeds preliminary structural guidance into early architectural workflows. The project responds to a common problem in small architecture practices, where design decisions are often made before structural expertise becomes available.

Rather than replacing structural consultants, the tool supports architects during early design by translating structural rules of thumb, span logic, material selection, product-based sizing, and visualization feedback into an interactive computational workflow.

## Motivation

In many small architecture offices, design and expertise do not happen at the same time. Architects design, send drawings to consultants, wait for feedback, and then revise the design. This delay means that many early design decisions are made without immediate structural input.

Structure Assistant explores how structural knowledge can become more present during early-stage design, especially for small firms that may not have in-house structural consultants.

## System Overview

The tool connects a custom Rhino panel interface with a Grasshopper backend. Users select ceiling and floor slab geometry directly in Rhino, choose a material system, and receive preliminary feedback on beam layout, span direction, beam depth, product suggestions, and estimated cost range.

![Structure Assistant interface inside Rhino.](/img/2026/small-architecture-office-structure-assistant/ui.png)

## Workflow

The system follows a pipeline from geometric input to structural feedback:

1. Select floor and ceiling slab geometry in Rhino.
2. Detect slab dimensions and span directions.
3. Generate primary and secondary beam layouts.
4. Estimate preliminary beam depths based on material and span logic.
5. Match results to prefabricated structural products.
6. Visualize the result inside Rhino.
7. Optionally bake outputs and export results.

![Grasshopper system pipeline.](/img/2026/small-architecture-office-structure-assistant/pipeline.mp4)

## Demo

<video
  src="/img/2026/small-architecture-office-structure-assistant/demo.mp4"
  controls
  style="aspect-ratio: 16 / 9; width: 100%;">
</video>

## Technical Implementation

The project is built with Rhino 8, Grasshopper, and C#. A custom Eto WebView panel provides the user interface, while Grasshopper handles geometric analysis and rule-based structural computation. The communication between the Rhino panel and Grasshopper allows selected geometry and material input to be passed into the computational definition, with results returned to the interface.

The Grasshopper definition includes span detection, beam layout generation, preliminary depth sizing, product matching, budget estimation, baking, export, and visualization logic.

## Audience and Scope

This project is designed for small architecture practices, homeowners, co-op boards, landlords, and early-stage design teams working on small to mid-scale residential and commercial projects. The tool focuses on preliminary design feedback rather than final engineering calculation.

## Reflection

Structure Assistant proposes a workflow where architects do not need to wait until later design phases to receive basic structural feedback. By embedding structural intelligence into the design environment, the project helps make expertise more accessible while design decisions are still flexible.

The future direction of the project is to expand beyond structure and include other forms of embedded expertise, such as energy modeling, zoning analysis, code compliance, and environmental performance.