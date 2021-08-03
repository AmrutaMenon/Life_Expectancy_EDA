# Life_Expectancy_EDA

# Life Expectancy - A statistical analysis on the factors influencing Life expectancy


## Objective

The objective here is to find the factors that affect the Life Expectancy from the year 2000-2015. Apart from that there were different analysis conducted based upon the data.


## About the data

Although there have been lot of studies undertaken in the past on factors affecting life expectancy considering demographic variables, income composition and mortality rates, it was found that effect of immunization and human development index was not taken into account in the past. Also, some of the past research was done considering multiple linear regression based on data set of one year for all the countries. Important immunization like Hepatitis B, Polio and Diphtheria will also be considered. In a nutshell, this study will focus on immunization factors, mortality factors, economic factors, social factors and other health related factors as well. Since the observations in this dataset are based on different countries, it will be easier for a country to determine the predicting factor which is contributing to lower value of life expectancy. This will help in suggesting a country which area should be given importance in order to efficiently improve the life expectancy of its population.

The data was collected from kaggle - Life Expectancy data by WHO

Link to download the dataset: https://www.kaggle.com/kumarajarshi/life-expectancy-who


## Data Description
The dataset contained 22 columns and 2938 rows.

### Columns

### Country

Names of 193 Countries.

### Year

Years from 2000-2015 was taken into account.

### Status

Status of a Country: Developing and Developed.

### Life expectancy

Life expectancy in age.

### Adult Mortality

Adult Mortality Rates of both sexes (probability of dying between 15 and 60 years per 1000 population).

### Infant Deaths(death before his/her 1st birthday)

Number of Infant Deaths per 1000 population.

### Alcohol

Alcohol, recorded per capita (15+) consumption (in litres of pure alcohol).

### Percentage Expenditure

Expenditure on health as a percentage of Gross Domestic Product per capita(%).

### Hepatitis B

Hepatitis B (HepB) immunization coverage among 1-year-olds (%).

### Measles

Measles - number of reported cases per 1000 population.

### BMI

Average Body Mass Index of entire population.

### Under-five Deaths

Number of under-five deaths per 1000 population.

### Polio

Polio (Pol3) immunization coverage among 1-year-olds (%).

### Total expenditure

General government expenditure on health as a percentage of total government expenditure (%).

### Diphtheria

Diphtheria tetanus toxoid and pertussis (DTP3) immunization coverage among 1-year-olds (%).

### HIV/AIDS

Deaths per 1000 live births HIV/AIDS (0-4 years).

### GDP

Gross Domestic Product per capita (in USD).

### Population

Population of the country.

### Thinness 1-19 years

Prevalence of thinness among children and adolescents for Age 10 to 19 (%).

### Thinness 5-9 years

Prevalence of thinness among children for Age 5 to 9(%).

### Income composition of resources

Human Development Index in terms of income composition of resources (index ranging from 0 to 1).

### Schooling

Number of years of Schooling(years).


## Procedure
Initially, all the required packages were imported and the dataset was loaded. The data contained a healthy amount of missing values. During the pre-processing of the data, all the missing values were removed using bfill(), ffill() and drop() methods. During EDA, different insights were drawn based on each question and visualization was also done for a better understanding of the analysis.


## Conclusion

From the analysis, various insights were drawn. There are different factors that influence life expectancy such as BMI and body diseases, thinness_1to19_years and thinness_5to9_years, Schooling and Income composition of resources and adult mortality.

So to increase the life expectancy of people, the country should provide more immunization coverage and should also contribute to its total expenditure in health care.

