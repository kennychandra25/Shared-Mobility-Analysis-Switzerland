This repository provides tools for collecting, processing, and visualizing shared mobility data in Switzerland using the sharedmobility.ch GBFS API. The project focuses on analyzing vehicle availability and inferring trips from time-based snapshots of shared mobility systems.

The notebook demonstrates how to retrieve real-time system data, explore spatial supply patterns, and estimate trip activity using repeated API observations.

. 
├── sharedmobility_analysis.ipynb # Main analysis notebook
├── snapshots/ # (Optional) directory storing vehicle snapshots 
├── inferred_trips.csv # Output dataset of inferred trips
├── supply_heatmap.html # Interactive heatmap of vehicle supply 
├── system_map.html # Interactive system-level map └── README.md # Project documentation