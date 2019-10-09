![](media/c1b04cd81c7afefa111aeac4b966ad18.png)

# Humanitarian Engineering for Energy for Displacement (HEED)

## Technical Documentation for Tool Calculations

>   Authors: Rembrandt Koppelaar (Scene), Jonathon Nixon (Coventry University)

## 4. Option Indicator calculations

### 4.1 Cooking – Indicators

The RERT tool v1 incorporates ten performance indicators for cooking solutions
as presented in table 11, calculated for each of the 16 cooking solutions. The
methodology on how they are calculated for each are discussed in this section by
type of indicator: economic, environmental and health indicators.

**Table 9**. Indicators for Cooking Solutions

| **No.** | **Scale** | **Indicators for Cooking Solutions**                    | **Unit**               |
|---------|-----------|---------------------------------------------------------|------------------------|
| 1       | Camp      | Investment cost for cooking interventions               | Currency (as selected) |
| 2       | Camp      | Total Monthly Cooking Fuel Cost                         | Currency (as selected) |
| 3       | Camp      | Carbon Dioxide emissions per year                       | Tonnes                 |
| 4       | Camp      | Annual area at risk from deforestation for woodfuel use | Km2                    |
| 5       | Camp      | Area used for providing woodfuel from plantations       | Km2                    |
| 6       | Household | Affordability of Cooking Fuel                           | Very low to Very High  |
| 7       | Household | Monthly Cooking Fuel Cost                               | Currency (as selected) |
| 8       | Household | Cost of purchasing cooking stove                        | Currency (as selected) |
| 9       | Household | Carbon Dioxide emissions per family per year            | Tonnes                 |
| 10      | Household | Health risk associated with cooking                     | Very low to Very High  |

**Cooking - Economic indicators**

Generalised cookstove costings data including purchase cost, and fuel cost
estimates and lifespan for 47 cookstoves are available from Vianello et al.
(2016).[1] The approach incorporates location and currency specific data based
on 2018 exchange rates, so as to make the calculations as localised as possible.
The country and associated currency can be selected in the overview tab.

The **investment cost for cooking interventions** is based on the total cost of
the cooking stoves for supplying these to all families in the camp as a one-off
purchase. The **monthly cooking fuel cost** is based on the parameter for the
price of fuel multiplied with the amount of fuel usage per month as estimated
with user inputs, split out between households and total camp use for all
families.

**Affordability of cooking fuel is** based on an estimate provided by the user
of camp household incomes split into low income, medium income, and high-income
households, and their % shares in the camp (for example, 70% low, 20% medium,
10% high income households), based on camp surveys or other estimates.

The user also needs to supply the average cost of a healthy food basket per
month. Subsequently, the RERT tool calculates how much income would be left for
each household type after subtracting the cost of food to the income level. Then
it calculates what % of households would have sufficient income left to afford
monthly cooking fuel based on remaining income, as an approximation of the
affordability of cooking fuel.

Finally, the % share is categories among the very low to very high scale as
follows:

-   Very low if less than 20% of households being able to afford cooking fuel.

-   Low if between 20% and 40% of households are able to afford cooking fuel.

-   Medium if between 40% and 60% of households are able to afford cooking fuel.

-   High if between 60% and 80% of households are able to afford cooking fuel.

-   Very high if more than 80% of households are able to afford cooking fuel.

**Cooking Solutions - Air Pollution/Health indicators**

The **health risk from cooking solutions** is a tiered indicator with five
levels from very low, low, medium, high, to very high risks. The qualitative
levels correspond to the IWA tiers for indoor-emissions (see Table 10 below).
Each International Workshop Agreement (IWA) tier, as set by the clean cooking
alliance, from 0 to 4 was utilised with 0 corresponding to very low and 4
corresponding to very high risks. Based on the statistical assessment using the
database for cookstoves from the clean cooking alliance, and additional
literature sources, as described in section 2, each of the 16 cookstove types in
the tool were assessed on what their IWA tier level was ranked at based on the
carbon monoxide emissions, and the fine particulate matter emissions, as these
are directly related to health risks. As such, the RERT tool can identify how
different cookstove solutions rank on IWA tiers, and thereby on the qualitative
scaling from very low to very high risks.

