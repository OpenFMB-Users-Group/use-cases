# **OpenFMB Operational Use Cases**

This repository contains documentation for the OpenFMB operational use cases.

## Use cases

There are currently 4 operational use cases for OpenFMB:

* [DER Circuit Segment Management][1]
* [Circuit Segment Optimization][2]
* [Microgrid Unscheduled Islanding][3]
* [Microgrid Reconnection][4]

There is also 1 supplementary document referenced by all of the above use cases:

* [Information Exchanged][5]

[1]: https://gitlab.com/openfmb/use-cases/ops/blob/master/OpenFMBUseCases-DERCircuitSegmentManagement.pdf
[2]: https://gitlab.com/openfmb/use-cases/ops/blob/master/OpenFMBUseCases-CircuitSegmentOptimization.pdf
[3]: https://gitlab.com/openfmb/use-cases/ops/blob/master/OpenFMBUseCases-MicrogridUnscheduledIslanding.pdf
[4]: https://gitlab.com/openfmb/use-cases/ops/blob/master/OpenFMBUseCases-MicrogridReconnection.pdf
[5]: https://gitlab.com/openfmb/use-cases/ops/blob/master/OpenFMBUseCases-InformationExchanged.pdf

## Short descriptions of the use cases

Below is a short description of each individual use case listed above. For detailed information, please download the relevant use case PDF from the repository.

### **DER Circuit Segment Management**

The business objective of this Distributed Energy Resources (DER) Circuit Segment Management use case is to actively coordinate circuit segment power system
equipment to accommodate DER. This grid edge is moving from a hub-and-spoke control paradigm to devices with layered intelligence
incrementally applied where it is most valuable. For a specific circuit segment, localized edge analytics combined with coordinated self-
optimization, handle the increasing volume, velocity, and variety of information from an expanding number of heterogeneous devices. Local
data exchange for a circuit segment satisfies that segment’s actionable decision in the field without a roundtrip to a central site. Multiple
communications paths and observable interfaces enable interactions between devices and systems at all layer hierarchies. While
complimenting existing systems such as DMS, EMS, and SCADA, new devices and current plant interoperate to foster enhanced safety,
reliability, resiliency, and security.

Building upon the primary scenario, examples of added value business case extension scenarios include solar smoothing, peak demand,
Volt – VAr, distribution transfer-trip, and anti-islanding.

### **Circuit Segment Optimization**

The business objective of this DER Circuit Segment Optimization use case is to harmonize local device coordination with centralized system
controls through schedule optimization for a service provider defined period of time based upon information such as weather, markets, and
dispatch / load forecasts. Considering component status and capabilities over appropriate timeframes, circuit segment optimization
schedules maintain proper voltage, frequency, and power factor for safe, reliable operation either while connected to the larger grid or as an
islanded microgrid for those circuit segments with appropriate capabilities. Circuit segment schedules may also consider objectives such as:

* Import or export schedules
* Economic dispatch
* Solar smoothing to reduce circuit segment volatility
* Volt-VAr for power factor optimization
* Peak demand management by shaving / shifting

### **Microgrid Unscheduled Islanding**

The business objective of this Microgrid Unscheduled Islanding use case is to seamlessly transition a low-inertia microgrid from grid-
connected to islanded mode. The microgrid PCC Coordination Service creates device schedules considering the status and capabilities of
circuit segment actors over appropriate timeframes. These schedules maintain proper voltage, frequency, and power factor for safe, reliable
operation, including switching the Primary Energy Storage System to voltage source inverter (VSI) isosynchronous (ISO) mode upon loss of
grid power at the Point of Common Coupling (PCC).

### **Microgrid Reconnection**

The business objective of this Microgrid Reconnection use case is to seamlessly transition a low-inertia microgrid from islanded to grid-
connected mode. The microgrid PCC Coordination Service creates device schedules considering the status and capabilities of circuit
segment actors over appropriate timeframes. These schedules maintain proper voltage, frequency, and power factor for safe, reliable
operation, including switching the Primary Energy Storage System from voltage source inverter (VSI) isosynchronous (ISO) mode upon
reconnection to the grid.

### **Information Exchanged**

This document contains common UML diagrams from section 5 of each of the use case documents above.

## Copyright

See the COPYRIGHT file for copyright information of information contained in this repository.

## License

Unless otherwise noted, all files in this repository are distributed under the Apache Version 2.0 license found in the LICENSE file.
