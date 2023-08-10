# energy_consumption
## Table of contents 
- [Introduction](#business-understanding)
- [Problem statement](#data-preparation)
- [Data understanding](#modeling)
- [Data analysis](#evaluations)
- [Conclusion](#evaluations)
- [Recommendation](#evaluations)

## **Introduction**
In an era of increasing energy costs and environmental concerns, harnessing solar power has become a viable option for reducing electricity expenses and carbon footprint. This exercise involves a comprehensive analysis of solar electricity generation, battery storage, and electricity consumption for a household. The objective is to determine the potential savings and benefits of installing a battery to store excess solar energy. By constructing a robust model, we aim to provide Naomi with valuable insights into the financial implications of this investment.

## **Problem statement**
Naomi, a homeowner, has solar panels installed on her house to generate electricity. The excess energy generated beyond her immediate consumption is not currently utilized and goes unused. Naomi is contemplating the installation of a battery system to store surplus solar energy and use it during periods of low solar generation. This exercise involves creating a model that evaluates the financial impact of installing a battery, taking into account various factors such as solar electricity generation, electricity consumption, battery capacity, electricity prices, inflation rates, and potential savings.

## **Data understanding**
The model uses a dataset containing hourly solar electricity generation and electricity usage data for the year 2020. The dataset has four columns:
- `Hour`: Hour of the day (0-23)
- `Date/hour start`: Timestamp of the data
- `Solar electricity generation (kWh)`: Amount of solar electricity generated in kilowatt-hours (kWh)
- `Electricity usage (kWh)`: Amount of electricity consumed in kilowatt-hours (kWh)


## **Data analysis**
1. Average solar electricity generation and electricity usage were calculated for each hour of the day and visualized in a graph.
2. The amount of electricity bought from the electricity provider was calculated for each hour in 2020, both with and without a battery system.
3. Excess solar electricity generated over electricity used was calculated for each hour in 2020.
4. Cumulative battery charge level was modeled for each hour over 2020, considering excess solar generation and electricity bought.
5. The savings from installing a battery compared to using existing solar panels alone were calculated for 2020.

6. Annual savings for the next 20 years were projected based on specified scenarios of electricity price increases.
7. Net Present Value (NPV) of future annual savings was calculated for each scenario, using a discount rate of 6%.
8. Internal Rate of Return (IRR) was calculated for each scenario by finding the discount rate that equates NPV to the initial battery cost.


## **Conclusion**
* Harnessing solar power is a viable strategy for reducing energy costs and environmental impact.
* The analysis focused on evaluating the financial implications of installing a battery to store excess solar energy.
* Average solar electricity generation exhibited a peak during midday hours, while electricity usage increased during daytime.

* Net Present Value (NPV) analysis demonstrated positive returns for both scenarios, indicating the battery installation's financial viability.
* Internal Rate of Return (IRR) calculations supported the positive outlook, with IRR values of 12.69% and 9.16% for the respective scenarios.

## **Recommendation**

* Battery Installation: Proceed with installing a battery system to store excess solar energy.

* Continuous Monitoring: Implement continuous monitoring of energy generation and usage patterns.

* Regular Maintenance: Schedule routine upkeep for solar panels and battery system.

* Evaluate Electricity Plans: Periodically assess electricity plans to optimize cost savings.

* Stay Updated: Monitor government policies for solar and storage incentives.

* Consider Future Expansion: Plan for system upgrades as technology improves.

* Educational Outreach: Provide resources to promote solar and battery benefits.

* Collaboration: Partner with experts to stay informed on energy advancements.

* Long-Term Planning: Incorporate battery savings into overall financial strategy.

* Environmental Impact: Emphasize solar's positive influence on sustainability.
