# mcdonalds_dataset_challenge

This is the result of a challenge for EDA-ing the McDonalds Menu Dataset, which available in Kaggle. I do this as part of online scholarship training program called Digitalent, specifically the Data Scientist Program. The challenge is quite simple. There are 5 questions pertaining the dataset, and you need to answer it using analytical skills and data science tools.

However, the challenge is not actually homogenous at all. There are several ways interpreting the questions, thus every team probably have their own interpretaions. What I post here is my team's interpretations. The questions are:

## 1. How many calories does the average McDonald's value meal contain?
This question is pretty simple. However some team interpret it differently. The question ask 'meal', so they did not include beverages. My team stick with the simplest interpretation.

## 2. How much do beverages, like soda or coffee, contribute to the overall caloric intake? 
This one is also pretty simple. The main dataset, "menu.csv", already have column called category.

## 3. Does ordered grilled chicken instead of crispy increase a sandwich's nutritional value? 
## 4. What about ordering egg whites instead of whole eggs? 
This 2 questions actually similar. If you can answer one, you'll probably can answer the other.

## 5. What is the least number of items could you order from the menu to meet one day's nutritional requirements?
This question have the most interpretations. My team interpret it as the minimum amount for each of the item to fulfill someone daily needs. For example, for item sandwich, you need to eat it 7 times (not actual result of the algorithm). There are other way to solve it. For example, you need to calculate average calories needed for someone, and build meal plan based on the items in the dataset. Overall, I still think our team's approach is more inline with computer science way.

For further info about the dataset, visit this [link](https://www.kaggle.com/mcdonalds/nutrition-facts)
