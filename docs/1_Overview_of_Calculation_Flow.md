![](media/c1b04cd81c7afefa111aeac4b966ad18.png)

**Humanitarian Engineering for Energy for Displacement (HEED)**

**Technical Documentation for Tool Calculations**

>   Authors: Rembrandt Koppelaar (Scene), Jonathon Nixon (Coventry University)

# Overview of Calculation Flow
-------------------------------

The calculation setup is a linear flow based on five calculation “modules”, and
three mechanisms by which the user adds data and conditions for the calculations
(see Figure 1). The setup is designed without iteration in a demand-driven
manner, in that supply is calculated to match demands, in contrast to an
equilibrium-based calculation. Any iterations will be carried out by the user,
by enabling a real-time output change due to user input alterations.

![A screenshot of a cell phone Description automatically generated](media/bf4ed8ad8815b791bd9411d8fc825d9e.jpg)

**Figure 1.** Calculation Flow of the RERT Tool

Each of the calculation steps are described in the next sections including the
parameters and user inputs as applicable. The energy demand calculations (B) are
described in section 2, the calculations of supply options to meet the demands
(C) are described in section 3. The calculation of performance indicators for
energy supply options (D) is described in section 4, and the threshold grouping
& ranking based on energy access tiers and indicator thresholds (E) is described
in section 5.