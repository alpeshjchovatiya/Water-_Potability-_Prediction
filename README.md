
### Title: Water Potability Prediction  
### Author: Alpesh Chovatiya

### Problem Statement:
Access to clean and safe drinking water is critical, yet many regions struggle with water contamination, and millions of people worldwide suffer from waterborne diseases 
ue to the consumption of contaminated water.Traditional methods of testing water potability are often time-consuming, costly, and require specialized equipment. 
There is a need for an efficient and cost-effective method to predict water potability based on easily measurable water quality parameters.

### Objective:
Develop a machine learning model to predict water potability using key water properties (e.g., pH, hardness, turbidity). The model will classify water as potable or non-potable, 
offering a fast, reliable tool for assessing drinking water safety.

### Dataset Overview:
This dataset has 3276 records with following 10 attributes.
**1. ph:** Acidity/alkalinity level of the water.    
**2. Hardness:** Concentration of calcium and magnesium.       
**3. Solids:** Total dissolved solids in the water.      
**4. Chloramines:** Concentration of chloramines, used for disinfection.        
**5. Sulfate:** Sulfate ion concentration in the water.       
**6. Conductivity:** Water's ability to conduct electricity, related to ion content.         
**7. Organic_carbon:** Organic matter content in the water.     
**8. Trihalomethanes:** Byproducts of water chlorination.       
**9. Turbidity:** Water clarity, indicating particle presence.        
**10. Potability:** Whether the water is potable ("Potable" or "Not Potable").        

### Summary of Results:
**Random Forest:** 0.81    
**XGB:** 0.78    
**Decision Tree:** 0.74    
**Support Vector Classifier:** 0.68    
**Logistic Regression:** 0.63    
**K-Nearest Neighbors:** 0.61    

#### Best performing model for current dataset is Random Forest  with accuracy of 81%.




