---
layout: project
title: "Pass It On: A Forward-Facing Chain of Custody for Clothing"
author: Violet Hyun
year: 2026
image: /img/2026/pass-it-on/thumbnail.png
links:
  - text: Prototype
    url: https://passit-on-lac.vercel.app
  - text: Video
    url: https://www.youtube.com/watch?v=cCqaJpkksS4
---

![Pass It On — speculative product and physical prototype for a visible garment chain of custody.](/img/2026/pass-it-on/thumbnail.png)

**Pass It On** is a speculative product and physical prototype that explores how garments can carry a visible chain of custody.

The project asks a simple question: *what if clothing could retain memory?*

Today, most garments lose their history the moment they are sold. We know little about where they came from, who wore them, or how they moved through different lives. This absence of memory contributes to a culture in which clothing is treated as disposable.

Pass It On introduces a mobile platform and NFC-enabled garment tag that records ownership over time. By scanning the tag, users can access a **garment passport** that reveals material information, ownership history, and notes left by previous owners.

The goal is to shift how people define value—from novelty to narrative.

<br>

## Research

To understand why clothing remains unused, I surveyed **50 participants** between the ages of 19 and 26 and conducted **8 follow-up interviews**.

Three recurring themes emerged:

1. **Overconsumption** — people buy more than they need.
2. **Disposal anxiety** — people feel guilty letting go of clothing.
3. **Friction** — reselling and donating require too much effort.

These behaviors create a self-reinforcing loop in which unwanted garments remain stored rather than recirculated.

<br>

## Design Strategy

The project focuses on the **handoff moment**.

If releasing clothing feels emotionally rewarding, users are more likely to let items circulate.

The design strategy is built around three principles:

- **Reward the release**
- **Make demand visible**
- **Replace guilt with story**

<br>

## System Overview

Pass It On combines a **mobile marketplace** with a **physical NFC tag** embedded in the garment.

The mobile app is organized into four main areas:

- **Explore** — Discover available garments.
- **My Closet** — Manage outgoing items.
- **My Bag** — Track incoming items.
- **Profile** — View ReLeaf points and ownership history.

The physical prototype consists of a fabric hang tag containing an NFC chip. Scanning the tag opens the garment passport.

<br>

## Garment Passport

Each garment has a dedicated digital record containing:

- Product information
- Material details
- Supply chain transparency
- Chain of custody
- Messages from previous owners

This transforms the garment into a **living record** rather than a static object.

<br>

## Prototype

The prototype was built in **Next.js** and deployed on **Vercel**. It demonstrates a full end-to-end flow from listing a garment to transferring it to a new owner.

Interactive preview (embedded live app):

<iframe
  src="https://passit-on-lac.vercel.app"
  title="Pass It On — live prototype on Vercel"
  loading="lazy"
  referrerpolicy="no-referrer-when-downgrade"
  style="width: 100%; min-height: 720px; border: 1px solid rgba(0,0,0,0.12); border-radius: 8px;">
</iframe>

If the preview does not load here (some browsers block embedding), [open the prototype in a new tab](https://passit-on-lac.vercel.app).

<iframe
  src="https://www.youtube.com/embed/cCqaJpkksS4"
  frameborder="0"
  allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture; web-share"
  allowfullscreen
  style="aspect-ratio: 16 / 9; width: 100%;">
</iframe>

<br>

## Reflection

Pass It On reframes secondhand clothing as a **carrier of memory**.

By making ownership visible, the project suggests that garments can gain value as they move through more lives.

Instead of asking, *“Who owned this before me?”* the project asks:

> *“What stories become possible when we choose to pass it on?”*
