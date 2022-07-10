# Amazon_Vine_Analysis
## Overview of the analysis
- Analyzing Amazon reviews written by members of the paid Amazon Vine program. 
- Analized  reviews for Pet products from Amazon Review dataset.
- Used PySpark to perform the ETL process to extract the dataset
- Transform the data, connect to an AWS RDS instance and load the transformed data into pgAdmin.
- Used PySpark to find out if there is any bias toward favorable reviews from Vine memberes in the database.

## Results
- How many Vine reviews and non-Vine reviews were there?
    - There are total of 170 Vine reviews
![Text to Column](https://github.com/Hanitapatel/Amazon_Vine_Analysis/blob/main/Resources/Number%20of%20Vine%20reviews.png)
    - There are total of 37,840 non-Vine reviews
![Text to Column](https://github.com/Hanitapatel/Amazon_Vine_Analysis/blob/main/Resources/Number%20of%20non-Vine%20reviews.png)
- How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars? 
    - There are 65 5 stars Vine reviews 
![Text to Column](https://github.com/Hanitapatel/Amazon_Vine_Analysis/blob/main/Resources/Number%20of%20vine%20Five%20star%20revies.png)
    - There are 20,612 5 stars non-Vine reviews
![Text to Column](https://github.com/Hanitapatel/Amazon_Vine_Analysis/blob/main/Resources/Number%20of%20non-Vine%20Five%20star%20reviews.png)
- What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
    - There are 38.235% of Vine 5 star reviews
![Text to Column](https://github.com/Hanitapatel/Amazon_Vine_Analysis/blob/main/Resources/Vine%20Five%20star%20reviews%20percentage.png)
    - There are 54.47% of non-Vine 5 star reviews
![Text to Column](https://github.com/Hanitapatel/Amazon_Vine_Analysis/blob/main/Resources/Non-Vine%20Five%20star%20reviews%20percentage.png)
    
## Summary
For perticular Pet products analysis there is no positive bias for reviews in the Vine program, because if you see there are only 38% of Vine Five star reviews over 54% of non-Vine Five star reviews.
We can also analyze less than 4 star reviews and find out if bias for reviews in the Vine program is positve or not.





    
    

