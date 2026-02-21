# Cloud Architecture Design – Week 6

## System Overview

The project implements a cloud-enabled interactive data visualization system using a layered architecture model.

## Architecture Layers

### 1. Data Layer
- Raw dataset (raw.csv)
- Cleaned dataset (clean.csv)
- Structured for visualization

### 2. Visualization Layer
- Tableau dashboards
- KPI indicators
- Interactive filters
- Dashboard actions

### 3. Virtualization Layer
- Virtual Machine used for isolated execution
- Ensures platform independence
- Provides controlled environment for deployment

### 4. Cloud Layer
- Tableau Public hosting
- Public cloud access via browser
- Remote and device-independent access

## Data Flow

Dataset → Tableau Processing → Dashboard Creation → VM Testing → Cloud Hosting → Remote Access

## Benefits Achieved

- Scalable hosting
- Centralized dashboard access
- Remote availability
- Platform independence
- Separation of local and cloud environments

## Conclusion

The implemented architecture successfully integrates data visualization, virtualization, and cloud computing into a unified analytical system.