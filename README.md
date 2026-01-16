Checkout my other widgets:

https://github.com/moshirfakhoury/edgetx-postflight-widget

https://github.com/moshirfakhoury/edgetx-preflighttest-widget

https://github.com/moshirfakhoury/edgetx-images-widget

Overview

FlightDash is a custom EdgeTX Lua widget designed to provide a clear, at-a-glance flight dashboard for helicopters. It consolidates critical telemetry, status, and system information into a single, visually intuitive layout optimised for in-flight use.
The widget focuses on situational awareness, using colour-coded icons, flashing alerts, and status tiles to highlight important conditions such as arming state, motor state, receiver health, battery status, and remaining flight time.
FlightDash is compatible with EdgeTX 2.11+ and is designed for RadioMaster transmitters, but should work on any EdgeTX-supported radio with sufficient screen resolution.
The widget is fully configurable using EdgeTX widget parameters, allowing users to select their own telemetry sources as well as define which switches or channels are used for Arm and Motor status detection.

Functions
- Displays model name, date, time, and TX battery
- Model icon shows arm and motor state
- Icon can dynamically change between helicopter, plane, or drone based on a user-defined value (GV9 FM1 - Off: Heli, 1 Plane, 2 Drone)
- Receiver battery voltage with automatic cell count and per-cell voltage
- Receiver signal strength (1RSS) and link quality (RQTY)
- ESC temperature display
- RPM and current telemetry
- Flight timer with progress bar
- Status tiles for motor, arm state, and flight mode
- Fully configurable telemetry sources and switches via widget parameters
- Icons and indicators use clear colour changes and flashing states to make important conditions easy to notice at a glance

Notes
- All colour and flashing logic is handled in real time
- Telemetry sources, Arm switch, and Motor switch are user-selectable via widget parameters
- No persistent data is stored; all detection resets safely on RX signal loss or radio reboot
- Designed for clarity, minimal clutter, and fast interpretation while flying

Widget - not connected to model

<img width="487" height="276" alt="image" src="https://github.com/user-attachments/assets/b93c4190-4106-42e2-aded-cd524e5b5257" />

Widget - connected to model but not armed

<img width="490" height="278" alt="image" src="https://github.com/user-attachments/assets/cdd9bb73-1655-429b-b801-9c57a14da131" />

Widget - connected to model and armed

<img width="487" height="277" alt="image" src="https://github.com/user-attachments/assets/e94fca6c-bd04-4994-8009-25f68a974011" />

Widget - Plane Icon - GV9 FM1 = 1

<img width="492" height="283" alt="image" src="https://github.com/user-attachments/assets/7bdc8e70-5cd1-46e9-b82e-0a034759e8fe" />

Widget - Drone Icon - GV9 FM1 = 2

<img width="487" height="282" alt="image" src="https://github.com/user-attachments/assets/81bed855-a3f1-4221-bd58-3fb6c8854f1b" />

