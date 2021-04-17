# Background
This repository is for a [data visualization](https://public.tableau.com/profile/notast#!/vizhome/LAcrimedarkmode/GeographicalDistributionofCrime) assignment using `Tableau`.  Through dashboards, insights about

1. crime activity in Los Angeles 
2. geographical distribution of crime in LA
3. relationship between crime and victim’s demographic were gathered. 

# Dataset 
The dataset `Crime_Data_from_2016_to_2019` was provided by the school and it was adopted from the [Los Angeles crime data](https://data.lacity.org/A-Safe-City/Crime-Data-from-2010-to-2019/63jg-8b9z).  The dataset contained 900,555 rows while the original data contained 2,120,000 rows; there were fewer rows as the dataset contained crime incidents from 2016 while the original data contained observations from 2010. 
<br>
The dataset contained 24 columns while the original dataset contained 28 columns. The school supplied the other 4 variables as a separate meta- data spreadsheet, `Dimension Tables`. 
<br>
There were two variables which required expansion in the dataset; Modus Operandi `Mocodes` and the victim’s race `Vict Descent`. These variables were also unexpanded in the original dataset.  The expanded values for `Mocodes` were downloaded as a [pdf file]( https://data.lacity.org/api/views/63jg-8b9z/files/e14442b9-a6b8-4531-83f3-f7ba980b1377?download=true&filename=MO_CODES_Numerical_20191119.pdf) and exported as a csv file `extra_mocode`. The expanded values for `Vict Descent` were found on the meta dictionary on the Los Angeles crime data website. These values were scrapped and exported as a csv file `extra_race`. The Jupyter notebook on how the above was done is available as [`extra_dataset_steps `](https://github.com/notast/LA-crime-viz/blob/main/images/3%20victim%20demographic.png). 
<br>
An [external ShapeFile](https://data.lacounty.gov/GIS-Data/Reporting-Districts/kvwy-dqs6) `geo_export_372f5f95-ca8b-48a2-8a22-84a98b0dd969` was also used to allow plotting of the LAPD districts. The crime rates at district level were mapped out as there was varying crime rates among the districts in the same area. 

# Dashboard Consideration
The theme for the dashboard is inspired by recent trends with dark mode. When designing the dashboard,  creativity, interactivity and users' experience were considered.
<br>
![](https://github.com/notast/LA-crime-viz/blob/main/images/3%20victim%20demographic.png)

# EDA and Recommendation
<img src="https://github.com/notast/LA-crime-viz/blob/main/images/crimes%20against%20women.png" width="550"/>
One of the insights gathered was the top crime against females is `Intimate Partner- Simple Assault`. It is possible that the total incident of 38,432 crimes is underreported. These females may be fearful of further assaults from their partner if they report the crime or encounter emotional conflict whether to report their partner. LAPD can continue to refine its workflow to ensure these victims have a sense of psychological and physical safety when officers respond to such crimes. On a macro level, such assaults should not be addressed as a distinct crime but addressed with other crimes that fall under domestic violence. LAPD should continue to work with social services and women welfare groups to assist these female victims where possible. 
