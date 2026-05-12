---
layout: project
title: "Embedding Earth: A Critical Atlas of Planetary Computation"
author: Ellie Madsen
advisor: Michael Krisch
year: 2026
image: /img/2026/EmbeddingEarth/grid.png
links:
  - text: About the Author
    url: https://elliemadsen.net
  - text: Code Repository
    url: https://github.com/elliemadsen/satellite-embeddings
---

<link href="https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,300;0,400;0,700;1,300;1,400&display=swap" rel="stylesheet" />
<style>
  :root {
    --title-font-family: 'Roboto', sans-serif;
    --body-font-family: 'Roboto', sans-serif;
    --caption-font-family: 'Roboto', sans-serif;
  }
  html {
    font-weight: 300;
  }
  em, i {
    font-weight: 300;
  }
  .sub-caption {
    font-family: var(--caption-font-family);
    font-size: calc(0.75 * var(--caption-font-size));
    line-height: calc(0.75 * var(--caption-line-height));
    color: var(--secondary-color);
    text-align: center;
  }
  .img-width img {
    display: block;
    margin-left: auto;
    margin-right: auto;
    width: var(--img-width, 100%);
    height: auto;
  }
  .footnotes {
    font-size: calc(0.8 * var(--caption-font-size));
    line-height: calc(0.8 * var(--caption-line-height));
  }
</style>

![](/img/2026/EmbeddingEarth/globes.png)

<!-- <p class="sub-caption">Global view of AlphaEarth Satellite Embeddings, visualized in false color by converting bands A00-A02 to RGB.</p> -->

<br>
<br>

_Embedding Earth: A Critical Atlas of Planetary Computation_ is a thesis that applies methods of writing, computation, mapping, and representation to critically analyze the epistemic conditions of Earth embedding technologies. I practice data analysis and visualization alongside conceptual frameworks from geography, science and technology studies, philosophy, and media theory in order to question not how well Earth embeddings represent the planet, but what kind of world they construct.

The application of machine learning foundation models to remotely sensed data has accelerated rapidly, promising to transform geospatial and environmental sciences.[^1] I argue that the development of Earth embeddings is not merely technological, but an epistemological shift in how the planet is represented and known. Embedding models do not simply advance existing methods of Earth observation; they reconstruct the Earth’s terrestrial features in a unified, high-dimensional space. While prior computational advancements in geography retained human legibility, Earth embeddings operate at a machine-oriented scale and dimensionality that exceeds human perception, widening the distance between representation and reality.

<br>
<br>

<div class="img-width" style="--img-width: 80%">

![](/img/2026/EmbeddingEarth/remote_sensing_papers.png)

<p class="sub-caption">Remote Sensing Foundation Models Papers Published</p>
</div>

<br>
<br>

Remote sensing foundation models are trained on massive quantities of multimodal environmental data—satellite imagery, radar, thermal, and climate—to learn generalizable representations, or features, of the Earth. These features are represented as embeddings: multidimensional vectors of numbers. Earth embedding data can be applied to a wide range of downstream applications including land classification, clustering, segmentation, similarity search, and change detection.
I conceive of Earth embeddings as the newest layer of abstraction within a long lineage of increasingly complex modes of geographic representation: from material archives to scientific drawings, catalogs to databases, remote sensing to machine learning. Yet this development is not linear—embedding Earth data in high-dimensional space marks an exponential acceleration in computational complexity.

Contextualizing these complex computational logics within longer traditions of geography, cartography, philosophy, and computation offers a “view from somewhere” — a positioned perspective from which we can make sense of this technology.[^2] Historicizing Earth embeddings across multiple lineages of scholarship provides theoretical frameworks and established vocabularies that help to untease the semiotics and rhetoric encoded in machine language. Words like _distance_, _space_, _vector_, _image_, _feature_, and _resolution_ carry different meanings across disciplines and contexts. In contending with these alternate understandings, I contribute a common lexicon that works to disambiguate terminology and improve interdisciplinary accessibility to discourse. In this work, I conceive of embedded Earth as data, map, space, representation, archive, and search infrastructure. Situating satellite embeddings across these registers, I analyze how they extend, complicate, and depart from traditional schools of thought within each.

