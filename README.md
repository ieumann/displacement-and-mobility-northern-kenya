## Analysing and Evaluating Mobility in Northern Kenya

The project's aim is to identify the key factors influencing mobility in the North of Kenya. And specifically observe the role droughts play in the region. With a multi-feature target, the analysis is done by applying unsupervised learning.

**BACKGROUND:** The ASAL region of Kenya has endured three severe droughts in the last decade (2010-2011, 2016-2017 and 2020-2022). The most recent drought (2020 - 2022) has also been the most severe and longest with widespread livelihood losses and massive displacement of populations.

**PROCESS:**

The dataset is based on in-situ surveys carried out in five counties in Northern Kenya in November 2022 organized by United Nations Office for the Coordination of Humanitarian Affairs (OCHA). In order to combine the datasets, I previously standardized in Excel the questions across the five surveys. Additionally, I deleted (majorily) empty columns, columns that don't exist across all five datasets, and columns with identical/highly similar information. I also divided columns with more than one data point per cell in the respective amount of individual cells.

The original datasource: https://data.humdata.org/dataset/kenya-displacement-baseline-multi-sectoral-location-assessment-iom-dtm

The data analysis involved extensive cleaning of the dataset derived from the five surveys. The final dataset contains 861 entries (=locations with differing number of households) and 48 features. The machine learning algorithm applied is KMeans for clustering and involves Principal Component Analysis (PCA). 
During PCA, 10 features were identified to weight most allowing to identify specific drivers for mobility and displacement in the region. Based on these

**SUMMARY OF FINDINGS:**
    
1. In approx. one third of locations (village unit or urban settlement/town) in the region surveyed, only 25% of inhabitants have access to cooking as well as to drinking water.
2. In approximately 50% of locations inhabitants have a water source distance of 50 minutes and additionally experience a water queue time of 50 minutes.
3. In around 45% of the locations, drought was the primary reason for returning of households to this location.
4. In around 75% of locations, resource-based conflict was the second reason for departure of households from this location.
5. In approximately one third of locations, resource-based conflict was also the second reason for households to drop pastoralism.
6. Environmental challenges was reported as the first challenge in approx. 45% of locations.
7. Lack of food and water was reported as the second challenge in approx. 35% of locations.
8. The health concern that influenced the analysis most was pneumonia in around 50% of locations with Malaria being the main health concern overall.

**It is possible to discern that several of these factors are related to water scarcity.**
 
The accessibility of water for cooking is directly indicated by one feature. A lower percentage here suggests that water scarcity is an issue.
Similarly, another feature shows the availability of drinking water. If the percentage is low, it suggests a scarcity of water.
Another feature is the distance to the water source. A larger distance could signify that water scarcity is present, as it means individuals need to travel further to reach water.
The time spent in queues for water is another feature. Longer waiting times could indicate water scarcity, as it suggests that more individuals are attempting to access limited water resources.
One feature presents the first reason for returning to the original location, where 'drought' is mentioned. This suggests that water scarcity, taking the form of a drought, was a significant factor in a household's decision to return.
The second challenge faced, as indicated by one feature, is 'lack of food and water'. This challenge is a direct reference to water scarcity.
The first challenge, described as 'environmental challenges' in another feature, could indirectly be related to water scarcity. This is because environmental challenges often encompass issues related to water availability.

Adding to these:
The second reason for departure, as stated in one feature, is 'resource-based conflict'. In this region, such conflicts often emerge due to water scarcity.
The second reason to abandon pastoralism, according to another feature, is also 'resource-based conflict'. The reason for dropping pastoralism could be the lack of water for cattle due to drought. Given the vast space in this region, it is unlikely that a land-related conflict is the cause.

**Based on the current analysis 9 out of the 10 features can be directly or indirectly associated with water scarcity under certain conditions. Hence, 90% of the drivers for mobility can be linked to water scarcity.**
    
Features such as ethnic clashes, safety concerns or access to an educational facility appear to be less important drivers for displacement in the region. <br>

However, a more detailed analysis e.g. of additional features in the dataset could provide a more accurate picture of the individual motivation for mobility at a specific point in time.
