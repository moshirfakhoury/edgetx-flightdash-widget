FlightDash Widget (EdgeTX)

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
<img width="1031" height="590" alt="image" src="https://github.com/user-attachments/assets/1904bdde-9f5e-4770-a317-28ccabe33f16" />

Widget - connected to model but not armed
[screen-2026-01-13-091604.bmp](https://github.com/user-attachments/files/24625043/screen-2026-01-13-091604.bmp)

Widget - connected to model and armed
[screen-2026-01-13-091611.bmp](https://github.com/user-attachments/files/24625052/screen-2026-01-13-091611.bmp)

Widget - Plane Icon - GV9 FM1 = 1
[screen-2026-01-13-215028.bmp](https://github.com/user-attachments/files/24625058/screen-2026-01-13-215028.bmp)

Widget - Drone Icon - GV9 FM1 = 2
[screen-2026-01-13-215053.bmp](https://github.com/user-attachments/files/24625064/screen-2026-01-13-215053.bmp)
