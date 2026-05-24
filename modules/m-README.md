# HVAC Digital Twin - Modules

## Overview
This folder contains the core engineering simulation modules that form the HVAC digital twin system.

Each module represents a physical subsystem modeled using first principles of thermodynamics and process engineering.

## Module Structure

- thermodynamics/ → Energy balance and first law systems
- heat_transfer/ → Conduction, convection, radiation models
- fluid_flow/ → Air and fluid movement in ducts and pipes
- psychrometrics/ → Moist air property calculations
- refrigeration_cycle/ → Vapor compression cycle modeling
- ahu_system/ → Air handling unit behavior
- cooling_load/ → Building thermal load estimation
- hydronic_system/ → Water-based HVAC loops
- controls/ → System regulation and control logic

## Design Philosophy
- Physics-based modeling (first principles)
- Modular architecture
- Scalable system integration
- Digital twin readiness

## Goal
To build a fully integrated HVAC system simulation from component-level physics.