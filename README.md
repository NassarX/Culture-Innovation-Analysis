# The Impact of National Culture on Innovation.
Course project of **`Statistics For Data Science`**  course - [MDSAA-DS](www.novaims.unl.pt/MDSAA-DS) - Fall 2022

## Details of the Project

### Abstract

>This project aims to explore the impact of national culture on innovation by comparing developed and developing nations during the 2022 edition of the [GII](https://www.globalinnovationindex.org) which tracks most recent global innovation trends against the background of an ongoing COVID-19 pandemic. 
>
>Using [Hofstede's 6D model](https://geerthofstede.com) of national culture, which includes dimensions such as power distance, individualism, masculinity, uncertainty avoidance, long-term orientation and indulgence, the study will investigate the relationship between cultural values and innovation as measured by the Global Innovation Index (GII).
>
>By examining the link between these cultural dimensions and the GII, the study will identify which dimensions are more or less related to a country's innovation performance.
>Additionally, the study will investigate whether the significance of cultural factors changes over time and whether the impact of culture on innovation is stronger in developed countries than in developing countries.
>
>The findings of this research will provide valuable insights into how cultural values can impact a nation's ability to innovate and inform policy decisions related to innovation.

## Data

The data used in this project is sourced from publicly available databases :
- [Geert Hofstede's website](<https://www.geert-hofstede.com/countries.html>)
- [World Intellectual Property Organization (WIPO)](<https://www.wipo.int/gii/en/>)


## Analysis

The analysis consists of several steps:

- Data preparation and cleaning
- Exploratory Data Analysis (EDA)
- Pearson’s correlation matrix
- Regression Analysis (OLS and Robust)
- Model comparison
- More Investigation (Developed Vs Developing Countries)
- Results and Discussion

The results of the OLS regression analysis suggest that there is a strong and statistically significant relationship between cultural values and innovation as measured by the GII for all countries, developed countries and developing countries, and the model fits the data better for developed countries than for all countries and developing countries.

## Requirements

- R version 4.0.2 or higher
- R packages: dplyr, ggplot2, lmtest, plm, quantreg, lmtest, sandwich, vif, ggparallel

## How to run

1. Clone the repository
2. Open R Studio
3. Set the working directory to the location of the cloned repository
4. Run the R markdown file

## Conclusion

This research highlights the importance of considering a country's level of development when analyzing the relationship between cultural values and innovation. The findings of this study can help policymakers and organizations understand how cultural values can impact a nation's ability to innovate and inform decisions related to innovation.

Contributing

If you would like to contribute to this project, please fork the repository, make your changes and submit a pull request.