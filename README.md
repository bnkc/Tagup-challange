## Tagup Takehome

This challenge from Tagup revolves around machine data, and exploring what can be found from the 3 sensors.
In this project, I dive into some simple, yet insightful tactics in an effort to find statistical moments and outliers within the machine data.



**Steps Taken:**
- [x] Found some statistical moments before manipulating the data
- [x] Data visualization via histogram and scatterplot
- [x] Checked for and treated outliers 
- [x] Visualized data after manipulation
- [x] Mapped data into an SQLite database

**Summary:**

  When analyzing the data provided for the machines, I found some pretty interesting insights. 
I began with getting a description of the dataset so I could view the means, maximums, and minimums. This was important as it helped me eventually find the outiers in the dataset. From the statistical moments found, it became clear that the max and mins seemed out of place. <br/>

  I decided to then plot data on various graphs to get a better understanding of the relationships within the data. Plotting the data supported my theory that the tail ends were skewed. I decided to treat this data by deleting values outside of the 25-75% range by performing a simple IQR test. This left me with a new dataset that I then plotted on a scatterplot and found statistical moments in order to compare to the original dataset. This cleaned data was then mapped into a database. <br/>
  
  In conclusion, I was left with an interesting question. What if those extreme values had some importance to the dataset in determining when a machine was reaching a failure point?

#IMPORTANT: This analysis is replicable for all of the machine data. 


