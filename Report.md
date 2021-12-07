# Final Report to project Health Insurance Cost

### 1. Abstract

> A Medical Cost Personal Datasets it's medically company in USA , dedicated to the price of treatment of various patients. 
via we have predicted the costs of insurances and what is the features we have the most affected on the charges, this is what we need.

### 2.Design

> predict insurance costs?

### 3.Data

> Database source is [Kaggle](https://www.kaggle.com/mirichoi0218/insurance) it is a Medical Cost Personal Datasets, depends on: designation, form of clinic, town of residence, sex, age and if this person smoker or not, and do have children or not.
dedicated to the price of treatment of various patients. the price of treatment depends on several factors: designation, form of clinic, town of residence, age then on.

### 4. What did we conclude?

  * First of all We concluded through Correlations that there is a strong relationship between Charges and the person who smokes.
          
                
                    
![Screenshot 2021-12-07 183235](https://user-images.githubusercontent.com/93244403/145059071-e836b351-9d16-4f77-8c2c-a3f9879aad7b.png)


#### Note in this representation explain to us how much insurance pays more, a smoker than a non-smoker for female and male.

  
  
  
  
* After That We Do Some Expermints to find best model, in this part we find models scores And it turned out that the best model is Polynomial.
> * Train ratio: 0.843331 
> * validation : 0.822541
this scored is the (best fit)
    
        
            
![Screenshot 2021-12-07 183814](https://user-images.githubusercontent.com/93244403/145059634-f7124e90-0454-48f5-8645-d15f73c69347.png)





### Polynomial Model Representation
        
![Screenshot 2021-12-07 190343](https://user-images.githubusercontent.com/93244403/145064042-31dbaffa-a1be-408a-a1ef-305885bfd847.png)
