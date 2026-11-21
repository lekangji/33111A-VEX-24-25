# 2024–2025 High Stakes

Team 33111A’s VEX V5 code for High Stakes, the 2024–2025 VEX Robotics Competition game.

## Robot 1 · Middle school

| Revision | Build | Programs |
| --- | --- | --- |
| V1 | Original sliding conveyor | [Teleop](robot-1/robot-v1/teleop/teleop.cpp) |
| V2 | Hook-chain redesign based on the high school robot | [Teleop](robot-1/robot-v2/teleop/teleop.cpp) · [Skills auton](robot-1/robot-v2/auton/auton.cpp) |
| V3 | Worlds update to the hook-chain robot | [Teleop](robot-1/robot-v3/teleop/teleop.cpp) |

Robot 1 V2’s teleop started as a copy of Robot 2 V1’s code after the October 5, 2024 redesign. That snapshot is `v1.1 Fix` in Robot 1’s history and `v4.1 Fix` in Robot 2’s.

## Robot 2 · High school

| Revision | Build | Programs |
| --- | --- | --- |
| V1 | First hook-chain robot | [Teleop](robot-2/robot-v1/teleop/teleop.cpp) |
| V2 | Rebuild with general improvements | [Teleop](robot-2/robot-v2/teleop/teleop.cpp) · [Auton](robot-2/robot-v2/auton/auton.cpp) |
| V3 | Third revision | [Teleop](robot-2/robot-v3/teleop/teleop.cpp) · [Auton](robot-2/robot-v3/auton/auton.cpp) |

## Build a program

Use one linked program as `main.cpp` in a VEXcode V5 C++ project. Each program has its own entry point. To build the separate [Robot 1 V2 drivetrain-controller beta](robot-1/robot-v2/auton/drivetrain-controller/auton.cpp), add its [controller source](robot-1/robot-v2/auton/drivetrain-controller/drivetrain_controller.cpp) and [header](robot-1/robot-v2/auton/drivetrain-controller/drivetrain_controller.h) to the same project.

The program links point to the latest snapshots on `main`. Open a file’s **History** to find earlier versions and their original dates.

## Competition results

- Qualified for Worlds
- State competition finalist
