## Takehome Tagup 

This Challenge from tagup revolves around machine data, and exploring what can be found from the 3 sensors.

In this project, I dive into some simple yet insightful tactics to learn a little more about the sensors and

if there are any interesting statistical moments within them.


**What was done:**
- loaded in all necessary libraries 
- Read in the CSV file and got a description of the data
- Found some statistical moments before manipulating data
- Data visualization via histogram and scatterplot
- Checked for outliers in the data using a simple IQR test
- Treated outliers 
- Visualized data after manipulation
- Mapped data into an SQLite database

**Summary:**

I found some pretty clear outliers in the tail ends of the data.
From the statistical moments found in Machine 0, all sensors remained ~0. I found that even though the mean, 25%, 50%,
and 75% range all followed this pattern, there were some pretty large maximums and minimums. I decided to dive a little
deeper into this by plotting this data on scatterplots and histograms. The relationships were clear indicators that values well into
the 100's were outliers. I decided to treat this data by deleting values outside of the 25-75% range. This left me with a new dataset
that I then plotted on a scatterplot and also checked the new statistical moments.


