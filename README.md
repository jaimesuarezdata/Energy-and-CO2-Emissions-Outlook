# Overview

## Introduction

![image](images/mapofemissions2021.JPG){:style="display:block;margin:0 auto"}

Energy production has surged in recent years due to a notable increase in demand, primarily due to population growth, coupled with rising standards of living and a rapid industrial development. Energy production is closely linked to carbon dioxide emissions, because the dominant sources of energy globally are fossil fuels, like coal, oil and natural gas.

## Data Used
The data was downloaded from the U.S. Energy Information Administration (EIA), and contains information from 1980 to 2021, including energy production by source and country, Gross Domestic Product (GDP) and carbon dioxide emissions (CO2) by country.

## Challenges
There were some Non-Available (NA) data that had to be zeroed out, to make it suitable for analysis. The data had to be rearranged, grouped and new columns were derived in Excel and Python with the Pandas library to make it more understandable and prepare it for exporting to Tableau, where the visualizations were created.

## Tools
* Python and Excel for data cleaning and wrangling.
* Tableau for visualization.

## Questions
* Is there a relationship between energy production and Gross Domestic Product?
* How have energy production and CO2 emissions evolved in the past years?
* Which countries emit the most CO2? How have they changed their emissions and their energy sources mix?
* What is their renewables energy mix?
* How have the CO2 emissions changed in the last years?

## Skills
* Data cleaning and wrangling with Pandas and Excel.
* Data consistency checks.
* Conducting statistical analyses.
* Combining and exporting data.
* Deriving new variables.
* Grouping and aggregating data.
* Data visualization with Python.
* Data visualization with Tableau.

## Goals
* Provide a clear understanding about how energy production and Carbon dioxide emissions are related and their evolution in the past years.
* Provide conclusions consistent with the exploratory analysis.
<p>&nbsp;  </p>

# Analysis

![image](images/EnergyvsGDP.JPG){:style="display:block;margin:0 auto"}

The world has had a need to increase the production of goods and services to thrive in. This growth in production requires a higher energy consumption and production.
##### * Gross Domestic Product (GDP): Standard measure of the value added created through the production of goods and services in a country during a certain period.
##### * Quad Btu: Unit of energy equal to 1 quadrillion British Thermal Units.
<p>&nbsp;  </p>


![image](images/evolutionofenergyandco2.JPG){:style="display:block;margin:0 auto"}

Energy production is one of the sources of CO2 emission. The greenhouse effect is what keeps our temperature ideal for humans, animals, plants and other species to live in. Higher CO2 emissions can tip the greenhouse out of balance, which could increase earth's temperature. In the last forty years, both energy production and CO2 emissions have doubled.
<p>&nbsp;  </p>


![image](images/top10co2emitters.JPG){:style="display:block;margin:0 auto"}

Ten countries were responsible in 2021 for 70% of the total global emissions. China emitted 32% , United States 14% and India 7%.  These countries account to more than half of the total global emissions.
<p>&nbsp;  </p>


![image](images/energyproductionandco2top10.JPG)|![image](images/legend.png)

Proportionally to their energy production, Germany, Japan and South Korea emit more CO2 than the other countries in the top 10.
<p>&nbsp;  </p>


![image](images/energymixandemissions2000.JPG) ![image](images/energymixandemissions2021.JPG)
<p>&nbsp;  </p>
![image](images/energymixabsoluteandemissions2000.JPG) ![image](images/energymixabsoluteandemissions2021.JPG)
<p>&nbsp;  </p>
![image](images/legend.png)

CO2 Emissions in China have tripled in the last 21 years, regardless of having a higher participation of renewable energies in the Energy Source Mix; this can be explained by the significant growth in fossil energy that the country has developed. United States has reduced the emissions, even with a higher fossil energy production.

In India, the emission has also increased due principally to the growth in fossil fuel production.
<p>&nbsp;  </p>


![image](images/renewableenergymix.JPG)|![image](images/legend.png)

Although China emits the most CO2, it is also the country that leads energy transition to renewables sources. United States is also making efforts to include more renewable sources to their energy mix. Indonesia, South Korea, Iran and Saudi Arabia are still a little behind in energy transition, compared to Germany which emits the same amount but produces four times more renewable energy.
<p>&nbsp;  </p>


![image](images/evolutionofenergymixandco2emissions.JPG) | ![image](images/totalenergyandemissionsperenergy.JPG)

The increase in Total energy Production implies a higher CO2 emission; however, when comparing the evolution of the ratio of Emissions/Energy through time, we can see that the ratio has declined in the past forty years. The energy is apparently cleaner in terms of emissions per energy. This could be explained by three factors: 

1- There is a reduction of energy production from forms of fossil fuel that emit more CO2 than others, such as coal. 
2- Technology is enabling a cleaner fossil fuel production, in terms of CO2 emission. 
3- Renewable energies, with virtually none CO2 emissions, are leveraging this increase in Total energy Production, in terms of the Emissions/Energy ratio.
<p>&nbsp;  </p>


# Links

