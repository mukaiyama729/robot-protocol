# robot-protocol

Shared, `no_std` communication contract for Linux drivers and embedded
firmware. Keep framing, command, reply, and version compatibility decisions
here so a microcontroller can be replaced without changing the Linux use cases.

The main repository pins this project as `crates/robot-adapter/protocol`; the
firmware repository consumes it as a sibling checkout at `../protocol` when
developed independently.
