# Matplotlib Challenge - The Power of Plots

Pymaceuticals specializes in drug-based, anti-cancer pharmaceuticals. The data analysis shows how 250 mice were treated through a variety of drug (Capomulin, Infubinol, Ketapril, and Placebo)over the course of 45 days.Their physiological responses were then monitored over the course of that time.


* [Background](#background)
* [Observable Trends Based on the Data](#trends)
* [Jupyter Notebook](#nb)
* [Technologies Used](#technologies)

##  <a name="background"></a>Background

For this project, I started with 2 csv files. This file can be found [here](./Pymaceuticals/data/). One [csv file](./Pymaceuticals/data/clinicaltrial_data.csv) includes information about the mouseid, timepoint, tumor volume.Second [csv file](./Pymaceuticals/data/mouse_drug_data.csv) includes information about the mouseid and the drug which is use for treatment.


## <a name="trends"></a>Observable Trends Based on the Data

These were the key insights I found in my analysis:

Below are the 3 observations generated from the results of the study:

 1.Capomulin is most effective drug 1 )To reduce the Tumor volume 2) limiting metastatic spread 3) Survival Rate.

 2.For Tumor volume change katapril is the least effective drug whereas Capomulin is most effective drug

 3.Mice treated with Infubinol had less tumor growth and metastatic site spread than those treated with Ketapril or placebo, but the mortality rate was higher than the other two.
  
I used basic Pandas methods and functions to do my analysis and matplotlib for Visualization.

Final Report includes charts for:

 *Tumor response to tratment.
 *Metastatic spread during treatment.
 *Survival rate during treatment.
 *Tumor change over treatment.

##  <a name="nb"></a>Jupyter Notebook

For this project, I used jupyter notebook to render and display the results of this analysis. You can view the notebook here:

<https://github.com/PunamSonawane/matplotlib-challenge/blob/master/Pymaceuticals/pymaceuticals_starter.ipynb>

The notebook is also available inside this repository [here](./Pymaceuticals/pymaceuticals_starter.ipynb).

##  <a name="technologies"></a>Technologies Used

* Python
* Pandas library
* Matplotlib library
* Jupyter Notebook