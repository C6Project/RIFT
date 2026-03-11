
# RIFT

**Rigidity Inference from Trajectories**

RIFT is a protocol for analyzing the structural behavior of dynamic systems using trajectory-based observations.

Instead of examining isolated measurements, RIFT evaluates how system states evolve along a sequence of observations and embeds those trajectories into a statistical feature space. By measuring deviations from baseline behavior using statistical distance metrics, RIFT enables detection of structural patterns, stability properties, and anomalous system behavior.

The protocol is designed to work across many domains where systems evolve over time and space, including communications infrastructure, cyber-physical systems, and other environments where traditional snapshot analysis provides limited visibility.

## Core Idea

RIFT treats observations as part of a **trajectory**, not as independent measurements.

```
trajectory → windowed observations → feature space → structural analysis
```

By analyzing how system behavior evolves along trajectories, RIFT can identify structural changes that may not be visible in single-point measurements.

## Related Work

* **TRACE (Trajectory Radio Analysis and Coupling Engine)**
  A measurement and analysis system that implements the RIFT protocol for studying cellular radio environments along real-world trajectories.

## Status

RIFT is currently being developed and evaluated as part of ongoing research.

Additional documentation and reference implementations will be added as the work progresses.
