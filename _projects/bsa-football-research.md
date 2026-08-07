---
layout: page
title: Defensive play calling in clutch time
description: XGBoost models for expected points added on NFL two-minute-drill defensive scenarios, served through a Streamlit app.
img: assets/img/projects/bsa-football-research.png
importance: 3
category: coursework
---

What strategies can defensive play callers use to maximize defensive EPA in clutch time? This project defines clutch time as the two-minute drill with a point differential of eight or fewer, and models expected points added on a per-play basis within that window.

Bruin Sports Analytics research project, Fall 2024.

## Data and model

- nflverse play-by-play (formation, pressure, coverage type), restricted to 2018–2023 because rule changes shifted play styles
- nflverse comprehensive game data, 1999–2024, for EPA and in-game timestamps
- An XGBoost regression predicting passing EPA against all coverages given a situation and targeted route

Model features split three ways: situational (points down, down, distance, yardline, timeouts, seconds remaining), defensive (defenders in box, pass rushers, time to throw, QB pressured, coverage played), and offensive (pass length, pass location, out of bounds, no huddle, route targeted).

The model evaluates a play in a vacuum — it does not carry state from the preceding 58 minutes of the game. Scenarios can be entered interactively through a Streamlit web app.

## Materials

- [Slides (PDF)](https://github.com/narenp12/my_work/blob/main/Undergraduate/BSA_Football_Research/BSA_Football_Research_Slides.pdf)
