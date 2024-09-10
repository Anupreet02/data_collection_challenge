# data_collection_challenge


Part 1: Scrape Titles and Preview Text from Mars News
	a. Automated browsing was used to visit the link to the Mars news site. Inspect the page to identify which elements to scrape.

    b. Created a Beautiful Soup object to extract text elements from the website.

    c. Stored each title-and-preview pair in a Python dictionary and, give each dictionary two keys: title and preview. An example is the following: Store all the 		dictionaries in a Python list. Print the list in your notebook.

Part 2: Scrape and Analyze Mars Weather Data

1. Automate browsing was used to visit the link of Mars Temperature Data Site. Inspect the page to identify which elements to scrape.
2. Created a Beautiful Soup object and used it to scrape the data in the HTML table. Note that this can also be achieved by using the Pandas function. However, use Beautiful Soup here to continue sharpening your web scraping skills.
3. Assemble the scraped data into a Pandas Data Frame. The columns should have the same headings as the table on the website. Here’s an explanation of the column headings:

    id: the identification number of a single transmission from the Curiosity rover

    terrestrial date: the date on Earth
	sol: the number of elapsed sols (Martian days) since Curiosity landed on Mars
	ls: the solar longitude
	month: the Martian month
	min_temp: the minimum temperature, in Celsius, of a single Martian day (sol)
	pressure: The atmospheric pressure at Curiosity's loc

4. Examine the data types that are currently associated with each column.
5. Analyze the dataset by using Pandas functions in all of the questions were given that is:
   a. How many months exist on Mars?
   b. how many Martian (and not Earth) days worth of data exist in the scraped dataset?
   c. what are the coldest and the warmest months on Mars.
   d. Find the average minimum daily temperature for all of the months.
   e. Plot the results as a bar chart.
   f. Which months have the lowest and the highest atmospheric pressure on Mars?
   g. Find the average daily atmospheric pressure of all the months.
   h. Plot the results as a bar chart.
   i. About how many terrestrial (Earth) days exist in a Martian year?
   j. Consider how many days elapse on Earth in the time that Mars circles the Sun once.
   h. Visually estimate the result by plotting the daily minimum temperature of each observation.
6. Export the Dataframe to a CSV file.
7. An analysis has been written on the topics :Minimum Temperature,Atmospheric Pressure,Year Length.
8. #REFERENCE: class recordings : Zoom cloud link.
