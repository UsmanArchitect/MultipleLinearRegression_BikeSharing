# Project Name: Multiple Linear Regression on US bike-sharing dataset
> Build multiple linear regression model for the prediction of demand for shared bikes.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
- This project is part of processing dataset from one of the bike-sharing Dataset based on US using MLP. 
- Service Provider is suffering considerable dips in their revenues due to the ongoing Corona pandemic.
- aspires to understand the demand for shared bikes
- the companry want to understand the factors affecting the demand for these shared bikes in the American market. 
- Identify significant variables and how the variables describe the problem.

## Conclusions
- Recursive feature Elimination is used to eliminate the features 
- After RFE the initial model build with R2-score of 0.902 using 15 features
- After manual removal of features the Final model arrived with R2-score of 0.886 and using 9 features.
- The model with 9 features with below coefficient is selected which is giving fairly good result.
|sl |feature        | coeff       | Remarks         |
|:--|:--------------|:------------|:----------------|
|1. |const          | 0.038556    |                 |
|2. |yr             | 0.177746    |                 |
|3. |workingday     | 0.186646    |                 |
|4. |casual         | 0.684203    |                 |
|5. |season_2       | 0.113569    | Season: Summer  |
|6. |season_3       | 0.150432    | Season: Fall    |
|7. |season_4       | 0.162670    | Season: Winter  |
|8. |mnth_9         | 0.046096    |                 |
|9. |weathersit_2   |-0.040541    | Mist + Cloudy   |
|10.|weathersit_3   |-0.198460    |Light Snow       |



## Technologies Used
- library - pandas
- library - seaborn
- library - matplotlib
- library - sklearn


## Acknowledgements
Give credit here.
- This project was inspired by... UpGrad


## Contact
Created by [@UsmanArchitect] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->