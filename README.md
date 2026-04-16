# West Virginia Broadband Gap Analysis
# wv-broadband-gap

A geospatial analysis identifying underserved communities in West Virginia 
using infrastructure coverage modeling and population-weighted feasibility scoring.

## Methodology
- Infrastructure data sourced from OpenStreetMap via OSMnx
- Population data from US Census TIGER/Line
- Coverage gaps identified via spatial overlay analysis
- Gaps scored by: population density (40%), road proximity (35%), distance to existing nodes (25%)

## How to run
1. Activate virtual environment: `source venv/bin/activate`
2. Run notebooks in order: `01_data_acquisition.ipynb` → `02_analysis.ipynb` → `03_output.ipynb`

## Data sources
- OpenStreetMap (OSMnx)
- US Census Bureau TIGER/Line Shapefiles
- FCC Broadband Data Collection

## Key findings
*(To be filled in after analysis)*

## My understanding
Here's what to focus on as you build:
The scoring model is your differentiator. Anyone can buffer a line and find gaps. What sets you apart is building a defensible, weighted scoring model and explaining your reasoning — that's exactly the "combine geospatial logic and judgment" skill they're hiring for.

Document the messiness. OSM telecom data in West Virginia is patchy and inconsistent. Don't hide that — write about it in your README and methodology. HIP explicitly says they work with "incomplete, inconsistent, or evolving" data. Showing you can reason through that is the whole point.

The write-up is as important as the code. They ask for a writing sample in the application, and your 1-page methodology summary can serve as both the project write-up and your writing sample — two birds, one stone.
Want me to give you the starter code for Day 1 — pulling WV data with OSMnx and setting up the project structure?