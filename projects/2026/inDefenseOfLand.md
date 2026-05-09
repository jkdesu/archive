---
layout: project
title: In Defense of the Land
author: Steven Dela Cruz Duncan
year: 2026
image: /img/2026/inDefenseOfLand/titleScreenVid.gif
links:
  - text: View the Interactive Web Experience
    url: https://sfdduncan.github.io/digitalColonialismStory/
---

<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Host+Grotesk:ital,wght@0,300..800;1,300..800&display=swap" rel="stylesheet">
<style>
  .container { font-family: 'Host Grotesk', Arial, sans-serif; }
</style>

# Provocation

***What does it mean to position a hacktivist breach within five centuries of Indigenous land defense across the Americas, and how do we make that history legible without flattening the distinct, complex histories of the peoples who have lived and continue to live it? What does it mean to create a digital narrative experience that dismantles the colonial logics embedded within the video game medium it borrows from, asking the viewer to confront the kinstillations of Indigenous resistance, the trouble of the archive, and the multiplicity of ways Indigenous peoples have refused, and continue to refuse, the project of settler colonialism?***

In March of 2022, a hacktivist collective calling itself Guacamaya, the Maya word for the macaw parrot, breached the networks of mining companies operating in Guatemala's Fenix nickel project, leaking over four terabytes of data exposing working conditions, environmental damage, gender-based violence, and the internal corporate messaging that had coordinated it all. They understood themselves as acting in defense of the Maya Q'eqchi', the Indigenous people who have existed in reciprocity with their lands prior to and during the ongoing mining projects, as well as all Indigenous peoples of Abya Yala, the Kuna term for the Americas meaning "land in full maturity."

<div style="display:flex;gap:1rem;">
  <img src="/img/2026/inDefenseOfLand/guacamaya1.png" style="width:50%;object-fit:cover;">
  <img src="/img/2026/inDefenseOfLand/guacamaya2.png" style="width:50%;object-fit:cover;">
</div>


What I kept returning to was a single passage from one of their statements:

> "This form of resistance is just one more tool of what we have been doing for more than five centuries. It is a tool of this time. Haven't Indigenous peoples' leaders been stigmatized for defending their territory for ages?"[^1]

This statement reframes what might otherwise be read as a disruptive, cyberterroristic act as something far older: a continuation of Indigenous refusal and resistance. In aligning this form of digital insurgency with centuries of land defense, Guacamaya insists that although the medium is new, the struggle they are working within is not.

---
<br>

# In Defense of the Land

## A digital narrative experience situating Guacamaya's 2022 breach within centuries of Indigenous land defense across Abya Yala.

The goal of this digital narrative experience is twofold. For those encountering these histories for the first time, the aim is to make legible that Indigenous peoples have continued to resist, in a myriad of ways, despite the ongoing attempts of settler colonialism to erase them. For those already engaged with anti-colonial or decolonization movements, the aim is to internalize the notion of kinstillation, of Indigenous internationalism, and to inspire a turn toward how other Indigenous peoples across the Americas have worked in tandem, all under the umbrella of defending the land, and inherently, defending themselves.

![](/img/2026/inDefenseOfLand/titleScreenVid.gif)

<br></br>

## Walking Through the Experience

The experience moves through a sequence of distinct natural environments: arctic tundra, forest, grassland, mountain pass, ocean, rainforest, and finally the dark digital corridor of the hack itself. The viewer walks through each environment as written narration, audio of prevalent scholars engaging in Critical Native and Indigenous studies, and archival imagery surface alongside them.

![](/img/2026/inDefenseOfLand/environments_grid.png)
<br>

## The Subtitles as Essay Spine

The written narration that appears as the viewer moves through the environment functions as the essay's spine, making the central argument explicit: that refusal, the ongoing insistence on existing on one's own terms and on one's own land, is not solely confined to moments of dramatic political action but is the continuous texture of Indigenous life under settler colonialism. The narration traces this argument from its theoretical grounding, through the specific history of Maya Q'eqchi' land defense at El Estor, to Guacamaya's breach as its most recent expression. Audio recordings of prominent scholars in critical Native and Indigenous studies surface alongside the narration, ensuring that the conceptual frameworks informing this work are spoken by the thinkers themselves.

