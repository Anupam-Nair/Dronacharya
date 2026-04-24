# ADDC Autonomous Drone Mission System

## Overview
This project simulates an autonomous drone system designed for SAE ISS ADDC 2025.

The system models real-world drone operations including:
- Autonomous takeoff and landing
- Waypoint navigation
- Payload pickup and delivery
- QR code-based verification
- Obstacle avoidance
- Battery-aware return-to-home

## Features
- Finite State Machine (FSM) mission planner
- Sensor simulation (GPS, LiDAR, QR)
- Autonomous navigation and decision-making
- Payload handling (pick & drop mechanism)
- Manual override mode
- Mission logging

## Mission Flow
INIT → TAKEOFF → NAV_PICKUP → PICK → NAV_DROP → QR_VERIFY → DROP → RETURN → LAND

## Tech Stack
- Python

## How to Run
```bash
python drone_mission.py
