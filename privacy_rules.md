# Privacy Rules

## Allowed Data
The system is allowed to process:

- Blink rate
- Eye closure duration
- Posture angle
- Typing speed
- Typing variance
- Fatigue score

## Restricted Data
The system must NOT store or share:

- Raw camera video
- Screenshots
- Typed text content
- Passwords or sensitive inputs
- Cloud-uploaded user data

## Privacy Policies

### Local Processing
All fatigue analysis is performed locally on the device.
No external APIs or cloud services are used.

### User Permission Control
Users can enable or disable:
- Camera access
- Typing behavior tracking

### Adaptive Monitoring
If a sensor is disabled, the system adapts fatigue detection
using only the remaining available inputs.

### Data Minimization
Only required fatigue-related features are processed.
Unnecessary personal data is not collected.
