# UFOs
### **"The Truth Is Out There!"** 

## Overview of Project: 
The purpose of this analysis is to create a webpage with dynamic table that would provide a more in-depth analysis of UFO sightings by allowing end users to filter for multiple criteria at the same time.

## Results:
**__Deliverable 1: Filter UFO sightings on multiple criteria__**

The search criteria has been modified so users may search for sightings based on date, city, state, country, shape or combination of any of these criteria. The users will need to enter criteria as shown below.

- Example 1: filter by date and state
![image](https://user-images.githubusercontent.com/106962921/186904387-05f8befd-74e7-4bfe-8033-ad8b0e19906e.png)

- Example 2: filter by state and shape
![image](https://user-images.githubusercontent.com/106962921/186904660-f59746f9-18f9-4068-8ef7-05001e238525.png)

- Example 3: filter by date and city
![image](https://user-images.githubusercontent.com/106962921/186905129-73469fd1-70a8-4646-aa41-e64ca3da9d74.png)

## Summary: In a summary statement, describe one drawback of this new design and two recommendations for further development.
- One drawback noted for the new design is that the search parameters are specific and not intuitive. One specific parameter observed is that it is case sensitive. If a search is made for a city "Sacramento" or "sacramento ", the table would not procure any information:
![image](https://user-images.githubusercontent.com/106962921/186909888-eecbe6d3-eac6-42aa-9146-b96e7a2703e6.png)
![image](https://user-images.githubusercontent.com/106962921/186910069-15710d8e-1a4e-46d9-88bd-1bc217339858.png)

- A non-intuitive paramenter observed is the date parameter. The filter would not accept any other date format except 'mm/dd/yyyy'. Input such is 'mm-dd-yyyy' and 'yyyy/mm/dd' are not acceptable date format
![image](https://user-images.githubusercontent.com/106962921/186914958-b67da920-b291-454e-953e-a840ffcaf0e6.png)
![image](https://user-images.githubusercontent.com/106962921/186915070-21acbfdb-cc7a-4a07-9a82-87b43a8dafcd.png)

- One recommendation for futher development is to update the search parameter so that filter search would include case sensitive parameter for city, state and country. For ease of search, update the state and country to be a drop-down menu. 

- Another recommendation for futher development is to update the date parameter so it include entries besides 'mm/dd/yyyy' format.