<video controls width="100%">
  <source src="/img/2026/inDefenseOfLand/demoVId2.mp4" type="video/mp4">
</video>

<br>

## Archival Images Moving Alongside the Viewer

Archival photographs, documentary images, and Indigenous artworks surface from the landscape and move alongside the viewer rather than being displayed behind glass. This design choice is rooted in a concept common across many Indigenous traditions: that the past is not behind us but travels with us, that ancestors and ancestral knowledge inform and accompany the present rather than receding into history. Some of these images originate from a colonial lens, produced by and for institutions that sought to render Indigenous peoples as salvageable objects frozen in the moment of their capture. Drawing on Pierce, the images are approached as opportunities to recover within them moments of tenderness, care, kinship, and refusal that the colonial archive was never designed to hold but could not fully erase.

<video controls width="100%">
  <source src="/img/2026/inDefenseOfLand/demoVidPopUp.mp4" type="video/mp4">
</video>

---
<br>

# Computational Design Practice

This project is the culmination of my discovery and development of a computational design practice centered on digital storytelling, archival research, and interactive media. 

## Speculation

I am interested in how interactive and immersive digital environments can serve as sites for the legible articulation of complex historical, political, and relational arguments, particularly in relation to Indigenous resistance and land defense. In wrestling with Guacamaya's claim, I have been grappling with two conceptual frameworks throughout this project, which I hold together because they are answering different but interlocking questions.

![](/img/2026/inDefenseOfLand/archiveImg.png)

The first is Joseph M. Pierce's (Cherokee Nation) framework of speculative relations and kinstillation,[^2] which presents an opportunity to recognize a unified decolonial struggle across the Americas while making clear not to flatten the individual and complex histories of distinct Indigenous groups. Through this framing, distinct movements of decolonial resistance can be put in conversation with one another, in tandem rather than collapsed, as they are all ultimately working to defend the land and, inherently, themselves.

The second is Jodi Byrd's (Chickasaw Nation) argument regarding the ways in which traditional video games, and media like it, openly reflect and reinstantiate settler colonial operations and ideologies.[^3] As Byrd writes, "in the repetitious invasion-to-ashes script, video games stage for us a sovereign nomos that continually spawns Indigeneity as only ever unknowable, uninhabitable objects of conquest who must inevitably be already dead while that same nomos seizes territoriality." But within Byrd's work, they leave room to argue that the conventions that make games complicit in colonial logics, namely immersion, inhabitation, and the movement of a body through an environment, are also the conventions that, when redirected, can do the opposite work.

This project takes precedent from games such as Umurangi Generation by Māori developer Naphtali Faulkner, in which the act of bearing witness through the environment becomes the form of resistance the work itself enacts, and Never Alone (Kisima Ingitchuna), developed in collaboration with the Iñupiaq community of Alaska as an act of cultural continuity and education.

![](/img/2026/inDefenseOfLand/inspo.png)

<br>

## Function

At its core, the experience is an environment entirely constructed in Three.js, structured as a sequence of distinct environments through which the viewer walks. As the viewer moves, three layers of content surface in synchronized relation: written narration, audio recordings of scholar voices, and archival photographs and Indigenous artworks. The narration and audio triggers are governed by the viewer's position within each environment, with subtitle cards and audio cues calibrated to give the viewer enough time to read and listen without halting their movement through the space.

The system is comprised of:

1. A Three.js scene graph governing each environment's geometry, lighting, and camera behavior
2. A subtitle and audio trigger system tied to viewer position
3. Interactive archival image objects that surface from the landscape and move alongside the viewer rather than being displayed statically
4. Audio recordings of scholars in critical Native and Indigenous studies, integrated as ambient voice alongside the written narration

<video controls width="100%">
  <source src="/img/2026/inDefenseOfLand/demoVid1.mp4" type="video/mp4">
</video>

