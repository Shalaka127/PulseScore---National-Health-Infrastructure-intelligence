# PulseScore---National-Health-Infrastructure-intelligence
# PulseScore  
## National Health Infrastructure Intelligence & Surge Risk Simulator

---

## Problem Statement

India’s healthcare infrastructure operates without a centralized, real-time operational intelligence system at the district level. Although hospital, workforce, and emergency datasets exist, they remain fragmented and difficult to convert into actionable insights.

Key challenges include:

- Fragmented infrastructure data across states and districts  
- No unified visibility into bed capacity, ICU readiness, and emergency services  
- Limited clarity on doctor availability and workforce distribution  
- Difficulty identifying structurally weak or high-risk regions  
- Manual reporting processes delaying strategic decisions  
- Lack of surge simulation capability for crisis preparedness  

As a result, policymakers and healthcare administrators face challenges in proactive planning, efficient resource allocation, and emergency response optimization.

---

## Solution Statement

PulseScore is a centralized, data-driven healthcare intelligence platform that transforms raw infrastructure data into predictive operational insights.

The system:

- Integrates hospital-level datasets across states and districts  
- Normalizes infrastructure metrics using population benchmarks  
- Computes Structural Deficit Scores (SDS) and Systemic Adequacy indices  
- Applies weighted composite scoring based on clinical criticality  
- Simulates surge scenarios using demand multipliers  
- Adjusts capacity using hospital elasticity modeling  
- Identifies high-risk states and vulnerable districts  
- Quantifies additional beds, ICU units, and doctors required under stress  

This approach shifts healthcare analytics from static reporting to dynamic risk intelligence and strategic planning.

---

## Technology Stack

**Language**
- Python

**Framework**
- Streamlit

**Libraries**
- Pandas (data manipulation and aggregation)
- NumPy (numerical computations)
- Plotly (interactive visualizations)
- Geopy (geospatial computations)
- FPDF2 (PDF report generation)
- Kaleido (static image export for charts)

**Data Format**
- CSV
- 
---
  **Demo**


https://github.com/user-attachments/assets/07368af7-b5ea-4b8b-9dcf-c12335360589



  
  
---
## How to Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/pulsescore.git
cd pulsescore