In 1970, Walter Tobler coined the First Law of Geography: “everything is related to everything else, but near things are more related than distant things.”[^3] Geospatial foundation models follow this law to its logical conclusion by constructing a mathematical space in which semantic similarity is a direct product of distance. In embedding space, nearness and relatedness are one and the same. This notion of similarity can be quantified by measuring the distance between any two embeddings using a metric such as dot product, L2 distance, or cosine similarity.

<br>
<br>

<div class="img-width" style="--img-width: 80%">

![](/img/2026/EmbeddingEarth/geographic_vs_embedding_distance_scatter.png)

</div>
<p class="sub-caption">Correlation between physical distance and embedding distance in the 2024 AlphaEarth Foundations Satellite Embedding Dataset.</p>

<br>
<br>

I argue that Earth embeddings are a new kind of map that spatially organizes entities based on relationships of embedding distance. The fact that distance in high-dimensional space represents semantic similarity, not physical proximity, pushes the boundary of what a map is and does in the age of artificial intelligence. I illustrate how embedding distance functions as a metric of environmental change detection and a mode of linking intrinsically similar yet physically disparate places. By framing dimension reduction algorithms as attempts to preserve embedding distance in two dimensions, I situate their application to Earth embeddings as a contemporary mode of cartographic projection. I also produce maps to support these arguments, applying conventions of cartography to spatialize the data in familiar forms.

<br>
<br>

![A World Map of Embedding Space](/img/2026/EmbeddingEarth/embedding_umap.png)

<p class="sub-caption">
Countries are positioned by relative location in embedding space. Per-country mean 64-dimensional AlphaEarth embeddings are clustered into 8 “continents” using k-means and projected to 2D with UMAP, an algorithm that reduces dimensionality while minimizing embedding distance. Places that are more similar appear closer together.</p>

<br>
<br>

In addition to maps, I create a variety of false-color visualizations and low-dimensional projections to illustrate encoded features and spatial distribution of Earth embeddings. I reflexively analyze the aesthetic conditions of these representations, drawing attention to the inherent limitations of attempting to render visible unfathomable quantities of numerical data. Earth embeddings are operational; they are not intended to be seen.[^4] Representing machine vision for human perception is limited at best and paradoxical at worst. Nonetheless, I employ representation because I believe in its affordances to communicate the slippery ontology of Earth embeddings. Trevor Paglen writes that operational images “can only be seen by humans in special circumstances and for short periods of time.”[^5] This atlas is one such special circumstance.

<br>
<br>

![](/img/2026/EmbeddingEarth/dimension_reductions.png)

<br>
<br>

I present Earth embeddings as an opportunity to re-examine the metaphysical dichotomy between object and field in a new context. In turn, the representational distinction between vector and raster offers visual and conceptual affordances to illustrate the intrinsic nature of embeddings.[^6] A single Earth embedding is an object—a vector of numbers, a point in a diagram, an item in a database. A set of Earth embeddings is a field—a continuous mathematical space, a raster image painted by the brushstrokes of a billion vectors. In scaling in and out, we move back and forth between discrete and continuous. This is rendered visible by two complementary modes of representation. False color composites conceive of Earth embeddings as a field, portraying rasters up close in evocative, hyper-real imagery. Dimension-reduced scatter plots construct Whole-Earth images from afar: the Blue Marbles of planetary artificial intelligence. Viewing Earth embeddings from a distant vantage point enacts the same experiential effects as seeing the Earth from outer space, imparting “the god trick of seeing everything from nowhere.”[^2] Earth embeddings thus blur boundaries between object and field, vector and raster, discrete and continuous, algebra and geometry, digital and aesthetic.

<br>
<br>

![](/img/2026/EmbeddingEarth/tsne_zoom_100_c3_embedding.png)

