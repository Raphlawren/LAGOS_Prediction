# Machine Learning for Flood Prediction in Lagos
## Introduction:
Lagos state is one of the states in the southwestern part of Nigeria that is notably prone to frequent flooding. This makes it a critical area for implementing advanced predictive technologies. For this purpose, i developed a flood prediction model tailored for this state. This project aims to enhance local disaster preparedness and mitigate the impact of flood through accurate forecasting.
The weather dataset I used for this project was sourced from Kaggle website, which can be accessed here.
### Methodologies:
I extracted the day, month, and year from the datetime column to gain more meaningful insights from the data.
Based on my research from the World Meteorological Organization (WMO) webpage, rainfall exceeding 50mm in a 24-hour period is classified as heavy rain, which is a known cause of flooding. Consequently, I filtered the dataset for precipitation levels above 50mm to improve forecasting.
I calculated the average yearly precipitation to uncover trends over the years.
![AYP](https://github.com/Raphlawren/LAGOS_Prediction/assets/130583230/f1e5e538-9913-407d-9914-4d908b5e70c1)
In the graph above, we see that 2005 had the highest average precipitation, measuring 177.67mm, which indicates flooding, followed by the year 2011.
### Daily Precipitation:
I checked the average daily precipitation and found that days 13 and 24 have the highest precipitation. These days experience a higher rate of heavy rain.
![DAP](https://github.com/Raphlawren/LAGOS_Prediction/assets/130583230/ad9ac15f-77f9-4318-967b-4e799452a3ed)

### Moon Cycle Precipitation:
The moon phase is measured on a scale from 0, representing a new moon, to 1, representing a full moon. A moon phase of 0.79 suggests a growing gibbous moon, nearing fullness. When this phase coincides with heavy rainfall, the risk of flooding can significantly increase.
![MOPR](https://github.com/Raphlawren/LAGOS_Prediction/assets/130583230/6472413b-02b5-42ab-8c2d-3de759ced22e)

## Conclusions:
After training, the model achieved high accuracy in predictions.
![Screenshot 2024-07-08 at 9 28 01 PM](https://github.com/Raphlawren/LAGOS_Prediction/assets/130583230/8985d5c5-dd32-4830-9023-f826fa30fe42)


We have predicted that the next flood will occur on July 9, 2024.
![Screenshot 2024-07-08 at 9 29 11 PM](https://github.com/Raphlawren/LAGOS_Prediction/assets/130583230/d21f459a-837a-48d4-85e3-733ad4278efb)


### CAUSES:
Deforestation and land Degradation: Removing vegetation cover and altering land surfaces can increase flood risk. Vegetation helps absorb rainwater, and without it, there is more surface runoff. Soil erosion also contributes to it.
Blocked or Bad Drainage Systems: Drainage systems can be blocked by trash, pile of leaves. This wastes/materials can be washed into drains accumulating and eventually block the flow of water.

### Impacts of flood on Communities and Infrastructure:
Floods can render homes uninhabitable, leading to temporary or permanent displacement of residents.
Infrastructure such as roads, bridges, and public transportation systems can be severely damaged by flooding.
Flood waters often carry pathogens and pollutants that can contaminate drinking water and food supplies.

#### Reference:
Kaggle: https://www.kaggle.com/datasets/kalusamuel/lagos-weather-dataset
