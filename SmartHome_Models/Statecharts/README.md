# Multi-state Machines

This folder contains the smart home statechart models used in our study. It includes both the generated statechart models derived from the architecture models and the manually created statechart models used for evaluation and comparison.

## Folder Structure

### `Generated`
This folder contains the statechart models automatically generated from the ArchML4IoT architecture models.

### `Manual`
This folder contains the manually created statechart models used as reference models for evaluation and comparison.

## Example: Garage Door System

![Inline Definition Section](./Statechart%20-%20system%20-%20inline%20definition%20section.PNG)

---

This figure shows the **inline definition** section of the **Garage Door System** statechart model. 
It defines the internal elements required by the system, such as interfaces, events, variables, and component instances, which support communication and coordination among the statecharts in the model.

---

![System Statechart](./Statechart%20-%20system%20-%20statechart.PNG)
![System Statechart 2](./Statechart%20-%20system%20-%20statechart%202.PNG)

---

These figures presents the main system-level statechart of the **Garage Door System** model. 
It captures the overall system behavior and coordinates the interaction among the internal components that realize the garage door logic.

---

![Garage Door Logic Unit](./Statechart%20-%20garage%20door.PNG)

---

This figure shows the **Garage Door Logic Unit** statechart. It represents the behavior of the garage door core logic.
Combined with the system-level statecharts, it contributes to the complete multi-state machine model of the Garage Door system.
---
