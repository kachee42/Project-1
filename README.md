# Covid-19 Analysis

This project pulls from the [Covid-19 API](https://covid19api.com/) and analyses information from all counties across California and cross-chekcs with the US Census API for the year of 2021. This project analyses whether lower median income results in higher death rates across counties and whether minority populations are impacted more severely by Covid than non-minority populations.

# Hypotheses for Project

- Counties with higher population density will have more deaths per 100,000 people.

- Counties with lower median income will have more deaths?

- Counties with a higher percentage of racial minorities will have more deaths per 100,000?

- Vaccinated people will have fewer cases and deaths than unvaccinated people?

# COVID-19 and US Census Data

<img width="623" alt="image" src="https://user-images.githubusercontent.com/115186079/218022674-829f2f58-9885-463d-978d-9596a050b370.png">


# Cleaning Data

<img width="874" alt="image" src="https://user-images.githubusercontent.com/115186079/218014757-c0233741-a986-4b81-bd28-31d39dc5a872.png">



# Data Analysis and Graphs

***Did counties with lower median income have more deaths?*** 

- No, there was no correlation between lower median income and deaths. The linear regression r value was 0.01095 indicating a very weak correlation


<img width="869" alt="image" src="https://user-images.githubusercontent.com/115186079/218016514-b3bbd099-769e-4846-9045-5bcfcfb690a3.png">


***Did counties with a higher percentage of racial minorities have more deaths per 100,000?***

- Counties with a higher minority population had higher death rates per 100,000. The p-value 0.0074 indicates a significant correlation.


<img width="383" alt="image" src="https://user-images.githubusercontent.com/115186079/218017131-5caea991-548d-4541-8ea0-59240e93523a.png">


***Did vaccinated people have fewer COVID cases and deaths than unvaccinated people?***

- Vaccinated people had fewer cases and deaths than unvaccinated people. Unvaccinated people accounted for 70% of cases and deaths, where vaccinated people accounted for 9% to 16%


<img width="560" alt="image" src="https://user-images.githubusercontent.com/115186079/218018961-fc5c2ed6-25cd-4fc4-a44a-0dead049677b.png">


***Counties with higher population density will have more deaths per 100,000 people?*** 

- Populations with higher density did not have more deaths. The p-value was 0.140 indicating no significant correlation.


![image](https://user-images.githubusercontent.com/118322354/217722335-cd128f73-51de-492c-9bfa-e09ec83adfd0.png)




