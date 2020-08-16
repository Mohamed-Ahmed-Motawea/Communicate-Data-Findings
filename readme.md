## Bay Wheels Ride Data Exploration and Explanation
### Dataset
Bay Wheels (previously known as Ford GoBike) is a regional public bike sharing system . Bay Wheels is the first regional and large-scale bicycle sharing system deployed in California and on the West Coast of the United States with nearly 500,000 rides since the launch in 2017 . The dataset used for this exploratory analysis consists of monthly individual trip data from Mars 2020 to April 2020 in CSV format covering the greater San Francisco Bay area, also available here [link](https://s3.amazonaws.com/baywheels-data/202003-baywheels-tripdata.csv.zip)

#### Data wrangling :
1. importing libraries like ( numpy , pandas , matplotlib , seaborn ).
2. importing dataset (202003-baywheels-tripdata.csv) .
3. Explore the first look of dataset and identify it .

#### Data Cleaning :
1. Check Duplicates values.
2. Check missing values.
3. Dropping unuseful columns.
4. Drop missing values .
5. Fix datatypes.

### Summary of Findings
There are a lot of subscriber usage than customers.
The number of trips peaked around 8am-8pm specially at 5pm during a day, there were more trips on work days (Mon-Fri) compared to weekends.

Subscribers use the bike for work so most trips were on work days (Mon-Fri) and specially during rush hours (when going to work in the morning and getting off work in the afternoon).

customers use bikes for fun in the afternoon or early evenings over weekends.
Subscriber are older than customer users who tend to take longer rides overall


### Key Insights for Presentation
Different usage between the two type of riders are seen from the exploration. 
Subscribers use the system on work days .
Monday through Friday whereas customers ride a lot on weekends, specially  in the afternoon.
Many trips concentrated around 8-9am and 17-18pm on work days for subscribers.
customers use more in the late afternoon around 17pm Monday to Friday.
The usage for subscribers concentrated to their high concentration on rush hours Monday through Friday.
customer use of the bike sharing system different from the subscribers, specially   weekends and in the afternoon.