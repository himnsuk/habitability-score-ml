### Identify the habitability score of a property

* * *


Problem Statement
-----------------

Finding the correct property to live in is a crucial task while moving to a new city/location. An inappropriate property can make our life miserable. Can AI help us find better places?

**Task**

You have given a relevant dataset about various properties in the USA. Your task is to identify the habitability score of the property.   

Dataset description
-------------------

The dataset contains the following files: 

*   _train.csv_: 39499 x 15
*   _test.csv_: 10500 x 14
*   _sample\_submission.csv_: 5 x 2 

 The columns provided in the dataset are as follows:

| Column                 | Description|
|------------------------|------------------------------------------|
| Property_ID            | Represents a unique identification of a property |
| Property_Type          | Represents the type of the property( Apartment, Bungalow, etc)&nbsp;|
| Property_Area          | Represents the area of the property in square feets|
| Number_of_Windows      | Represents the number of windows available in the property|
| Number_of_Doors        | Represents the number of doors available in the property |
| Furnishing             | Represents the furnishing type ( Fully Furnished, Semi Furnished, or Unfurnished )|
| Frequency_of_Powercuts | Represents the average number of power cuts per week |
| Power_Backup           | Represents the availability of power backup |
| Water_Supply           | Represents the availability of water supply ( All time, Once in a day - Morning, Once in a day - Evening, and Once in two days)&nbsp;              |
| Traffic_Density_Score  | Represents the density of traffic on a scale of&nbsp; 1 to&nbsp; 10 |
| Crime_Rate             | Represents the crime rate in the neighborhood ( Well below average, Slightly below average, Slightly above average, and&nbsp; Well above average ) |
| Dust_and_Noise         | Represents the quantity of dust and noise in the neighborhood ( High, Medium, Low ) |
| Air_Quality_Index      | Represents the Air Quality Index of the neighborhood |
| Neighborhood_Review    | Represents the average ratings given to the neighborhood by the people&nbsp;|
| Habitability_score     | Represents the habitability score of the property|


Evaluation metric
-----------------

    score = max( 0, 100*(metrics.r2_score(actual , predicted))

Result submission guidelines
----------------------------

*   The index is "**Property\_ID**" and the target is the _"_**Habitability\_score**" column. 
*   The submission file must be submitted in **_.csv_** format only.
*   The size of this submission file must be 10500 _x 2_.

_Note_: Ensure that your submission file contains the following:

*   Correct index values as per the _test.csv_ file
*   Correct names of columns as provided in the _sample\_submission.csv_ file

**Instructions:** 

*   Click _Download dataset_ to download the dataset.
*   Solve the problem in your local environment.
*   Save the submission in a _.csv_ file.
*   Click _Upload File_ (under the _Upload File_ section) to upload your prediction file (_.csv_).
*   Add any instructions or comments in the _Your Answer_ section.
*   Click _Submit_.


* * *

Upload Prediction File

Please upload the prediction file in the format as stated in the problem.

* * *

