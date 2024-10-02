

This project aims to conduct exploratory data analysis and apply clustering techniques to uncover hidden patterns in the data. Python libraries such as `scikit-learn`, `matplotlib`, and `seaborn` are used for visualization and analysis of the results.

### Dataset Information:

The dataset contains 244 instances, representing data from two regions in Algeria: the **Bejaia** region, located in the northeast, and the **Sidi Bel-Abbès** region, located in the northwest. Each region is represented by 122 instances, collected over the period from **June 2012 to September 2012**.

The dataset consists of **11 attributes** and **1 output attribute (class)**. The 244 instances are classified into two categories:
- **Fire**: 138 instances
- **Not Fire**: 106 instances

### Attribute Information:

1. **Date**: (DD/MM/YYYY) Day, month (June to September), and year (2012) of the weather observation.
   
   **Weather Data**:
   
2. **Temp**: Maximum temperature at noon in Celsius (range: 22°C to 42°C).
3. **RH**: Relative Humidity in percentage (range: 21% to 90%).
4. **Ws**: Wind speed in km/h (range: 6 to 29 km/h).
5. **Rain**: Total daily rainfall in mm (range: 0 to 16.8 mm).

   **FWI (Fire Weather Index) Components**:

6. **FFMC (Fine Fuel Moisture Code)**: FFMC index from the FWI system (range: 28.6 to 92.5).
7. **DMC (Duff Moisture Code)**: DMC index from the FWI system (range: 1.1 to 65.9).
8. **DC (Drought Code)**: DC index from the FWI system (range: 7 to 220.4).
9. **ISI (Initial Spread Index)**: ISI index from the FWI system (range: 0 to 18.5).
10. **BUI (Buildup Index)**: BUI index from the FWI system (range: 1.1 to 68).
11. **FWI (Fire Weather Index)**: FWI index from the FWI system (range: 0 to 31.1).

12. **Class**: Two categories – **Fire** and **Not Fire**.

