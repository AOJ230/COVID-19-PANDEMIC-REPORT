# COVID-19-PANDEMIC-REPORT

# Covid-19

## Problem Statement

This dashboard helps the World Health Organisation (WHO) understand the cases of Covid-19. It helps them know the number of cases confirmed in each country/region, they get to know their number of cases, number of death and those recovered from the Covid-19. it also let them know the number of cases by each country, with this dashboard they have identified the cases and further work on their process.


### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a csv file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".
- Step 4 : In the report view, under the view tab, theme was selected.
- Step 5 : Since the data contains various ratings, thus in order to represent ratings, a new visual was added using the three ellipses in the visualizations pane in report view. 
- Step 6 : Four card visuals were added to the canvas, one representing Total deaths, total positive cases, total new cases & Total recovering case.
           Using visual level filter from the filters pane, basic filtering was used & null values were unselected for consideration into average calculation.
- Step 7 : A bar chart was also added to the report design area representing the Death by Country/Region. 
- Step 8 : Ratings Visual was used to represent different ratings mentioned below,

  (a) Active

  (b) Confirmed

  (c) Country/Region

  (d) Date

  (e) Deaths

  (f) New Cases

  (g) New Death

  (h) New Recovered

  (i) Recovered

  (j) WHO Region

  
In our dataset, Some parameters were assigned value 0, representing those parameters are not applicable for some cases.

All these values have been ignored while calculating rating for each of the parameters mentioned above.

- Step 9 : In the report view, under the insert tab, one text boxes were added to the canvas, the name of the report was mentioned.
- Step 10 : In the report view, under the insert tab, using image option from elements group a rectangle was inserted & similarly using image option company's logo was added to the report design area. 
- Step 11 : A card visual was used to represent sum of deaths.

![sum of death](https://github.com/user-attachments/assets/a2b5d91f-001d-431b-92d9-d1ed13c6003f)

        
 - Step 12 : A card visual was used to represent the Total confirmed Cases.

![sum of confirmed](https://github.com/user-attachments/assets/537b24b1-99f9-4f7a-b23e-bff2f573ca7c)

 - Step 13 : A card visual was used to represent the Total number of New Cases.

![sum of new cases](https://github.com/user-attachments/assets/a0e1ef76-7753-48e3-be18-241637ffef85)

Step 14 : A card visual was used to represent the Total number of Recovery Cases.

![sum of recovered](https://github.com/user-attachments/assets/6e5c6680-80b8-4dd6-9e46-6ec00c7e7f49)

 - Step 15 : The report was then published to Power BI Service.


![dashboard](https://github.com/user-attachments/assets/b0312c49-eb92-4a01-b23e-fe3f93d2ca07)
