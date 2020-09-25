https://delanybroome.github.io/Final-Project/

Goal: To Train a Model that can be applied to California Fires. 
Dataset from https://archive.ics.uci.edu/ml/datasets/Forest+Fires
For reference: For more information, read [Cortez and Morais, 2007].

3. month - month of the year: 'jan' to 'dec'
4. day - day of the week: 'mon' to 'sun'
5. FFMC - FFMC index from the FWI system: 18.7 to 96.20
6. DMC - DMC index from the FWI system: 1.1 to 291.3
7. DC - DC index from the FWI system: 7.9 to 860.6
8. ISI - ISI index from the FWI system: 0.0 to 56.10
9. temp - temperature in Celsius degrees: 2.2 to 33.30
10. RH - relative humidity in %: 15.0 to 100
11. wind - wind speed in km/h: 0.40 to 9.40
12. rain - outside rain in mm/m2 : 0.0 to 6.4
13. area - the burned area of the forest (in ha): 0.00 to 1090.84




#3,4,10,11,12,13

#Notes 
categorical data activity - encoding 
play around with different modeling types
feature that prioritizes columns (in forest actiivty) SVN 
Day 2 Activity 4 
random forest classifier - .feature_importance 
shows list of columns used to predict target and output the effected numbers 
figure out which has the most effect on area outcome
recommendations: section on machine learning for this data set. trained dataset on these types of models, which models have the highest accuracy rates, and what features we ued from machine learning ( .feature_importance)
(also have references section)

clear requirements: machine learning 
host project on Heroku 
make sure project is a flask app

Tableau: 
 https://public.tableau.com/profile/dave2243#!/vizhome/ProjectFire/AreavsTemp
 https://public.tableau.com/profile/dave2243#!/vizhome/ProjectFire/AreavsWind
 https://public.tableau.com/profile/dave2243#!/vizhome/ProjectFire/MonthlySummary
 https://public.tableau.com/profile/dave2243#!/vizhome/ProjectFire/Sheet1
 https://public.tableau.com/profile/dave2243#!/vizhome/ProjectFire/Sheet2

