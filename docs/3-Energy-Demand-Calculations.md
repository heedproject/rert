## Energy Demand Calculations 

**Generalised Equations for Energy Use Calculations**

Energy use $$E$$ in kWh is calculated for sets of devices with $$i = 1,2\ldots
n$$as an index for the category of device, including cooking, lamps,
streetlights, electric appliances, and electricity generation devices. The index
$$j = 1,2\ldots n$$ denotes the sub-type within a category, such as the type of
cooking device for example, and $$k = 1,2\ldots n$$ is an index for energy
carrier type used including individual fuels and electricity. Energy use per
period of time is thereby calculated as:

$$E_{\text{ijk}} = \ \frac{c_{\text{ijk}} \cdot \ u_{\text{ij}} \cdot
\sum_{t}^{n}A_{\text{ijt}}}{\varepsilon_{\text{ijk}}}$$ (1)

With $$\varepsilon_{\text{ij}}$$ as the efficiency in %, $$c$$ as a capacity
parameter typically in kW, $$u$$ as a utilisation parameter indicating the
proportion of capacity used, $$A_{\text{ij}}$$ as a variable for average daily
device use in hours. The time index $$t = 1,2\ldots n$$ indicated the number of
days in a month to obtain monthly device energy use.

Fuel used in weight or volume unit can then be calculated as:

$$F_{\text{ijk}} = \frac{\text{\ E}_{\text{ijk}} \cdot 3.6}{f_{\text{ijk}}}$$
(2)

With $$f_{\text{ijk}}$$ as a variable for fuel energy content per fuel type
$$\text{k\ }$$in MJ per kilogram for solid fuels or MJ per m3 for gaseous fuels.

**Energy Use – Cooking Specifics**

Cooking energy demand is calculated in an integral manner with supply, as the
energy need is highly interrelated with the type of stove used and the
efficiency of fuel utilisation. First, the tool estimates which cooking devices
are used based on how common they are (X,Y,Z, stoves of type A,B,C, per 10
families) and what type of fuels are used for these stoves. Based on the
questions posed to the user and particular answers the current fuel requirements
are calculated. The equation (1) above for cooking devices $$i = c$$ is used to
calculate cooking device energy usage. Fuel used for cooking in weight or volume
unit is calculated with equation (2) as applicable. Cookstove fuel energy
content data was taken from Vianello et al. (2016).[1]

The combination of stoves and fuels results in a simplified approximation of the
amount of “fuel stacking” that occurs, by allowing the user to set different
fuel ratio’s per stove that is utilised on average. Fuel stacking is defined as
the alternation between use of different fuels due to various factors including
meal types, fuel prices, and disposable cash available.[2]

To establish the type of cooking devices $$\text{j\ }$$and their range of usable
fuels $$k$$ the literature was consulted. The aim was to find distinct devices
by energy carrier type and efficiency parameter $$\varepsilon_{\text{ijk}}$$.
First, international standards to make cookstoves comparable in terms of
performance were consulted, of which the most prominent is the IWA standard was
developed by the Global Alliance for Clean Cookstoves (GACC). The IWA standard
classifies cooking stoves by tiers from 0 to 4 based on their efficiency, carbon
monoxide and particular matter emissions (outdoor and indoor), and use safety.
This standard was adopted to link to the efficiency parameter
$$\varepsilon_{\text{ijk}}$$ and for calculating air pollution/health
indicators.

Second, studies with a comprehensive overview of different classifications of
cooking stoves (traditional, improved, rocket etc.) were consulted.[3] As well
as the categories of legacy and basic ICS, Intermediate ICS, Advanced ICS and
Modern fuel stove as per Vianello et al. (2016)[1] Third datasets were analysed
for cooking stoves in terms of their design, fuel use and IWA standard rating
from lab and field tests. The main data sourced used was The Clean Cooking
Alliance online cookstove catalogue with 476 stoves of which 81 have IWA
efficiency ratings, and 60 have IWA indoor-emission ratings (see for the online
catalogue: catalog.cleancookstoves.org). These were further supplemented with
operational testing data for 15 different cookstoves on IWA parameters under lab
conditions from Dean et al. (2015).[4] And with data from operational testing of
fifty cooking stoves for efficiency, CO emissions and PM emissions by MacCarty
et al. (2010).[5]

