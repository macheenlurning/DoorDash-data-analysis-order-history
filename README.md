# Machine Learning and DoorDash - Can ML Predict My Next Food Craving?

### Below you will find a basic description of the project and the process we take to cross the finish line. As a new Data Analytics student, this project will be another step toward achieving my personal goal of becoming a Value-Driven Data Scientist.

## Defining the Process
* Project Description
* Current Limitations
* Goals
* Data Sourcing Methods
* Understanding the Data
* Preparing the Data
* Modeling
* Final Evaluation and Analysis


### Project Description
DoorDash is a convenient tool that allows mobile and desktop users the ability to order just about anything from their favorite restaurants. During the COVID-19 outbreak, we've watched ecommerce and door-to-door delivery service companies explode. The "Stay At Home" movement allows DoorDash users the ability to have a restaurant worthy meal delivered at their doorstep within the hour. For me, DoorDash was always a matter of saving precious time, that when I'm in a flow state, is extremely convenient.

My initial thought was to see if we can create a program that will accurately predict what I would like to order from DoorDash on any given day. I'm still not sure whether or not we have enough data to support the end result, however, this project will be interesting regardless.


### Current Limitations:
- Personal Knowledge of Machine Learning program design: as a new student, given my own limited knowledge on machine learning and the capabilities of one man to build such a program, I'm not entirely sure this is even possible. This limitation should dissipate as we progress through the project.
- Is the goal Prediction? or Persuasion? I will have to further determine whether or not our program should accurately "predict" what I am already planning on ordering, or if it will simply give me suggestions of what to order. In the first scenario, I may have to backtest this by ordering DoorDash for a few weeks and then use the model to see if my recent Order History matches the machine's predictions. In the second scenario, will these machine learning suggestions end up being sub-conscious persuasions? Or an accurate model for predicting what my stomach is thinking? Maybe both?
- My limited knowledge of web scraping: DoorDash does not provide your order history in a downloadable format....trust me I tried for three days begging customer service. This means we will have to scrape the website for the data, which may not even be possible. Or I will have to do what our forefathers did: roll up those sleeves and get it done.
- Mentally I'm planning for about 3 weeks worth of work on this project, but out of sheer noobieness I simply have no way to gauge how long said program will take to build. I'm prepared to do whatever it takes to complete the project, even if I end up hitting the self-destruct button to save humanity from a potentially weaponized DoorDash AI.


### Goals
The main goal of this project is self-educational: to collect and analyze personal data that has not been evaluated before, implement a machine learning model, and build a simple wrapper around the program in something like flask or django. This project will be a crucial step in achieving my long term goal of becoming a data scientist.


### Data Sourcing Methods
After logging in to my profile through DoorDash.com, we navigate to the "Orders" tab to find my complete order history. 

There is a small button at the bottom of the limited history view that says "Load More Deliveries." After clicking this button for what felt like eons we arrived at the very first DoorDash order I placed on December 23, 2018. I remember that day like it was yesterday, a delicious red clam pie from Delorenzo's Tomato Pies. My guestimate is there will be somewhere around 100 total orders from that day almost 21 months ago.

To acquire this data I've determined that web scraping will only take me too long. So I will be entering in the information into a Microsoft Excel file. See you next year!


### Understanding the Data
This section includes:
* Describing the data
* Exploring the data
* Data cleaning




### Preparing the Data

This section may include:
* Importing 
* New Variable Assignments
* Splitting Data for Testing / Holdout


### Modeling 

This section will include the predictive modeling we used to achieve the desired business goals.


### Evaluation and Analysis

This section will include the final analysis of our outcome.