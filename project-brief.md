# GeoDev Lab Africa — Project Brief

## The question

Which settlements within 5 km of Bodija Market have poor road access to the market?

## Why it matters

Bodija Market is an important market area in Ibadan, and road accessibility can affect how easily residents and traders reach the market. This project will identify settlements within a 5 km study area that have relatively poor road access, which could help local planners, transport stakeholders, traders, and residents understand areas that may need better connectivity.

## The data I need

- **Bodija Market location** — OpenStreetMap marketplace/location data.
- **Road network** — OpenStreetMap road network for the Bodija/Ibadan study area.
- **Road surface/type information** — OpenStreetMap road attributes, where available, to help assess road quality/access.
- **Settlement extents** — GRID3 NGA Settlement Extents v4.1.
- **Study area** — A 5 km buffer created around Bodija Market in GIS; this is a derived layer rather than an external dataset.

## Where each dataset comes from

- **Bodija Market / roads / road attributes:** OpenStreetMap — https://www.openstreetmap.org/
- **GRID3 NGA Settlement Extents v4.1:** GRID3 Data Hub — https://data.grid3.org/datasets/GRID3::grid3-nga-settlement-extents-v4-1/about
- **GRID3 Nigeria spatial data portal:** https://grid3.org/geospatial-data-nigeria

The GRID3 Nigeria portal lists Settlement Extents v4.1 (August 2026) and Roads v1.0 (October 2025) among its current Nigeria datasets.

## What I would build

I would build an interactive GIS/web map showing Bodija Market, the surrounding settlements, and the road network within a 5 km study area. The final system would classify or highlight settlements with relatively poor road access and allow a user to inspect the road route and distance from each settlement to Bodija Market.

## Initial data-check plan

1. Download/check the GRID3 settlement dataset.
2. Obtain the road network and road attributes for the Bodija area.
3. Confirm that Bodija Market is correctly represented.
4. Create the 5 km study-area buffer.
5. Test whether settlement-to-market road distances can be calculated reliably.
6. Define the final meaning of “poor road access” from the available data before performing the final analysis.
