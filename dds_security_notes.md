# DDS Security and Secure ROS2 Communication

## Overview

ROS2 uses DDS (Data Distribution Service) middleware for communication between distributed nodes.

In a multimodal fatigue detection system, DDS communication may involve sensitive behavioral telemetry such as:

- eye behavior
- typing telemetry
- fatigue inference data
- privacy permission settings

Without security protections, unauthorized ROS2 nodes could potentially:

- subscribe to sensitive topics
- inject false fatigue data
- manipulate monitoring behavior
- intercept behavioral telemetry

---

## DDS Security Concepts

DDS security mechanisms help improve communication security through:

### Authentication
Verifies trusted ROS2 nodes before communication.

### Access Control
Restricts which nodes can publish or subscribe to sensitive topics.

### Secure Communication
Protects telemetry exchange through encrypted middleware transport concepts.

---

## Sensitive ROS2 Topics

Examples of sensitive topics in the architecture include:

- /permissions
- /fatigue_score
- /camera_features
- /typing_features

These topics may contain behavioral or privacy-related telemetry.

---

## Privacy-Aware Communication Design

The system follows privacy-aware communication principles:

- local-only fatigue processing
- permission-controlled sensing
- modular sensor disabling
- reduced telemetry collection
- no raw biometric storage

---

## Security Goals

The architecture aims to:

- reduce unauthorized monitoring risks
- minimize behavioral data exposure
- prevent misuse of fatigue telemetry
- support secure ROS2 communication practices
