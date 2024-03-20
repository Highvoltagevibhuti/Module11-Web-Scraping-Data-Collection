**Files:**

**1. part_1_mars_news.jpynb** contains code to scrape mars news website: https://static.bc-edx.com/data/web/mars_news/index.html

extract all the text element and store the result into python dictionary to display title and preview seperately. 
Mars Data Analysis

**2. part_2_mars_weather.jpynb** contains code to scrape the weather table of mars from website: https://static.bc-edx.com/data/web/mars_facts/temperature.html

**Prepare the data for analysis.**

Analyze your dataset by using Pandas functions to answer the following questions:

1. How many months exist on Mars?
month

1     174

2     178

3     192

4     194

5     149

6     147

7     142

8     141

9     134

10    112

11    138

12    166

Name: month, dtype: int64

2. How many Martian (and not Earth) days worth of data exist in the scraped dataset?

1867

3. What are the coldest and the warmest months on Mars (at the location of Curiosity)? To answer this question:

Find the average minimum daily temperature for all of the months.

Plot the results as a bar chart.

4. Which months have the lowest and the highest atmospheric pressure on Mars? To answer this question:

Find the average daily atmospheric pressure of all the months.

Plot the results as a bar chart.

**Refer part_2_mars_weather file for bar charts for item 3 and 4.**

5. About how many terrestrial (Earth) days exist in a Martian year? To answer this question:

Consider how many days elapse on Earth in the time that Mars circles the Sun once.

Visually estimate the result by plotting the daily minimum temperature.

**Refer part_2_mars_weather file for plot.**

**3. Export the DataFrame to a CSV file.**

**It is uploaded to this repository.**
