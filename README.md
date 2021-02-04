# Housing-Prediction
Factors influencing the future prices of recidential houses


Goal : Predicting selling price of the House

For this project I have chosen to investigate the Boston House Price dataset. Each record in the database
describes a Boston suburb or town. The data was drawn from the Boston Standard Metropolitan
Statistical Area (SMSA) in 1970. The attributes are defined as follows (taken from the UCI
Machine Learning Repository 1 ):

Dataset : (504r,15col), Target : MEDV(price for buyers house)
Features : 
1. CRIM: per capita crime rate by town
2. ZN: proportion of residential land zoned for lots over 25,000 sq.ft.
3. INDUS: proportion of non-retail business acres per town
4. CHAS: Charles River dummy variable (= 1 if tract bounds river; 0 otherwise)
5. NOX: nitric oxides concentration (parts per 10 million)
6. RM: average number of rooms per dwelling
7. AGE: proportion of owner-occupied units built prior to 1940
8. DIS: weighted distances to five Boston employment centers
9. RAD: index of accessibility to radial highways
10. TAX: full-value property-tax rate per $ 10,000
11. PTRATIO: pupil-teacher ratio by town
12. B: 1000(Bk − 0.63) 2 where Bk is the proportion of blacks by town
13. LSTAT: % lower status of the population
14. MEDV: Median value of owner-occupied homes in $ 1000s

Conclusions: 
1. Here,we can see that all features like nitric oxides concentration and weighted distances to five Boston employment centers and full-value property-tax rate per $ 10,000 have a strong correlation to proportion of non-retail business acres per town, similarly  facotrs like AGE has about 0.73 correalation with NOX(nitric oxides concentration (parts per 10 million)) (e.g.
 0.70 or < −0.70). For example:
NOX and INDUS with 0.77.
DIS and INDUS with -0.71.
TAX and INDUS with 0.72.
AGE and NOX with 0.73.
DIS and NOX with -0.78.

2. Factors like Average room size(RM), more rooms implys more space and more costs, therfore it affects price. 

3. Lower class locality (LSTAT), unsafe area therefore they have low demand. And they tend to have lower prices

4. Also every parent wants their kids to attend good school, therefore PTRATIO i.e student to teacher ratio by
town affects the price of the house. Families prefer to live in the locality where good schools are located. 
School quality,Walkability from schools tend to matters alot for hardworking families. 


5. Though these were the conclusions I have from this given dataset, still those factors are *all* the factors that will influence residential home prices in the United States over the next 10 years.
Being a bachelorite, I have my own preferences for a buying a house,
1. Good Location,not situated in a busy corner
2. Home size, age,layout, more sunlight
3. Near amenities like beach or shopping centers
4. Apart from that , economy, lower interest rates, current market trends will majorly influence future prices of residential homes.   

