# Corona-Virus-Covid_19-Build-In-Patient-Prediction-Model-Algorithm-in-Machine-Learning
## COVID-19 Visualizations, Predictions Model Algorithm, SVM, Logistic Regression
COVID-19 may not be fatal but it spreads faster than other diseases, like common cold. Every virus has Basic Reproduction number (R0) which implies how many people will get the disease from the infected person. As per initial research work R0 of COVID-19 is 2.7.
Currently the goal of all scientists around the world is to "Flatten the Curve". COVID-19 currently has exponential growth rate around the world which we will be seeing in the notebook ahead. Flattening the Curve typically implies even if the number of Confirmed Cases are increasing but the distribution of those cases should be over longer timestamp. To put it in simple words if say suppose COVID-19 is going infect 100K people then those many people should be infected in 1 year but not in a month.

The sole reason to Flatten the Curve is to reudce the load on the Medical Systems so as to increase the focus of Research to find the Medicine for the disease.

Every Pandemic has four stages:

Stage 1: Confirmed Cases come from other countries

Stage 2: Local Transmission Begins

Stage 3: Communities impacted with local transimission

Stage 4: Significant Transmission with no end in sight

Italy, USA, UK and France are the two countries which are currently in Stage 4 While India is in on the edge of Stage 3.

Other ways to tackle the disease like Corona other than Travel Ban, Cross-Border shutdown, Ban on immigrants are Testing, Contact Tracing and Quarantine.

## AIMS & OBJECTIVE:
The goals of the research are used machine learning model approaches to determine if a person is 
COVID_19 or not. Prediction is based on the patients’ common symptoms. The objective is to 
determine whether a patient may be COVID_19. 
Our research main primary objectives are as follow:
* Identifying the most suitable machine learning technique for prediction, to perform on 
clinical reports of patients.
* Develop a machine learning model that could make accurate predictions of COVID-19 in 
patients.
* Identifying the features that affects the prediction of COVID-19 in patients.
* The characteristics that influence CVOID_19 predictions in patient

## Used Libraries’ in Software Environment:
Python is a high-level general-purpose programming language. It accepts many paradigms. 
Python have many standard libraries that contain tools for doing numerical works. Python 
is basic unstructured language with a large number of feature and libraries. 
Following Python Libraries’ Were Utilized in this Research:
* Pandas - is Python module that provide expressive data models that are designed which 
operate with relational and labelled data. It is a free and open source Python module that 
allows data to be read and written across data structure [30]. 
* Numpy-Numpy - is a Python open source library for scientific computing. Numpy 
additionally extends Python’s array processing capabilities [29].
* Matplotlib – It’s free and open source Python tool for creating plots and 2D representation. 
To interacts with Python to provide interactive and effective visualization plot [29].
* TenserFlow – TenserFlow is a free, open source Python library for math created by Google 
Machine Intelligence Brain Team [55].
* Sklearn – is a Python Machine Learning package that works in tandem with Numpy. It 
includes for classification, there are a variety of machine learning approaches clustering 
and regression.
* Anaconda Navigator – is a desktop GUI that comes with Anaconda individual edition. It 
makes it easy to launch application and mange packages and environment without using 
CMD.
* Jupyter Notebook – is a free & open-source online application that allows you to create 
and share documents that include live code, equation and graphics. Visualizations well as 
narrative pros Data cleaning, transformation, numerical simulation, and statistical 
modelling these are all example of machine learning are some of applications [58]. For 
online quick tutorial is available at: https://nbviewer.org/github/pauleve/pint/blob/mast 
er/notebook/quick-tutorial.ipynb.

## SUPPORT VECTOR MACHINE (SVM):
Support Vector Machine creates N-dimensional classification system for data hyper plan that 
divides it into two categories [12]. In SVM, the predict variable is referring to an attribute, and 
transformed attributes are referred to as features. Features selections refer to the selecting of 
process the data that is most representative. A vector is collection of features that describe 
single case.
The final aim of SVM modelling is to determine the optimum hyper plane that divide’s the 
cluster, the target variable in one side of the plane and the other category on the others. The 
support vectors are those that are close to the plane [12]. Figure 2.1 depicts a common support 
vector machine example.
Support Vector Machine – SVM 
SVC (kernel = ‘linear,’ random state = 0)

## LOGISTIC REGRESSION:
Logistic Regression is a Machine Learning methods use to solve classification issue it is a 
predictive analytic technique that is based on the ideas of probability.
### Logistic Regression: 
It is a method of predicting the future based on past data,

clf = Logistic Regression () clf.fit (X train, Y train) clf.fit (X train, Y train) 

clf.fit (X train, Y train)

## COMPARISON OF ALGORITHM RESULTS:
The total accuracy results from the tests are summarized for comparison in Figure 5.1 and 
5.2, in these models regression model give us 99% accuracy.

### Analysis of Experiment Algorithm (Review):
Many studies have purposefully undertaken a clear comparison of various machine 
learning algorithms, but the collection could not be reached, all proposed a comparison 
model SVM & Regression Model were chosen to undertake an experimental assessment to 
determine the best method to predict COVID_19. 
The experiment is divided into two stages:
* Assessment of machine learning methods chosen from the Literature Review and 
Experimental work to address RQ1.
* Importance Feature generation for determining the influence of a certain feature on 
the prediction of COVID_19 which is used to answer RQ2.

## ANALYSIS OF PHASE_1:
Quantitative data compared to estimated accuracy for each machine learning method in 
order to determine the best algorithm for COVID_19 predications.
When compared to Support Vector Machine and other methods, the regression model 
performs significantly better in terms of accuracy and predication.
When compared to other algorithm, the Regression Model produced superior results with 
less and bigger training data records. When the quantity of records was doubled, there was 
no discernible difference in prediction accuracy.

## ANALYSIS OF PHASE_1:
Phase_2 is being carried in order to responds RQ2. The goal of this experiment is determine 
which feature in the dataset have an impact on the predicted outcome.


