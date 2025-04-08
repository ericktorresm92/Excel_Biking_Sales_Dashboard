# Biking Data Analysis
## Project Purpose:
This project aims to use Excel data analysis techniques as Practice to achieve the following main objectives:
1. Customer Analysis for Bicycle Sales:
Identify which types of customers are most likely to purchase a bicycle based on factors such as age, income, occupation, marital status, and commuting distance, and determine whether certain groups are more likely to purchase.
2. Market Segmentation and Marketing Strategies:
Understand which regions have higher or lower demand for bicycles, analyze whether education or marital status influences purchase, and suggest marketing strategies targeted at specific segments of the population.
3. Relationship between Transportation Habits and Bicycle Purchase:
Evaluate whether people who live closer to their work are more likely to purchase a bicycle, as well as analyze whether car ownership affects the purchase decision.
4. Impact of Socioeconomic Status on Purchase Decisions:
Explore whether income or home ownership influences the decision to purchase a bicycle and whether there is a trade-off between educational level and purchase likelihood.
## Data utilized
### Bike Buyers 1000: https://www.kaggle.com/datasets/heeraldedhia/bike-buyers

## Methods
A practice dataset containing the following columns was used:
- ID
- Marital Status
- Gender
- Income
- Children
- Education
- Occupation
- Home Owner
- Cars
- Commute Distance
- Region
- Age
- Purchased Bike

### Techniques Applied:

#### Removing Duplicates:
Duplicates were removed from the dataset, a total of 26 duplicates were removed.

#### Find and Replace:
The columns for marital status and sex (gender) were replaced; instead of a single letter, they were replaced with the entire word.

#### Creating Age Ranges:
Here, compound IF statements were used to create age ranges for further study. For example: =IF(L2>=65, "65 +", (IF(L2>=40, "40-64", IF(L2>=18, "18-39", IF(L2<=17, "Adolescent", "Other")))))

#### Creating Pivot Tables:
The following pivot tables were created:

- Average Income per Purchase:
Here, the goal is to understand whether average income affects bicycle purchases, as well as whether gender affects them.
![image](https://drive.google.com/file/d/1mvJ16VuOOtNobv_WskjBPlr07v2PrLVK/view?usp=sharing)

- Travel Distance per Client:
Here, the daily distance and how many of these clients travel these distances are studied, to see if this affected the purchase of a bicycle or not.
![image](https://drive.google.com/file/d/1lSvlUm6b5EFLol3XqT-NfzauGpyc8A7Z/view?usp=sharing)

- Age range per client:
In this table, the age range created by the IFs and the count of how many of these clients there were were taken, to determine if this affected the purchase.
![image](https://drive.google.com/file/d/1YJyfdyDkyA4Wchav6vaRtrKQHSQz_ToB/view?usp=sharing)

- Panel creation:
From the pivot tables, the following graphs were created:

- Average Income per Purchase:
![image](https://drive.google.com/file/d/155ZbCiFNV8uahYJRA4d39K_24ajU__rb/view?usp=sharing)

- Travel Distance per Client:
![image](https://drive.google.com/file/d/1fnoR8BSqO3n2SCuBhkNUDhZ5epHBItyz/view?usp=sharing)

- Age range per client:
![image](https://drive.google.com/file/d/1IhWV3ieQ86tVJnkZOXV_I8zlB69ziUHh/view?usp=sharing)

From here, the panel was created, which included the following filters:
- Marital status
- Whether the client owns a home
- Whether the client owns a vehicle
- The client's region of origin
- Their educational level.

![image](https://drive.google.com/file/d/1OgYEIoQP86eYNA1wc2pGynHXt1jmUcWl/view?usp=sharing)

## Results and conclusions
### Conclusions:
1. Relationship between Income and Bicycle Purchase
People who purchase bicycles tend to have higher average incomes compared to those who did not. We can therefore say that bicycles may be perceived more as a discretionary purchase, and people with higher incomes can afford to acquire them more easily.

2. Distribution of Purchases by Age Group
The highest number of bicycle purchases is found in the 40-64 age group, although this is also the group with the most non-purchasers, so it may be a key target for bicycle sales. Although the low purchase rate among older adults may be due to mobility, health, or preference for other modes of transportation, perhaps other types of bicycles, such as electric ones, could be added, where less effort is required.

3. Impact of Commuting Distance on Bicycle Purchase
Those living 0-1 miles away have the highest number of bicycle buyers. We see that as commuting distance increases, bicycle purchases decrease slightly, as bicycles are a preferred transportation option for short distances, possibly because they are more convenient and cost-effective for short trips.

### Potential Data-Based Recommendations
1. Market Segmentation:
Focus marketing strategies on people aged 40-64 with higher incomes.
Perhaps offer discounts or payment options for young people (18-39 years old) to encourage their purchase.
2. Location-Based Promotion:
Promote bicycles in urban areas with short commutes.
For long distances, offer electric bicycles or more comfortable models.
3. Product Differentiation:
Design campaigns focused on recreational or health cycling to attract customers in the 65+ age group.
Focus on more affordable bicycle models for short urban commutes.
