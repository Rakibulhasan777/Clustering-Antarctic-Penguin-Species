# Clustering-Antarctic-Penguin-Species 
Arctic Penguin Exploration: Unraveling Clusters in the Icy Domain with K-means clustering 

## Project Overview 
![Alt text](https://imgur.com/orZWHly.png)
source: @allison_horst https://github.com/allisonhorst/penguins 

Unsupervised learning is a critical task in machine learning, and it plays a significant role in this project. The objective is to delve into the information about penguins by utilizing unsupervised learning techniques on a thoughtfully curated dataset. By conducting thorough data exploration, extracting meaningful features, and employing advanced algorithms, this project aims to uncover concealed patterns, clusters, and relationships that exist within the dataset. 


## Data Source 
The dataset used in this project is from a major online data science source and is available in the `penguins.csv` file.

**Origin of this data** : Data were collected and made available by Dr. Kristen Gorman and the Palmer Station, Antarctica LTER, a member of the Long Term Ecological Research Network. 

**The dataset consists of 5 columns.**

- culmen_length_mm: culmen length (mm)
- culmen_depth_mm: culmen depth (mm)
- flipper_length_mm: flipper length (mm)
- body_mass_g: body mass (g)
- sex: penguin sex

Unfortunately, they have not been able to record the species of penguin, but they know that there are three species that are native to the region: **Adelie**, **Chinstrap**, and **Gentoo**, so the task is to apply data science skills to help them identify groups in the dataset! 

## Download & Importings 
You can install the released version of Python from
[Here](https://www.python.org/downloads/)

``` r
import pandas as pd
import matplotlib.pyplot as plt
from sklearn.decomposition import PCA
from sklearn.cluster import KMeans
from sklearn.preprocessing import StandardScaler
```

## Steps to complete 
  * Loading and examining the dataset
  * Dealing with null values and outliers
  * Perform preprocessing steps on the dataset to create dummy variables
  * Using get dummies method on the categorical feature
  * Perform preprocessing steps on the dataset - scaling
  * Perform PCA
  * Detect the optimal number of clusters for k-means clustering
  * Run the k-means clustering algorithm
  * Create a final statistical DataFrame for each cluster.
    



## Additional data use information 
Anyone interested in publishing the data should contact [Dr. Kristen
Gorman](https://www.uaf.edu/cfos/people/faculty/detail/kristen-gorman.php)
about analysis and working together on any final products. From Gorman
et al. (2014): “Individuals interested in using these data are expected
to follow the US LTER Network’s Data Access Policy, Requirements and Use
Agreement: <https://lternet.edu/data-access-policy/>.” 

## References

**Data originally published in:**

-   Gorman KB, Williams TD, Fraser WR (2014). Ecological sexual
    dimorphism and environmental variability within a community of
    Antarctic penguins (genus *Pygoscelis*). PLoS ONE 9(3):e90081.
    <https://doi.org/10.1371/journal.pone.0090081>

**Data citations:**

Adélie penguins:

-   Palmer Station Antarctica LTER and K. Gorman, 2020. Structural size
    measurements and isotopic signatures of foraging among adult male
    and female Adélie penguins (*Pygoscelis adeliae*) nesting along the
    Palmer Archipelago near Palmer Station, 2007-2009 ver 5.
    Environmental Data Initiative.
    <https://doi.org/10.6073/pasta/98b16d7d563f265cb52372c8ca99e60f>
    (Accessed 2020-06-08).

Gentoo penguins:

-   Palmer Station Antarctica LTER and K. Gorman, 2020. Structural size
    measurements and isotopic signatures of foraging among adult male
    and female Gentoo penguin (*Pygoscelis papua*) nesting along the
    Palmer Archipelago near Palmer Station, 2007-2009 ver 5.
    Environmental Data Initiative.
    <https://doi.org/10.6073/pasta/7fca67fb28d56ee2ffa3d9370ebda689>
    (Accessed 2020-06-08).

Chinstrap penguins:

-   Palmer Station Antarctica LTER and K. Gorman, 2020. Structural size
    measurements and isotopic signatures of foraging among adult male
    and female Chinstrap penguin (*Pygoscelis antarcticus*) nesting
    along the Palmer Archipelago near Palmer Station, 2007-2009 ver 6.
    Environmental Data Initiative.
    <https://doi.org/10.6073/pasta/c14dfcfada8ea13a17536e73eb6fbe9e>
    (Accessed 2020-06-08).
