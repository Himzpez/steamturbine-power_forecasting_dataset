# Data Dictionary

| Column                | Type    | Unit  | Caption / Meaning                                                |
|-----------------------|---------|-------|------------------------------------------------------------------|
| date                  | date    | —     | Calendar date (YYYY-MM-DD)                                       |
| kVA_value             | float   | kVA   | Electrical load proxy of turbine (target variable)               |
| turbine_speed         | float   | rpm   | Turbine rotational speed                                         |
| inlet_steam_pressure  | float   | bar   | Steam pressure at turbine inlet                                  |
| nozzle_steam_pressure | float   | bar   | Steam pressure at nozzle stage                                   |
| exhaust_steam_pressure| float   | bar   | Exhaust steam pressure                                           |
| total_energy_unit     | float   | kWh   | Daily energy output (if present)                                 |
| ffb_throughput        | float   | t/day | Fresh Fruit Bunch processed (if present)                         |
| year                  | int     | —     | Extracted from date                                              |
| day_of_year           | int     | —     | 1–365/366                                                        |
