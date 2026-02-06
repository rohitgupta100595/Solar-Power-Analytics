# Solar Power Analytics
Python and Power BI dashboard project uncovering inefficiencies in solar power generation and solar utilization for solar power plant in India.

## Context
Solar power plants management system relies on solar panel performance to schedule panel & inverter maintenance. This ensures smooth hpower generation by the unit without much power losses or low efficiency.

Persistent underperformance of solar panels can lead to unmet power demand or AC power bottlenecking in peak generation hours.

## Business Problem
A Solar power plant operator in India is facing significant drop in efficiency of the plant.

## Core Business Questions
**i. Can we identify the need for panel cleaning / maintenance?**

**ii. Can we identify faulty or suboptimally performing equipments?**

## Solar Power Plant Info
**Power Plant 1**
  - Number of modules = 22
  - Capacity per Panel = 15000 kW
  - Inverter rating(Transformer incl.) = 1500 kVA

**Power Plant 2**
  - Number of modules = 22
  - Capacity per Panel = 1500 kW
  - Inverter rating(Transformer incl.) = 1500 kVA

## Evidence
i. Daily generation data shows that the plant 1 solar modules operate at higher efficiently **(11.1%)** higher than plant 2 modules.

ii. Palnt 2 efficiency drops significantly from 0.97 to 0.63 during peak irradiance hours. This suggests that the plant 2 panels have aged, or degraded or failing.

iii. Average hourly AC power output of plant 2 also drops or bottlenecks during peak irradience hours. This leads to less capacity utilization.

## Insights
i. Plant 2 shows consistent drop in efficiency as compared to plant 1 **(-11.1%)**.

ii. Plant 2 records consistently more critical alerts everyday as compared to plant 1.

iii. Plant 2 panels are less efficient than plant 1. These panels require maintenance.

## Recomendatons and Impact
By replacing the failing panels & maintaining / cleaning the underperforming panels in plant 2, the plant operators can

  - Improve solar power generation.
  - Improve bottlenecking issue during peak irradiance hours.
  - Increase efficiency of the system.
