# ArchML4IoT Models

This folder contains the architecture models created in ArchML4IoT for the smart home systems used in our study. These models represent the system structure at the architecture level and serve as the source models for downstream generation, including configuration models and STL4IoT statechart models.

This folder currently includes architecture models for:

- Fire Alarm
- Garage Door
- Smart Home Hub
- Smart Light

Each model captures the main structural elements of the system, such as subsystems, devices, controllers, resources, ports, and communication relationships.

## ArchML4IoT modelling environment featuring a sample model of a smart farm system.

![Smart Home Hub](./Smart%20Home%20Hub.PNG)

## Example: Smart Home Hub

![Smart Home Hub](./Smart%20Home%20Hub.PNG)

The **Smart Home Hub** architecture diagram presents the hub as the central coordination unit in a smart home system-of-systems. It shows how multiple subsystems are organized within clearly defined boundaries, while ports and connectors represent the communication interfaces that link them together. By making these structural relationships explicit, the model provides a clear architectural specification for the overall smart home system and serves as a foundation for deriving downstream artifacts, helping maintain consistency between the architecture and later digital twin, simulation, and deployment models.

More specifically, the diagram shows how the Smart Home Hub integrates different functional parts of the smart home environment into a unified architecture model. This makes the system structure explicit at an early stage and provides a shared architectural specification that can later support the generation of downstream artifacts, such as configuration models and executable statechart-based behavioral models. In this way, the architecture model helps maintain consistency between high-level system design and later implementation artifacts.
