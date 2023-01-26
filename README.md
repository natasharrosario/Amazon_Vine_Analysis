# Amazon Vine Analysis

## Overview of the project: 

For this project I collected data on customer reviews regarding **pet products** and used **Pyspark** to conduct the ETL process of *extracting, transforming and connecting*  the data to a database that we created via the *AWS server*. Once this process was complete an analysis was carried out to determine if there was a **favorable review bias** from the Vine members in our data set.

## Results
	
**How many Vine reviews and non-Vine reviews were there?**	

<img width="1053" alt="Screen Shot 2023-01-26 at 5 10 56 PM" src="https://user-images.githubusercontent.com/113553238/214962270-fbf62c2c-62bf-4eca-b3e7-80ad4225ed05.png">

<img width="1017" alt="Screen Shot 2023-01-26 at 5 11 22 PM" src="https://user-images.githubusercontent.com/113553238/214962284-f5638335-1762-43a3-b17c-24457e53ac1b.png">

- There were 170 *Vine reviews* and 37,840 *non-Vine reviews*. 
  
**How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?**	

<img width="1067" alt="Screen Shot 2023-01-26 at 5 12 37 PM" src="https://user-images.githubusercontent.com/113553238/214962425-080e0ad1-421c-444b-a4b4-36e445e99933.png">

- 65 of the Vine reviews were 5 star.
- 20,612 of the non-Vine reviews were 5 star.

**What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?**	

<img width="1026" alt="Screen Shot 2023-01-26 at 5 13 28 PM" src="https://user-images.githubusercontent.com/113553238/214962540-f278994d-6ae0-415b-b237-bc11b8137938.png">

- 38.2% of the 5 star reviews were Vine.
- 54.4% of the 5 star reviews were non-Vine.

## Summary

There are only **38.2%** of *5 star* Vine reviews in the dataset as opposed to **54.4%** of *5 star* non-Vine reviews which suggests a lack of bias. I believe there is a lack of proportion in the data set since 170 of the 37,840 reviews were from Vine users, which can lead to a lack representation in the analysis. 
