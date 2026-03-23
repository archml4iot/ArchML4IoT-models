# STL4IoT

This folder contains the STL4IoT statechart models used in our study. It includes both the generated statechart models derived from the architecture models and the manually created statechart models used for evaluation and comparison.

## Folder Structure

### `Generated`
This folder contains the statechart models automatically generated from the ArchML4IoT architecture models.

### `Manual`
This folder contains the manually created statechart models used as reference models for evaluation and comparison.

## Example: Hub Template Statechart

![Hub Template Statechart](./Statechart%20-%20hub%20template.PNG)

The **hub template statechart** illustrates the structural foundation provided for the smart home hub in the STL4IoT model set. Since the hub is responsible for coordinating multiple subsystems, its behavior is more complex and less predictable than that of individual smart home components. For this reason, the generated hub model is provided as a reusable template rather than as a fully completed behavioral design.

The diagram shows the key regions and states that form the skeleton of the hub logic. These elements provide an initial behavioral structure that supports later refinement, allowing developers to adapt the hub model to the coordination needs of a specific smart home system. In this way, the generated hub template helps reduce the effort required to bootstrap statechart development while still preserving a consistent structure derived from the architecture model.
