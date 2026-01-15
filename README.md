# UFO Sightings Data Visualization

## Author: Richard Montes Lemus

## Purpose

This repository contains the analysis and visualization of UFO sighting data. This assignment focuses on created custom ggplot objects for a variety of plots and then patching them together onto a base plot to create a custom plot. This custom plot representing UFO sighting frequency over time and space using a variety of visualization techniques. 

## File Description

-   `HW1.qmd` - Quarto document containing code interpretation and analysis
-   `images/` - Folder containing the UFO image used for the final visualization
    -   `ufo.png` - UFO graphic
-   `fonts/` - Folder containing custom fonts
-   `outputs/` - Folder for rendered visualizations
    -   `ufo_sightings_infographic.png` - Final custom infographic
-   `README.md` - This file

## Data Access

The analysis uses two data sets from the [TidyTuesday project](https://github.com/rfordatascience/tidytuesday):

1.  **UFO Sightings Data**: Accessible via URL in the code
    -   `https://raw.githubusercontent.com/rfordatascience/tidytuesday/main/data/2023/2023-06-20/ufo_sightings.csv`
2.  **Places Data**: Population data for locations with UFO sightings
    -   `https://raw.githubusercontent.com/rfordatascience/tidytuesday/main/data/2023/2023-06-20/places.csv`

Both data sets are read in from GitHub in the code and do not need to be downloaded separately.

## Required Packages

To run this analysis, the following R packages are needed:

-   `tidyverse`
-   `ggtext`
-   `patchwork`
-   `geofacet`
-   `showtext`
-   `colorspace`
-   `scales`
-   `glue`
-   `magick`
-   `grid`


## Acknowledgements

-   **Original Visualization**: Created by [Dan Oehm](https://github.com/doehm) as part of TidyTuesday
-   **Course information**: The code and content for this analysis comes from the EDS 240 course in the Bren School of Environmental Science and Managment Master of Environmental Data Science Program. This course is led by Sam Shanny-Csik and co-led by Annie Adams.
