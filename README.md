# Benchmark
Benchmark Exercise

# Executive Summary: 30-Year Global CO2 Emissions Dynamics (1993–2023)

## Key Findings
Over the last 30 years, global CO2 trajectory shifts have been concentrated in a small group of rapidly industrializing nations and economies actively transitioning off coal:

* **Fastest Rising:** China and India lead global emissions growth by a significant margin. China's annual emissions increased by **8,255 Million Tonnes (Mt) CO2 (+298%)**, while India grew by **2,049 Mt CO2 (+286%)**. Rapidly growing economies like Indonesia, Saudi Arabia, and Iran round out the top five growth trajectories.
* **Fastest Falling:** The United States and the United Kingdom recorded the largest absolute reductions in annual emissions. The US reduced annual output by **824 Mt CO2 (-15.2%)**, while the UK achieved a **301 Mt CO2 (-52.7%)** decrease, driven largely by coal phase-outs and increased renewable integration.

![30-Year CO2 Emission Shifts](co2_emissions_trend.png)

---

## Data Source & Methodology
* **Source:** Our World in Data (OWID) Global Carbon Budget Dataset.
* **Timeframe:** 1993 to 2023 (30-year delta).
* **Filtering:** To ensure actionable comparisons, international regions (e.g., "World", "EU-27") were excluded. Additionally, countries emitting under 10 Mt CO2 in 1993 were filtered out to avoid statistical distortion from micro-states experiencing large relative percentage swings on negligible base numbers.

---

## Confidence Level & Limitations
* **Confidence Level:** High for production-based territorial emissions data.
* **Key Caveat (Territorial vs. Consumption):** This data tracks **production-based emissions** (CO2 emitted physically within national borders). It does not reflect **consumption-based emissions**, which account for international trade. Part of the emission reductions seen in Western nations stems from offshoring heavy manufacturing to nations like China.

---

## Recommended Next Steps (If Time Permitted)
1. **Trade-Adjusted Analysis:** Re-evaluate trends using consumption-based emissions to account for imported carbon embedded in trade.
2. **Per-Capita Normalization:** Measure emissions per capita to differentiate between demographic growth and industrial intensity.
3. **Sector Breakdown:** Disaggregate country trends into power generation, transport, and industrial manufacturing to identify specific policy drivers.

---

## Tools Used
* **Data Processing:** Python (`pandas`)
* **Visualization:** `matplotlib`
* **Data Source:** Our World in Data (GitHub repository)
