
# Data-Center-Thermal-Scavenger

## Description
An external, decoupled thermal scavenging retrofit for data center exhaust. This project converts waste heat from server exhaust into usable electrical power using a closed-loop refrigerant cycle and a scroll-expander, creating a "cool-to-power" feedback loop that lowers facility energy costs.

## Design Philosophy
- **Non-Invasive:** Decoupled from server internals to ensure zero risk to uptime.
- **Waste-Deleting:** Transforms heat from an environmental hazard into a localized energy source.
- **Convection-Assisted:** Leverages natural thermosiphon effects (hot air rise/cool air sink) to assist server airflow.

## How It Works
1. **Thermal Interface:** Exhaust air passes through a high-surface-area manifold (micro-channel aluminum plates).
2. **Refrigerant Loop:** Heat is transferred to an R-290 or R-134a loop.
3. **Conversion:** A scroll-expander drives a permanent magnet generator.
4. **Feedback:** Recovered energy is injected back into the server rack cooling infrastructure.

## Bill of Materials (BOM)
| Component | Specification |
| :--- | :--- |
| **Thermal Plates** | Anodized Aluminum Micro-channel Heat Sinks |
| **Working Fluid** | R-290 (Propane) or R-134a |
| **Expander** | Modified Scroll Compressor (Reversed) |
| **Generator** | Permanent Magnet DC (PMDC) Motor |

## Contributing
Contributions are welcome! Please see the `CHANGES.txt` file for instructions on how to document any modifications to this design, as per the CERN-OHL-W v2 license.

## License
Licensed under CERN-OHL-W v2 or later. See the `LICENSE` file for full terms.



