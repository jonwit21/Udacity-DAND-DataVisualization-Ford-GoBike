## Data Visualization - Ford GoBike 2019 (Bike Sharing)

### Dataset



The dataset, 201902-fordgobike-tripdata.csv, was obtaned from Ford GoBike and licensed by Ford GoBike. This dataset includes 15340 trips with 24 features such as duration, user type, and weekday. There are start and end stations. I observed that majority of trips took place at the same stations, so I subset the dataset by choosing top 5 trips start stations with the most trips. Thus, the following analysis is performed by this subsetted dataset.



### Summary of Findings

1. Univariate exploration: I observed that during the day, there are more trips in the morning and afternoon than the night. In addition to this, I notices that there most trips takes place during the weekdays and less trips during the weekends. It makes sense that there are more subscribers than customers. For the gender groups, the number of trips in male riders is about 3 times more than the number of trips in females. It needs to be investigated more. Most of riders are 30 to 40 years old and the duration of trips is around 650 seconds.
<br></br>
2. Bivariate exploration: there is a a little bit of a negative correlation between age and duration of trips. After separation the top 8 stations, half of stations have the most trips in the morning and another half of stations has the most trips in the afternoon. Weekdays have the most trips than weekends.
<br></br>
3. Multivariate exploration: Segregating user types, customers and subscribers, affords more insights. Customers prefer to ride during the weekend. On the other hand, the trips in subscribers increase during the weekdays and after launching, the number of trips gradually increases and then decreases when the weather becomes colder. Moreover, customers ride longer than subscribers.

### Key Insights

User types perform a crucial role on the number of trips in each location and time group. For customers, there are more trips in the weekends. They also have longer trips. On the other hand, for subscribers, there are more trips during the weekends. Thus, collecting more information individually from these two user types is important for the future analysis.


```python

```
