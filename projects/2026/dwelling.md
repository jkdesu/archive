---
layout: project
title: "Dwelling: Reconstructing Spaces through Attention"
author: Benny Yang
advisor: Seth Thompson
year: 2026
image: /img/2026/dwelling/dwelling.gif
links:
  - text: About the Author
    url: https://www.bennyyyang.com/
---



We assume space is stable. 

But what we experience is selective.

We never see everything. 

We see what we attend to.

Perception is an active filtering process. So this project begins with a simple inversion:

What if attention left spatial traces?


![ ](/img/2026/dwelling/packing.png)

My family is currently moving out of my childhood home.

And during this process, I realized something.

I don’t remember the house as a whole.

I remember fragments. 

Specific objects. 

Corners. 

Moments I kept returning to.

![ ](/img/2026/dwelling/references.png)


Moholy-Nagy argued photography generates new visual knowledge.

Crary reframed the photograph as intimate and subjective.

Barthes explores the effects of photography on the spectator.

The camera is never neutral. It structures perception.

![ ](/img/2026/dwelling/punctum.png)


Barthes describes the punctum as the detail that pierces you.

Traditional photography captures the scene, but what stays with us is not the whole image.

It’s the specific detail that we dwell on.

This project shifts the question from:

What did you see?

to:

How did you look?

<video
  src="/img/2026/dwelling/demo.mov"
  controls
  style="aspect-ratio: 16 / 9; width: 100%; ">
</video>

The system works by combining two cameras on the iphone.

The front camera sees eye direction. 

The rear camera captures the environment.

A gaze vector is projected outward, thus estimating the area the user is looking at.

So instead of recording images, the system records spatial traces.

![ ](/img/2026/dwelling/framework1.png)

From this data, a structure begins to emerge.

Attention is not static: It accumulates. It moves. It leaves gaps.

And these gaps are not noise. They are fundamental to how we perceive space.

![ ](/img/2026/dwelling/framework2.png)

When attention lingers, density builds.

<video
  src="/img/2026/dwelling/accumulate.mov"
  controls
  style="aspect-ratio: 16 / 9; width: 100%; ">
</video>

When attention scans, it forms trajectories.

Here footages is sampled at 10 frames per second. 

Each frame deposited a fixation point onto a spatial board.

When you move your eyes slowly, clusters form where the gaze paused.

When you move quickly, the path becomes sparse.


![ ](/img/2026/dwelling/move.png)

And across any environment, large portions receive little to no attention at all.

Perception is not continuous, but selective.

![ ](/img/2026/dwelling/gap.png)

From this premise, the project branches into two parts of a whole: 

The Residual Space and Sites of Dwelling.

Both begin from the same dataset, but they interpret attention differently.


The Residual space asks:

What happens if attention removes space?



<video
  src="/img/2026/dwelling/data.mov"
  controls
  style="aspect-ratio: 16 / 9; width: 100%; ">
</video>




Each gaze recording is processed through a spatial reconstruction pipeline involving slam3r and lingbot-map. Video frames are sampled over time. Each frame contributes a projected fixation point into 3D space. These points accumulate into a dense spatial field, a kind of perceptual point cloud. This produces a temporal reconstruction of how the space was experienced. Not geometrically exact, but perceptually weighted.

At this stage, attention exists as density. Clusters indicate prolonged fixation. Sparse regions indicate rapid movement or absence. 

So the model already encodes behavior:

Where attention paused. 

Where it scanned. 

Where it never arrived.

<video
  src="/img/2026/dwelling/construction.mov"
  controls
  style="aspect-ratio: 16 / 9; width: 100%; ">
</video>




But instead of using this density to reinforce the model, I invert it.

The accumulated gaze field is mapped onto a pre-scanned 3D model of the house, and then used as a subtractive mask. Areas with high fixation density are progressively removed from the geometry. So what disappears first are the areas that received the most attention. What remains are the areas that were ignored.This produces a spatial inversion. The more you look at something, the less it exists. So instead of reconstructing the house, the system erodes it. And what you are left with is not a more accurate representation, but a confrontation. You are no longer looking at the space. You are being confronted by what you’ve ignored.

This challenges a fundamental assumption that that attention stabilizes reality. That looking makes things more real. I want to make the opposite happen, where attention destabilizes the object. What emerges is not presence, but absence. This is the attentional void. And this void is not empty. It is structured. It reveals: perceptual bias, habitual scanning patterns, and zones of neglect. 

Vision, as Crary suggests, is structured by habit. We repeatedly attend to certain areas while systematically ignoring others. This system makes that structure visible. It externalizes omission. The void is not what is missing. It is what was never seen.


<video
  src="/img/2026/dwelling/home.mov"
  controls
  style="aspect-ratio: 16 / 9; width: 100%; ">
</video>




Sites of Dwelling asks:

What happens if attention defines what remains?


Here, instead of subtracting attention, I isolate it. The same gaze dataset is reinterpreted. But instead of treating it as a continuous field, it is segmented into discrete events. Fixations are clustered based on: duration, spatial stability, recurrence over time. This allows individual attention events to be separated from general movement. From these clusters, specific regions of interest are extracted. These are not algorithmically “important” objects. They are not recognized or labeled. They are simply where attention stayed. From these regions, corresponding visual fragments are captured. Objects are isolated from their surroundings and normalized into a consistent format.


![ ](/img/2026/dwelling/definition.png)

The word dwelling has two meanings.

A place of residence.

And the act of lingering attention.

These objects are both. They are parts of the house, and traces of attention. They are not meaningful because of what they are. They are meaningful because of it sparked an emotion within my parents. It doesn’t have to be an object. It can be a small stain.or a corner of a shelf.

![ ](/img/2026/dwelling/items.png)


What emerges is a catalog of instantiated attention.

These become perceptual anchors.

Points where attention repeatedly returns.

In Barthes’ terms, they function as puncta. But instead of being chosen after the fact, they are computationally surfaced.


The house is reconstructed in two parallel forms.

On one side, the attentional void: what disappears.

On the other, sites of dwelling: what persists.

One is defined by removal.

The other by accumulation.

Together, they form a dual model of perception.

Not what space is, but how it is experienced.

![ ](/img/2026/dwelling/poster1.png)

![ ](/img/2026/dwelling/poster2.png)

The project shifted scale many times.

From general interaction, to specific environments.

From any user, to particular people.

From any space, to spaces that actually matter.

And eventually, to my own.

Applying the system to a space so personal was a continuation.

Because everything the system was already doing – tracking attention, capturing movement, revealing patterns – suddenly had consequence.

This project was a process of concentration, from interaction to recording to perception to memory.

Each step made the same system more specific.

More situated.

More meaningful to me.

Until attention itself became the artifact.

Not a means, but an end.

Something to reflect on.


