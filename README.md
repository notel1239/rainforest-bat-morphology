# Rainforest Bat Morphology Dataset

A curated dataset of bat wing morphology and vertical capture heights from an old-growth rainforest field study.

## Overview

This dataset contains morphological measurements and vertical capture heights for multiple bat species collected during a field season in an old-growth rainforest. The data are intended to support research on bat vertical stratification, wing morphology, and habitat use.

## Data Collection Methods

Bats were captured using mist nets erected at various heights within the forest canopy. Captures were conducted over a 3-month field season across multiple sites. For each captured individual, we recorded species identification, measured wing loading (body mass divided by wing area), aspect ratio (wingspan squared divided by wing area), and the height (in meters) at which the bat was captured. All measurements were taken following standard protocols for bat morphological data.

## Dataset Description

The primary dataset is stored in `data/bat_morphology_raw.csv` with the following columns:

- **species_id** (string): A unique identifier for each bat species (e.g., "PTP1", "MGL2"). Refer to `data/data_dictionary.md` for full species names and ecological notes.
- **wing_loading** (float): Wing loading in N/m² (Newtons per square meter). This is a measure of the bat's body mass relative to its wing area, influencing flight performance and maneuverability.
- **aspect_ratio** (float): Wing aspect ratio (dimensionless). Calculated as wingspan squared divided by wing area, indicating wing shape and flight efficiency.
- **capture_height_m** (float): Height at which the bat was captured, measured in meters above ground.

## Usage and Citation

If you use this dataset in a publication, please cite it as follows:

> Researcher Name. (Year). Rainforest Bat Morphology Dataset (Version 1.0) [Data set]. GitHub. https://github.com/notel1239/rainforest-bat-morphology

You can also cite the specific release (e.g., v1.0) using its DOI if one is created (e.g., via Zenodo integration).

## License

This dataset is released under a [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/) license. You are free to share and adapt the material, provided you give appropriate credit, provide a link to the license, and indicate if changes were made.

## Repository Structure

- `data/`: Contains the raw data file and data dictionary.
- `.github/ISSUE_TEMPLATE/`: Contains templates for reporting issues or suggesting enhancements.
- `README.md`: This file.

## Contact

For questions or to report data errors, please open an issue in this repository or contact the maintainer directly.

## Acknowledgments

We thank field assistants, local collaborators, and funding agencies for their support in data collection.