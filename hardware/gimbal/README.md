# Gimbal

Two-axis (pan and pitch) camera gimbal for a FLIR Blackfly S machine-vision camera with lens, actuated by Dynamixel XC330 smart servos. Intended as an auxiliary sensor payload for the OpenSpot platform.

These files are **alpha reference** artifacts, not a complete fabrication package. All published models are STEP exports; preferred native CAD sources, dimensioned drawings, tolerances, fastener schedules, print parameters, and assembly procedures remain planned.

## Published designs

| File | Intended use | Maturity |
| --- | --- | --- |
| `base_plate.step` | Structural base; carries the pan-axis Dynamixel XC330 | Alpha reference |
| `pitch_servo_mount.step` | Yoke that carries the pitch-axis Dynamixel XC330 and couples to the camera mount | Alpha reference |
| `camera_mount.step` | Cradle for a FLIR Blackfly S with lens | Alpha reference |
| `full_assembly.step` | Reference assembly of the components above | Alpha reference |

## Reference hardware

- Camera: FLIR Blackfly S (with lens)
- Actuation: 2× Dynamixel XC330 smart servos (one pan, one pitch)

<!--
Exact part revisions, lens selection, cabling, servo controller, power protection, and mounting interface to the rest of the OpenSpot payload stack will be frozen with the first reproducible hardware release.

## Before fabrication

1. Confirm the design revision, material, process, fasteners, camera and lens mass, center of mass, and clearance envelope through the full pan and pitch range.
2. Verify Dynamixel XC330 mounting features, horn interface, and cable routing against the current manufacturer datasheet.
3. Independently validate structural strength, servo torque margin, retention, cable strain relief, and collision clearance with adjacent OpenSpot payloads.
4. Review the current Boston Dynamics payload mechanical and electrical requirements before mounting to Spot.
5. Treat any file without a released drawing and assembly procedure as experimental.

## Planned reproducibility package

- Native editable CAD alongside the neutral STEP exports.
- Dimensioned drawings and a fastener/insert schedule.
- Manufacturing and print settings with material specifications.
- Servo wiring, controller selection, and power budget for the gimbal subsystem.
- Assembly photographs and torque guidance.
- Mass, center-of-mass, and range-of-motion table for the assembled gimbal.
-->
Hardware files in this directory are licensed under CERN-OHL-W-2.0; see [`../../LICENSES/`](../../LICENSES/README.md).