Standard categories for cookstoves as used in Viannelo et al. (2016)[1] were not
found helpful, to make a meaningful distinction between the efficiency of
cookstoves. Cookstoves in particular categories were not found to correlate with
IWA tiers of efficiency and indoor emissions, plausibly due to the fluidity of
the categories in defining the stoves the variety of quality of builds within
these categories. The data analysis did yield relevant results, however,
resulting in a new classification of 8 types of cookstoves. These are distinct
in their fuel use and IWA efficiency tiers, so as to form a meaningful
classification for household cookstoves in terms of IWA efficiency and IWA
indoor emissions. The subsets were defined based on manually analysing distinct
IWA values based on specific properties of cookstoves in the above datasets,
such as the difference between batch-loaded and side-fed cookstoves, which
together result in the classification as per table 2 and 3 below for IWA
efficiency, and IWA indoor-emissions.

The capacity values for cookstoves $$c_{i = c,jk}$$ and utilisation parameter
$$u_{i = c,jt}$$ were in the first iteration simplified to a standardised value
of 1.0 kW for cookstove capacity, and an assumed 0.8 estimated for utilisation,
indicating 80% utilisation of a cookstove’s capacity as it will not be fully
loaded with wood or another fuel. The time of use variable value
$$A_{\text{ijt}}$$was approximated at 2.5 hours per day assuming three meals
per day. Analysis of these parameters has been carried out by Johnson & Chiang
(2015)[6], Ruiz-Mercado et al. (2012)[7], Bentson et al. (2013)[8], Pillarisetti
et al. (2014)[9].

**Categorisation of stove subtypes:**

-   Stoves built with (unfired) clay components are typically of a tier 0 to 1
    IWA efficiency and a 0 to 1 IWA indoor-emissions, unless they have advanced
    features such as a chimney.

-   Stoves that are built with ceramic components (heated clay) in a metal
    housing are typically of a tier 2 IWA efficiency and a 0 to 1 IWA
    indoor-emissions efficiency.

-   Stoves that are side-fed are typically of a Tier 0 to 2 IWA efficiency and 0
    to 2 IWA indoor-emissions. If they have a fan they are on the higher
    spectrum within these IWA efficiency and indoor-emissions ranges.

-   Stoves that are batch-loaded made from metal and burn on charcoal typically
    have a 3-4 efficiency tier and a 3-4 indoor emissions tier.

-   Stoves that are batch-loaded made from metal and burn on wood typically have
    a 2 IWA efficiency tier and a 0-1 indoor emissions tier.

-   No substantial distinction was found between IWA tiers for stoves with a fan
    as a single variable.

**Fuels specific:**

-   Ethanol/Alcohol burning stoves typically are of a Tier 4 efficiency and Tier
    4 indoor-emissions category

-   Stoves that can also burn on crop residues typically have a 0-2 IWA
    efficiency and 0-2 IWA indoor emissions.

-   Stoves that burn on liquid petroleum gas typically have a 3 IWA tier for
    efficiency and indoor emissions.

-   Stoves that burn pellets with a gasifier typically have a 3 to 4 IWA tier
    for indoor emissions, and a 3 to 4 IWA efficiency for high power thermal
    efficiency, whilst their low power specific consumption tier can vary
    between 0 and 4 depending on design.

-   Stoves that burn on briquettes vary from 0 to 2 IWA Tier for efficiency and
    0-2 Tier for indoor emissions.

Note that more data is required to properly analyse these findings (outside of
the scope of the renewable energy recommendations tool effort/HEED project) as
the datasets utilised and available are too limited to draw robust conclusions.

**Table 1.** Overview of cook-stoves implemented in the model in relation to
utilisable fuel types

| **Fuel type Cookstove**                | Wood | Charcoal | Pellets | Ethanol | Kerosene | LPG | Biogas | Electricity |
|----------------------------------------|------|----------|---------|---------|----------|-----|--------|-------------|
| Traditional three stone with pot stove | X    | X        |         |         |          |     |        |             |
| Unfired Clay Stove                     | X    | X        |         |         |          |     |        |             |
| Ceramic Clay stove in metal housing    | X    | X        |         |         |          |     |        |             |
| Side-fed metal stove                   | X    | X        |         |         |          |     |        |             |
| Batch-loaded metal stove               | X    | X        |         |         |          |     |        |             |
| Pellet gasifier stoves                 |      |          | X       |         |          |     |        |             |
| LPG/Bio-gas stoves                     |      |          |         |         |          | X   | X      |             |
| Liquid Fuel stoves                     |      |          |         | X       | X        |     |        |             |
| Electric cooking stoves                |      |          |         |         |          |     |        | X           |

