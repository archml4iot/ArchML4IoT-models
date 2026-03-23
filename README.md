# Archml4IoT-models

This repository contains the models used in the ArchML4IoT workflow for smart home systems.

## Overview

The repository provides three categories of models derived from our ArchML4IoT-based modelling process:

- **Architecture models** created in ArchML4IoT for smart home systems
- **Configuration models** generated from the architecture models
- **Statechart models** generated from the architecture models for STL4IoT
- **Figures** attached to the paper.

In addition to the generated models, this repository also includes manually created versions of the configuration and statechart models for evaluation and comparison.

## Repository Structure

### `Archml4IoT-models/ArchML4IoT Model`
This folder contains all architecture models created for smart home systems using ArchML4IoT.

These models describe the system structure at the architecture level and serve as the source models for downstream model generation.

### `Archml4IoT-models/Config Model`
This folder contains all configuration models generated from the architecture models.

It also includes manually created configuration models that are used for evaluation and comparison against the generated results.

### `Archml4IoT-models/STL4IoT`
This folder contains all statechart models generated from the architecture models.

It also includes manually created statechart models that are used for evaluation and comparison against the generated results.

### `Figures`
This folder contains figures in the paper. In case the figures are not clear enough for the reader.

## Purpose

This repository is intended to:

- provide the model artifacts used in the ArchML4IoT workflow
- support evaluation of the generated results against manually created models
- make the modelling results publicly available for reference and reuse

## Notes

- The models in this repository are focused on **smart home system** examples.
- The generated models are organized together with manually created baseline models for evaluation purposes.
- The ArchML4IoT modelling editor and transformation scripts are maintained separately.

## Require Tools

- Eclipse Modeling Tools - 2023-06
- Eclipse Sirius - releases/7.4.11/2023-03
- itemis CREATE - version 5.2.2