<p class="sub-caption">One hundred randomly sampled AlphaEarth embeddings are projected from 64D to 2D with t-SNE and positioned according their 2D coordinates. Each is represented by a false color composite (RGB: bands A61, A62, and A63). </p>

<br>
<br>

The representations throughout this work do not operate as mirrors of nature, but windows into a new space. These images are both representations _of_ space and representations _as_ space. Foundation models do not merely recuce reality to representation, but also produce—constructing a new multidimensional space where there was none. This act of construction is unequivocally human. Various decisions throughout the model training pipeline—from data selection to hyperparameter tuning—manifest unassumingly in produced embedding data. I use the example of clouds to demonstrate how the erasure of environmental phenomena deemed irrelevant to geospatial analysis compounds into recursively enfolding simulacra. While clouds are systematically removed from satellite imagery via post-processing,[^7] satellite embedding models trained on this masked imagery produce data that is cloudless from its genesis. Thus the existence of the physical referent—Earth—moves further and further away from its representational proxy.

<br>
<br>

![](/img/2026/EmbeddingEarth/clouds.png)

<p class="sub-caption">Imbabura, Ecuador</p>

<br>
<br>

As an archive, Earth embeddings extend and transform a long history of environmental data collection.[^8] The introduction of foundation models to Earth observation marks an exponential shift in the speed at which our planetary archive gains computational complexity and distance from its source of truth. These big data archives are sites of tension between uncertainty and stability: they introduce potential disruptions to industry while simultaneously systematizing massive quantities of unlabeled remotely sensed data into fixed schematics.[^9]

Framing this data as an archive sets the stage to apply well-established theories of the archive, drawing attention to the selection and omission of data as well as their semantic ascription and interpretation. I argue that the eradication of environmental phenomena which evade binary vectorization—clouds, oceans, seas, hurricanes, and other transient features—is a form of archival violence.[^10]

<br>
<br>

![](/img/2026/EmbeddingEarth/tsne_zoom_100_c2_vector.png)

<p class="sub-caption">One hundred randomly sampled AlphaEarth embeddings are projected from 64D to 2D with t-SNE and positioned according their 2D coordinates. Each is represented by its raw numerical floating-point values. </p>

<br>
<br>

Maps, words, and archives are rhetorical. The human unintelligibility of the numerical values that comprise Earth embeddings obscures such rhetoric. Yet deconstructionism calls us to search for latent ideology "between the lines of the map” and "in the margins of the text.”[^11] I argue that the margins of embedding space are those environmental features excluded from the archive, as well as geographic regions with sparse remotely sensed data or limited labeled datasets. These areas—primarily in the Global South—are asymmetrically interpolated based on the statistical patterns of regions with dense data coverage in the Global North.

The analogy of the blurry JPEG illustrates this uneven compression.[^12] Computational encoding enables embeddings to generalize dense global patterns—yet it simultaneously eradicates data provenance and begets lossiness and digital artefacts. As a hybrid collage of multimodal data inputs, Earth embeddings depart from traditional information infrastructures which deterministically index satellite imagery by metadata such as source, date, and location. Geospatial foundation models render the Earth a search engine, queryable in the same manner as the Web. Replacing indexical catalogs with vector databases marks an epistemological shift from explicit to implicit, specificity to relativity, provenance to prediction.

<br>
<br>

![](/img/2026/EmbeddingEarth/k16_combined.png)

<p class="sub-caption">A division of the Earth’s terrestrial surface into 16 clusters based on environmental similarity. Global AlphaEarth embeddings were sampled at 1° resolution across all land pixels and clustered into 16 groups with k-means, minimising per-cluster embedding distance. The result is a grouping of regions that share similar environmental characteristics without any explicit labels provided.</p>

<br>
<br>

