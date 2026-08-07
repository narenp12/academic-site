---
layout: page
title: Puffer's Disease — an extended SIR model
description: Compartmental ODE model adding an asymptomatic infectious state and vaccination to the classic SIR structure.
img: assets/img/projects/puffers-disease-model.png
importance: 7
category: coursework
---

A compartmental disease model built on the SIR structure, extended with a fourth state and a vaccine. The team chose SIR deliberately: well-documented enough to build on confidently, simple enough to leave room to complicate.

Group modeling project with Kay, Sam, and Sophie.

## Model

Four state variables, all rates per day:

- **S** — susceptible
- **N** — infectious but not yet symptomatic
- **I** — currently infected and symptomatic
- **M** — recovered with immunity

Parameters were chosen to track real disease behavior: susceptible individuals are 2% more likely to be infected by symptomatic than asymptomatic individuals, and individuals are always asymptomatic before becoming symptomatic. A vaccine is incorporated into the flow. The motivating question is the effect of the steepness of negative feedback loops.

## Materials

- [Slides (PDF)](https://github.com/narenp12/my_work/blob/main/Undergraduate/Puffers_Disease_Model/Puffers_Disease_Model_Slides.pdf)
