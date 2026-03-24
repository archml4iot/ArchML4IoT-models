# Figures

This folder contains figures related to the ArchML4IoT framework.

## Figure 3: The ArchML4IoT Metamodel

![Figure 3: The ArchML4IoT metamodel.](./Figure%203%3A%20The%20ArchML4IoT%20metamodel.PNG)

This figure presents the ArchML4IoT metamodel and its main architectural elements. The core elements are described in Table 1.

### Table 1: ArchML4IoT metamodel core elements

| Element(s) | Description |
|---|---|
| **System** | Represents a high-level subsystem, such as a smart fire alarm, which acts as a container for organizing control and operational logic. |
| **PhysicalEntity** | Describes the real, tangible thing in the physical world that the system monitors, controls, or interacts with. |
| **Controller and Logic Unit** | Models the controller hardware and its decision-making logic, enabling the unit to automatically inherit behavioural templates from the statechart library. The Controller is constrained to associate with exactly one corresponding PhysicalEntity. |
| **Devices** | Captures the concrete I/O endpoints in the environment, including Sensors for measurements, Actuators for commands, and Tags for identification. |
| **Virtual Entity** | Abstracts the software representation of the system. It covers the information and capabilities needed to observe, reason about, and interact with the physical world through software. |
| **Resource** | Characterizes any software-accessible artifact that the Virtual Entity exposes or relies on to store, publish, or provide access to the state of its associated Physical Entity. |
| **System Hub and UI** | Encapsulates the front-end and back-end elements of a user interactive interface. |
| **Boundary, Port, and Network Type** | Specifies the network connectivity between components and systems, and the interfaces and deployment layers. |
