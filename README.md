# Detailed exploration of Caitlin Clark's gameplay through the lens of data visualization.

## Summary 
Utilizing the power of R and the extensive capabilities of the wehoop package, I’ve transformed complex play-by-play data from ESPN into insightful visualizations. Through a series of shooting charts and heat maps, I’ve decoded patterns that reveal both the strengths and potential vulnerabilities in Clark's technique.

The visualizations paint a story of her dominance on the court, showcasing why she's considered among the best in NCAA history. But they also hint at strategies that could challenge her, highlighting the depth and nuance that data brings to understanding sports excellence. 

## Prerequisites

### Required Packages

- **Required Packages**:
  - `wehoop`
  - `ggplot2`
  - `tidyverse`
  - `nbastatR`
  - `devtools`
  - `ncaahoopR`
  - `extrafont`
  - `cowplot`
  - `paletteer`
  - `dplyr`

## Running the Analysis

1. **Setup**: Ensure all required packages are installed and loaded in your R environment.
2. **Data Loading**: Load the play-by-play data using the `wehoop` package.
3. **Data Filtering**: Filter the data for Caitlin Clark's shooting and assist plays, and for Iowa Hawkeyes team shooting plays.
4. **Visualization**: Create shooting charts, heat maps, and assist charts using ggplot2 and custom functions to plot basketball courts.