**Table 2.** overview of cook-stoves implemented in the model in relation to IWA
efficiency tiers

| **Fuel type Cookstove**                | Wood | Charcoal | Pellets | Ethanol | Kerosene | LPG | Biogas | Electricity |
|----------------------------------------|------|----------|---------|---------|----------|-----|--------|-------------|
| Traditional three stone with pot stove | 0    | 0        |         |         |          |     |        |             |
| Unfired Clay Stove                     | 0-1  | 0-1      |         |         |          |     |        |             |
| Ceramic Clay stove in metal housing    | 2    | 2        |         |         |          |     |        |             |
| Side-fed metal stove                   | 0-2  | 0-2      |         |         |          |     |        |             |
| Batch-loaded metal stove               | 2    | 3-4      |         |         |          |     |        |             |
| Pellet gasifier stoves                 |      |          | 3-4     |         |          |     |        |             |
| LPG/Bio-gas stoves                     |      |          |         |         |          | 3   | 3      |             |
| Liquid Fuel stoves                     |      |          |         | 4       | 4        |     |        |             |
| Electric cooking stoves                |      |          |         |         |          |     |        | 4           |

**Table 3**. overview of cook-stoves implemented in the model in relation to IWA
indoor-emission tiers

| **Fuel type Cookstove**                | Wood | Charcoal | Pellets | Ethanol | Kerosene | LPG | Biogas | Electricity |
|----------------------------------------|------|----------|---------|---------|----------|-----|--------|-------------|
| Traditional three stone with pot stove | 0    | 0        |         |         |          |     |        |             |
| Unfired Clay Stove                     | 0-1  | 0-1      |         |         |          |     |        |             |
| Ceramic Clay stove in metal housing    | 2    | 2        |         |         |          |     |        |             |
| Side-fed metal stove                   | 0-2  | 0-2      |         |         |          |     |        |             |
| Batch-loaded metal stove               | 0-1  | 3-4      |         |         |          |     |        |             |
| Pellet gasifier stoves                 |      |          | 3-4     |         |          |     |        |             |
| LPG/Bio-gas stoves                     |      |          |         |         |          | 3   | 3      |             |
| Liquid Fuel stoves                     |      |          |         | 4       | 4        |     |        |             |
| Electric cooking stoves                |      |          |         |         |          |     |        | 4           |

**Energy Use – Household Lighting**

Lighting energy needs are calculated on the basis of equation (1) with $$i = l$$
with subtypes $$j$$ using energy carriers $$k$$. Capacity of a light source for
lighting $$c$$ is expressed in Wh/hour, the $$\varepsilon$$ parameter is not
utilised here and set to 1. Values for Average use per day in hours$$\text{A}$$ can be entered by the user and are pre-loaded with literature values from
surveys.[10] The utilisation rate $$u$$ is set to 0.95 indicating the frequency
of using the lighting source.[10] In case of kerosene lamps, fuel use can be
calculated using equation 2 to obtain litres of Kerosene used per family per
month.

