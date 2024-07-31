[![DOI](https://zenodo.org/badge/749951605.svg)](https://zenodo.org/doi/10.5281/zenodo.13205855)

# Interactive geospatial fleet transition and decision support (Geo-FTADS)
>>>>>>> 6b609f8 (Update README.md)

This repo contains code to produce and interactively visualize publicly available geospatial data to support trucking fleets in navigating the transition to alternative energy carriers. The tool uses data from the "freight analysis framework" (FAF5) database and other public data sources.

## Pre-requisites
* pixi ([link to installation instructions](https://prefix.dev/docs/pixi/overview#installation))

## Setup

```bash
git clone git@github.com:danikam/FAF5-Analysis.git
cd FAF5-Analysis
```

## Running the geospatial mapping tool

The code in [web](./web) contains all functionality to visualize the geojsons interactively on a web interface. The web interface is deployed as follows:

```bash
pixi run runserver
```

If that executes without issue, you should be able to view the map in your browser at http://127.0.0.1:5000/transportation. It currently looks something like this:

![Interactive Web Map](./images/web_map.png)