**Table 10**. IWA Tiers for Cooking Solutions.

| IWA Tier  | Thermal Efficiency (%) |  Carbon   Monoxide   Emissions (gram/megajoule   delivered)  | Fine Particulate   Matter Emissions   (milligram/megajoule   delivered) |  Safety   (score)   |  Durability   (score)   |
|-----------|------------------------|--------------------------------------------------------------|-------------------------------------------------------------------------|---------------------|-------------------------|
| 5         | ≥50                    | ≤3.0                                                         | ≤5                                                                      | ≥95                 | \<10                    |
| 4         | ≥40                    | ≤4.4                                                         | ≤62                                                                     | ≥86                 | \<15                    |
| 3         | ≥30                    | ≤7.2                                                         | ≤218                                                                    | ≥77                 | \<20                    |
| 2         | ≥20                    | ≤11.5                                                        | ≤481                                                                    | ≥68                 | \<25                    |
| 1         | ≥10                    | ≤18.3                                                        | ≤1031                                                                   | ≥60                 | \<35                    |
| 0         | \<10                   | \>18.3                                                       | \>1031                                                                  | \<60                | \>35                    |

The approach provides for a robust simple means to categorise different stoves
and assess their health risks in a transparent manner. A more detailed approach
is the global burden of disease and exposure distribution method developed for
Household Air Pollution (HAP).[30] An existing tool that includes this is the
Household Air Pollution Intervention Tool (HAPIT).[^3]

[^3]: https://hapit.shinyapps.io/HAPIT/

**Cooking Solutions – Carbon Emissions indicators**

The amount of carbon dioxide emissions $$E_{\text{ijk}}\$$associated with
cooking can be established based on a direct association of CO2 emissions, per
unit of fuel consumed, as :

$$E_{\text{ijk}} = \ F_{\text{ijk}} \bullet \ \gamma_{\text{jk}}$$ (13)

With $$\gamma_{\text{jk}}$$ as a parameter to establish the carbon dioxide
emissions in weight value per cookstove and fuel type weight that is burnt. Data
for this parameter for 22 cookstoves with six fuel types was analysed by Jetter
et al. (2012) as utilised in the tool.[31] The approach allows for calculating
the carbon dioxide emissions per household/family and for the entire camp.

**Cooking Solutions – Deforestation Risk indicators**

The RERT tool includes two indicators related to biomass use and deforestation
risk. The first, **the annual area at risk from deforestation for woodfuel
use**, is estimated based on the calculated amount of woodfuel need either
directly or from charcoal usage. The value is compared with the estimated
biomass growth in tonne per km2 per year from different ecosystem types,
including evergreen forest/rain forest, forest-savanna (Mosaic), deciduous
forest, sparse forest (woodland), shrubland, and grassland/savannah. As such the
total km2 that is at risk is provided as the amount of wood taken commensurate
with the growth per year per km2. Values for tonnes per year were taken from
[reference].

Second, **the area used for providing woodfuel from plantations**, based on the
user inputs on whether either woodfuel or charcoal is provided by the camp
management or other organisations sourcing from managed plantations. As well as
the amount of woodfuel or charcoal is provided. It is assumed that the sourcing
is based on eucalyptus plantations biomass growth per km2 per year, with a
standard value from Ugande et al. (2001).[32] Thereby the total area used for
providing plantation woodfuel is calculated, through estimating the amount
supplied, and the area needed to grow this supply.

###  4.2 Household/Family Electricity & Lighting – Indicators

