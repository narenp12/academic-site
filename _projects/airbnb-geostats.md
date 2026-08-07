---
layout: page
title: Predicting Airbnb prices with geostatistics
description: Ordinary kriging and co-kriging on Austin Airbnb listings, with variogram fitting and cross-validation.
img: assets/img/projects/airbnb-geostats.png
importance: 2
category: coursework
---

A geostatistical approach to predicting nightly price for Airbnb listings in Austin, treating price as a spatially correlated surface rather than a set of independent observations. Data comes from the 14 December 2024 Inside Airbnb release, sampled down to 1,000 distinct listings.

Final project for a spatial statistics course.

## Approach

- Non-spatial exploration and summary of listing attributes (property type, room type, bathrooms, bedrooms, beds, price)
- Sample variogram fitting, comparing exponential and spherical models
- Ordinary kriging over the listing coordinates, with leave-one-out cross-validation
- Ordinary co-kriging with a covariate, compared against ordinary kriging on prediction and variance surfaces

## Materials

- [Report (PDF)](https://github.com/narenp12/my_work/blob/main/Undergraduate/Airbnb_Geostats/Airbnb_Geostats.pdf)
