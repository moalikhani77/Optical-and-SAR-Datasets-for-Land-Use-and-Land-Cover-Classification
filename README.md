📂 Dataset Description
This repository contains two paired and co-registered datasets designed for patch-level land use and land cover (LULC) classification using Sentinel-1 SAR and Sentinel-2 optical imagery. The datasets were created manually as part of a research study aiming to evaluate the effectiveness of deep CNN models in remote sensing tasks.

📌 Key Features
Data Sources:

Optical: Sentinel-2 (12 spectral bands)

SAR: Sentinel-1 (VV & VH polarizations from both ascending and descending passes)

LULC Classes:
6 categories — Barrenland, Farmland, Forest, River, Sea/Lake, Urban

Patch Details:

Size: 64×64 pixels

Resolution: 10 meters

Format: Each patch is saved as an individual GeoTIFF (.tif) file with georeferencing metadata

Number of Samples:

600 labeled patches per class per dataset
→ Total: 3,600 optical + 3,600 SAR patches

Spatial Alignment:
Each SAR-optical patch pair is spatially co-registered to ensure direct comparability under identical ground conditions.
