# **Travel Analysis**

### Project Overview

This project looked into providing insights on customers travel preferences in order to provide tailored and efficient services as a travel agency. By analyzing various aspects of the data, I seek to provide insight amongst many others on the most preferred destination, month of travel and preferred transportation.

### Data Acquisition and Cleaning

The data was acquired using a Google form that aimed to understand customers preferences on their travel needs. The form was connected to Google Sheet to view the data.
The data was then exported as a csv file and loaded into Excel. EDA was carried out to check for errors, missing values, and black cells. I also ensured each column had the appropriate data type.
The dataset initially contained 7 columns and 334 rows excluding the header but was brought down to 6 columns and 332 rows due to the missing values in cells F78 and F211, which I didn’t want to infer so as to maintain the integrity of the data.

### Data Analysis

- The timestamp column was deleted as it was not needed for the analysis.
- The following columns were renamed to enhance readability
  - Your preferred destination- Destination
  - How will you move around?  - Transport
  - Type of Activities- Activity
  - When would like to travel? (Jan = 1, Dec = 12)- Month of travel
- The IFS function was used to convert the 'When would you like to travel' to Month text by using a helper column and then pasting the values only to keep the dataset simple for the Month of Travel.


### Tools Used

- Google Form - Data Collecton
- Excel - Data Cleaning
- Power BI - Visualization

### Data Visualizations

After cleaning the data in Excel, it was loaded into Power Query in Power BI. The data was checked so that the data tpyes were consistent and correct.
8  visualizations were created to help understand customers preferences and provide tailored services while increasing revenue.

### Insights
### Takeaway

