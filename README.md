# Behavioural responses of macropods to drones

## Overview

This repository contains the behavioural response datasets associated with the manuscript:

**"Evaluating behavioural responses of macropods to drones"**

The study investigates the behavioural responses of macropods to drone-based surveys, with a focus on determining how flight altitude influences animal reactions. Behavioural observations were collected for Forester kangaroos (*Macropus giganteus tasmaniensis*) and Bennett's wallabies (*Notamacropus rufogriseus*) exposed to flights conducted using a DJI Phantom 4 Pro quadcopter.

The datasets include behavioural observations collected through direct field observations and video-based assessments across two study sites in Tasmania, Australia.

## Dataset contents

This repository contains two datasets of macropod behavioural responses to drone surveys:

| File                      | Description                                                                                                                                                                                                  |
| ------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| `field_observations.xlsx` | Behavioural responses recorded during direct field observations of macropods during drone flights.     |
| `video_observations.xlsx` | Behavioural responses recorded from video footage collected during drone flights. |

## Data structure

### Field observations dataset

The field observations dataset contains behavioural observations recorded during drone surveys. The variables include:

| Variable     | Description                                                 |
| ------------ | ----------------------------------------------------------- |
| Date         | Date of observation                                         |
| Time         | Time of observation                                         |
| Altitude (m) | Drone flight altitude above ground level                    |
| V            | Vigilance                                                   |
| M            | Move                                                        |
| F            | Foraging/feeding                                            |
| R            | Resting                                                     |
| SC           | Social                                                      |
| OOS          | Out of sight                                                |
| Undisturbed  | Number of observations classified as undisturbed            |
| Vigilant     | Number of observations classified as vigilant               |
| Fled         | Number of observations classified as fled                   |
| Study site   | Study site identifier                                       |
| Species      | Species identity                                            |

The Excel file also includes summary tables of behavioural response counts and standard errors across different drone flight altitudes.

### Video observations dataset

The video observations dataset contains behavioural observations extracted from drone survey videos. The variables include:

| Variable               | Description                                          |
| ---------------------- | ---------------------------------------------------- |
| Date                   | Date of observation                                  |
| Time                   | Time of observation                                  |
| Altitude (m)           | Drone flight altitude above ground level             |
| Noise level (dB)       | Recorded drone noise level at each altitude          |
| No. of animal observed | Number of animals observed in the video recording    |
| Still                  | Number of observations classified as remaining still |
| Fled                   | Number of observations classified as fleeing         |
| Study site             | Study site identifier                                |
| Species                | Species identity                                     |

The Excel file also includes summary tables of behavioural response counts across different drone flight altitudes.

## Repository structure

```
macropod_drone_behaviour/
│
├── README.md
│
└── data/
    ├── field_observations.xlsx
    └── video_observations.xlsx
```