The RERT tool v1 incorporates 6 performance indicators for household/family
lighting and electricity solutions as presented in table 11, calculated for each
of the 11 solutions. The methodology on how they are calculated for each are
discussed in this section by type of indicator: economic, availability, and
environmental.

**Table 11**. indicators for Household Lighting and Electricity Solutions
(decentralised)

| **No.** | **Scale** | **Indicators for Cooking Solutions**                                                                               | **Unit**               |
|---------|-----------|--------------------------------------------------------------------------------------------------------------------|------------------------|
| 1       | Camp      | Investment cost for household lighting and electricity                                                             | Currency (as selected) |
| 2       | Household | First three years Monthly total electricity cost including lighting per household with 3-year leasing of equipment | Currency (as selected) |
| 3       | Household | Affordability of Lighting and Electricity Options                                                                  | Very low to very high  |
| 4       | Household | Time availability of electricity and lighting (17:00 - 24:00) on average                                           | Hours                  |
| 5       | Household | Time availability of electricity and lighting (24 hours) on average                                                | Hours                  |
| 6       | Household | Lighting and Electricity Carbon Dioxide emissions per year                                                         | Tonnes                 |

**Household/family lighting and electricity – Economic Indicators**

The affordability indicators and investment cost indicators are calculated in a
similar manner to the cooking solution indicators as described in section 5.1.
In case of affordability, not the cooking solution cost, but the monthly
electricity cost if the investment and operation for solar-PV and/or wind and/or
batteries would need to be recouped over a three year period is selected based
on dividing the investment costs over 3 years. This assumes that the equipment
is leased to the households over a three year period.

In addition a new indicator is introduced that is related **– First three years
Monthly total electricity cost including lighting per household with 3-year
leasing of equipment –** which calculates the total monthly cost if the
equipment would need to be fully costed by the household/family under a three
year leasing scheme, based on i) the total investment cost divided into 36
portions covering 3 years x 12 months, the total operational and maintenance
cost over a 12 month period, and any remaining diesel generation cost if diesel
generators are part of the solution.

**Household/family lighting and electricity – Availability indicators**

The time availability indicators are based on comparing the demand and supply
load profiles for electricity usage and how each technology solution provides or
does not provide power during particular hours. Based on the comparison for each
solution the availability from 17:00 to 24:00 is estimated, and that relative to
a 24 hour period. As such the solutions that can provide as much evening time
electricity (for cooking, lighting and other uses) and night-time electricity
are ranked higher under these indicators.

**Household/family lighting and electricity – Carbon Emissions indicators**

The calculation is carried out in a similar fashion as the cooking solution
carbon emission indicators, as described in section 5.1.

### 4.3 Household/Family Electricity & Lighting – Indicators

The RERT tool v1 incorporates 3 performance indicators for
community/institutional electricity solutions as presented in table 12,
calculated for each of the 12 solutions. The methodology on how they are
calculated for each are discussed in this section by type of indicator:
economic, and environmental.

**Table 12.** Indicators for Camp Lighting and Electricity Solutions
(centralised)

| **No.** | **Scale** | **Indicators for Camp Lighting and Electricity Solutions**            | **Unit**               |
|---------|-----------|-----------------------------------------------------------------------|------------------------|
| 1       | Camp      | Total lighting and electricity operational cost (max threshold)       | Currency (as selected) |
| 2       | Camp      | Total annual lighting and electricity Investment cost (max threshold) | Currency (as selected) |
| 3       | Camp      | Total fuel combustion CO2 emissions per year (max threshold)          | Tonnes                 |

**Community/Institutional lighting and electricity – Economic Indicators**

The investment cost and operational costs are standard indicators based on the
aggregate investment cost for the 12 electricity supply solutions (e.g.
combinations of solar-PV, wind energy, batteries, diesel generation), and
estimated operational costs on an annual basis.

**Household/family lighting and electricity – Carbon Emissions indicators**

The calculation is carried out in a similar fashion as the cooking solution
carbon emission indicators, as described in section 5.1.