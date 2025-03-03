# Multiphase Flow: Buckley–Leverett and Spontaneous Imbibition

This repository contains Python scripts and Jupyter notebooks demonstrating both analytical and numerical solutions for:
1. **Buckley–Leverett** (viscous-dominated) displacement.
2. **Spontaneous Imbibition** (capillary-driven) processes.

## Contents

- **Case 1**: Non-wetting phase (e.g., CO₂) displacing wetting phase (water-wet).
- **Case 2**: Wetting phase (water) displacing non-wetting phase (strongly water-wet).
- **Case 3**: Mixed-wet scenario, where the wetting condition is intermediate.

### File Structure
- `buckley_leverett_case1.py` / `buckley_leverett_case2.py` / `buckley_leverett_case3.py`
  - Scripts implementing explicit finite difference solutions for Buckley–Leverett under different wettability conditions.
- `imbibition_case2.py` / `imbibition_case3.py`
  - Scripts for spontaneous imbibition (Case 2: strongly water-wet, Case 3: mixed-wet), showing capillary-dominated flow solutions.
- `plots/`
  - Directory containing output plots and figures illustrating saturation profiles vs. dimensionless variables.
- `README.md`
  - This file, describing the project setup and usage.

## Requirements

- **Python 3.7+**
- Packages:
  - `numpy`
  - `matplotlib`
  - `pandas` (optional, if saving results to CSV)
- A working environment such as Jupyter Notebook (recommended) or any Python IDE.

## How to Run

1. **Clone** this repository:
   ```bash
   git clone https://github.com/YourUsername/Multiphase-Flow-Buckley-Leverett-and-Spontaneous-Imbibition.git
