
# Chapter 1: Introduction

## 1.1 Background

With the explosive growth of cloud computing, data centers have become essential infrastructure to support computing, storage, and application hosting services. These large-scale facilities consume enormous amounts of electricity, contributing significantly to global carbon emissions. As energy costs rise and sustainability becomes a priority, energy efficiency in cloud infrastructure has emerged as a critical area of research.

Cloud data centers utilize virtualization, enabling multiple virtual machines (VMs) to run on shared physical hardware. However, suboptimal VM placement leads to poor resource utilization, increased power consumption, and carbon inefficiency. Addressing these challenges requires intelligent scheduling, optimization techniques, and emission-aware strategies.

## 1.2 Problem Statement

While virtualization allows for flexible resource allocation, traditional VM placement policies prioritize performance without considering energy consumption or environmental impact. This leads to over-provisioning, idle resources, and excessive energy usage. Furthermore, cloud platforms lack visibility into the carbon emissions associated with workloads.

This thesis investigates strategies for **energy-aware VM placement** using metaheuristic optimization techniques and introduces a **carbon footprint estimation model** to quantify environmental impact. The goal is to reduce energy usage while maintaining Service Level Agreements (SLAs) and providing real-time emission feedback.

## 1.3 Objectives

- To design and simulate energy-efficient VM placement strategies in cloud data centers.
- To implement optimization algorithms (GA, ACO, PSO) for improving resource utilization.
- To estimate carbon emissions based on regional power grid intensity.
- To develop a prototype for real-time carbon feedback to developers.

## 1.4 Methodology

- Use CloudSim Plus for simulation of VM allocation scenarios.
- Implement and compare metaheuristic optimization algorithms.
- Integrate emission factors based on geographic electricity data.
- Evaluate performance based on power consumption, SLA violation rate, and emission savings.

## 1.5 Scope of Work

This research focuses on Infrastructure-as-a-Service (IaaS) cloud models and assumes access to regional energy emission data. The scope includes simulation-based evaluation but not deployment on real-world cloud providers.

## 1.6 Thesis Organization

- **Chapter 2**: Literature Review  
- **Chapter 3**: System Architecture and Design  
- **Chapter 4**: VM Placement Algorithms  
- **Chapter 5**: Carbon Footprint Modeling  
- **Chapter 6**: Implementation and Simulation Setup  
- **Chapter 7**: Experimental Results and Evaluation  
- **Chapter 8**: Conclusion and Future Work
