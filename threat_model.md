# Threat Model and Risk Analysis

| Threat | Impact | Mitigation |
|---|---|---|
| Unauthorized camera monitoring | Behavioral surveillance and privacy violation | Permission-controlled camera activation and privacy modes |
| Typing telemetry misuse | Behavioral privacy leakage | No raw keystroke logging and permission-controlled typing analysis |
| Fatigue score misuse | Sensitive behavioral inference exposure | Local-only processing and restricted system access |
| Unauthorized ROS2 node access | False data injection or monitoring manipulation | Authenticated DDS communication concepts |
| Sensitive topic interception | Exposure of behavioral telemetry | Secure ROS2/DDS transport concepts |
