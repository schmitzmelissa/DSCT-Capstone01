# Predicting Biocapacity
#### By Melissa Schmitz
This is the first of two capstone projects as part of the Springboard Data Science Career Track.

## Useful Links
- <a href="https://www.kaggle.com/footprintnetwork/ecological-footprint">Kaggle Dataset</a>
- <a href="https://www.footprintnetwork.org/">Data Source Website</a>
- <a href="https://www.footprintnetwork.org/resources/glossary/">Glossary of Relevant Terms</a>
- <a href="https://www.youtube.com/watch?v=Z0qHA93oOSc">Video on GDP per Capita and HDI</a> (two important variables in the dataset)
- <a href="https://github.com/schmitzmelissa/DSCT-Capstone01/blob/master/Data%20Wrangling%20Checkpoint.pdf">Data Cleaning Process</a>

## Background
A nation’s ecological footprint is a measure of the ecological assets that its population requires in order to produce the natural resources it consumes and to absorb the waste generated. Consumables include plant-based food and fiber products, livestock and fish products, timber and forest products, and space for urban infrastructure. A type of waste would include carbon emissions.

The aggregate total footprint for each country includes six categories of productive surface areas (cropland, grazing land, fishing grounds, urban land, forest area, and carbon demand on land) whereas a country’s biocapacity represents the productivity of these ecological assets. These areas can also absorb generated waste, especially carbon emissions.

If a population’s ecological footprint exceeds the biocapacity of the region, that nation creates an ecological deficit. That is, its demand for resources that land and water can provide has exceeded what the region’s ecosystems can renew. Such a deficit prompts a nation to meet those demands through importing, draining its own ecological assets (e.g., overfishing), and/or emitting carbon dioxide into the atmosphere. Alternatively, if a region’s biocapacity can exceed its ecological footprint, it then has an ecological reserve (producing more than it consumes).

While the ultimate goal of environmentalists is to reduce all types of pollution and improve sustainability holistically, governing bodies do not necessarily share the same priorities. Therefore, analysis of these factors could provide a means of prioritization in order to create more tangible goals for government regulations or independent environmental programs.

## Dataset
The ecological footprint measure was invented by Mathis Wackernagel and William Rees at the University of British Columbia and this ecological footprint data was provided by the Global Footprint Network. The variables contained in this data set include:

- __Country__ – The country where data in the other columns originated.
- __Region__ – The major part of the world where the Country resides.
- __Population__ – The number of people residing in that country, in millions.
- __HDI__ – The Human Development Index, an assessment of the capability of a country’s inhabitants, shifting focus away from economics as a measure of success. It is measured with indicators such as life expectancy, education levels, and standard of living (GNI index).
- __GDP per capita__ – The Gross Domestic Product, a monetary measure of the market value of all final goods and services which does not take into account the cost of living or inflation rates. Per capita indicates per person (does not take into account distribution of income, which may skew the value in either direction).
- __Cropland Footprint__ – The amount of cropland required to meet the crop demands of a country. Measured in global hectares.
- __Grazing Footprint__ – The amount of land required within a country to meet the demands of animal grazing. Measured in global hectares.
- __Forest Footprint__ – The amount of land within a country where trees are cut down for lumber. Measured in global hectares.
- __Carbon Footprint__ – The measure of CO2 emissions associated with fossil fuel use. Measured in units of tonnes per year.
- __Fish Footprint__ – The area within a country where fish are collected for food. Measured in global hectares.
- __Total Ecological Footprint__ – A sum of the demand on biocapacity measured from the aforementioned footprint data. Measured in global hectares.
- __Cropland__ – The land area within a country available for harvesting crops. Measured in global hectares.
- __Grazing Land__ – The land area within a country available for animal grazing. Measured in global hectares.
- __Forest Land__ – The land area within a country available for forests. Measured in global hectares.
- __Fishing Water__ – The land area within a country available for fishing. Measured in global hectares.
- __Urban Land__ – The land area within a country that is built-up with man-made structures. Measured in global hectares.
- __Total Biocapacity__ – The capacity of a physical area in an ecosystem to produce resources, regenerating what is removed by demand, and absorb waste material. Measured in standardized hectares.
- __Biocapacity Deficit__ – The difference between total biocapacity and the total ecological footprint.
- __Earths Required__ – The number of Earths required to sustain the consumption of a country.
- __Countries Required__ – The number of countries required to sustain the consumption of a single country.

_Note: There is a productivity scaling factor (the equivalence factor) that converts a specific land type into a universal unit of biologically productive area, a global hectare. In a given year, the equivalence factors are the same for all countries._

## Project Approach
1. __Data Cleaning:__ Check for missing data and determine the appropriate substitute for missing values. Examine any major outliers to see if they have significance to the data. Search for other abnormalities in the data set.

2. __Exploratory Analysis:__ Exploratory data analysis with data visualization techniques to find interesting patterns. Look at potential correlations between different variables to determine how they might impact prediction results.

3. __Predictive Analysis:__ TBD. Suspected regression to predict the biocapacity deficit or reserve based on the types of footprints and available resources. May also examine whether population is the only major impact on resources by looking at data per capita rather than gross data.

## Writeup
The deliverables will include a PowerPoint presentation and a Github repository with the main Python code displayed in Jupyter notebooks with appropriate comments and notes.
