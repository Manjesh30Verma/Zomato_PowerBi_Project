 # Zomato-Dashboard

### Dashboard Link : https://app.powerbi.com/Redirect?action=OpenReport&appId=bfc8cbf3-db8c-4223-ba2b-8275df28146e&reportObjectId=418e7249-5cd4-4869-95f7-fe9992d185c4&ctid=c3e8fb7a-11a9-4a44-a1b4-1dda7786becf&reportPage=ReportSection1787ff8ce9e8a871027e&pbi_source=appShareLink&portalSessionId=92fe1719-b490-4945-a28e-232f1e09019a

## Problem Statement

This dashboard helps the Zomato understand their customers better. It helps the zomato know if their customers are satisfied with their services. Through different ratings, they get to know their improvement area, & thus they can improve their services by identifying these area. It also lets them know the average delay of food, thus since by using this dashboard they have identified this problem.

Since, number of Restaurents (allover 7429 %) are more than satisfied customers (around 4 Millions), thus in all they must work on improving their services. 


### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a csv file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Also since by default, profile will be opened, so you need to select "column profiling based on entire dataset".
- Step 4 : It was observed that in none of the columns errors & empty values.
- Step 5 : In the report view, under the view tab, theme was selected.
- Step 6 : Since the data contains various ratings, thus in order to represent ratings, a new visual was added using the three ellipses in the visualizations pane in report view. 
- Step 7 : Visual filters (Slicers) were added for four fields named "Class", "Customer Type", "Location".
           
           Using visual level filter from the filters pane, basic filtering was used & null values were unselected for consideration into average calculation.
           
           Although, by default, while calculating average, blank values are ignored.

- Step 8 : A bar chart was also added to the report design area representing the number of satisfied & neutral/unsatisfied customers. 
- Step 9 : Ratings Visual was used to represent different ratings mentioned below,

  (a) Rating by online orders

  (b) Rating by Table booking
  
  (c) Rating by votes
  
  (d) Cuisines by Price range
  
  (e) Food & Drink
  
  
All these values have been ignored while calculating average rating for each of the parameters mentioned above.
         
 - Step 10 : The report was then published to Power BI Service.
 
 
![Dashboard](https://github.com/volcanusacademy/Manjesh-Verma-13/assets/144987266/241a5b1c-cf33-4884-baf3-a38352497862)

![Dashboard](https://github.com/volcanusacademy/Manjesh-Verma-13/assets/144987266/cf814178-0553-4d1d-ac3a-bba39dccaf62)


# Snapshot of Dashboard (Power BI Service)

![Dashboard](https://github.com/volcanusacademy/Manjesh-Verma-13/assets/144987266/39c5d45e-30cc-4d0b-bf76-8b6861ec8862)

![image](https://github.com/volcanusacademy/Manjesh-Verma-13/assets/144987266/b6a4e9b2-be89-44e8-aefd-1118ce5c7fe7)

 
 # Report Snapshot (Power BI DESKTOP)

![Dashboard](https://github.com/volcanusacademy/Manjesh-Verma-13/assets/144987266/b919236f-b7c5-42af-907c-34734d4a0096)
 

# Home 
  We have buttons, so click on buttons and go on the page
      a) Insight
      b) Top Restaurants
      c) Cost & rating
      b) Restaurant selection


### [1] Insights

A single page report was created on Power BI Desktop & it was then published to Power BI Service.

Following inferences can be drawn from the dashboard;

### [2] Total Number of Restaurants = 7429

   Number of Votes of Customer = 4 M


   Number of Total Cities= 141

   The GPS location is also mentioned, and you can view it in a table        
### [3] Top Restaurants

    a) Top Restaurants by 
        Cuisines - Subway|Domino's
    b) Top Loaction by Cuisines
    c) Cusines Distribution
    d) Total Restaurants by locality
    e) Max selling Cuisines
  
  
  These ratings will change if different visual filters will be applied.  
  
  
 ### [4] Restaurant selection
 
 You can select your county and city, and then choose your preferred cuisine. You can also check whether the restaurant offers table booking and online ordering. Additionally, you can view the number of votes the restaurant has received. Finally, the price range of the restaurant is also provided.

# This is my App Barcode
![Manjesh_Zomato_BARCODE](https://github.com/Manjesh30Verma/PowerBi_Projects/assets/144987266/64d4373b-ae8d-4ac8-b55c-fa9f8c135a0f)
 