Capacity values for solar lighting devices were obtained from specification
sheets in the lighting global database
(<http://www.lightingglobal.org/products/>) which were averaged to obtain a
representative value. Flashlight data was taken from Evan’s et al. (2015)[11]
and Kerosene Lamp data from Mills et al. (2003).[12] Values were also obtained
for specific torches/flaslights from product data on the Kenyan electronic goods
website [www.jumia.co.ke](http://www.jumia.co.ke).

**Table 4.** types of lighting devices and their parameters used

|                                                           | **Total Capacity Wh** | **Hourly cons.**  **(Wh/h)** | **Total hours of usage** | **Max. Lumens\*** | **Panel**  **Watts** | **Fuel fill (Wh)** | **Fuel Cons. (Wh/h)** | **Source of data**                                                                                             |
|-----------------------------------------------------------|-----------------------|------------------------------|--------------------------|-------------------|----------------------|--------------------|-----------------------|----------------------------------------------------------------------------------------------------------------|
| Battery torch/flashlight                                  | 3.20                  | 0.03                         | 120                      | 120               | \-                   | \-                 | \-                    | [www.jumia.co.ke](http://www.jumia.co.ke) - SK68 LED Torch Cree - CREE XPE Mini LED Flashlight - LED Flaslight |
| Mobile phone torch/flashlight                             | 30.40                 | 0.15                         | 200                      | 100               | \-                   | \-                 | \-                    | [www.x-tigi.com](http://www.x-tigi.com)                                                                        |
| Rechargeable battery torch/flashlight (sealed battery)    | 1.90                  | 0.38                         | 5                        | 300               | \-                   | \-                 | \-                    | [www.jumia.co.uk](http://www.jumia.co.uk)                                                                      |
| Solar lantern (mobile) with integrated solar panel        | 1.70                  | 0.31                         | 5.5                      | 35                | 0.45                 | \-                 | \-                    | [www.lightingglobal.org](http://www.lightingglobal.org)                                                        |
| Solar lantern (mobile) with pico solar panel (\<10 W)     | 10.50                 | 1.55                         | 6.8                      | 142               | 4.00                 | \-                 | \-                    | [www.lightingglobal.org](http://www.lightingglobal.org)                                                        |
| Solar lamp(s) (stationary) with pico solar panel (\<10 W) | 14.40                 | 3.07                         | 4.7                      | 500               | 5.60                 | \-                 | \-                    | [www.lightingglobal.org](http://www.lightingglobal.org)                                                        |
| Kerosene wick lamp                                        | \-                    |                              | 12.6                     | 8                 | \-                   | 1042               | 83                    | Mills (2003)[12]                                                                                               |
| Kerosene Hurricane Style Lamp                             | \-                    |                              | 7.9                      | 36                | \-                   | 2257               | 285                   |                                                                                                                |
| Candles                                                   | \-                    | \-                           | 7.5                      | 12                | \-                   | 1476               | 197                   | Grimm et al. (2005)[13]                                                                                        |
| Grid connected stationary LED lighting                    | \-                    | 2.50                         | \-                       | 350               |                      | \-                 | \-                    | Mills et al. (2015)[11]                                                                                        |

-   Universal Powerbank phone S23

-   \- Ultabright USB-rechargeable LED Torch

Mills et al. (2015)[11]

-   Waka Waka

-   D.light S3

-   Enviro SL36

-   Sun King Pico Plus

-   PSHS 3000

-   Sun King Boom

-   CAA Solar Lantern

-   Lagazel Kalo 3000

-   Sun King Pro easybuy/Pro X

-   Shanghai Easy Solar Home Light Kit (2 lamps)

-   Poly oslar 10W Solar Home Lighting System

-   Sun King Home 40Z

-   Solarway Solar Home Power System

-   WOWSolar 60

\*Total value across multiple lamps if systems have multiple lamps.

**Energy Use – Mobile Phones**

The electricity use for mobile phones $$i = m$$ per month in kWh is estimated on
the basis of the number of times the phone is charged per day, $$r_{j}$$
,multiplied by the time-period of use, $$t$$, the electricity required for a
full charge as battery capacity, $$\theta$$, and the average depth of charging
from a discharged to charged state, $$d$$ , as:

$$E_{j} = r_{j} \cdot \theta_{j} \cdot d \cdot t$$ (3)

The assumption for the depth of charging parameter $$d$$ is 0.8 indicating an
80% average charge of the battery capacity. Electricity required for a full
charge, and the number of times charged per day, vary depending on phone type
$$j = 1,2,3,4$$ with four types of phones distinguished in the model:

-   ‘Dumb’ phones that have no internet access capabilities

-   Feature phones that can access the internet and run one app at a time

-   Low end smart phones that have costs 50 pounds or less, typically restricted
    to 3G capability

-   High end smart phones that have all modern phone capabilities

To obtain values for $$\theta$$ battery capacities for a wide range of phones
were evaluated as sold in low- and middle-income countries based on vendor
websites, such as [www.jumia.co.ke](http://www.jumia.co.ke), and specific
popularity tech articles (Maina 2017)[14], resulting in a selection of
smartphones listed in Table 5 below.

**Table 5**. Mobile phone brands for which capacity data was obtained to obtain
charge value averages

| **Dumb phones**          | **Feature phones**  | **Low-end smart phones** | **High-end smart phones** |
|--------------------------|---------------------|--------------------------|---------------------------|
| Nokia 150                | Nokia 3310          | Oukitel C9               | Samsung Galaxy J1 Ace     |
| Alcatel one Touch 10.35X | Doro 6050           | FreeTel ICE 3            | Samsung Galaxy J5         |
| Nokia 225                | Alcatel OneTouch    | Motorola Moto C          | Huawei P8 Lite            |
| Samsung E1270            | STK R45i            | viWa i7                  | Samsung Grand Prime Plus  |
|                          | Nokia 105           |                          | Huawei P9 Lite            |
|                          | Nokia 3310          |                          | Samsung Galaxy S5         |
|                          | Amplicomms PowerTel |                          | Samsung Galaxy S6         |
|                          | iTel 2080           |                          | Samsung galaxy S7 edge    |
|                          | iTel 5010           |                          | Infinix Hot 4             |
|                          | iTel 5610           |                          | Infinix Hot 4 Lite        |
|                          | Samsung Guru        |                          | Tecno Y3+                 |
|                          |                     |                          | Tecno C8                  |
|                          |                     |                          | Infinix X507              |
|                          |                     |                          | Xiaomo Redmi Note 4       |
|                          |                     |                          | Oppo a37F                 |

Capacity is measured by the industry in electrical charge as milliamp-hours. To
establish battery capacity in terms of energy usable in kilowatt-hours, the mAh
value is converted by multiplication with the battery voltage (typically 4 volt)
as:

$$\theta_{j} = \frac{\text{mAh}_{j}\  \cdot V}{10^{6}}$$ (4)

The following values were obtained at 0.0035, 0.0044, 0.0079, and 0.0120 kWh for
dumb, feature, low end, and high-end smart phones, based on the average for each
category of the phones in Table 5, respectively. To obtain values for the number
of times the phone is charged per day, $$r_{j}$$ , values were consulted from
the literature to obtain a base value for charging frequency.[15] In the tool
the user can insert the distribution across the four mobile phone types, the
number of phones owned by a family, and the charging frequency estimate.

**Table 6.** Default parameter values used for mobile phones

|                       | **Charge (kWh)** | **Default values for charging frequency (times per week)** |
|-----------------------|------------------|------------------------------------------------------------|
| Dumb phones           | 0.0035           | 12                                                         |
| Feature phones        | 0.0044           | 9                                                          |
| Low-end smart phones  | 0.0079           | 5                                                          |
| High-end smart phones | 0.0120           | 5                                                          |

**Energy Use – Electric appliances**

The energy use associated with electric appliances is informed by user questions
about the number of appliances per family (x out of 10 families), and for
variable appliances their utilisation rate per day in hours.

Appliance use is then calculated using a simplified version of formula (1) as:

$$E_{\text{ijk}} = \ c_{\text{ijk}} \cdot \ \sum_{t}^{n}A_{\text{ijt}}$$ (5)

The capacity value in watts is predetermined based on literature values. A
preliminary assessment for capacity wattage can be found in Table 6 below.
Values for appliances sold with Solar Home Systems were taken from the validated
catalogue from [www.lightingglobal.org](http://www.lightingglobal.org), and the
study by Phadke et al. (2015).[16] Values for other appliances were derived from
the studies of Blodgett et al. (2017), Hartvigsson and Ahlgren (2018), the LEAP
2017 off-grid appliance market survey, and the GIZ 2016 Catalogue of DC
Appliances for Photovoltaics.[17]–[20]

A total of five appliances are included in the first version of the Renewable
Energy Recommendations Tool, as listed in Table 6 with the data values. Further
expansion will be made in a future version. The duration of use for each
appliance was simplified based on taking an estimated 2 hour per day value for
each appliance as a default value, with the possibility of creating specific per
appliance use durations where data is available. Users can adjust the parameters
to create localised solutions based on specific appliances.

**Table 7**. Electricity Input requirements for Electric Appliances

| **Appliance**          | **AC/DC** | **Type/Context**            | **Wattage** | **Included in V1 RERT** |
|------------------------|-----------|-----------------------------|-------------|-------------------------|
| Television             | DC        | With Solar Household System | 10.8        | No                      |
| Radio                  | DC        | With Solar Household System | 5.0         | No                      |
| Fan                    | DC        | With Solar Household System | 20.0        | No                      |
| Small Fridge 50 Litres | DC        |                             |             | No                      |
| Television             | AC        | Standalone / without SHS    | 88.0        | Yes                     |
| Radio                  | AC        | Standalone / without SHS    | 26.0        | Yes                     |
| Fan                    | AC        | Standalone / without SHS    | 20.0        | Yes                     |
| Air Cooler             | AC        |                             | 100.0       | No                      |
| Small Fridge 50 Litres | AC        |                             | 40.0        | Yes                     |
| Small Fridge + Freezer | AC        |                             | 120.0       | No                      |
| Music system           | AC        |                             | 75.0        | No                      |
| Laptop                 | AC        |                             | 60.0        | No                      |
| Iron                   | AC        |                             | 1000.0      | No                      |
| Washing Machine        | AC        |                             | 500.0       | Yes                     |
| Hair dryer             | AC        |                             | 900.0       | No                      |
| Microwave              | AC        |                             | 900.0       | No                      |

**Energy Use – Street lighting**

The number of streetlights in the current situation is informed by the answers
from the user in terms of the housing density and the % of main roads area
covered by grid connected or solar streetlights. It is assumed that streetlights
are placed only on main roads.

The main road area length, $$R$$, is approximated based on the number of
families in the camp,$$n$$, the average camp area per person, $$x$$, in m2, a
percentage of main road area per camp area parameter, $$s$$, and the average
width of roads or streets, $$w$$, as:

$$R = \frac{n \cdot x \cdot s}{w}$$ (6)

The value of the parameter $$s$$ will vary per camp and is to be established
(pre-loaded) by analysis of satellite imagery for a sample of refugee camps. As
a standard value 3% is assumed.

After the main road area length is calculated the number of streetlights can be
determined based on the spacing,$$\text{\ S}$$, required per pole. The formula
for this is taken from Shehadeh (2015)[21] as:

$$S = \frac{l \cdot u \cdot 0.8}{lt \cdot w}$$ (7)

With$$\text{\ l}$$ as the amount of lamp lumens,$$\ u,$$ as a coefficient of
utilisation, and$$\text{\ lt}$$, as a threshold minimum required average
illumination in lumen per m2. The number of estimated streetlights thereby
varies depending on the quality of the light source.

The type of existing streetlights are informed by the user questions on how long
the street lights typically are on during the dark hours in terms of hours,
whether they are grid connected or solar street lights.

Two main types, $$j$$, of streetlights are incorporated, a solar streetlight and
a grid connected High Pressure Sodium (HPS) gas discharge street light. It is
assumed that the solar streetlight integrates a lamp, battery and solar panel
per light.

Electrical energy used $$E$$ for streetlights is calculated using equation (1)
above based on the efficiency $$\varepsilon$$ of streetlights, the standardised
capacity, $$c$$, the usage hours per day $$A$$, and the coefficient of
utilisation $$u$$.

A solar supply calculation is carried out to establish the solar-PV and battery
sizing of the solar streetlights to match with the hours of use required for the
ESMAP street-lighting energy access tier. In case of tier 1 a night-time
availability of 2 hours per day is required, in case of tier 2 a 25%
neighbourhood coverage and 4 nights per day availability, and in case of tier 4
a 50% neighbourhood availability and 50% of night hours per day is required. By
selecting a particular energy access tier the number of street lights required
are multiplied to achieve the required coverage, and in case of solar street
lights, the type of street lights are altered so as to achieve night-time
availability.

**Energy Use – Camp Community & Management Buildings Cooling & Heating**

The energy use for central camp buildings cooling and heating was estimate using
the heating and cooling degree day method. Heating Degree Days (HDD) are
expressed as the average number of degrees for a day above a specified base
temperature for a period (monthly or yearly). Cooling Degree Days (CDD) are the
opposite, as the number of degrees for a day below a specified base temperature.
Usually these values are expressed in a cumulative manner for a particular
period, such as the monthly or annual HDD or CDD. Cumulative annual HDD and CDD
per country was taken from the CMCC-KAPSARC database developed by Atalla et al.
(2018) containing values for 147 countries from 1948 to 2013.[22]

The energy use associated with HDD and CDD is estimated based on an amended
version of the formulation in Sarak & Satman (2003)[23], resulting in the
formula:

$$E_{j,t} = \frac{m\  \cdot \ U}{H\eta_{j}}{p \cdot DD}_{t}$$ (8)

With $$E$$ as energy consumption, $$p$$, as the share of time that the system is
heating or cooling for non-continuous operation, $$\ m$$ as the building surface
area in m2, $$\ U$$ as the building heat transfer coefficient in W per m2 per
degree, $$H$$, as the fuel heating value (with 1 if no fuel is used), $$\eta$$,
the efficiency of the heating system per type $$j$$, and $$\text{DD}$$ the
cooling or heating degree days value.

Standardised values used for these parameters as described above used to
calculate cooling and heating systems can be found in table 8 below. Users can
adjust the parameters based on more advanced studies or specific localised
technology systems for particular camps.

**Table 8.** Standard Values for Buildings for Heating and Cooling

| **Building Type**                 | **Typical building size (m2)** | **Heating Time %** | **Building heat loss coefficient (AU)** | **Heating Systems Efficiency** | **Cooling Time %** | **Cooling System efficiency (%)** |
|-----------------------------------|--------------------------------|--------------------|-----------------------------------------|--------------------------------|--------------------|-----------------------------------|
| Administrative office building    | 300                            | 10%                | 1.5                                     | 45%                            | 30%                | 45%                               |
| Registration office               | 50                             | 10%                | 1.5                                     | 45%                            | 30%                | 45%                               |
| Camp Staff accommodation building | 200                            | 10%                | 1.5                                     | 45%                            | 30%                | 45%                               |
| Health centre building            | 150                            | 10%                | 1.5                                     | 45%                            | 30%                | 45%                               |
| Security Post Building            | 100                            | 10%                | 1.5                                     | 45%                            | 30%                | 45%                               |
| School building                   | 300                            | 10%                | 1.5                                     | 45%                            | 30%                | 45%                               |
| Large Market Building             | 500                            | 10%                | 1.5                                     | 45%                            | 30%                | 45%                               |
| Food Centre Building              | 500                            | 10%                | 1.5                                     | 45%                            | 30%                | 45%                               |
| Distribution Centre Building      | 100                            | 10%                | 1.5                                     | 45%                            | 30%                | 45%                               |
| Storage Building                  | 200                            | 10%                | 1.5                                     | 45%                            | 30%                | 45%                               |

**Energy Demand – Water Supply**

The water supply requirements were first established, based on a fixed average
demand per camp family for low, medium and high-income families with a
distribution as provided by the user. For example, data surveys for Ghana’s
capital city Accra provide a range of 25-50 litres per day per capita for low
income families, 50-90 litres per day per capita for middle income families, and
90 to 140 litres per day per capita for high income families.[24] Water usage is
influenced by the type of supply and its intermittency. UN guidelines for
refugee camps indicate a minimum requirement of 20 litres per person per day
that should be available. Water usage surveys for refugee camps indicate a wide
range of water availability with about 53% of camps in 2005 meeting the 20
litres per day standard on average (excluding distribution effects). [25],[26]

The tool does not estimate the amount of water used, instead the electricity use
for water use is defined based on the number of electrically run ground water
pumps installed in the camp. It is assumed that water supplied from local
boreholes and is not treated for improving the quality. In addition, if the
water comes from an external piped system then no direct energy use is assumed
for the camp energy use.

The energy use for groundwater pumps is calculated based on the total vertical
distance from the groundwater source to the points of consumption, the hours of
operation, and a standard hydraulic pumping equation that incorporates the flow
needs for water usage. The hydraulic power equation utilised is expressed as:

$$P_{\text{hydraulic}} = H \cdot \rho \cdot g \cdot Q*(1 + \varepsilon)$$
(9)

Where H is the difference in height between the inlet and outlet of the pipe
from the pump under which the fluid is lifted, in this case water, $$\rho$$ is
the density of the fluid involved, g is the gravitational constant, Q is the
desired low rate per second, and $$\varepsilon$$ is an efficiency factor that
captures the friction of the pump system.[27] The equation captures the main
factor of influence on the energy costs: the vertical distance to which the
water needs to be lifted, both within the borehole, and between the borehole and
the point of use. For example, a height difference between 50- and 200-meters
lift can result in an increase from 0.3 to 1.2 kWh/m3 of water pumped for a 44%
efficient pump.[^1]

[^1]: Internal calculations

As a standard value for the desired flow rate Q a value of 0.0006 m3 per second
is used, which amounts to a little over 2 cubic metres per hour or over 50 cubic
metres if operating constantly during a 24-hour period. The standard parameters
used for pump efficiency are 44%, and for the friction in the pump system is
10%. The system efficiency fin converting electricity to mechanical energy to
lift the water is based on a large number of real life evaluations (Conlon et
al. 1996).[28] Based on these values total energy costs amount to 0.24 kWh per
m3 of water pumped for a 35 meter vertical distance.  
  