# Tactical Cover AI

An Unreal Engine 5.3 project exploring scoring-based AI decision-making for tactical cover selection and coordinated squad behavior.

## About

This is a gameplay AI prototype where enemies evaluate cover positions, coordinate roles, and execute flanking maneuvers. The goal is to build believable tactical behavior using a scoring system.

Built with C++ and Blueprints in Unreal Engine 5.3.

## Current Features

- Third-person shooter controller with aiming and shooting
- Hit detection with physical material support
- Health system with death and respawn
- Basic HUD with crosshair and health bar
- Enemy AI with NavMesh-based navigation
- Multiplayer game mode with split-screen support

## Planned AI Features

**Cover System**
- Cover point placement and evaluation
- Centralized Cover Manager to handle occupancy and prevent conflicts between AI agents
- Line-of-sight and exposure checks against known threats

**Scoring-Based Decision Making**
- Each cover point scored by distance, exposure, angle to threat, and tactical value
- Dynamic reevaluation when conditions change (player moves, allies go down)
- Weighted scoring with tunable parameters for different AI personalities

**Role System**
- Suppressor role — holds position and applies pressure from the front
- Flanker role — repositions to attack from the side or rear
- Role assignment based on current squad state and opportunity scoring

**Debug Visualization**
- Cover point markers with occupancy state
- Line-of-sight debug drawing
- Per-agent score breakdowns for tuning and demonstration

## Assets Used

This project uses the following free assets from the Unreal Marketplace:

- Animation Starter Pack
- Military Weapons Dark
- Realistic Starter VFX Pack Vol 2

## Author

Alex Lukoshkin
