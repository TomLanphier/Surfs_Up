# Surfs Up: Weather Analysis with SQLite
## Overview
This analysis was to help convince the surfer W. Avy to start a surf and ice cream business on Oahu with us. He had requested the temperature data for the months of June and December on Oahu to help determine if this business would be sustainable year-round. SQLite, SQLAlchemy, Pandas, Python, and Jupyter Notebook were utilized in this analysis. Dataset used contained temperature data from 2010 to 2017.

## Results
### Data
The summary temperature data for the months of June and December on Oahu are shown in Figure 1 and Figure 2 respectively.

![June_Data_Summary.png](/June_Data_Summary.png)

Figure 1. Summary of temperatures (°F) from Oahu in June.

![December_Data_Summary.png](/December_Data_Summary.png)

Figure 2. Summary of temperatures (°F) from Oahu in December.

### Take-Aways
The three key take-aways from this data are:
- The temperature is ~3°F colder on average in December than in June.
- In June, more than 75% of the days were above 70°F, whereas in December the percentage of days with temperatures greater than 70°F was between 50% and 75%.
- In June, at the coldest, the temperature was 64°F, whereas in December the lowest temperature was 56°F.

## Summary
### High Level Summary
The June temperatures were all in the mid-60s and higher, with a significant majority being in the 70s, and the maximum being mid-80s. The month of december is relatively similar, except the minimum temperature was mid-50s, most of the temperature was high-60s to mid-70s, and the maximum temperature was mid- to low-80s. All this data indicates that year-round temperatures are suitable for surfing and ice-cream.

### Further Queries
Here are a couple futher weather queries to help get a better idea of the year-round sustainability of the business:
- How often is it raining, overcast, or sunny in December and June on Oahu?
- How windy is it in December and June on Oahu?
