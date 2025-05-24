![airplane](https://github.com/user-attachments/assets/c62d28d3-b8df-4a78-a7ea-6e98d10c1bd3)
# STQD6324-Assignment 2-P149793

## 1. Introduction
- The data set uses the 2006 airline on-time performance data on Kaggle.

---

## 2. Delay Pattern Analysis
![Delay_Patterns](https://github.com/user-attachments/assets/a1ad35a6-9f4e-4403-b316-969f12ed297b)
- Read the year, month, dayofmonth, dayofweek, crsdeptime, arrdelay, cancelled, and diverted columns in the data set for Delay Patterns analysis.  
![image](https://github.com/user-attachments/assets/367037c2-922e-4fd4-a9bc-d8c212803514)

- Generate a new column named dephour to record the hour of delay.
- 0 to 5 o'clock is defined as Late Night, 5 to 12 o'clock is defined as Morning, 12 to 17 o'clock is defined as Afternoon, 17 to 21 o'clock is defined as Evening, and 21 to 24 o'clock is defined as Night.
- March to May is defined as spring, June to August as summer, September to November as fall, and December to February as winter.
### 1. Time of Day Analysis
- Visualization  
![Visualization1](https://github.com/user-attachments/assets/12e847ba-927e-46af-b517-3aa95da1228b)

- The average delay time is the longest during the evening period, while it is relatively short during the late night and morning periods. It can be inferred that the evening may be the peak period of traffic or business activities, resulting in more serious delay situations; while business activities or travel demands are relatively low during the late night and morning, leading to fewer delays. 

### 2. Day of the Week Analysis
- Visualization  
![Visualization2](https://github.com/user-attachments/assets/3c1be686-9070-4854-a8c9-ceeb88f70abe)
- The average delay time fluctuates significantly within a week. Delays are most severe on Fridays, while punctuality is highest on Saturdays. It can be inferred that on Fridays, the superposition of commuting, business activities, etc. may lead to a significant increase in travel demand, resulting in more delays. On the other hand, on Saturdays, the travel mode may change, with a decrease in the number of travelers and business volume, thus increasing the punctuality rate.

### 3. Seasonal Analysis
- Visualization  
![Visualization3](https://github.com/user-attachments/assets/3cd6a5e7-24cb-44b8-8ee6-c3bc9c1c0893)
- The average delay time is the longest in summer and the shortest in spring. The possible reason is that activities such as traveling increase in summer, and the demand for transportation or business rises significantly, resulting in more delays. In contrast, the demand in all aspects is relatively stable in spring, so there are fewer delays.

### 4. Analysis Summary
![Analysis_Summary1](https://github.com/user-attachments/assets/842247be-3b54-4e5d-8341-89e58464057c)

---

## 3. Delay Factors Analysis
![Delay_Factors](https://github.com/user-attachments/assets/52d45ec3-e91e-47c9-a068-0698f9855a46)
- Select the carrierdelay, weatherdelay, nasdelay, securitydelay, and lateaircraftdelay columns in the data set for Delay Factors analysis.
### 1. Analysis of Flight Delay Factors
- Visualization  
![Visualization4](https://github.com/user-attachments/assets/472f516c-39c5-426d-b5f4-a3de0c757c52)
- In 2006, among the factors contributing to flight delays, aircraft late arrival accounted for 37.0%, ranking first and being the primary cause. Delays in the national airspace system accounted for 29.4%, ranking second. Carrier - related delays accounted for 27.8%, weather - related delays accounted for 5.6%, and security check - related delays accounted for only 0.3%, having the least impact.   

### 2. Top 5 Delay Factor Analysis
![Top 5 Delay Factor Analysis](https://github.com/user-attachments/assets/74a0a5b7-2300-4a8f-913a-663093abbce3)

---

## 4. Cancellation Analysis
![Cancellation](https://github.com/user-attachments/assets/8491f985-c1f4-4731-805a-9868b52d9963)

- Select uniquecarrier, origin, det, year, month, dayofweek, cancellationcode columns in the data set for Cancellation analysis.  
![cancelreason](https://github.com/user-attachments/assets/0976dfe4-20b8-49a5-bf60-9eb27395de23)
- Generate a CancelReason column to specifically display the reason for the cancellation.
### 1. Distribution of Reasons for Flight Cancellation
- Visualization  
![Visualization5](https://github.com/user-attachments/assets/99e01812-4d79-4a59-bab8-fbfd4942446e)
- In 2006, among the reasons for flight cancellations, carrier - related reasons accounted for 45.6% and ranked first, being the main cause. Weather - related reasons accounted for 31.1% and ranked second. National Airspace System - related reasons accounted for 23.1%. Security - related reasons accounted for only 0.1% and had the least impact.

### 2. Flight Cancellations by Airline
- Visualization  
![Visualization6](https://github.com/user-attachments/assets/a03fccb0-948c-420a-ba63-cb351db9d0e6)
- The number of flight cancellations for MQ reached 19,990, accounting for 7.8%; OO had 12,844 cancellations, accounting for 8.0%; and UA had 10,238 cancellations, accounting for 7.3%.

### 3. TOP10 cancellations at departure airports
- Visualization  
![Visualization7](https://github.com/user-attachments/assets/f159f98d-dc90-4961-9f40-f8c8e70a9c9e)
- ORD Airport had the most cancellations, reaching 12,915 times; ATL Airport had 6,624 cancellations; and DFW Airport had 5,502 cancellations.

### 4. Monthly trend of flight cancellations
- Visualization  
![Visualization8](https://github.com/user-attachments/assets/f670fd4d-6be0-4eb8-9c75-1a7242c7256a)
- Overall, the fluctuations are significant. The cancellation frequency was the lowest in April and reached the highest in December. There were also relatively high peaks in February, July, and October. This reflects that there are significant differences in flight cancellations in different months, which may be related to factors such as seasons and holidays.

### 5. Seasonal distribution of flight cancellations
- Visualization  
![Visualization9](https://github.com/user-attachments/assets/4e9c6923-400e-4db4-a941-eb0cd6f478c3)
- The proportion of flight cancellations in winter is 32.1%, the highest among the four seasons; the proportion in autumn is 25.3%, and the proportion in summer is 25.1%, with similar proportions for the two; the proportion in spring is the lowest, at 17.4%. This indicates that winter is the season with relatively frequent flight cancellations.

### 6. Analysis Summary
![Analysis_Summary](https://github.com/user-attachments/assets/a8673f46-a5a4-478a-ac32-e132caabbeef)

---

## 5. Problematic Routes Analysis
![Problematic_Routes](https://github.com/user-attachments/assets/47239601-2dde-4052-a4a9-a796bdebcec7)
- Select the data sets origin,dest,uniquecarrier, flightnum,arrdelay, cancelled,cancellationcode,carrierdelay, weatherdelay, nasdelay,securitydelay, lateaircraftdelay columns for Problematic Routes analysis.
### 1. Analysis of the top 3 problematic routes
![Analysis of the top 3 problematic routes](https://github.com/user-attachments/assets/f0dbf87a-20da-4d5e-abfa-1be208fc76cf)

### 2. Analysis of the Delay Rates of the Top Problematic Routes
- Visualization  
![Visualization10](https://github.com/user-attachments/assets/9ec4115d-9c9f-4176-bc4b-73a3f60ed2bc)

### 3. Analyzing Problem Airlines
![Analyzing Problem Airlines](https://github.com/user-attachments/assets/527666c5-e38b-4916-82aa-364bd695c342)
- Among them, the maintenance ratios of EV and YV are relatively high, at 0.50370 and 0.529942 respectively. The maintenance ratios of B6 and TZ are relatively low, at 0.237860 and 0.252344 respectively. MQ is at an intermediate level, at 0.319680.

### 4. Decomposition of the causes of delays on major routes
- Visualization  
![Visualization11](https://github.com/user-attachments/assets/c07bb412-782d-4ea1-980b-96dee41b8641)
- The delays on the ABE - LGA and SRQ - BDL routes are all 0 in terms of carrier, National Airspace System, and weather; the weather - related delay value of the DTW - CID route reaches 710, indicating that the main cause of its delay is weather.

### 5.Analysis Summary
![Analysis Summary](https://github.com/user-attachments/assets/5b24c97c-8d3c-4135-8c22-a45e5a4ce177)

---

## 6. Conclusion & Recommendations

### 1. Conclusion
- Related to DelaysTime Dimension: Delays are most severe in the evening of a day, more prominent on Fridays in a week, and longer in summer within a year.
- Factor Dimension: Among the factors causing flight delays, aircraft late arrival, the national airspace system, and carrier - related reasons account for a relatively large proportion. For specific routes like DTW - CID, the main cause of delay is weather. Different airlines have different maintenance ratios, which may affect operational stability.
- Related to CancellationsCause Aspect: The main cause of flight cancellations is carrier - related reasons, followed by weather and national airspace system reasons.
- Entity Aspect: Different airlines have different numbers of flight cancellations. Some airports like ORD have a high frequency of flight cancellations. In terms of months, December has the most cancellations, and in the seasonal distribution, the proportion of cancellations in winter is high.

### 2. Recommendations

#### Airlines
- Optimize Operational Management: In response to the high proportion of delays and cancellations caused by carriers, strengthen internal operational coordination, such as arranging flight crew reasonably, optimizing aircraft allocation and maintenance plans. For airlines with a high maintenance ratio, more efficient maintenance models can be explored to balance cost and safety; airlines with a low ratio need to be vigilant against potential failure risks and increase maintenance investment in a timely manner.
- Pay Attention to Peak Hours and Seasons: In peak hours of delays and cancellations such as evenings, Fridays, summers, and winters, make advance plans, such as increasing capacity reserves and flexibly adjusting flight schedules.

#### Airport
- Frequently Cancelled Airports like ORD: Strengthen cooperation with airlines, improve ground service efficiency, optimize flight scheduling, and relieve operational pressure.
- General Strategies: Improve the weather warning mechanism, closely cooperate with the air traffic control department, respond efficiently in bad weather, and reduce flight delays and cancellations caused by weather.

#### Passenger
- Travel Planning: Try to avoid peak hours, routes, and airports with a high incidence of flight delays and cancellations. If you need to travel during peak hours, leave sufficient time for connecting flights and waiting at the airport, and purchase flight delay insurance.
- Information Attention: Pay attention to notifications from airlines and airports, keep informed of flight status in a timely manner. When facing flight delays or cancellations, be aware of and utilize relevant rights to safeguard your own interests.