<br>

## Form

The aesthetic of the experience is deliberate. The environments are stylized rather than photorealistic, refusing the open-world game's logic of conquering empty, hyper-rendered territory. The archival images are set apart from the environment by their treatment, surfacing as discrete artifacts that travel alongside the viewer rather than being embedded into the world as decoration. The shifting landscapes, from arctic tundra to rainforest to the dark corridor of the hack, are an attempt to visualize something of the territorial vastness at stake: the sheer scale and diversity of the lands, waters, and ecologies that Indigenous peoples across the Americas have defended and continue to defend. No single environment can hold that scope. The movement between them is an acknowledgment of it.

<br>

## Interaction

Where the open-world game traditionally invites the player to conquer empty territory, this work asks the viewer to move through territory that is already inhabited, already defended, already alive with relation, and to confront, through that inhabitation, the ongoing presence of peoples the medium has historically tried to render absent. The interaction is intentionally limited: the viewer walks, they look, they listen, they read. There are no win conditions. There is no accumulation. The viewer's only task is to be present with these histories, to allow themselves to be moved through them, and to recognize them for what they are: not history, not exception, but the continuous texture of life lived in good relation, exactly as Guacamaya named it.

<br>

## A Companion Two-Channel Video Installation: Resistance in Plaintext

Alongside the digital narrative experience, this work includes a two-channel video installation titled *Resistance in Plaintext*. The first channel, *Methods of Refusal*, displays a grid of various forms of what is to be considered refusal and resistance of the Maya Q'eqchi, from protest to ceremony to people simply existing on the land, overlaid with the hack tutorial Guacamaya themselves published. The second channel, *Exposure*, layers leaked documents from the Guacamaya breach over a promotional video produced by Pronico, the corporation operating the Fenix nickel mine. Together, the two channels make legible what was always hidden in plain sight.

<div style="position:relative;padding-bottom:56.25%;height:0;overflow:hidden;">
  <iframe src="https://www.youtube.com/embed/spspradFaiA?autoplay=1&mute=1" style="position:absolute;top:0;left:0;width:100%;height:100%;" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
</div>

---
<br>

[^1]: Guacamaya. "RESISTENCIA." Distributed via Enlace Hacktivista, 2022.
[^2]: Pierce, Joseph M. *Speculative Relations: Indigenous Worlding and Repair*. Durham: Duke University Press, 2025.
[^3]: Byrd, Jodi A. *The Transit of Empire: Indigenous Critiques of Colonialism*. Minneapolis: University of Minnesota Press, 2011.
[^4]: Wolfe, Patrick. "Settler Colonialism and the Elimination of the Native." *Journal of Genocide Research* 8, no. 4 (2006): 387–409.
[^5]: Coulthard, Glen Sean. *Red Skin, White Masks: Rejecting the Colonial Politics of Recognition*. Minneapolis: University of Minnesota Press, 2014.
[^6]: Coulthard, Glen Sean, and Leanne Betasamosake Simpson. "Grounded Normativity / Place-Based Solidarity." *American Quarterly* 68, no. 2 (2016): 249–255.
[^7]: Simpson, Audra. *Mohawk Interruptus: Political Life Across the Borders of Settler States*. Durham: Duke University Press, 2014.
[^8]: Estes, Nick. *Our History Is the Future: Standing Rock Versus the Dakota Access Pipeline, and the Long Tradition of Indigenous Resistance*. London: Verso, 2019.
[^9]: Deloria, Vine, Jr. *Custer Died for Your Sins: An Indian Manifesto*. New York: Macmillan, 1969.
[^10]: Deloria, Vine, Jr. *God Is Red: A Native View of Religion*. New York: Grosset & Dunlap, 1973.
[^11]: Barker, Joanne. *Red Scare: The State's Indigenous Terrorist*. Oakland: University of California Press, 2021.
[^12]: Recollet, Karyn. "Glyphing Decolonial Love through Urban Flash Mobbing and Walking with Our Sisters." *Curriculum Inquiry* 45, no. 1 (2015): 129–145.

