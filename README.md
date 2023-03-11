# UFOs
## Overview of Project
### Purpose
In this week's challenge we were tasked with building a dynamic table using stored data in a JavaScript array. The data was information on UFOs that have been spotted in the United States, broken down by date, city, state, country, shape, and a comment on the UFO spotting. Before we could complete the challenge we created the base table with one filter option. Once we completed the base table and utilized it through the HTML file, it was easy to see in our web browser what we developed. What the challenge required us to complete was adding additional filter criteria to react to multiple search criteria inputed by the user. The additional filter criteria was including the rest of the keys in our UFO data JavaScript array. These additional filters would allow for the user to easily sort through the provided data using multiple criterias. 

## Results
### Implementation

To run a search on the website using the input filters, this is what one would initially see when viewing the website. We have sample text in each of the filters suggesting a user how and what to input. 

![Screenshot 2023-03-11 105331](https://user-images.githubusercontent.com/119636655/224494309-3005d52a-567a-4681-b49f-8a7c0c5a6bf9.png)

#### To Search by Date
In this search we will start with searching by the date of occurance. For this example we will use "1/4/2010". After we enter this date into the input bar, we can click anywhere on the site or hit "enter" on our keyboard to activate the search. This is true to execute any additional criteria we request a search for. We see now that the returned results are all from the date we entered. 

![Screenshot 2023-03-11 105245](https://user-images.githubusercontent.com/119636655/224494254-d6b4ae66-f3a4-4d20-bf07-9f14208c1ab0.png)

#### To Search by Date and City
To delve deeper into this search, we will use the city "reedville" in the "City" filter. We can see that one table entry fits our criteria. 

![Screenshot 2023-03-11 105448](https://user-images.githubusercontent.com/119636655/224494352-1bdef6f3-feae-4274-ad10-a6f46330853e.png)

#### To Search by Date and Shape
We can remove our "City" by erasing what we entered into the input box and add "light" to the "Shape" parameter. This will show us all of the "light" shapes on 1/4/2010.

![Screenshot 2023-03-11 105533](https://user-images.githubusercontent.com/119636655/224494395-4d735c16-ad28-480d-bcfb-31e9e7a216c7.png)

#### To Search by Date and State
If we want to see all of a specific state occurance on a date, we can remove our "light" criteria and enter "ca" in the "State" input. This shows us all the instances California has had a UFO sighting on 1/4/2010.

![Screenshot 2023-03-11 105628](https://user-images.githubusercontent.com/119636655/224494431-07f5b0d0-23d3-4b2a-a803-d2564e73f08a.png)

#### How to Reset the Filters
To state a new search, there are multiple ways to reset the filters:
- Reset the webpage by using the refresh button at the top
- Click on "UFO Sightings" in the top left corner (pictured below)
- Manually delete your information from the input boxes. 

![Screenshot 2023-03-11 105802](https://user-images.githubusercontent.com/119636655/224494503-10831f21-71b4-4fac-b4c4-540ce965b2f9.png)

## Summary
### Conclusion
In conclusion, we were able to take a JavaScript UFO array to create a website that supported a multi-filter search through the linked data and customize the website to reflect the UFO theme. To fulfill the challenge requirements, we modified the inital input date search to include multiple filter inputs. 

#### Further Development
After further review of this webpage and the information that is stored and provided for analysis, one drawback that has been identified is the limited data avaialble for review. This table data is solely based on information from January 2010, thus creates an extremely narrow window for analysis. Which is why there are two additional recommendations for further development as we move grow this website. To use our new filters to their fullest potential and for an overall thorough analysis, it is recommended that UFO data is comtinuously gathered and pushed to the table in the UFO site. Setting up the data collection and push process on a monthly or quarterly basis would provide the users current data as they explore the table information. The final recommendation would be to modify our input on the filters to accept and search by any text. Currently our filters are letter case specific and if the user is not aware of this setting they could be missing out on information they are looking for. 
