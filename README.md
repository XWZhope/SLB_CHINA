# SLB_CHINA
Code and data for the distributed deployment of second-life battery energy storage systems in China.

## Overview
This repository contains the Python source code and supporting input datasets to reproduce the optimization modelling, battery degradation prediction, economic and carbon benefit analysis in the manuscript.

The four core scripts are:
- `OPTIMIZED_DEPLOYMENT.py`: Main optimization model for spatial deployment of second-life battery energy storage
- `CAPACITY_RETENTION_RATE_PREDICTION.py`: Battery capacity retention and degradation prediction
- `ECONOMIC_FEASIBILITY.py`: Economic assessment and cost analysis
- `CARBON_EMISSION_REDUCTION_BENEFIT.py`: Carbon emission reduction benefit quantification

## System requirements
All modelling and analysis are implemented in Python.
- Python ≥ 3.9
- Gurobi Optimizer ≥ 10.0
- Required packages: numpy, pandas, scipy, matplotlib

Supported operating systems: Windows 10/11, Linux, macOS.

## File structure
├── CODE
│   ├── OPTIMIZED_DEPLOYMENT.py
│   ├── CAPACITY_RETENTION_RATE_PREDICTION.py
│   ├── ECONOMIC_FEASIBILITY.py
│   └── CARBON_EMISSION_REDUCTION_BENEFIT.py
├── DATA
│   ├── AMBIENT_TEMPERATURE.xlsx
│   └── veh_byd.csv
└── README.md


## Instructions to run
1. Clone or download this repository to your local machine.
2. Install required Python dependencies and activate your Gurobi license.
3. Set the local file path correctly in each script.
4. Run the Python files in sequence according to your analysis needs.

## Datasets
Large raw datasets including real-world bus operational data and derived driving cycles under various operating conditions are available in the latest release of this repository.

## License
This project is licensed under the MIT License. See the LICENSE file for details.
