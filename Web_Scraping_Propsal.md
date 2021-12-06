# Regression_Project

# Ehsan website
![ehsan](https://user-images.githubusercontent.com/93244403/143563051-c5f9565e-0310-4512-be2a-c6f5f2d7c83e.jpg)
project 2 : Web Scraping and Linear Regression Project



## Background
In this project, we will use data from the [Ehsan](https://ehsan.sa/tyassarat?p=1) website it is a national platform that work to collecting donations for cases , Which shows us difficult cases whit details and that need a donate money. 
Our goal from this project is to build a linear regression model that predict how many days need to complete the each case.


## Data Description 
In this project, we used data on donations from Saudi Arabia, we'll see the type of cases, the number of days we're expected to spend on the type of debt, the number of donors, and the fastest type of cases that pay off their debt.That all the data from [Ehsan](https://ehsan.sa/tyassarat?p=1)


| Field Name          | Description                                                                                                |
|---------------------|------------------------------------------------------------------------------------------------------------|
|Case                 |The age of the person mentioned in the case                                                                 |
|ID                   |Each person has a unique invoice number                                                                     |
|Debt                 |The amount owed by the person, Which must be paid in order to end the case                                  |
|Num_donation         |The amount collected and donated by website visitors, in order to complete the debt amount & Number of person donation                  |
|Percentage           | Complete full amount by percentage                                                                         |
|visits               | Number of person visits of an one donation                                                                 |
|Link                 | It's a  Link for evereone  state                                                                                 | 
| last_donation	      |Time for last donation have it                                                                              |

Number of rows = 769 rows

Number of columns = 11 columns

## tools
#### Technologies

* Python
* Jupyter Notebook
* Web

#### Libraries
* Pandas
* NumPy
* IPython.core.display
* plotly.express
* plotly.express
* requests
* time,os
* bs4
* selenium 
* selenium.webdriver.common.keys
* fake_useragent
* sklearn.model_selection
* sklearn.linear_selection
* webdriver_manager.chrome 
* warnings
