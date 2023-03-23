# Nosql--Challenge-
## Module 12

# Description
The UK Food Standards Agency evaluates various establishments across the United Kingdom, and gives them a food hygiene rating. You've been contracted by the editors of a food magazine, Eat Safe, Love, to evaluate some of the ratings data in order to help their journalists and food critics decide where to focus future articles.

Part 1: Database and Jupyter Notebook Set Up

Part 2: Update the Database

Part 3: Exploratory Analysis

# Getting Started
## Dependencies

<img width="960" alt="image" src="https://user-images.githubusercontent.com/118647940/227287903-4eda0ad9-4477-46cd-b636-912ab788ff75.png">

## Part 1 and 2 


<img width="473" alt="image" src="https://user-images.githubusercontent.com/118647940/227288200-7edc354e-5cb5-4c24-bc53-f0aa03e987f6.png">

## Part 3 




 ## Installing
-run in Jupyter Notebook/ Visual Studio /
 
-Python File/ Pandas Library 

-Ran in PythonData 3.7 Environment

-Mongodb

-pprint
  
# Executing Program
## Part 1: Database and Jupyter Notebook Set Up

<img width="960" alt="image" src="https://user-images.githubusercontent.com/118647940/227289269-a477c104-0660-4311-a8ec-c365fef283e6.png">
<img width="547" alt="image" src="https://user-images.githubusercontent.com/118647940/227290356-8bc11199-a31a-4ca7-8250-5d6f577faabb.png">


-Import dependencies

-Create and instance of MongoClient, and confirm data base was created

-Assign variable

-Review collections

-Review document in collection

-Assign variable to collection

## Part 2: Update the Database
<img width="960" alt="image" src="https://user-images.githubusercontent.com/118647940/227291186-90ef0db9-6124-4baa-8808-a78f166f6015.png">
<img width="960" alt="image" src="https://user-images.githubusercontent.com/118647940/227292214-f7328008-ca5d-4771-8bb9-9404f6dc1195.png">
<img width="960" alt="image" src="https://user-images.githubusercontent.com/118647940/227293081-5ce6ca3c-f5e9-4ddc-9afb-a752241da472.png">
<img width="960" alt="image" src="https://user-images.githubusercontent.com/118647940/227293830-c96db030-68d1-4ae5-8117-82ac667f4f97.png">
<img width="960" alt="image" src="https://user-images.githubusercontent.com/118647940/227294276-ca370a0a-7f64-4b1d-a341-66ef8ef1255c.png">






-Create dictionary for new restaurant data 

-Insert new restaurant data into the collection and check if it was inserted 

-Find BusinessTypeID for Restaurant/cafe/canteen and return only bussinesstypeid and businesstype fields

-Update the new data with correct BusinessTypeID and confirm update.

-Find how many documents have LocalAuthority Name as Dover and delete

-Check other doucments 

-Change data type from string to decimal for longitude and latitude and check 


## Part 3: Exploratory Analysis 

<img width="960" alt="image" src="https://user-images.githubusercontent.com/118647940/227312171-c4420285-9f38-4b49-81e3-bb4c3be7bda5.png">
<img width="960" alt="image" src="https://user-images.githubusercontent.com/118647940/227312706-a1d59458-43cb-4eb3-ab10-5e91dcda64f5.png">
<img width="960" alt="image" src="https://user-images.githubusercontent.com/118647940/227312915-4af9c839-7c8e-4b77-8cc5-5fe0149ed21a.png">
<img width="960" alt="image" src="https://user-images.githubusercontent.com/118647940/227313076-78151b88-21c9-495f-b123-73b63b55b24d.png">
<img width="960" alt="image" src="https://user-images.githubusercontent.com/118647940/227313455-52011122-464f-4a75-a57e-5e7fac0dec23.png">
<img width="960" alt="image" src="https://user-images.githubusercontent.com/118647940/227313803-af5f869e-f002-46fa-8dcc-f59833519c61.png">
<img width="960" alt="image" src="https://user-images.githubusercontent.com/118647940/227313937-ab8ded93-3a5b-45ad-8ddf-d7d5ecff2cb1.png">
<img width="960" alt="image" src="https://user-images.githubusercontent.com/118647940/227313994-a3a3c75b-c5da-42ba-b3d4-337e9d031c48.png">








-Import dependencies

-Create instance and assign data base variable name 

-Review collections and assign variable 

-Find establishment with hygiene score equal to 0, convert to pandas dataframe, and display 10 rows 

-Find establishments in Lone with RatingValue greater than or equal to 4, count documents, convert to Pandas Dataframe and displey first 10 rows

-Find top 5 establishments with RatingValue of 5 and sorted by lowest hygiene score nearest to Penang Flavours and convert to pandas dataframe

-Create pipleine that has a matches of hygiene score 0, grouped by localauthorityid, and sorted. convert result to pandas dataframe and display first 10 results. 



# Authors
-Kayla Bailey     github:baileykayla953





















