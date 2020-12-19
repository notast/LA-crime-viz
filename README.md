# Background
This repository is for a data visualization assignment using `Tableau`.  Through dashboards, insights about

1. crime activity in Los Angeles 
2. geographical distribution of crime in LA
3. relationship between crime and victim’s demographic were gathered. 

# Dataset 
The dataset `Crime_Data_from_2016_to_2019` was provided by the school and it was adopted from the [Los Angeles crime data](https://data.lacity.org/A-Safe-City/Crime-Data-from-2010-to-2019/63jg-8b9z).  The dataset contained 900,555 rows while the original data contained 2,120,000 rows; there were fewer rows as the dataset contained crime incidents from 2016 while the original data contained observations from 2010. 
<br>
The dataset contained 24 columns while the original dataset contained 28 columns. The school supplied the other 4 variables as a separate meta- data spreadsheet, `Dimension Tables`. 
<br>
There were two variables which required expansion in the dataset; Modus Operandi `Mocodes` and the victim’s race `Vict Descent`. These variables were also unexpanded in the original dataset.  The expanded values for `Mocodes` were downloaded as a [pdf file]( https://data.lacity.org/api/views/63jg-8b9z/files/e14442b9-a6b8-4531-83f3-f7ba980b1377?download=true&filename=MO_CODES_Numerical_20191119.pdf) and exported as a csv file `extra_mocode`. The expanded values for `Vict Descent` were found on the meta dictionary on the Los Angeles crime data website. These values were scrapped and exported as a csv file `extra_race`. The Jupyter notebook on how the above was done is available as `extra_dataset_steps `. 
<br>
An [external ShapeFile](https://data.lacounty.gov/GIS-Data/Reporting-Districts/kvwy-dqs6) `geo_export_372f5f95-ca8b-48a2-8a22-84a98b0dd969` was also used to allow plotting of the LAPD districts. The crime rates at district level were mapped out as there was varying crime rates among the districts in the same area. 

# EDA 
TBA 

