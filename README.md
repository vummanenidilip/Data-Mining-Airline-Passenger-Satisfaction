# Data-Mining-Airline-Passenger-Satisfaction

**About the Dataset**
This dataset contains an airline passenger satisfaction survey. The dataset contains 25 unique characteristics derived from a passenger satisfaction survey of more than 100,000 people. These characteristics give useful insights into passengers' thoughts and ratings of numerous elements of their flying experiences. The variable that we will be predicting is customer satisfaction whether he is “satisfied” or “neutral or unsatisfied”. We are using second-hand data. The data we have collected is sourced from Kaggle and the link provided below.
kaggle link: https://www.kaggle.com/datasets/teejmahal20/airline-passenger-satisfaction.

The attributes and their description are -
1.	Number of the passengers.
2.	ID: ID of the Passenger
3.	Gender: Gender of the passengers (Male or Female)
4.	Customer Type: The customer type as per loyalty and behavior.
•	Loyal Customer
•	Disloyal Customer
6.	Age: The actual age of the passengers.
•	In Range
7.	Type of Travel: Purpose of the flight of the passengers
•	Personal Travel
•	Business Travel
8.	Class: Travel class in the plane of the passengers
•	Eco: Economy Class
•	Eco Plus: Premium Economy Class
•	Business: Business Class
9.	Flight distance: The flight distance of this journey (in miles).
10.	Inflight Wi-Fi service: Satisfaction level of the inflight Wi-Fi service.
•	0: Not Applicable
•	General Rating: 1-5
11.	Departure/Arrival time convenient: Satisfaction level of Departure/Arrival time convenient.
•	0: Not Applicable
•	General Rating: 1-5
12.	Ease of Online booking: Satisfaction level of online booking.
•	0: Not Applicable
•	General Rating: 1-5
13.	Gate location: Satisfaction level of Gate location
•	0: Not Applicable
•	General Rating: 1-5
14.	Food and drink: Satisfaction level of Food and drink
•	0: Not Applicable
•	General Rating: 1-5
15.	Online boarding: Satisfaction level of online boarding
•	0: Not Applicable
•	General Rating: 1-5
16.	Seat comfort: Satisfaction level of Seat comfort
•	0: Not Applicable
•	General Rating: 1-5
17.	Inflight entertainment: Satisfaction level of inflight entertainment
•	0: Not Applicable
•	General Rating: 1-5
18.	On-board service: Satisfaction level of On-board service
•	0: Not Applicable
•	General Rating: 1-5
19.	Leg room service: Satisfaction level of Leg room service
•	0: Not Applicable
•	General Rating: 1-5
20.	Baggage handling: Satisfaction level of baggage handling
•	0: Not Applicable
•	General Rating: 1-5
21.	Check-in service: Satisfaction level of Check-in service
•	0: Not Applicable
•	General Rating: 1-5
22.	Inflight service: Satisfaction level of inflight service
•	0: Not Applicable
•	General Rating: 1-5
23.	Cleanliness: Satisfaction level of Cleanliness.
•	0: Not Applicable
•	General Rating: 1-5
24.	Departure Delay in Minutes: Minutes delayed when departure.
•	In Continuous Range (Minutes)
25.	Arrival Delay in Minutes: Minutes delayed when Arrival.
•	In Continuous Range (Minutes)
26.	Satisfaction: Airline satisfaction level (Prediction Target)
•	Satisfaction (1): Overall satisfied with the services.
•	Neutral or Dissatisfaction (0): Overall unsatisfied with the services


**Executive Summary**
The goal of this study was to implement predictive modeling approaches to improve our understanding of airline passenger satisfaction. The dataset contains 25 unique characteristics derived from a passenger satisfaction survey of more than 100,000 people. These characteristics give useful insights into passengers' thoughts and ratings of numerous elements of their flying experiences. The variable that we will be predicting is customer satisfaction whether he is “satisfied” or “neutral or unsatisfied”.
We employed multiple predictive modeling techniques including Logistic regression, Decision Trees, Random Forest, Neural Networks and we found out the most accurate predictive model among these four. We also repeated the same models on principal component analysis
(Dimensionality reduction). 


