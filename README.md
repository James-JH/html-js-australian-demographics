Access the visualisation through this link: [https://james-jh.github.io/html-js-australian-demographics//](https://james-jh.github.io/html-js-australian-demographics/)

# Exploring Demographic Insights in Australia

<img width="595" height="841" alt="Exploring Demographic Insights in Australia" src="https://github.com/user-attachments/assets/c1181787-6a2f-48f3-8929-c50bbf5e6874" />
<img width="595" height="841" alt="Exploring Demographic Insights in Australia copy" src="https://github.com/user-attachments/assets/4533faec-545e-42d9-adfc-b18f34903f94" />

## Overview
In this project, I explore Australia’s demographic landscape, focusing on population dynamics such as age distribution, migration patterns, and birth and death rates. The aim is to communicate complex demographic trends through clear and engaging visualisations that are accessible to both decision-makers and the general public.

Demographic change affects nearly every aspect of society, from healthcare and housing to education, employment, and infrastructure planning. This project was designed to support better understanding of how these trends vary across states and capital cities in Australia.

## Why This Project
I built this visualisation to help translate large demographic datasets into insights that can support informed decision-making. Understanding where populations are ageing, where migration is increasing, and how natural population change differs across regions is critical for effective policy, funding, and service planning.

By presenting this information in an interactive webpage, the project allows users to explore demographic patterns rather than relying on static summaries.

## Intended Audience
This visualisation is targeted towards:
- Policymakers and government stakeholders responsible for funding and resource allocation
- Urban and infrastructure planners
- Members of the public interested in population change, migration, and ageing trends in Australia

## Data Sources
All data used in this project was sourced from the **Australian Bureau of Statistics (ABS)**.  
The datasets provide authoritative insights into:
- Median age by capital city
- Birth and death counts by state
- Net overseas migration by state
- Countries of origin for overseas migrants

These datasets are particularly useful for understanding long-term demographic shifts, such as population ageing in cities like Adelaide and increased migration into New South Wales and Victoria.

## Visualisations Included
- **Choropleth map of median age by capital city**
  - I used a choropleth map to provide an intuitive comparison of age distribution across Australian capital cities. Shading by median age allows users to quickly identify cities with younger or older populations.
- **Births and deaths bar charts**
  - Bar charts were used to compare birth and death counts across regions, making it easier to assess natural population change.
- **Net overseas migration bar chart**
  - This visualisation highlights differences in migration inflows across states.
- **Radial diagram of top migrant source countries**
  - The radial chart emphasises the relative contribution of the top source countries and highlights shifts in migration origins over time.

## Key Insights
- Cities such as Adelaide have higher median ages, reflecting their attractiveness to older populations and retirees.
- Cities like Darwin attract younger, working-age populations and therefore have lower median ages.
- New South Wales consistently records the highest number of births and deaths due to its larger population.
- Net overseas migration is concentrated in Victoria and New South Wales, driven by employment opportunities in Melbourne and Sydney.
- Migrant source countries have shifted towards Asia, particularly China and India.

## Design Decisions
- I used a choropleth map to support fast, intuitive comparison of age distributions.
- Bar charts were chosen for births, deaths, and migration flows to clearly represent scale.
- A radial diagram was used to present migration source countries in a visually distinctive way.
- Interactive tooltips were added to allow users to explore details such as sex ratios and exact values.
- Colour scales were selected to highlight key trends while maintaining readability.

## Limitations & Future Work
- The analysis focuses on aggregated state and capital city data, limiting suburb-level insights.
- Migration data reflects net flows and does not capture temporary or short-term movement.
- The visualisations do not include future demographic projections.

In future iterations, I would like to:
- Add demographic projections and time-series analysis
- Include socioeconomic indicators such as employment and housing demand
- Improve interactivity for deeper regional comparison

## Tools & Technologies
- **HTML, CSS, and JavaScript** for building the interactive webpage
- **Vega-Lite** for declarative data visualisation
- Data sourced and prepared from **Australian Bureau of Statistics (ABS)** datasets

This repository contains all the necessary files and data for the "Exploring Demographic Insights in Australia" webpage containing the relevant visualisations.

Important references:
- Latitude and longitude of the Australian capital cities - https://simplemaps.com/data/au-cities
- Map of Australia TopoJson MapChart - https://github.com/alwaysblazing/Australia-State-TopoJson-MapChart

Plagiarism Notice:
Code in this repository is not endorsed by Monash University. Please note that copying the code for unit assessments without referencing will result in a breach in Academic Integrity Policy. The author @James-JH will not be held responsible for these breaches. For more information please visit: https://www.monash.edu/students/academic/policies/academic-integrity.

## Author
James Huynh  
Visualisation created: 25/09/2024
