# Roof Inspection Drone Return-to-Home Safety

Build a drones prototype that uses IMU, flight controller to return safely on low battery or signal loss. Include setup instructions, a circuit diagram, tested firmware, and sample output.

> Build and test at safe low voltage. Real machinery, vehicles, aircraft, pumps, and power systems require qualified engineering review and certified safeguards.

## Project details

| Field | Value |
| --- | --- |
| Roadmap ID | 845 |
| Category | Drones |
| Platform | Arduino Nano 33 BLE |
| Difficulty | Advanced |
| Estimated build time | 40 hours |
| Connectivity | LoRa |
| Core components | IMU, flight controller |
| Control mode | safety latch |

## Repository layout

- `firmware/roof-inspection-drone-return-to-home-safety/roof-inspection-drone-return-to-home-safety.ino`: runnable firmware or application
- `docs/wiring.md`: suggested low-voltage wiring plan
- `docs/architecture.md`: system data flow
- `docs/test-plan.md`: repeatable verification steps
- `sample-data/example.json`: example telemetry record
- `tools/validate.py`: dependency-free repository validation

## Quick start

1. Open `firmware/roof-inspection-drone-return-to-home-safety/roof-inspection-drone-return-to-home-safety.ino` in Arduino IDE or Arduino CLI.
2. Select the board matching **Arduino Nano 33 BLE**.
3. Compile and upload, then open the serial monitor at 115200 baud.

## Expected behavior

Return-to-Home Safety demonstration with repeatable test steps. The default implementation supports simulated or generic analog inputs so the control path can be exercised before hardware-specific drivers are added.

## Hardware adaptation

The included code is a safe reference implementation. Update pin assignments and sensor conversions from the exact component datasheets, then repeat the test plan before connecting actuators.

## License

MIT
