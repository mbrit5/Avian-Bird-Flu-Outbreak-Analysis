# Avian-Bird-Flu-Outbreak-Analysis
## <ins>Dataset:</ins>
  https://wahis.woah.org/#/dashboards/qd-dashboard

## <ins>Abstract:</ins>
Our data science project focuses on the predicting future cases for the H5N1 virus in countries that prime exporters of poultry across each continent.

## <ins>Introduction:</ins>
In the recent months, the prevalence of the H5N1 virus (a strand of Influenza A that primarily affects avian species) has led to the increase costs of eggs within the US. This had led to the US starting to import eggs from Turkey to increase supply to meet the demand, in a recent article from CNN<sup>1</sup>.\
Additionally, the number of human mortalities related to the H5N1 virus has been slowly increasing. This is important as the way the H5N1 virus works is that it attacks the host's nervous system. Hence why the survival rate in humans is approximately 50% and for pets it can be especially deadly. In humans, the symtoms of those affected are very similar to that of a regular flu, making detection so much harder.<sup>2</sup>


## <ins>Methodology:</ins>
The countries that we have selected (USA, China, Thailand, Brazil, Turkey, Poland, South Africa, Australia) are considered some of the biggest exporters of poultry either in the world or within their distinct continent. As we have been given specific hubs, we are using geopy to help identify their respective lattitudes and longitudes. The dataset we have decided to use is from World organization for Animal health (constisting of 1481 rows annd 21 columns) We decided to examine the number of cases within the last 20-25 years. We are planning to use spatial regression, decision tree, and spatiaal clustering to analyze the number of cases in each location and predict the humber of cases as time passes. 

## <ins>Sources:</ins>
1. https://www.cnn.com/2025/02/24/business/egg-prices-turkey-vaccine/index.html#:~:text=Turkey%20plans%20to%20export%20420,alone%20in%20November%20and%20December.
2. https://www.yalemedicine.org/news/h5n1-bird-flu-what-to-know#:~:text=At%20this%20point%2C%20there%20is,general%20public%20is%20so%20low.%E2%80%9D

## <ins>Data Dictionary:</ins>
| Column name | Data Type |
| --- | --- |
| Year | int64 |
| Semester | object |
| World region | object |
| Country | object |
| Administrative Division | object |
| Disease | object |
| Serotype/Subtype/Genotype | object |
| Animal Category | object |
| Species | object |
| New outbreaks | int64 |
| Susceptible | int64 |
| Measuring units | int64 |
| Cases | int64 |
| Killed and disposed of | int64 |
| Deaths | int64 |
| Latitude | int64 |
