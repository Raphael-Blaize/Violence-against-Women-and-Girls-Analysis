# Violence-against-Women-and-Girls-Analysis

## Links to the various tools used 

Tableau Presentation -  [Tableau Link](https://public.tableau.com/views/VisulisationsRegradingagreementwithkeyquestionsacrossgendereducationlevelandmanyothersocioeconomicvariablesfrom70differentcountries/Overtimeaverageacrosstheworld2000-2018?:language=en&:display_count=y&:origin=viz_share_link)

Dataset - [Source link](https://www.kaggle.com/andrewmvd/violence-against-women-and-girls)

Data report - [Report Link](https://docs.google.com/document/d/158OyMtpdP_MGRnWsktfI1av5K7Z99L8oGWL1JbBt0ds/edit?usp=sharing)

## Dataset Description

This dataset aggregates agreement with key questions across gender, education level and many other socioeconomic variables from 70 different countries.
The data was collected as part of the Demographic and Health Surveys (DHS) program, which exists to advance the global understanding of health and population trends in developing countries.

#### -- Project Status: [Completed]

## Project Intro/Objective

Gender-based violence (GBV) ,is a global pandemic that affects 1 in 3 women in their lifetime.
The numbers are outstanding :
35% of women worldwide have experienced either physical and/or sexual intimate partner violence or non-partner sexual violence.
Globally, 7% of women have been sexually assaulted by someone other than a partner.
Globally, as many as 38% of murders of women are committed by an intimate partner.
200 million women have experienced female genital mutilation/cutting.
This is a problem that not only affects victims of violence and their families, but also has major social and economic consequences. Discrimination towards women is estimated to cost up to 3.7 percent of a country's GDP in some cases, which is more than twice what most governments spend on education.Failure to resolve this problem now would result in substantial potential costs. 

* Main objective
    * Focussing on key questions across gender, education level and many other socioeconomic variables across 70 countries and gaining a better understanding on where Gender violence stems .

* Specific objective.
   * Find the country with the highest number of responses.
   * Find the trend in responses across the years.
   * Find the distribution of responses in the different demographic groups :
       * Age 
       * Marital status
       * Education Background
       * Employment. 
       * Residence type { urban and rural}



### Collaborations
* Silivia-Barasra - silviabarasa16@gmail.com
* Sydney Tsuma - sydneytsuma1@gmail.com
* Ann Nyambura - anyambura5@gmail.com
* Gloria Kerubo - kerubogloria27@gmail.com

### Methods Used
* Descriptive Statistics
* Data Visualization
* Data Analysis
* Tableau
* Hypothesis Testing
* EDA Analysis

### Technologies
* Python
* Pandas,Numpy,Gooogle Colab
* Tableau
* Profiling report

```python
import pandas as pd # python library that import datasets into a working env and does so much more such as helping in cleaning datasets etc
import numpy as np # offers comprehensive mathematical functions etc
```

## Project Description
 * The UN describes violence against women and girls (VAWG) as: “one of the most widespread, persistent, and devastating human rights violations in our world today. It remains largely unreported due to the impunity, silence, stigma, and shame surrounding it.
In general terms, it manifests itself in physical, sexual, and psychological forms, encompassing:
Intimate partner violence (battering, psychological abuse, marital rape, femicide);
Sexual violence and harassment (rape, forced sexual acts, unwanted sexual advances, child sexual abuse, forced marriage, street harassment, stalking, cyber-harassment);
Human trafficking (slavery, sexual exploitation);
Female genital mutilation;
Child marriage

   * Dataset Source 
     * Link - https://www.kaggle.com/andrewmvd/violence-against-women-and-girls

  * Data Preprocessing Methods used
    *  Histogram to check the skewness of the data
    *  IQR to get rid of outliers in the data
    *  No null/missing values in the dataset 
    *  No duplicates in the dataset
    *  Concatinating of columns in the dataset
    *  Dropping of unnecessary columns in the dataset
    *  Creating a Pivot table for our data
    *  Creating Dummy variabels
    *  Label  Encoding 

   * Data Analysis used
      * Univariate Analysis 
          * [EDA.HTML](https://github.com/Raphael-Blaize/Financial-inclusion-in-Africa-Kenya-Rwanda-Tanzania-and-Uganda-/blob/main/output%20(1).html)
          * Frequency Distibutions
          * Bar graphs
          * Descriptive Statistics
              * Standard deviation
              * Mean
              * Variance
              * Skewness
              * Kurtosis
          * Histograms
       * Bivariate Analysis
           * Stacked column chart to understand the variables better and how the correlate
       * Univariate Analysis 
           * PCA Analysis
           * Pair plots
   
## Needs of this project
- data exploration/descriptive statistics
- data processing/cleaning - involves taking care of missing data, outliers and duplicates before after merging the datasets
- Data Repoort 
- Hypothesis Testing report 
- Data Analysis 
- Tableau 

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate

## License
[GPL](https://www.gnu.org/licenses/gpl-3.0.en.html)
