# hybrid-divertor-for-fusion
Computatinal models for hybrid snowflake-liquid metal divertor optimization
Fusion Hybrid Divertor Simulation

Project Overview
This repository contains computational models developed for the ISEF project: *"Computational Optimization and Economic Validation of a Hybrid Snowflake–Liquid Metal Divertor for Fusion Energy Applications"*

Files
1. **`ecrh_ohmic_comparison.py`** - Compares Electron Cyclotron Resonance Heating (ECRH) vs Ohmic heating efficiencies
2. **`hybrid_divertor_simulation.py`** - Multi-physics simulation of hybrid snowflake-liquid metal divertor

## Key Results
- ECRH efficiency: 48.7% vs Ohmic: 9.6% at 3 keV
- Hybrid divertor heat flux reduction: 77.8% (11.6 → 2.3 MW/m²)
- Lifetime cost savings: 80% ($162.95M over 20 years)

## Dependencies
- Python 3.8+
- NumPy
- SciPy
- Matplotlib

## Usage
```bash
python ecrh_ohmic_comparison.py
python hybrid_divertor_simulation.py
