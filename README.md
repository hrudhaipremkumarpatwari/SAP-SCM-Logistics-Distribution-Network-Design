# SAP SCM – Logistics and Distribution Network Design

## Project Overview

This repository contains a Week 3 SAP SCM internship simulation focused on logistics and distribution network design for a fictional millet-based food manufacturer, **Deccan Harvest Foods Pvt. Ltd.**

The project models a distribution network connecting the Hyderabad manufacturing and consolidation point with demand requirements in **Nizamabad, Vijayawada and Bengaluru**. It combines SAP SCM/APO Supply Network Planning concepts with SAP Transportation Management concepts to demonstrate how distribution decisions can affect transportation cost, vehicle utilization, inventory availability and service performance.

## Objectives

- Design a practical distribution network for regional demand.
- Define distribution-center roles, transportation lanes and delivery schedules.
- Simulate inventory transfers between network locations.
- Evaluate route and shipment-consolidation opportunities.
- Explain SAP SCM/APO and SAP TM configuration concepts.
- Analyze baseline versus optimized logistics performance.
- Evaluate disruption response and network resilience.
- Define KPIs, validation tests, risks and controls.

## Key Simulation Data

| Measure | Illustrative value |
|---|---:|
| Network origin | Hyderabad |
| Demand locations | Nizamabad, Vijayawada, Bengaluru |
| Baseline weekly trips | 12 |
| Optimized weekly trips | 10 |
| Baseline vehicle utilization | 78.1% |
| Optimized vehicle utilization | 87.2% |
| Baseline weekly transport cost | ₹1.78 lakh |
| Optimized weekly transport cost | ₹1.41 lakh |

The figures above are simulated for internship learning and are not claimed as live company or SAP production data.

## SAP Concepts Covered

- SAP SCM / APO Supply Network Planning
- Demand and supply planning
- Deployment and transportation planning
- Locations and products
- Transportation lanes
- Calendars and resources
- Sourcing relationships
- Planning parameters
- Inventory transfer planning
- SAP Transportation Management
- Route planning and shipment consolidation
- KPI and exception analysis
- Disruption and emergency replenishment planning

## Process Flow

The modeled process follows:

**Demand → Network Planning → Inventory Allocation → Transportation Planning → Route/Load Optimization → Shipment Execution → Inventory Receipt → KPI Review**

## Key Analysis

The baseline scenario contains 12 weekly trips. Through shipment consolidation and route planning, the optimized scenario reduces this to 10 trips while improving modeled vehicle utilization from approximately 78.1% to 87.2%.

An illustrative transportation-cost comparison reduces weekly cost from approximately ₹1.78 lakh to ₹1.41 lakh. The report also evaluates a Bengaluru disruption scenario to demonstrate emergency replenishment and network resilience.

## Repository Structure

```
SAP-SCM-Logistics-Distribution-Network-Design/
├── README.md
├── docs/
│   ├── SAP_SCM_Week3_Logistics_Distribution_Network_Design_Hrudhai_Optimized.docx
│   ├── network-design-analysis.md
│   ├── distribution-planning.md
│   ├── route-optimization.md
│   └── risk-and-validation.md
└── diagrams/
    ├── distribution-network-flow.md
    ├── inventory-transfer-flow.md
    └── route-optimization-flow.md
```

## Simulation Note

This repository is an academic/internship simulation. Company details, demand volumes, transportation costs, operational measurements and financial impacts are illustrative. The configuration guidance is presented as a practical SAP system blueprint and learning exercise; it does not claim live production-system execution.

## Author

**Hrudhai Prem Kumar Patwari**  
SAP SCM Internship Project – Week 3
