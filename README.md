# VigiaLinkApp

Mobile application for real-time monitoring, live camera streaming, AI alerts, and remote surveillance management.

Is the primary user interface for the Monitra ecosystem, providing centralized access to remote camera streams, intelligent alerts, event timelines, and live monitoring features directly from mobile devices.

The application is designed for simplicity, low latency, and real-time situational awareness across distributed surveillance environments.

---

# Features

- Live camera streaming
- Real-time AI alerts
- Remote camera access
- Event timeline
- Motion and intrusion notifications
- Multi-location monitoring
- Camera status monitoring
- Low-latency streaming
- Secure authentication
- Push notifications
- Snapshot previews
- Mobile-first monitoring experience

---

# Core Concepts

Monitra Mobile connects users directly to the centralized Monitra Server, allowing remote monitoring of cameras installed across multiple locations.

The app focuses on:
- simplicity
- reliability
- low latency
- fast access to events
- real-time monitoring

---

# Architecture

```text
┌─────────────────┐
│   IP Cameras    │
└────────┬────────┘
         │
         ▼
┌─────────────────┐
│      Agent       │
└────────┬────────┘
         │
         ▼
┌─────────────────┐
│      Server      │
└────────┬────────┘
         │
         ▼
┌─────────────────┐
│   VigiaLinkApp   │
└─────────────────┘
```

---

# Main Features

## Live Monitoring

Users can access live streams from remote cameras with low latency.

Supported technologies:
- WebRTC
- HLS
- RTSP relay (planned)

---

## AI Alerts

Receive instant notifications for:
- person detection
- intrusion events
- motion detection
- camera offline
- abnormal activity
- stream interruptions

---

## Event Timeline

Browse:
- alerts
- snapshots
- AI detections
- recent activity
- camera events

---

## Multi-Camera Support

Monitor multiple cameras across:
- stores
- warehouses
- offices
- industrial facilities
- remote locations

---

# Planned Features

- Multi-location grouping
- Interactive event timeline
- Camera favorites
- Smart notifications
- Stream quality adaptation
- Offline caching
- Local recording playback
- Event filtering
- AI event categories
- Emergency mode
- Dark mode
- Biometric authentication
- WebRTC ultra-low latency mode

---

# Tech Stack

- Flutter
- Dart

## Streaming

- WebRTC
- HLS

## Notifications

- Firebase Cloud Messaging (planned)

---

# Repository Structure

```text
mobile/
├── lib/
│   ├── core/
│   ├── features/
│   ├── services/
│   ├── models/
│   ├── screens/
│   ├── widgets/
│   └── utils/
│
├── assets/
├── android/
├── ios/
├── test/
├── pubspec.yaml
└── README.md
```

---

# Design Goals

Monitra Mobile is designed to be:

- lightweight
- responsive
- minimal
- fast
- reliable
- mobile-first

The application prioritizes:
- rapid alert access
- live monitoring
- operational simplicity
- low-friction navigation

---

# User Experience Goals

The mobile app should allow users to:

1. Open the app
2. Instantly view camera status
3. Access live streams
4. Receive alerts in real time
5. Review recent events
6. Respond quickly to incidents

with minimal interaction complexity.

---

# Development Roadmap

## Phase 1

- Authentication
- Camera list
- Live stream viewer
- Basic alerts

## Phase 2

- Event timeline
- Push notifications
- Snapshot previews
- Multi-camera support

## Phase 3

- Smart filtering
- AI event categories
- Camera grouping
- Stream optimization

## Phase 4

- Advanced analytics
- Offline support
- Emergency workflows
- Edge-aware features

---

# Use Cases

- Retail stores
- Warehouses
- Offices
- Industrial monitoring
- Smart surveillance systems
- Distributed monitoring
- Remote AI analytics

---

# Goals

Monitra Mobile aims to provide:

- real-time awareness
- centralized remote monitoring
- low-latency access
- intelligent event notifications
- reliable mobile surveillance

through a simple and modern mobile experience.

---

# Development Status

Early development / proof of concept.

---

# License

MIT License

Copyright (c) 2026 VigiaLinkApp

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND.
