# Security Architecture

## System Components

User
↓
Frontend / Permission Controls
↓
/permissions Topic
↓
Fusion Node
↓
Fatigue Score
↓
Alert System

---

## Sensor Inputs

Camera Features
- blink rate
- eye closure
- posture behavior

Typing Features
- typing speed
- typing variance
- pause behavior

---

## Privacy Layer

The privacy layer controls:

- camera access
- typing telemetry access
- adaptive monitoring modes
- sensor availability

Privacy Modes:
- FULL_MONITORING
- PRIVACY_MODE
- MINIMAL_MODE

---

## Security Concepts

The architecture considers:

- permission-controlled sensing
- local-only processing
- DDS secure communication concepts
- authenticated node communication
- reduced telemetry collection
- no raw biometric storage

---

## Adaptive Confidence Logic

| Available Sensors | Confidence |
|---|---|
| Camera + Typing | HIGH |
| Typing Only | MEDIUM |
| Minimal Telemetry | LOW |
