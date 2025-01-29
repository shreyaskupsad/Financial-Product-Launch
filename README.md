The dataset consists of characteris/cs and demographic features of individuals and their interac/ons with N/LAB bank. 
These features can be broadly classified into three categories: demographics, financial, and contact. 
Demographic features include the individual's age, job role, marital status, and educa/on level. 
Financial features include credit default status, current balance, housing, and personal loan status. 
Contact-related features include communica/on type, day of the month last contacted, dura/on of the last contact, the number of contacts, and days since the client was last contacted in a previous campaign. 
The target output is binary, indica/ng whether the call resulted in a sale ('yes' or 'no'). 
The data types include numerical (age, balance, day, dura/on, campaign, pdays, previous) and categorical (job, marital, educa/on, default, housing, loan, contact, poutcome, y).

A decision tree was applied to the given dataset to unravel the underlying factors that significantly influence the outcomes. 
The goal was to iden/fy a preliminary set of influen/al features and assess their importance in predic/ng whether a call to an individual resulted in a sale.

Some customers may find phone calls bothersome, and the real concern is in the expenses incurred from reaching out to clients who aren't interested, was/ng valuable staff /me. 
In this context, the success measure for the classifica?on problem is iden?fied as the F1-Score. 
This metric is chosen because it considers both precision and recall, offering a balanced evalua/on that aligns with the business goal of efficiently iden/fying genuinely interested customers while minimizing resource wastage.
Going by the above reasoning, Random Forest algorithm offers best predic/ve model for determining if a call will result in a sale. 
While Logis/c Regression also comes close to Random Forest in terms of F1 Score, it lacks in the overall accuracy of the model. 
Therefore, Random Forest will be chosen as the best model, and it will be trained again on full available dataset.
