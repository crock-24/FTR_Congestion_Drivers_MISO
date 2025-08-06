# Congestion and Constraint Visualization in MISO LMP Data

This project explores the relationship between wind generation, load, temperature, and transmission constraints with Locational Marginal Price (LMP) congestion in the MISO region. The goal is to uncover patterns in congestion behavior and highlight which transmission constraints have the most influence on congestion at various LMP nodes.

## Project Features

### Key Visuals

- ** Wind vs Congestion Correlation Map (Geospatial)**
  - Visualizes average wind-congestion correlation by state.
  - Helps identify which regions are more sensitive to wind output in relation to congestion.

- ** Heatmap: Weather, Load, and Wind Lagged Correlation**
  - Correlation of congestion with lagged values of temperature, load, and wind.
  - Supports identification of temporal influence on congestion.

- ** Top Constraints Per Area (Bar Chart)**
  - Displays the most influential constraints (by correlation) for each utility or area.
  - Highlights recurring transmission bottlenecks.

- ** Correlation Strength vs Lag (Line Chart)**
  - Shows how correlation between wind and congestion varies with different lags.
  - Useful for understanding delayed system response to wind changes.

- ** Bipartite Network Graph**
  - Links LMP nodes to their top 5 correlated constraints.
  - Offers insights into which constraints drive congestion across nodes.

## Data Sources

- MISO Day-Ahead LMP data
- MISO constraint and outage data
- Public weather and load datasets
- Utility service area metadata (scraped)

## Insights

- Certain constraints disproportionately impact congestion across many nodes.
- Wind has a stronger congestion correlation in some states than others.
- Most areas show consistent lag between load behavior and congestion response.
- Many nodes are influenced by a small subset of constraints—indicating network-wide bottlenecks.
