# Behavioural responses of macropods to drones

## Overview

This repository contains the behavioural response datasets associated with the manuscript:

**"Evaluating behavioural responses of macropods to drones"**

The study investigates the behavioural responses of macropods to drone-based surveys, with a focus on determining how flight altitude influences animal reactions. Behavioural observations were collected for Forester kangaroos (*Macropus giganteus tasmaniensis*) and Bennett's wallabies (*Notamacropus rufogriseus*) exposed to flights conducted using a DJI Phantom 4 Pro quadcopter.

The datasets include behavioural observations collected through direct field observations and video-based assessments across two study sites in Tasmania, Australia.

## Dataset contents

This repository contains the following Excel files:

| File                      | Description                                                                             |
| ------------------------- | --------------------------------------------------------------------------------------- |
| `field_observations.xlsx` | Raw field observations of macropod behavioural responses recorded during drone surveys. |
| `video_observations.xlsx` | Raw behavioural observations extracted from video recordings of drone surveys.          |

## Data structure

The observation datasets contain records of individual or group-level behavioural responses to drone flights. The main variables include:

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

Each Excel file also includes summary tables generated from the observations, including total response counts and standard errors across different drone flight altitudes.

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
