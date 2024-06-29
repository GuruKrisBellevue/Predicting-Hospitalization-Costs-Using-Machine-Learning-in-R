
# Predicting Hospitalization costs using Machine Learning in R

In this project, a machine learning model using Regression algorithms in R was built to predict the hospital bills in the US. Also the project was extended further to include clustering on the type of patients across the US using K-means clustering.


## Prerequisites 
The project was written in R and the code is available in the Rmd file format. You may need to install a tool that can process the .Rmd files preferrably RStudio.  Rstudio can be installed on your machine using the link: https://posit.co/download/rstudio-desktop/.

After installation, you can run the file by selecting the File --> Open File option to locate the file on your local.

Also you may have to install all the required libraries before executing the code. Refer to the Deployment section to install the required packages. 

Then you will have to download the source files and save them to the same location where the code is hosted. The files are available in the links:
https://catalog.data.gov/dataset/hospital-provider-cost-report  and  https://catalog.data.gov/dataset/medicare-inpatient-hospitals-by-provider-and-service-9af02

The required files are:

- MUP_IHP_RY21_P02_V10_DY18_PrvSvc.csv
- MUP_IHP_RY21_P02_V10_DY19_PrvSvc.csv
- MUP_IHP_RY22_P02_V10_DY20_PrvSvc.csv
- MUP_IHP_RY21_P02_V10_Dy18_Geo.csv
- MUP_IHP_RY21_P02_V10_Dy19_Geo.csv
- MUP_IHP_RY22_P02_V10_Dy20_Geo.csv

## Installation

Install the Required libraries using the below commands in R-studio

```{r}
install.packages("readxl")
install.packages("dplyr")
install.packages("lubridate")
install.packages("readr")
install.packages("ggplot2")
install.packages("ggthemes")
install.packages("tidyr")
install.packages("DT")
install.packages("scales")
install.packages("stringr")
install.packages("ggalt")
install.packages("treemap")
install.packages("knitr")
install.packages("lemon")
install.packages("kableExtra")
install.packages("reshape2")
install.packages("tidyverse")
install.packages("usmap") 
install.packages("plotly")
install.packages("leaflet")
install.packages("magrittr")
install.packages("olsrr")
install.packages("car")
install.packages("sf")
install.packages("factoextra")
install.packages("NbClust")
install.packages("maps")
```
    
## Deployment

To deploy this project run using "Run All" option in R-studio.
