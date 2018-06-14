## **Bike Share Data**

Over the past decade, bicycle-sharing systems have been growing in number and popularity in cities across the world. Bicycle-sharing systems allow users to rent bicycles on a very short-term basis for a price. This allows people to borrow a bike from point A and return it at point B, though they can also return it to the same location if they&#39;d like to just go for a ride. Regardless, each bike can serve several users per day.

Thanks to the rise in information technologies, it is easy for a user of the system to access a dock within the system to unlock or return bicycles. These technologies also provide a wealth of data that can be used to explore how these bike-sharing systems are used.

In this project, you will use data provided by  [**Motivate**](https://www.motivateco.com/), a bike share system provider for many major cities in the United States, to uncover bike share usage patterns. You will use the data from one of the largest cities of United States: Chicago.

## **The Datasets**

Data for the first six months of 2017 are provided. The data file contain **six (6)** columns:

- Start Time (e.g. 2017-01-01 00:07:57)
- End Time (e.g. 2017-01-01 00:20:53)
- Trip Duration (in seconds, e.g., 776)
- Start Station (e.g. Broadway &amp; Barry Ave)
- End Station (e.g. Sedgwick St &amp; North Ave)
- User Type (Subscriber or Customer)
- Gender (Male or Female)
- Birth Year (e.g., 1980)

The original files, which can be accessed here ( [**Chicago**](https://www.divvybikes.com/system-data),  [**New York City**](https://www.citibikenyc.com/system-data),  [**Washington**](https://www.capitalbikeshare.com/system-data)), had more columns and they differed in format in many cases. Some  [**data wrangling**](https://en.wikipedia.org/wiki/Data_wrangling) has been performed to condense these files to the above core six columns to make your analysis and the evaluation of your Python skills more straightforward. In the Data Wrangling course that follows this course in the Data Analyst Nanodegree program, students learn how to wrangle the dirtiest, messiest datasets so don&#39;t fret if you worried about missing out.

## **The Questions**

You will write code to complete the following tasks:

- Task 1: Print the first 20 samples(rows) from the database
- Task 2: Print the gender(column) of the first 20 samples
- Task 3: Create a function to get the columns as a list
- Task 4: Count how many of each gender do we have
- Task 5: Create a function to count the genders
- Task 6: Show the most popular gender
- Task 7: Plot a a chart using the previous data
- Task 8: Answer why summing the number of Males and Females doesn&#39;t match the number of samples
- Task 9: Find the minimum, maximum, mean and median duration of the trips
- Task 10: Get all the start stations of the dataset
- Task 11: Create a function count the occurrence of any given column (optional)
