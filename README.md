Container Transport Simulation Model
A discrete-event simulation model for optimizing container transport logistics from a Chinese gold mine to Hamburg, Germany. 

🎯 Project Overview
Simulates the transport of 2,000 FEU (40ft containers) monthly through a multi-modal logistics chain:

Route: Gold Mine → Chifeng Terminal → Tianjin Port → Hamburg Port
Transport Modes: Trucks → Train → Cargo Ships
Key Constraints: 91 FEUs/day production, 106 FEU train capacity, bi-weekly ships

🔧 Features

Resource Optimization: Determines optimal number of trucks, cranes, and buffer capacity
Discrete Event Simulation: Built with SimPy framework
Scenario Analysis: Tests system robustness under production variability
Comprehensive Visualizations: Network diagrams, utilization heatmaps, performance dashboards
No External Dependencies: All logging in-memory, no file I/O required

📊 Key Components

Entity Definitions: Container, Truck, Train, Ship entities with state tracking
Verification Model: 3-container test simulation
Optimization Engine: Tests 36+ configurations to find optimal resources
Extended Simulation: 30-day runs with steady-state and variable production
Performance Analytics: Utilization metrics, buffer analysis, throughput tracking

🛠️ Technologies

Python 3.x
SimPy (Discrete Event Simulation)
Pandas, NumPy (Data Analysis)
Matplotlib, Seaborn, NetworkX (Visualization)

📈 Results
Successfully handles 91 FEUs/day with optimized resource allocation, achieving monthly target of 2,000 FEUs with minimal buffer requirements.

This description is professional, informative, and gives potential viewers/employers a clear understanding of the project's scope and technical implementation.
