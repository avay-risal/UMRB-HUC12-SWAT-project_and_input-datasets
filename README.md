# SWAT-UMRB-HUC12: Enhanced HUC12 SWAT Model Project and input dataset for the Upper Mississippi River Basin

This repository provides a modified version of the SWAT model—**SWAT-UMRB-HUC12**—that incorporates the CENTURY-based carbon and nutrient cycling module and adaptations tailored for forest ecosystems. The model and datasets are designed for watershed-scale ecohydrological simulation and validation across agricultural lands, forests, and grasslands in the Upper Mississippi River Basin (UMRB).

## 🔗 Repository Overview

The `main` branch contains:
- The modified SWAT executable (`SWAT-UMRB-HUC12.exe`)
- Input datasets and calibrated parameter files
- Performance metrics (R², NSE, PBIAS) for ET, LAI, and NPP
- Time series plots for model-observation comparisons
- Land-use specific summaries (agriculture, forest, grassland)

## 📂 File Structure & Descriptions

| File/Folder | Description |
|-------------|-------------|
| `SWAT-UMRB-HUC12.exe` | Modified SWAT executable incorporating CENTURY-based routines and forest adaptations |
| `par_inf.txt` | List of calibrated parameters and their value ranges |
| `Summary_stat_for_all_subbasins.csv` | Summary of R², NSE, and PBIAS across all subbasins and variables |
| `Summary of Statistics-Calibration and Validation-Agriculture.csv` | Performance metrics for agricultural subbasins |
| `Summary of Statistics-Calibration and Validation-Forests.csv` | Performance metrics for forested subbasins |
| `Summary of Statistics-Calibration and Validation-Grasslands.csv` | Performance metrics for grassland subbasins |
| `Monthly_avg_ET_for_all_subbasins.csv` | Monthly average observed ET across subbasins |
| `Monthly_avg_LAI_for_all_subbasins.csv` | Monthly average observed LAI across subbasins |
| `Monthly_NPPC_for_all_subbasins.csv` | Monthly average observed NPP across  subbasins |
| `Time series – Observed and Simulated ET/LAI/NPP – [Land use].csv` | Time series plots comparing modeled and observed values for each land use class |
| `basins.cbn`, `basins.rwq` | SWAT output files used for nutrient and water quality validation |
| `README.md` | This file |

## 📈 Key Features

- **Land-use specific calibration:** ET, LAI, and NPP evaluated separately for croplands, forests, and grasslands
- **Improved realism for forest ecosystems** using forest-sensitive carbon/nutrient cycling
- **Comprehensive statistical summaries** across all UMRB subbasins
- **Open access data** for reproducibility and further research

## 🧪 How to Use

1. Clone or download this repository.
2. Use the provided executable `SWAT-UMRB-HUC12.exe` and rename it to SWAT.exe before placing it in SWAT TxInOutfolder.
3. Use the statistical summaries and time series data to analyze model performance.
4. Refer to the `par_inf.txt` file for parameter ranges during calibration.

## 📜 Citation

If you use this repository or its resources, please cite the associated manuscript.

---

Feel free to reach out via GitHub Issues if you encounter any problems or have questions about the dataset/model.


