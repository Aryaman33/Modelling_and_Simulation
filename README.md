# **Container Transport Simulation Model**<br>
A discrete-event simulation model for optimizing container transport logistics from a Chinese gold mine to Hamburg, Germany. 

## 🎯 Project Overview<br>
Simulates the transport of 2,000 FEU (40ft containers) monthly through a multi-modal logistics chain:

* Route: Gold Mine → Chifeng Terminal → Tianjin Port → Hamburg Port<br>
* Transport Modes: Trucks → Train → Cargo Ships<br>
* Key Constraints: 91 FEUs/day production, 106 FEU train capacity, bi-weekly ships<br>

## 🔧 Features <br>

Resource Optimization: Determines optimal number of trucks, cranes, and buffer capacity<br>
Discrete Event Simulation: Built with SimPy framework<br>
Scenario Analysis: Tests system robustness under production variability<br>
Comprehensive Visualizations: Network diagrams, utilization heatmaps, performance dashboards<br>
No External Dependencies: All logging in-memory, no file I/O required<br>

## 📊 Key Components

Entity Definitions: Container, Truck, Train, Ship entities with state tracking<br>
Verification Model: 3-container test simulation<br>
Optimization Engine: Tests 36+ configurations to find optimal resources<br>
Extended Simulation: 30-day runs with steady-state and variable production<br>
Performance Analytics: Utilization metrics, buffer analysis, throughput tracking
<br>
## 🛠️ Technologies <br>

Python 3.x<br>
SimPy (Discrete Event Simulation)<br>
Pandas, NumPy (Data Analysis)<br>
Matplotlib, Seaborn, NetworkX (Visualization)<br>

## 📈 Results <br>
Successfully handles 91 FEUs/day with optimized resource allocation, achieving monthly target of 2,000 FEUs with minimal buffer requirements.<br>

This description is professional, informative, and gives potential viewers/employers a clear understanding of the project's scope and technical implementation.
