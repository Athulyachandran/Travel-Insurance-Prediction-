# Travel-Insurance-Prediction-
#### Introduction
###### Context
A Tour & Travels Company Is Offering Travel Insurance Package To Their Customers. The Company Requires To Know The Which Customers Would Be Interested To Buy It Based On Its Database History. The Insurance Was Offered To Some Of The Customers In 2019 The Given Data Has Been Extracted From The Performance/Sales Of The Package During That Period. The Data Is Provided For Almost 2000 Of Its Previous Customers And You Are Required To Build An Intelligent Model That Can Predict If The Customer Will Be Interested To Buy The Travel Insurance Package Based On Certain Parameters Given Below. Image Credits-Unsplash(free to use)

###### Inspiration
The Solution Offered By You May Be Used For Customer Specific Advertising Of The Package. Exploratory Data Analysis Performed On The Data Would Help Find Interesting Insights. Predict Whether A Given Customer Would Like To Buy The Insurance Package, Once The Corona Lockdown Ends And Travelling Resumes. Your Work Could Probably Help Save Thousands Of Rupees Of A Family.

###### Gyaps In Existing System
There are less analysis based on the dataset
Properly not identified which is the factor that make people to not buy the insurance
Only 2 model is used to predict the customers interest,may be there is more suitable model is there than they considered
Not proper solution is given for current facing problem
The questions we want to answer are:
What kind of people are interested to purchase insurance?
Why is that group interested in the service?
If the insurance company to gain more customers, what should we change make them more inclined to make a purchase?

#### Features description
Age- Age Of The Customer

Employment Type- The Sector In Which Customer Is Employed

GraduateOrNot- Whether The Customer Is College Graduate Or Not

AnnualIncome- The Yearly Income Of The Customer In Indian Rupees[Rounded To Nearest 50 Thousand Rupees]

FamilyMembers- Number Of Members In Customer's Family

ChronicDisease- Whether The Customer Suffers From Any Major Disease Or Conditions Like Diabetes/High BP or Asthama,etc.

FrequentFlyer- Derived Data Based On Customer's History Of Booking Air Tickets On Atleast 4 Different Instances In The Last 2 Years[2017-2019].

EverTravelledAbroad- Has The Customer Ever Travelled To A Foreign Country[Not Necessarily Using The Company's Services]

TravelInsurance- Did The Customer Buy Travel Insurance Package During Introductory Offering Held In The Year 2019.


#### Data Analysis
Taking the sample or patiens done some surgery and identifying no.of people having risk after surgery and patient dont have any risk.

considering loot of features like pain,dyspnoea,cough etc in before and after surgery.

By checking the details and done basic analysis and plotted graph for beter understanding

Decision tree is ploted for better understanding,it is a grapphical representation for all possible solution The model giving 78 percentage accuracy

#### Tools used
Pandas library
Pandas makes it simple to do many of the time consuming, repetitive tasks associated with working with data, including:
Data cleansing.
Data fill.
Data normalization.
Merges and joins.
Data visualization.
Statistical analysis.
Data inspection.
Loading and saving data.
Numpy
NumPy is a Python library used for working with arrays.
It also has functions for working in domain of linear algebra, fourier transform, and matrices.
Matplotlib
Matplotlib is a comprehensive library for creating static, animated, and interactive visualizations in Python.
Matplotlib makes easy things easy and hard things possible.
Create publication quality plots. Make interactive figures that can zoom, pan, update.
Seaborn
Seaborn is a Python data visualization library based on matplotlib.
It provides a high-level interface for drawing attractive and informative statistical graphics.
Data Analysis
EDA analysis on sample that taken by tarel insurance company.Different analysis done based on descriptic and statistical analysis
Different graphical representation to fetching accurate information
Model applied to predict accuracy of the model

#### model used
Decision Tree
Random Forest
KNN
SVM
Logistic Regression


#### conclusion
Private sector people are more purchased travel insurance

people are earned maximum on their 20 's

Those who have above average income they are intrested to by travel insurance

The conclusion here is easy to make,from the above analysis we can find the the interest around the insurance is based on budget.

As from the data it clearly shows that the insurance package of this company taken by above average income people those who are working in private sector

may this is the main problem that company dont get the expected customers

Lower income people belongs to goverment sector,and actually they need not to travel abroad if needed that may be handled by the company itself

Lower income --> less travel --> if travel would happen, there is a higher chance of it being work-related and then the insurance might be covered by the government.

So we can finalize that govermnt sector also purchase the insurance the trvalinsurance company can reach up to there mark

For that the EDA can tell the company need to put a new offer, with a more appropriate price, to people who work in the government sector, are between 26-34 and don't move around a lot.if they allow holiday insurance,family travel insurance so that they will also took insurance

instead of large travel package a smaller insurance package for casual travel or a coupon for the first timers would make more customers to the company

some people not purchased beause the are not aware about travel insurance package so

proper information with limited actractive sentance make people to take that to get to know what is this how it actually work.

#### Machine learning Accuracy Analysis
Logistic regresion :79.89%
SVM :75.87%
kNN :84.17%
Random Forest :83.16%
Decision Tree :92.21%
In this Travel insurance prediction dataset the target variable is in the form of catogory
5 classification model is checked with this dataset like logistic regresion,randomforest,svm,knn,Decisiontree
from the above model the Decision got high accuracy compared with other 4,it around 92.21 %.
So the best model fit to this dataset is considered as Decision tree
