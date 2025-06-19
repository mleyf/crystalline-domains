# Polymer Crystalline Domain Analyzer

A Python toolkit for identifying crystalline domains in polymer systems using molecular dynamics data. 
It calculates:
- **P2 order parameter** to quantify molecular orientation
- **Crystalline fraction** via DBSCAN clustering
- **Domain statistics** (size/distribution)

Designed for polyethylene-like systems, the tool outputs cluster data to CSV for analysis in pandas. Suitable for studying crystallization kinetics and phase transitions.

## Key Features
1. **Modular Analysis Pipeline**
   - P2 calculation
   - Domain clustering
   - Crystalline fraction quantification

2. **Visualization Tools**
   - 3D molecular plots with directors
   - Time-series crystallization plots

3. **Configurable Parameters**
   - Adjust clustering sensitivity
   - Customize analysis frequency
