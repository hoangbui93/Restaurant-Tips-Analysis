# 🍽️ Restaurant Tips Analysis
![Alt text](https://github.com/hoangbui93/Restaurant-Tips-Analysis/blob/main/Pic1.jpg)

## Project description
This project aims to use the restaurant tips dataset to practice creating composition plots and visualizations. We will examine the relationship between different variables and the tips given.
## Source of the data
The dataset consists of information from 244 restaurant bills, collected in the US in 1987.

It includes details about the tips given to restaurant staff, such as the total bill, tip amount, gender of the person paying, smoking status, day of the week, time of day, and party size.

You can load data from the following link:
https://raw.githubusercontent.com/RusAbk/sca_datasets/main/tips.csv

## The main goals

Analyze Tip Patterns – Identify trends in tipping behavior based on different factors like gender, smoking status, day of the week, and time of day.

Visualize Data Composition – Create various composition plots to explore the relationship between tip amount and other categorical variables.

Compare Group Behaviors – Examine how different groups (e.g., smokers vs. non-smokers, weekdays vs. weekends) differ in their tipping habits.

Practice Data Visualization – Improve skills in creating effective and insightful visual representations of data.


## Results
### 🚬 Do people who smoke give more tips?

![Alt text](https://github.com/hoangbui93/Restaurant-Tips-Analysis/blob/main/Hist1.png)

* The frequency of tip amounts for non-smokers is more concentrated in the medium range (around 2-4) compared to smokers, where tip values are more widely distributed and tend to be lower (mostly in the 1-3 range). This suggests that non-smoking customers may be more generous or consistent with tipping.

* The overall dataset shows a right-skewed distribution of tips, with most values falling between 2-6, but a few cases of very high tips (8-10). Meanwhile, the smokers' group has a thinner distribution with fewer high tips, while non-smokers have a denser distribution around medium values, along with some instances of high tips (6-9).

**General conclusion:** There is a clear difference in tipping behavior between smoking and non-smoking customers. Non-smokers tend to tip more consistently and generously, while smokers tip less and more variably. This could be related to spending habits, cultural factors, or personal preferences. Businesses may consider tailored strategies to encourage tipping based on customer groups.

### 👨👩 Do males give more tips?

![Alt text](https://github.com/hoangbui93/Restaurant-Tips-Analysis/blob/main/Hist2.png)

* Different Tip Value Distributions Across Groups: In the whole dataset and the male customer group, there appear to be two frequency peaks, one at a lower level (around 1-2) and another at a higher level (around 3-5).

* Conversely, in the female customer group, the highest frequency is concentrated at a lower level (around 2-3) and gradually decreases at higher levels, indicating a tendency to tip less and fewer high-value tips.

**General conclusion:** Tipping behavior varies significantly between male and female customers. Male customers tend to tip across a wider range of values, including larger amounts, as shown by the broader distribution and potentially multiple frequency peaks. In contrast, female customers tend to tip at lower amounts with less significant variation in tip value. This might suggest differences in spending habits or perceptions of tipping between the two genders.

### 📆 Do weekends bring more tips?

![Alt text](https://github.com/hoangbui93/Restaurant-Tips-Analysis/blob/main/Hist3.png)

* The histograms clearly show a difference in the distribution of tip values between weekdays and weekends. On weekdays, the highest frequency is concentrated at lower tip values (around 1-2), and it decreases rapidly at higher levels. In contrast, on weekends, while the highest frequency is still at the lower levels, there's a significant amount of tips at the mid-range (around 3-5), indicating that customers tend to tip more generously on weekends.

* The weekend histogram shows a more pronounced presence of higher-value tips (above 5) compared to the weekday histogram. Although the frequency isn't as high as the lower amounts, there are still noticeable bars representing significant tips, which is less evident in the weekday data. This reinforces the observation that customers tend to tip more and give larger tips on weekends.

**General conclusion:** The time of the week significantly influences customer tipping behavior. On weekends, customers tend to tip higher, with the distribution showing more tips in the mid-range and even higher values compared to weekdays. Conversely, on weekdays, the majority of customers tend to tip at lower amounts, and there are fewer high-value tips.

### 🕑 Do dinners bring more tips?

![Alt text](https://github.com/hoangbui93/Restaurant-Tips-Analysis/blob/main/Hist4.png)

* Clear Difference in Tip Distribution Between Lunch and Dinner. The histograms show a significantly higher frequency of low tips (around 1-2) during lunch compared to dinner. Conversely, the frequency of mid-range (around 3-5) and higher tips tends to be greater during dinner. This indicates that customers are inclined to tip less during lunch and more generously during dinner.

* Limitation of Large Tips During Lunch. The lunch histogram shows a sharp decline in frequency at higher tip values, with very few or no tips exceeding 6. This contrasts with the dinner and whole dataset histograms, where higher-value tips still appear (albeit with lower frequency). This suggests that receiving large tips during lunchtime is quite rare.

**General conclusion:** The mealtime has a substantial impact on customer tipping behavior. Dinner service is generally associated with higher tip amounts and a greater likelihood of receiving mid-range and higher tips compared to lunch service. Lunch service tends to receive lower tips, and large-value tips are very infrequent.
