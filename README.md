# UFO Webpage with Filtering Table
## Overview of Project
The purpose of this project was to create a webpage that includes a filterable table with UFO sighting data. When a new filter value is entered into any of the text boxes, the table automatically updates with the filtered data. The table is also able to be filtered by multiple filter values.

## Results
Upon opening the website, the table will load with all data entries.
### Unfiltered Webpage
![Unfiltered Webpage](/static/images/webPage_1.PNG)
### Using Filters
The table can be filtered by entering filter values into the textboxes to the left. The table can be filtered by Date, City, State, Country, and Shape. The filter is case-senstive.
#### Filter by date (1/5/2010)
![Filter by date](/static/images/webPage_filter20100105.PNG)

#### Filter by country (Canada)
![Filter by country](/static/images/webPage_filterCanada.PNG)

#### Filter by shape (circle)
![Filter by shape](/static/images/webPage_filterCircle.PNG)
  
  
### Multiple Filters
Adding multiple entries to the filter search will filter the table by all of the filter criteria.
  
#### Filter by date, state, and shape (1/1/2010, ca, triangle)
![Filter by date state shape](/static/images/webPage_filter20100101_ca_triangle.PNG)

## Summary
A couple draw backs of this design include:
  
* Having to manually delete the inputs or reload the webpage to clear them. Including a button to clear all inputs would be a nice addition.  
* Because the filter is case-senstive and a user might not know what cities (etc) are in the table, a dropdown that gives the possible entries would be really helpful. Even better, for multiple filters, an updated dropdown with only the available entries in the filtered table would make the user experience much nicer.
