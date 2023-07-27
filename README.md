## Analysing and Evaluating Mobility in Northern Kenya

The project's aim is to identify the key factors influencing mobility in the North of Kenya. And specifically observe the role droughts play in the region. With a multi-feature target, the analysis is done by applying unsupervised learning.

**BACKGROUND:** The ASAL region of Kenya has endured three severe droughts in the last decade (2010-2011, 2016-2017 and 2020-2022). The most recent drought (2020 - 2022) has also been the most severe and longest with widespread livelihood losses and massive displacement of populations.

**PROCESS**

The dataset is based on in-situ surveys carried out in five counties in Northern Kenya in November 2022 organized by United Nations Office for the Coordination of Humanitarian Affairs (OCHA). In order to combine the datasets, I previously standardized in Excel the questions across the five surveys. Additionally, I deleted (majorily) empty columns, columns that don't exist across all five datasets, and columns with identical/highly similar information. I also divided columns with more than one data point per cell in the respective amount of individual cells.

The original datasource: https://data.humdata.org/dataset/kenya-displacement-baseline-multi-sectoral-location-assessment-iom-dtm

The data analysis involved intense cleaning of the dataset derived from the five surveys. The final dataset contains 861 entries (=locations with differing number of households) and 48 features. The machine learning algorithm applied is KMeans for clustering and involves Principal Component Analysis (PCA).

**SUMMARY OF FINDINGS:**
    
1. In one third of locations (village unit or urban settlement/town) in the region surveyed, only 25% of inhabitants have access to cooking water.
2. In one third of locations, only 25% of inhabitants have access to drinking water.
3. In approximately 40% of locations inhabitants have a water source distance of 50 minutes and additionally experience a water queue time of 50 minutes.
4. In around 40% of the locations, drought was the primary reason for returning of households to this location.
5. In around 75% of locations, resource-based conflict was the second reason for departure of households from this location.
6. In approximately one third of locations, resource-based conflict was also the second reason for households to drop pastoralism.
7. Environmental challenges was reported as the first challenge in 50% of locations.
8. Lack of food and water was reported as the second challenge in 40% of locations.
9. Malaria was the top health concern in just above 60% of locations.

#### It is possible to discern that several of these factors are related to water scarcity. 

Based on the current analysis 9 out of the 10 features can be directly or indirectly associated with water scarcity under certain conditions. **Hence, 90% of the factors can be linked to water scarcity.**
    
Features such as ethnic clashes, safety concerns or access to an educational facility appear to be less important drivers for mobility in the region. <br>

However, a more detailed analysis e.g. of additional features in the dataset could provide a more accurate picture of the individual motivation for mobility at a specific point in time.
