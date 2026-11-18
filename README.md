# Adaptive Headlight – Non-Sequential Ray Tracing (Zemax OpticStudio)

Design and simulation of a steerable car headlight in non-sequential mode
using Zemax OpticStudio. The headlight adapts its beam direction when the
vehicle takes a turn, improving road illumination and driver visibility.

> **Note: the full project report is written in French.**

## Overview

The goal of this project is to model and size a directional headlight
capable of steering its light beam in curves. Three driving configurations
were studied:

- Straight road
- Right turn
- Left turn

## Methodology

1. **Specifications**: definition of the system and expected performance
2. **Sequential design**: initial draft of the optical system in sequential mode
3. **Optimization**: tuning of the system against the requirements
4. **Non-sequential conversion**: full ray tracing with detectors to evaluate
   the illumination in each configuration
5. **Tolerancing**: Monte Carlo analysis (best and worst cases) to evaluate
   the sensitivity of the design to manufacturing errors

## Repository structure

| Folder | Content |
|---|---|
| `report/` | Full project report (PDF, **in French**) |
| `zemax/` | Main optical system file |
| `tolerancing/` | Monte Carlo best/worst case files |

## Requirements

- Zemax OpticStudio (version: *to be specified*)

## Usage

Open the files in `zemax/` and `tolerancing/` with OpticStudio, then run
the ray trace in non-sequential mode with the detectors enabled.

## Authors

- Robin Jegard
- Gaspard Milek