This research is primarily epistemic. I question how Earth embeddings change our ways of knowing and methods of producing knowledge. I unpack how this knowledge is created, what it excludes, how it is structured, and on what logic it operates. I search for representative examples and anomalous edge cases. I speculate what exists in the margins of embedding space, beyond binary digits and geometric operations. I attempt to render imperceptible numerical information visible. I argue that Earth embeddings map, structure, search, interpolate, predict, project, correlate, archive, blur, distance, operate, distort, deconstruct, reduce, and represent—and I make a first attempt at illustrating how.

In this thesis, I lay preliminary groundwork to propose a new way of understanding Earth embedding technology—or perhaps, drawing upon the work of past scholars, an old way of understanding something new. Earth embeddings are one site where broader contemporary questions of knowledge, meaning, and truth play out. Yet unlike other applications of artificial intelligence, the fact that this data represents our planet introduces complex spatial considerations which require a distinct analytical approach. We cannot afford to be data-agnostic: Earth embeddings are designed to operate on Earth. By untangling the logical basis, implicit semiotics, operational capacity, and representational affordances of Earth embeddings, I offer a glimpse into the confounding new world of high-dimensional planetary computation.

<br>
<br>

<!-- ![](/img/2026/EmbeddingEarth/grid.png) -->

<br>

[^1]: Aoran Xiao et al., “Foundation Models for Remote Sensing and Earth Observation: A Survey,” IEEE Geoscience and Remote Sensing Magazine 13, no. 4 (2025): 297–324, https://doi.org/10.1109/MGRS.2025.3576766

[^2]: Donna Haraway, “Situated Knowledges: The Science Question in Feminism and the Privilege of Partial Perspective,” Feminist Studies 14, no. 3 (1988): 575–99, https://doi.org/10.2307/3178066, 590.

[^3]: W. R. Tobler, “A Computer Movie Simulating Urban Growth in the Detroit Region,” Economic Geography 46 (1970): 234–40, https://doi.org/10.2307/143141, 236.

[^4]: Jussi Parikka, Operational Images: From the Visual to the Invisual (University of Minnesota Press, 2023), https://www.jstor.org/stable/10.5749/j.ctv2z86232, 11.

[^5]: Trevor Paglen, “Invisible Images: Your Pictures Are Looking at You,” Architectural Design 89, no. 1 (2019): 22–27, https://doi.org/10.1002/ad.2383, 24.

[^6]: Helen Couclelis, “People Manipulate Objects (but Cultivate Fields): Beyond the Raster-Vector Debate in GIS,” in Theories and Methods of Spatio-Temporal Reasoning in Geographic Space, ed. A. U. Frank et al. (Springer, 1992), https://doi.org/10.1007/3-540-55966-3_3, 66.

[^7]: Nicole Sansone Ruiz, “Days Without Clouds: Realism, Images, and Target Classifiers at Google Earth Engine,” Computational Culture, no. 9 (July 2023), http://computationalculture.net/days-without-clouds-realism-images-and-target-classifiers-at-google-earth-engine/.

[^8]: Shannon Mattern, “The Big Data of Ice, Rocks, Soils, and Sediments,” Places Journal, ahead of print, November 7, 2017, https://doi.org/10.22269/171107.

[^9]: Daniela Agostinho et al., “Uncertain Archives: Approaching the Unknowns, Errors, and Vulnerabilities of Big Data through Cultural Theories of the Archive,” Surveillance & Society 17, no. 3/4 (2019): 422–41, https://doi.org/10.24908/ss.v17i3/4.12330, 426.

[^10]: Jacques Derrida and Eric Prenowitz, “Archive Fever: A Freudian Impression,” Diacritics 25, no. 2 (1995): 9–63, https://doi.org/10.2307/465144, 12.

[^11]: J. B. Harley, “Deconstructing the Map,” Passages, 1992, http://hdl.handle.net/2027/sitpo.4761530.0003.008.

[^12]: Ted Chiang, “ChatGPT Is a Blurry JPEG of the Web,” Annals of Artificial Intelligence, The New Yorker, February 9, 2023, https://www.newyorker.com/tech/annals-of-technology/chatgpt-is-a-blurry-jpeg-of-the-web.
