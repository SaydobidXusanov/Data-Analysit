# Investigate a Dataset - No-show appointments
## by Saydobid Khusanov

This project includes investigating a dataset of 100k medical appointments in Brazil. The following questions were posed for analysis, and the corresponding conclusions were gained.

## Conclusions

The factors that are important for us to know in which cases patients will not visit the scheduled appointment:

#### 1. Which age and gender groups had the most number of 'No-show' cases?

The largest number of male patients who did not come to the appointment were members of the 0-20 age group. Meanwhile, the group interval was about 20-40 for the female ones. Almost the same percentages of people from both groups missed their appointments (about 20%).


#### 2. Which locations had the most number of 'No-show' cases?

The hospitals of `JARDIM CAMBURI` and `MARIA ORTIZ` had the most number of no-show patients during the given period with 1465 and 1219 cases, respectively. However, the `RESISTENCIA` hospital was the first in terms of percentages (about 26% of the patients did not show up).


#### 3. People suffering from which illness had the most number of 'No-show' cases?

The people who suffer from hypertension did not come to the appointments most of the times compared to other provided illnesses with the noticeably large difference. It was due to the fact that many people had scheduled appointments for this illness. Thus, alcoholism was number one in terms of percentages (about 20%).

#### 4. Do the appointment days have an impact on the number of 'No-show' cases?

Almost all the days had similar proportions of “no-show” cases (about 20%). Nevertheless, Thursday was the day with the fewest cases. It is worth noting almost no hospitals scheduled the appointment for Saturdays. The median number of total “no-show” cases was about 5000 over the weekdays.

### Limitations

Due to the lack of scheduled appointment hours in the dataset, it was not possible to analyse the specific parts of the days when the patients would not come.

Moreover, the location, illness and week_day based values of no-show cases were large due to the overall value counts of the dataset.

