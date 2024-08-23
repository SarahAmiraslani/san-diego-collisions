# San Diego County Collisions Exploratory Analysis

## Overview

This project explores the relationship between traffic collisions and various factors in San Diego County, focusing on data from 2015 to 2019. We investigate the correlation between collision locations and popular nightlife areas, temporal patterns of accidents, and potential police biases in traffic stops.

## Table of Contents

1. [Research Questions](#research-questions)
2. [Hypotheses](#hypotheses)
3. [Datasets](#datasets)
4. [Methods](#methods)
5. [Key Findings](#key-findings)
6. [Ethical Considerations](#ethical-considerations)
7. [Limitations](#limitations)
8. [Team Members](#team-members)
9. [Acknowledgements](#acknowledgements)

## Research Questions

1. What are the most common types of traffic collisions in San Diego County?
2. Is there a relationship between high bar density areas and traffic collision frequency?
3. Which police beats and geographic divisions experience the most severe accidents?
4. Are there any demographic biases in police traffic stops?

## Hypotheses

1. Minor, non-fatal accidents will be most prevalent.
2. More collisions will occur near nightlife hotspots (e.g., Pacific Beach, Gaslamp).
3. Lower-income neighborhoods will experience more severe accidents.
4. Younger drivers will be stopped and questioned more frequently.

## Datasets

1. **Traffic Collisions** (2015-2019): 28,122 observations
   - Source: [San Diego Data Portal](https://data.sandiego.gov/datasets/police-collisions/)
2. **Police Stops** (2018-2019): 179,725 observations
   - Source: [San Diego Data Portal](https://data.sandiego.gov/datasets/police-ripa-stops/)
3. **Yelp Bars**: 50 observations
   - Source: Yelp API
4. **Yelp Clubs**: 49 observations
   - Source: Yelp API

## Methods

- Geospatial analysis of collision locations relative to nightlife areas
- Temporal analysis of collision frequency by time and day
- Demographic analysis of police stops
- Statistical testing of hypotheses

## Key Findings

1. Most common violations: Traffic signal and sign violations
2. Highest collision frequency: Pacific Beach (1500 collisions)
3. Severe accidents: Northwestern San Diego (highest average injuries), Southern San Diego (highest average fatalities)
4. Demographics: Younger people stopped more frequently and for longer durations

## Ethical Considerations

- Implemented Safe Harbour protocol to protect individual privacy
- Careful interpretation of results to avoid reinforcing stereotypes or biases
- Consideration of socioeconomic factors in analyzing collision patterns

## Limitations

- Incomplete bar and nightclub data from Yelp API
- Overlapping violation categories in the dataset
- Broad geographic divisions may obscure local patterns
- Limited timeframe (2015-2019) may not capture long-term trends

## Team Members

- Sarah Amiraslani ([@SarahAmiraslani](https://github.com/SarahAmiraslani))
- Paul Chu ([@paulchu54](https://github.com/paulchu54))
- Catherine Eng ([@ceeng](https://github.com/ceeng))
- Jose Jimenez ([@JoseJimenezJr019](https://github.com/JoseJimenezJr019))
- Erin Park ([@eyp012](https://github.com/eyp012))
- Alysa Quijada ([@alysa-quijada](https://github.com/alysa-quijada))

## Acknowledgements

This project was completed as part of [COGS 108: Data Science in Practice](https://github.com/COGS108) at the University of California, San Diego. We thank our instructors and the San Diego Data Portal for providing resources and data.

For more information on San Diego police beats, visit the [San Diego Police Department website](https://www.sandiego.gov/police/services/divisions).
