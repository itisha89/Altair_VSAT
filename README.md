**Problem statement**

The city of Mistford and the Boonsong Lekagul Wildlife Preserve are facing a significant decline in the nesting pairs of the Rose-Crested Blue Pipit, a beloved local bird species. Previous investigations have suggested a potential link between the decline and activities at Kasios Office Furniture, a manufacturing firm in Mistford. However, no concrete evidence has been found to establish this link.
A detailed analysis of the water sensor readings from rivers and streams in the preserve needs to be carried out to identify any potential correlation between chemical measurements and decline in bird population

**Technology used:** 
Altair 

**Assumptions:**

The wildlife preserve is located in the UK.

If the readings of a chemical are not available, we assume that reading was not taken.

Readings with value=0 were included in the analysis for in-depth trend analysis.

The sites on the same river routes were marked together. Post this selection we had 4 routes with the bifurcation as

Route 1: Boonsri, Kohsoom, Busarakhan, Chai, Kannika.

Route 2: Somchair, Achara, Sakda.

Route 3: Tansanee.

Route 4: Decha.

After the route marking and distance calculation, Route 1 was found nearest to the dumping site and route 4 is the farthest.Kohsoom is nearest to the dumping site with a distance of 1.55 units and Decha is the farthest with 8.21 units of distance.

Since the exact manufacturing process of the furniture manufacturing company ‘Kasios Office Furniture’ is unknown, therefore it is assumed that all the chemicals listed in the dataset are emitted as a byproduct of the manufacturing activities.

**Dashboard:**

The aim of this dashboard is to analyze and display the distribution of chemical values at various locations over time, separated by routes and distance from a dumping site. It aims to explain how different routes and distances from a central point affect the spatial and temporal patterns of chemical distribution.

![image](https://github.com/user-attachments/assets/d09a1b71-27cb-4e46-b06d-40c508abfba9)
![image](https://github.com/user-attachments/assets/13f17bcb-6949-43b9-aa39-69fe1ea95d75)



**Visual 1: Discover trends, outliers, and missing data location-wise.**

![image](https://github.com/user-attachments/assets/23344f36-36eb-4d91-81b0-1571ddc75acf)


Data for all locations of Route 1 were available from 1988 to 2016.

Data for only 2 Route 2 sites (Somchair, Sakda) available from 1998 to 2016.

Other sites on Route 2 (Achara), Tansanee (Route 3), and Decha (Route 4) had data available from 2009 to 2016 (8 years).

Kohsoom had highest measures in 2003.

Majority of sites in green to blue zones.

2003 saw high values, possibly due to heat wave.

Tansanee consistently in blue to purple zone.

Achara mostly in green zone, except in 2009.

**Visual 2: Identify data irregularities in chemical metrics across all locations.**
![image](https://github.com/user-attachments/assets/8387b9b9-fcde-430e-8ce3-bee3bdb27d31)

All average measures across locations fall within the green zone

Achara recorded 'Total coliforms' in the red zone.

Missing values are evident from white spaces, indicating no readings for a specific measure in 19 years.

There were 38 chemicals out of 106 which were observed for all the locations namely -  'Ammonium', 'Anionic active surfactants', 'Arsenic', 'Atrazine', 'Bicarbonates', 'Biochemical Oxygen', 'Cadmium', 'Calcium', 'Chemical Oxygen Demand (Cr)', 'Chemical Oxygen Demand (Mn)', 'Chlorides', 'Chromium', 'Copper', 'Dissolved oxygen', 'Dissolved silicates', 'Iron', 'Lead', 'Macrozoobenthos', 'Magnesium', 'Manganese', 'Mercury', 'Nickel', 'Nitrates', 'Nitrites', 'Orthophosphate-phosphorus', 'Oxygen saturation', 'Petroleum hydrocarbons', 'Potassium', 'Sodium', 'Sulphates', 'Total dissolved salts', 'Total hardness', 'Total nitrogen', 'Total phosphorus', 'Water temperature', 'Zinc', 'gamma-Hexachlorocyclohexane', 'p,p-DDT'.

**Visual 3: To find out the missing values, data irregularities of all chemical values throughout the time period 1998-2016 (19years).**


![image](https://github.com/user-attachments/assets/24b1468f-3843-4d29-a03c-f5ee7744b649)

Inconsistencies in data collection frequency observed; e.g., Beryllium, PCB 28, PCB 118, PAHs, Boron, Cesium, PCB 52, Trifluralin, Fluorene collected once from 1998 to 2016.

'Total dissolved salts' and 'bicarbonates' consistently in the blue zone, indicating mediocre average values.

Iron's average value was in the red zone in 2003.

**Visual 4: To observe and compare the total number of records collected for each location and chemical measures.**

![image](https://github.com/user-attachments/assets/f0d7c965-eb57-4d4e-9b55-f60cd8354ad7)

Boonsri and Chai had the highest observations: Boonsri (31314) and Chai (31245).

Achara, Decha, and Tansanee had the fewest. 

Water temperature was the most frequently recorded measure with 5031 records.

**Visual 5: To see the trend of collection frequency over the span of 19 years**

![image](https://github.com/user-attachments/assets/da6fe2a0-ab7b-439f-aad4-02258a5b2b05)

Boonsri and Chai had the highest observations: Boonsri (31314) and Chai (31245).

Achara, Decha, and Tansanee had the fewest. 

Water temperature was the most frequently recorded measure with 5031 records.

**Following the observations from Task 1, for deeper analysis we consider:**

Sites: Route 1 (Boonsri, Kohsoom, Busarakhan, Chai, Kannika) and Route 2 (Somchair, Sakda) were available from 1998 to 2016 as the data is available from 1998 to 2016.

Chemicals (20 out of 106) which were observed for all the locations from 1998 to 2016 are - 'Ammonium', 'Biochemical Oxygen', 'Cadmium', 'Calcium', 'Chemical Oxygen Demand (Cr)', 'Chemical Oxygen Demand (Mn)', 'Chlorides', 'Chromium', 'Copper', 'Dissolved oxygen',  'Lead', 'Magnesium', 'Nitrates', 'Nitrites', 'Orthophosphate-phosphorus', 'Potassium', 'Sodium', 'Sulphates', 'Total phosphorus', 'Water temperature'.



**Visual 6: To illustrate average measure values over time across multiple locations using faceted line charts.**

![image](https://github.com/user-attachments/assets/e709993b-1682-4743-9cf1-cd54341bc388)


Across all locations, it has been noted that the average value of measures has exhibited a declining trend over a 19-year period, although the start was at high levels.

**Visual 7: To summarize the cumulative value of various chemicals from 1998 to 2016, providing yearly averages and identifying predominant chemicals annually.**

![image](https://github.com/user-attachments/assets/c2e270d8-a524-4641-a67c-4b09d942b10a)


During the course of the 19 years of monitoring, calcium, chlorides, and sulphates have continuously shown larger amounts than other chemicals.

Nitrate has consistently shown the lowest levels of all chemicals throughout the entire 19 years.


**Conclusion:**

Based on the findings from Task 1 and Task 2, it is inferred that the bird population could potentially be affected by the concentration of chemicals in the various locations. However, a definitive conclusion can only be reached with additional information regarding factors such as the quantity of pollutants emitted by the furniture company, the establishment date of the company, acceptable thresholds for each chemical, and so forth.

## 🌍 Explore More Projects  
For more exciting machine learning and AI projects, visit **[The iVision](https://theivision.wordpress.com/)** and stay updated with the latest innovations and research! 🚀  

---




