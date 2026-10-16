# GT4 distance camera v0.3

**Spec II 1.10 · SCUS-97436 · CRC 646B2E29 · PCSX2**

Download [646B2E29_camera-distance.pnach](646B2E29_camera-distance.pnach). Enable `Camera/Analog distance and pitch` and restart without a savestate.

- Right stick right/left: move closer/farther; release holds.
- Right stick up/down: adjust pitch; release holds.
- Center and diagonals: ignored. Each axis works only while the other is centered (raw 104–151).
- `C` → port-2 R3: restore the current car's factory camera. The next adjustment starts from that position.
- Optional `[` / `]` → port-2 L1 / R1: move closer/farther.

Use DualShock 2 on port 1 and port 2 for the optional keys. Use the normal chase camera and one camera mod at a time. Original FOV retained.

Version 0.3 fixes code placement and checks payloads before enabling hooks. Reported working by the user on PCSX2 2.8.2.