![image](https://github.com/vummanenidilip/Data-Mining-Airline-Passenger-Satisfaction/assets/44915745/a829b7a3-9d91-4c19-be12-f7649518eae9)

Based on Model fit statistics of the validation data the Misclassification rate and Average Squared error of the random forest model (HPDM Forest) was low when compared to the other models, which implies it has high accuracy rate while predicting the airline passenger satisfaction followed by Decision tree 3-way, PCA Random Forest, Neural Network, Decision Tree(2-way), PCA Neural Network,  PCA Decision Tree(3-way), PCA Decision Tree, Logistic Regression (with significant predictors), Logistic Regression, PCA Logistic Regression.

![image](https://github.com/vummanenidilip/Data-Mining-Airline-Passenger-Satisfaction/assets/44915745/1f71e36b-7fe9-45fc-99b2-bae3c3b3dcf3)

Based on the data we can say that almost 57% of the passengers who participated in the survey were neutral or dissatisfied with the services, the remaining 43% of passengers were satisfied with the services. The airline should focus, improve services and take precautions that can work towards improving customer satisfaction and ensuring a positive experience for passengers.


![image](https://github.com/vummanenidilip/Data-Mining-Airline-Passenger-Satisfaction/assets/44915745/7aade319-a697-4ab2-a66f-fc90b1e49231)

**Project Motivation/background**
This research on airline passenger satisfaction was started because it is understood to be crucial to the success and long-term viability of the airline sector. In the highly competitive airline industry, consumer loyalty, brand perception, and overall business performance are all strongly impacted by passenger happiness. The inspiration and context of this project are explained by the following factors:

**Customer Experience Improvement: **Understanding and predicting passenger satisfaction is crucial for airlines to enhance the overall customer experience. By analyzing the factors that contribute to satisfaction or dissatisfaction, airlines can make informed decisions to improve services and address pain points.

**	Business Competitiveness:** In the highly competitive airline industry, customer satisfaction plays a significant role in attracting and retaining customers. Airlines that consistently provide a positive experience are more likely to gain customer loyalty, repeat business, and positive word-of-mouth recommendations.

**Operational Efficiency:** Analyzing passenger satisfaction can uncover insights into specific areas of the airline's operations that may need improvement. This includes services such as online booking, inflight entertainment, seat comfort, and more. Identifying and addressing inefficiencies can lead to smoother operations and increased satisfaction.

**Revenue Generation:** Satisfied customers are more likely to become repeat customers and advocates for the airline. This can contribute to increased revenue through repeat business and positive referrals. On the other hand, dissatisfied customers may choose competing airlines for future travel, leading to potential revenue loss.

**Brand Reputation: **Customer satisfaction directly impacts on the reputation of an airline. Positive experiences contribute to a positive brand image, while negative experiences can harm the brand's reputation. Maintaining a high level of satisfaction is essential for building and sustaining a positive brand perception.

**Data-Driven Decision-Making:** The project provides an opportunity to apply data mining and machine learning techniques to analyze patterns and trends in customer satisfaction. This approach allows for data-driven decision-making, enabling the airline to tailor its services to meet customer expectations and preferences.

**Predictive Analytics for Satisfaction:** By building a predictive model for airline satisfaction, the project aims to provide the airline with a tool to forecast passenger satisfaction levels based on various attributes. This predictive capability can be valuable for proactively addressing potential issues and optimizing services.

**Data Description**
The dataset contains 25 attributes derived from a passenger satisfaction survey of more than 100,000 people. These characteristics give useful insights into passengers’ thoughts and ratings of numerous elements of their flying experiences. The variable that we will be predicting is customer satisfaction whether he is “satisfied” or “neutral or unsatisfied”. The data set contains categorical variables which are nominal and numerical variables which are interval. The levels and roles of data are set as shown in the below snippet. The target variable “satisfaction” is nominal data.

![image](https://github.com/vummanenidilip/Data-Mining-Airline-Passenger-Satisfaction/assets/44915745/da213644-089a-4dc8-90e6-7fa269f97179)

The summary statistics of the class variable (Nominal data):

![image](https://github.com/vummanenidilip/Data-Mining-Airline-Passenger-Satisfaction/assets/44915745/6f74dde2-b924-405c-9428-7ad2781d639b)

The summary statistics of the Numerical variables (Interval data):

![image](https://github.com/vummanenidilip/Data-Mining-Airline-Passenger-Satisfaction/assets/44915745/5f8e8cb9-d52f-4ad3-ad30-7b917de4be4a)

**Data Preparation Activities
The process of preparing data was essential to guaranteeing the accuracy and effectiveness of later modeling initiatives. During this stage, extreme caution was needed when handling non-normal distributions, outliers, and missing numbers. Robust predictive modeling is made possible by the deliberate choice to keep outliers and the openness with which missing values are reported.
**Handling Missing Values: ** From the above summary statistics, there were 306 values missing for Arrival_delay_in_minutes variable in the dataset. Depending on the amount and kind of missing data, alternate approaches to handle missing values could include imputation. Here, imputing minimum is the method of choice because if there is any delay in the arrival, the customer would have mentioned since they are not mentioned we imputed it to minimum which is 0.

<img width="373" alt="image" src="https://github.com/vummanenidilip/Data-Mining-Airline-Passenger-Satisfaction/assets/44915745/cbf1297a-a6db-4607-81c3-80b6086cfff3">

**Addressing Outliers: Critical variables such as "Departure_Delay_in Minutes," "Arrival Delay_in Minutes," and "Flight Distance" were found to have outliers, which were discovered by distribution analysis. In contrast to standard procedure, these outliers were purposefully kept since we utilize this data, and these data has some information which is important to predict passenger satisfaction.

<img width="461" alt="image" src="https://github.com/vummanenidilip/Data-Mining-Airline-Passenger-Satisfaction/assets/44915745/2cfe01a5-70a1-4e3f-a93a-ff23186684f6">

**Data Partition:** For evaluating the models we have distributed the data into Train (60%), Valid(20%), Test(20%). 

**Models Used**
During the project's modeling phase, four different methodologies were used, each selected for its ability to capture certain facets of the intricate relationships found in the data. Logistic Regression, Decision trees, Random forests, and Neural networks were the models used, displaying a variety of algorithmic methods to predictive modeling and also, I have also constructed the same models after doing the principal component analysis.

**Logistic regression:** A traditional statistical model for binary classification is logistic regression. Because it represents the likelihood of a binary result, it can be applied to situations in which the dependent variable is categorical. To capture linear correlations between the input variables and the binary result associated with passenger satisfaction, logistic regression was incorporated. It is an important baseline model because of its simplicity and interpretability.

**Decision Tree:** Robust models known as decision trees generate a tree-like framework for decision-making by analyzing input information. They are interpretable by nature and can capture complex decision boundaries. Using decision trees, complex patterns and principles of decision-making were found in the data, providing insights into the hierarchical linkages between factors and how they affect passenger pleasure.

**Random Forest:** An ensemble learning technique called Random Forest creates many decision trees during training and outputs the class mode for classification problems. Each tree predicts the target variable using a random subset of the available predictors each tree uses a random. It is excellent at managing intricate data connections and increasing forecast accuracy. 

**Neural Network:** Neural networks are made up of interconnected nodes arranged into layers and are modeled after the structure of the human brain. They are renowned for their ability to use sophisticated non-linear transformations to extract complicated patterns from data. Artificial neural networks, also known as neural networks (ANNs), were utilized because of their ability to identify complex patterns and relationships in the dataset. They are appropriate for collecting subtle features influencing passenger satisfaction because of their flexibility in non-linear interactions.

Findings:
Exploring and analyzing multiple prediction models, the project's findings provide important insights into airline passenger satisfaction. Below is a summary of the main findings and their implications:
The chi-square plot shows class variable has very high chi square value

![image](https://github.com/vummanenidilip/Data-Mining-Airline-Passenger-Satisfaction/assets/44915745/72f718d8-cad8-40b9-90fd-a95d10d6eee1)

The variable worth plot shows online_boarding variable has importance followed by inflight_wifi_service and others. 
![image](https://github.com/vummanenidilip/Data-Mining-Airline-Passenger-Satisfaction/assets/44915745/1b7ebabb-5715-4634-b49d-3d328e621ec9)

**Logistic Regression: **
Firstly, we have created a simple logistic regression model the we found that the model is significant (Pr <0.001) the predictor flight distance was insignificant. the average square error was 0.1, Misclassification rate is 0.12.

<img width="520" alt="image" src="https://github.com/vummanenidilip/Data-Mining-Airline-Passenger-Satisfaction/assets/44915745/8230e8fa-5b76-4682-b446-9e9f739c07f4">

<img width="350" alt="image" src="https://github.com/vummanenidilip/Data-Mining-Airline-Passenger-Satisfaction/assets/44915745/7b543b7a-ede0-4cab-bad7-b7e04f6df7d2">


Secondly, we have created a logistic regression model rejecting the flight distance since it is insignificant, we found that the model is significant (Pr <0.001). the average square error and , Misclassification rate was same.

<img width="528" alt="image" src="https://github.com/vummanenidilip/Data-Mining-Airline-Passenger-Satisfaction/assets/44915745/9c515a71-f4dc-40a4-b487-3c572efb23f0">

Thirdly, we have created a logistic regression model after performing Principal Component analysis (PCA) at eigne cutoff value of 0.85 we found that the model is significant (Pr <0.001). the average square error was 0.1 and, Misclassification rate was 0.13.

<img width="518" alt="image" src="https://github.com/vummanenidilip/Data-Mining-Airline-Passenger-Satisfaction/assets/44915745/ba7ee5d0-06cd-4432-af66-6915737c49d3">
<img width="332" alt="image" src="https://github.com/vummanenidilip/Data-Mining-Airline-Passenger-Satisfaction/assets/44915745/d715a149-f584-478e-8f6a-ac40be078e63">

**Decision Tress:**
Firstly, we have created 2-way Decision Tree model there 25 leaves in the optimal tree and it has the average square error was 0.06 and, Misclassification rate was 0.08.
![image](https://github.com/vummanenidilip/Data-Mining-Airline-Passenger-Satisfaction/assets/44915745/fe075579-9f11-479b-a5db-6f2e61a8552d)
![image](https://github.com/vummanenidilip/Data-Mining-Airline-Passenger-Satisfaction/assets/44915745/9e23f20c-591c-42ef-bb72-60661d3253b9)
![image](https://github.com/vummanenidilip/Data-Mining-Airline-Passenger-Satisfaction/assets/44915745/427967b9-f7bb-4af2-a586-2c4faca5fed4)

Secondly, we have created 3-way Decision Tree model there are 80 leaves in the optimal tree and it has the average square error was 0.05 and, Misclassification rate was 0.06.
![image](https://github.com/vummanenidilip/Data-Mining-Airline-Passenger-Satisfaction/assets/44915745/70696263-1726-47a5-a12b-4007a711701e)

![image](https://github.com/vummanenidilip/Data-Mining-Airline-Passenger-Satisfaction/assets/44915745/9974de13-267f-4266-8016-4a44ca4f9ff0)

![image](https://github.com/vummanenidilip/Data-Mining-Airline-Passenger-Satisfaction/assets/44915745/072e98f8-2700-4b98-846c-bc6616c04cb7)

Thirdly, we have created the 2-way Decision Tree model after performing Principal Component analysis (PCA) at eigne cutoff value of 0.85 there 40 leaves in the optimal tree and it has the average square error was 0.09 and, Misclassification rate was 0.12.
![image](https://github.com/vummanenidilip/Data-Mining-Airline-Passenger-Satisfaction/assets/44915745/33e34f95-a272-4cf5-824a-43447525eec4)

![image](https://github.com/vummanenidilip/Data-Mining-Airline-Passenger-Satisfaction/assets/44915745/d6d0fe68-c600-4e7e-8716-5aa8bfd44a11)

![image](https://github.com/vummanenidilip/Data-Mining-Airline-Passenger-Satisfaction/assets/44915745/df6dd5e0-1cca-4f6a-be64-7de5e9ab36c9)

Fourthly, we have created the 3-way Decision Tree model after performing Principal Component analysis (PCA) at eigne cutoff value of 0.85 there 125 leaves in the optimal tree and it has the average square error was 0.08 and, Misclassification rate was 0.10.

![image](https://github.com/vummanenidilip/Data-Mining-Airline-Passenger-Satisfaction/assets/44915745/3a4c3b98-4038-478a-ba85-3221520ef7a1)

![image](https://github.com/vummanenidilip/Data-Mining-Airline-Passenger-Satisfaction/assets/44915745/00c98fe4-daf3-451c-9739-e1196e0dfeeb)

![image](https://github.com/vummanenidilip/Data-Mining-Airline-Passenger-Satisfaction/assets/44915745/c6bc6a9e-3111-4dc4-a992-77bbbef3ff83)

**Random Forest:**
Firstly, we have created Random Forest model, it has the average square error was 0.03 and, Misclassification rate was 0.04.

![image](https://github.com/vummanenidilip/Data-Mining-Airline-Passenger-Satisfaction/assets/44915745/58beeffa-8d2d-4e18-8258-7f0fedec0e1c)

Secondly, we have created Random Forest model, after performing Principal Component analysis (PCA) at eigne cutoff value of 0.85 it has the average square error was 0.05 and, Misclassification rate was 0.07.

![image](https://github.com/vummanenidilip/Data-Mining-Airline-Passenger-Satisfaction/assets/44915745/a674995e-1c7c-40b7-acfe-ad939a48f2d9)

**Neural Networks:**
Firstly, we have created Neural Networks model, there were 50 iterations it has the average square error was 0.05 and, Misclassification rate was 0.07.

![image](https://github.com/vummanenidilip/Data-Mining-Airline-Passenger-Satisfaction/assets/44915745/34c9d3d2-4aa1-4bf3-8c0c-27c12856f14f)

![image](https://github.com/vummanenidilip/Data-Mining-Airline-Passenger-Satisfaction/assets/44915745/21d80240-1630-4656-8ae4-b651a627582a)

Secondly, we have created Neural Networks model, there were 23 iterations it has the average square error was 0.06 and, Misclassification rate was 0.08.

![image](https://github.com/vummanenidilip/Data-Mining-Airline-Passenger-Satisfaction/assets/44915745/785c9d29-af27-43b9-8a1f-43da0a47e1ec)

![image](https://github.com/vummanenidilip/Data-Mining-Airline-Passenger-Satisfaction/assets/44915745/c9ddcd22-fb96-4e60-bad0-9f04b63a4282)

Comparing all the models for validation data the Misclassification rate and Average Squared error of the random forest model (HPDM Forest) was low when compared to the other models, which implies it has high accuracy rate while predicting the airline passenger satisfaction followed by Decision tree 3-way, PCA Random Forest, Neural Network, Decision Tree(2-way), PCA Neural Network,  PCA Decision Tree(3-way), PCA Decision Tree, Logistic Regression (with significant predictors), Logistic Regression, PCA Logistic Regression.

![image](https://github.com/vummanenidilip/Data-Mining-Airline-Passenger-Satisfaction/assets/44915745/90912b0c-f9ca-4661-85c8-d76dc4b3e214)

**Managerial/ Business Implications**
Based on the findings from the predictive models and the overall analysis of airline passenger satisfaction. The actionable business takeaways that should be considered by airline:

**Focus on Key Satisfaction Drivers:** According to the models, features like online boarding, inflight Wi-Fi service, and others play a crucial role. Allocate resources and efforts to enhance these specific aspects of the flying experience.

**Address Flight Distance Concerns:** The logistic regression model identified flight distance as an insignificant predictor. Evaluate whether there are specific issues related to longer flight distances that may be affecting satisfaction. Consider customer feedback and take appropriate measures to address any concerns related to long-haul flights.

**Strategic Operational Improvements: **The operational aspects highlighted by the models, such as departure delay, arrival delay, and flight distance. Implement strategies to minimize delays and optimize flight schedules. Operational efficiency improvements can contribute to a more positive passenger experience.

**Invest in Staff Training:** On-board service, cleanliness, and other factors related to staff performance contribute to passenger satisfaction. Invest in training programs for airline staff to ensure high-quality service, cleanliness, and overall professionalism.

**Utilize Random Forest Model for Predictions:** The Random Forest model demonstrated the highest accuracy in predicting passenger satisfaction. Therefore, the airline should consider deploying this model for real-time predictions and monitoring customer satisfaction. This can enable proactive measures to address potential issues and enhance the overall flying experience.

**Continuous Monitoring and Feedback Loop:** Establish a continuous monitoring system for passenger satisfaction using the predictive models. Implement a feedback loop that collects real-time data on customer experiences. Use this information to adapt strategies, address emerging issues, and consistently improve services.

By implementing these specific steps, the airline can work towards enhancing customer satisfaction, building a positive brand image, and maintaining a competitive edge in the airline industry. Regularly monitoring customer feedback and adapting strategies based on predictive models will contribute to long-term success and customer loyalty.

**Conclusion:**

**Best Predictive Model:** Among logistic regression, decision trees, random forests, and neural networks, the Random Forest model demonstrated the highest accuracy in predicting passenger satisfaction, making it the recommended choice for real-time predictions and monitoring.

**Key Areas for Improvement:** Focus on enhancing online boarding and in-flight Wi-Fi services, as these were identified as crucial factors contributing to passenger satisfaction. Evaluate and address concerns related to longer flight distances and consider operational improvements to minimize delays.

**Continuous Monitoring and Staff Training:** Implement a continuous monitoring system using predictive models to collect real-time data on customer experiences, enabling proactive measures. Invest in staff training programs to improve on-board service, cleanliness, and overall professionalism, positively impacting passenger satisfaction.











































