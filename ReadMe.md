# Determine Top Indictators Heart Disease Using Logistical Regression
Author: Tommy Phung <br>
Source: [Kaggle](https://www.kaggle.com/datasets/bhaveshmisra/heart-disease-indicators/data)

# Overview
In America, heart related death are among the highest and is a global issue. Although 50% of heart disease are caused by genetics, the other 50% are determined by the individuals lifestyle.If patients are able to determine the main factors of heart disease, many can reduce their chances to them. using the models resutls however, factors should be looked at along with any connecting relation they have with one another. Age was the highest contributing factor to the chances in having a heart related disease or attack, but that is a factor that is not controlable. To suggest to patient that they should stop aging is impratical. Age, however can effect others that may be looked at. An older patient may have more difficulty walking or the amount of income at the time. We could argue that education the older an individual is that they would have more time to have a stroke or develop these disease generiticlly. 

Instead, the information should be used to inform patients to look at their life and determine whether this would apply to them so that they could improve while they are young. General health ranks second to only age and could impform those with low heath evaluation to reconsider their health discions. Of course, nothing is certain as the model only shows likelihood and not certainy. 

# Data Exploration
There are many features from teh dataset. The different types are binary, categorical and continous nermircal values with no string valuse needed to be convert. Binary columns would need to be interpreted such as if sex was determined to be a impactful feature ie, a positive effect, that means being male would increases the chances. 

| **Column Name** | **Description** | **Markers** |
|:---:|:---:|:---:|
| HeartDiseaseorAttack: | Indicates whether the individual has had a heart disease or heart attack | (binary: 0 = No, 1 = Yes) |
| HighBP | High blood pressure status | (binary: 0 = No, 1 = Yes) |
| HighChol | High cholesterol status | (binary: 0 = No, 1 = Yes) |
| CholCheck | Frequency of cholesterol check | categorical |
| BMI | Body Mass Index | continuous |
| Smoker | Smoking status | (binary: 0 = No, 1 = Yes) |
| Stroke | History of stroke | (binary: 0 = No, 1 = Yes) |
| Diabetes | Diabetes status | (binary: 0 = No, 1 = Yes) |
| PhysActivity | Level of physical activity | categorical |
| Fruits | Frequency of fruit consumption | categorical |
| Veggies | Frequency of vegetable consumption | categorical |
| HvyAlcoholConsump | Heavy alcohol consumption status | (binary: 0 = No, 1 = Yes) |
| AnyHealthcare | Access to any healthcare | (binary: 0 = No, 1 = Yes) |
| NoDocbcCost | No doctor because of cost | (binary: 0 = No, 1 = Yes) |
| GenHlth | General health assessment | categorical |
| MentHlth | Mental health assessment | categorical |
| PhysHlth | Level of physical activity | categorical |
| DiffWalk | Difficulty walking status | binary: 0 = No, 1 = Yes |
| Sex | Gender of the individual | binary: 0 = Female, 1 = Male |
| Age | Age of the individual | continuous |
| Education | Educational level | categorical |
| Income | Income level | categorical |

Some columns are harder to dertemine such as General Health, and Diabetes where we are assume that a higher general health would be better and that the values for diabetes is the type of diabetes, 0,1,2.  

