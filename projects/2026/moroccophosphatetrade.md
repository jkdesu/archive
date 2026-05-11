---
layout: project
title: "Morocco Phosphate Trade: A 25-Year Computational Analysis"
author: Rom El Idrissi
advisor: Dan Miller
year: 2026
published: false
links:
  - text: Prototype
    url: https://romeli7.github.io/moroccophosphatestrade/
---

Morocco Phosphate Trade is an interactive computational visualization of 25 years of global phosphate trade data, centered on Morocco's position as the world's leading phosphate producer and exporter. The project traces export revenue composition, processing input structure, and commodity price dynamics from 2000 to 2026, and documents OCP Group's green ammonia program as a pathway toward domestic ammonia production. Data for 2025 and 2026 are forward estimates based on OCP growth projections and trade trend extrapolation.

Morocco holds approximately 68% of known global phosphate reserves according to the USGS Mineral Commodity Summaries of January 2025, managed exclusively by OCP Group (Office Cherifien des Phosphates), a wholly state-owned entity.[^1] This reserve concentration positions Morocco as the central node in the global fertilizer supply chain, supplying markets across Asia, Latin America, Europe, and Africa. OCP's full-year 2024 revenue reached 96.9 billion dirhams (approximately 9.76 billion US dollars), reflecting sustained demand for Moroccan phosphate products across global agricultural markets.[^2]

Between 2000 and 2024, OCP significantly expanded its processing capacity, shifting the export mix from predominantly raw rock toward finished fertilizer compounds. Fertilizers accounted for 69% of OCP's total revenue in 2024, up from 66% the previous year, driven by investment in the Jorf Lasfar industrial complex on Morocco's Atlantic coast, now the world's largest fertilizer production facility.[^3] This vertical integration has substantially increased the value captured per tonne of rock extracted.

OCP's green ammonia program uses Morocco's exceptional solar and wind resources to power electrolysis, producing green hydrogen that is combined with atmospheric nitrogen via the Haber-Bosch process to make ammonia domestically. The Tarfaya complex is a 7 billion dollar project covering over 100,000 hectares, incorporating a 2.8 GW wind farm, a 1 GW solar photovoltaic plant, and 2.7 GWh of battery storage.[^4] OCP's green growth program totals approximately 13 billion dollars over the 2023 to 2027 period, targeting full carbon neutrality by 2040, with stated production targets of 1 million tonnes of green ammonia per year by 2027 and 3 million tonnes per year by 2032.[^5]

## Design Process

The project began with a data collection and structuring phase, assembling annual trade figures from the Office des Changes Maroc, OCP annual reports, UN Comtrade, the World Bank Pink Sheet, and the International Fertilizer Association. Raw data was cleaned, normalized to consistent USD values, and organized into product-level export series spanning 2000 to 2026.

The design process translated that dataset into a set of complementary visual artifacts, each addressing a different layer of the trade system. The primary interactive presentation was built in Reveal.js using IBM Plex Mono throughout, giving the interface a computational and data-forward aesthetic. Chart.js was used for quantitative charts. D3.js and TopoJSON were used to build two interactive world maps, one tracing export flows from Morocco to destination markets, one tracing inbound processing input flows, both animated across the full 27-year data range.

A standalone interactive map was developed separately, featuring a year scrubber, play function, togglable export and import display modes, and a sparkline revenue chart with hover annotation. A photographic collage was assembled from imagery of Morocco's four principal phosphate sites (Khouribga, Benguerir, Bou Craa, and Jorf Lasfar). A cinematic scrolling documentary was built using SVG-illustrated scenes depicting the geological formation of Morocco's phosphate deposits, the mining operations, and the processing chain from raw rock to finished fertilizer.

Color encoding is consistent across all artifacts: red for reserve data, blue for export market data, green for fertilizer and green ammonia data, amber for price and cost data.

## Prototype

<iframe src="https://www.youtube.com/embed/CVGRuzZCMZo" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

## Imagery

![Phosphate mining and processing operations across Morocco's principal production sites: Khouribga, Benguerir, Bou Craa, and Jorf Lasfar.](/img/2026/phosphatesimagery.png)

## Data Sources

Office des Changes Maroc. Annual trade statistics, 2000 to 2026.

OCP Group. Annual Reports, 2010 to 2024. Full Year 2024 Results Publication, March 2025.

United States Geological Survey. Mineral Commodity Summaries: Phosphate Rock. January 2025.

World Bank. Pink Sheet commodity price data, 2000 to 2024.

International Fertilizer Association. Trade statistics and price indices, 2000 to 2024.

UN Comtrade. Bilateral trade data, 2023 to 2024.

Ammonia Energy Association. OCP green hydrogen program updates, 2024 to 2025.

Worley Group. Annual Report, 2024.

CEIC Data. Morocco export revenue monthly series, 2000 to 2026.

OCP Group. Investment Plan 2023 to 2027. ocpgroup.ma.

OCP Eurobond Prospectus, April 2025.

Reuters. "Morocco's OCP plans $7bln green ammonia plant." June 2023.

[^1]: United States Geological Survey. Mineral Commodity Summaries: Phosphate Rock. January 2025. OCP Eurobond Prospectus, April 2025.
[^2]: OCP Group. Q4 and Full Year 2024 Results. March 2025.
[^3]: OCP Group. Full Year 2024 Results Publication. March 2025.
[^4]: Worley Group. Annual Report 2024.
[^5]: OCP Group. Investment Plan 2023 to 2027. ocpgroup.ma. Confirmed by Reuters, June 2023.

