# steamturbine-power_forecasting_dataset
Daily aggregated turbine and process logs from a biomass-fuelled palm oil plant (2016–2023) for power forecasting
# Steam Turbine Power Forecasting Dataset (2016–2023)

**Caption / Summary:**  
Daily-aggregated turbine and process measurements from a biomass-fuelled palm oil mill (2016–2023).  
Prepared to support research on non-linear steam turbine **power forecasting** and **biomass resource optimization**.

 What this dataset contains
- Granularity: daily (aggregated from hourly logs)
- Records: ~2,920 days covering 2016–2023
- Target: `kVA_value` (turbine electrical load proxy)
- Key inputs (physical/operational): Turbine Speed, Inlet Steam Pressure, Nozzle Steam Pressure, Exhaust Steam Pressure, kVA.


See `docs/DATA_DICTIONARY.md` for field definitions.

 Files
- `dataset` — main analysis-ready table  

Provenance & processing
Original hourly logs (≈70,000 rows) were aggregated to daily means to reduce noise and highlight long-term patterns.  
Missing values were handled with conservative imputation (mean for sparse gaps), then min–max scaled during modeling.

License
Data © by the authors — released under **CC BY 4.0** (attribution required).

## How to cite
If you use this dataset, please cite:
