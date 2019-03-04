# Hackaton Frankfurt 2018, Artificial Intelligence Lab Frankfurt School of Management and Deloitte
Data Science competition to address the question:  In what year will e-cars become mainstream?  


## Use of machine-learning techniques  
1) Polynomial  
2) Linear regression   
      
## Use of open-source tools like Python, R (or their libraries)  
scikit learn library in python  
rstudio  


## Documentation:  
1) Data for Diesel vs Hybrid Cars sales (slide 8):  
Hybrid cars >> https://www.afdc.energy.gov/uploads/data/data_source/10301/10301_hev_sales.xlsx  
Diesel Cars >> https://www.acea.be/uploads/statistic_documents/Share_of_diesel_in_new_cars_in_West_Europe_%281990-2017%29.xlsx  

2) Data for Total Car Sales All combustions and Electric cars (slide 9):  
Electric Cars >> https://about.bnef.com/electric-vehicle-outlook/  
All cars      >> http://www.oica.net/category/sales-statistics/  


## Summarization:  
Today challenge was to conduct predictive analysis about the time frame by which electric cars will be mainstream.  
One possible limitation of the disruptive power of electric technology is the battery composition. For this, we decided to explore the price fluctuations per Kw/h of litium battery over the years.  
We started our approach with data collection and data mining of candidate datasets to answer specific questions:   
1) how past trend/performance of diesel cars align over the time frame 1990 to 2017?  
2) how hybrid cars have performed from 1998 to 2015?  
We wanted to address these points by comparing the sales patterns of the two different car technologies. The behaviour of these trends allowed us to understand similar sales trends for electric cars: Diesel vs Hybrid/Electric cars.  
After the data intepretation, we decided to fit linear regression and polynomial models to get insight of the possible convergence between the global internal combustion engine (ICE) vs electric cars sales.   
On the limit of the data availability we were able to predict 2032-2035 as possible years in which electric cars would be mainstream.  


## Validation  
not enough data to perform cross validation or other machine learning techniques  
