# pandas-challenge
Pandas challenge assignment 4

For this assignment there were three requirements as given below:

1. Use the D3 library to read in the data from the URL "https://2u-data-curriculum-team.s3.amazonaws.com/dataviz-classroom/v1.1/14-Interactive-Web-Visualizations/02-Homework/samples.json".
2. Create a horizontal bar chart with a dropdown menu to display the top 10 OTUs found in that individual.

       • Use sample_values as the values for the bar chart.
       • Use otu_ids as the labels for the bar chart.
       • Use otu_labels as the hovertext for the chart.
       
3. Create a bubble chart that displays each sample.

       • Use otu_ids for the x values.
       • Use sample_values for the y values.
       • Use sample_values for the marker size.
       • Use otu_ids for the marker colors.
       • The link to the github page is "https://sbora0.github.io".
   

5. Display the sample metadata, i.e., an individual's demographic information.
6. Display each key-value pair from the metadata JSON object somewhere on the page.
7. Update all the plots when a new sample is selected.

1. Database and Jupyter Notebook Set Up

       Import the data provided in the establishments.json file from your Terminal. Name the database uk_food and the collection establishments. Copy the text you used to import your data from your Terminal to a markdown         cell in your notebook.
       Within your notebook, import the libraries you need: PyMongo and Pretty Print (pprint).
       Create an instance of the Mongo Client.
       Confirm that you created the database and loaded the data properly:
       List the databases you have in MongoDB. Confirm that uk_food is listed.
       List the collection(s) in the database to ensure that establishments is there.
       Find and display one document in the establishments collection using find_one and display with pprint.
       Assign the establishments collection to a variable to prepare the collection for use.

3. Scrape and Analyse Mars Weather Data
       
       •	Use automated browsing to visit the Mars Temperature data site "https://static.bc-edx.com/data/web/mars_facts/temperature.html". Inspect the page to identify which elements to scrape.
       •	Create a Beautiful Soup object and use it to scrape the data in the HTML table.
       •	Assemble the scraped data into a Pandas DataFrame.
       •	Examine the data types that are currently associated with each column. If necessary, cast (or convert) the data to the appropriate datetime, int, or float data types.
       •	Analyse your dataset by using Pandas functions to answer the following questions:
   
                     o	How many months exist on Mars?
                     o	How many Martian (and not Earth) days worth of data exist in the scraped dataset?
                     o	What are the coldest and the warmest months on Mars? by finding the average minimum daily temperature for all of the months and plotting the results as a bar chart.
                     o	Which months have the lowest and the highest atmospheric pressure on Mars? by finding the average daily atmospheric pressure of all the months and plotting the results as a bar chart.
                     o	About how many terrestrial (Earth) days exist in a Martian year? by considering how many days elapse on Earth in the time that Mars circles the Sun once and visually estimate the result by                                    plotting the daily minimum temperature.

       •	Export the DataFrame to a CSV file.

Files Information:

       •	The file “part_1_mars_news.ipynb” is used to complete the first requirement.
       •	The file “part_2_mars_weather.ipynb” is used to complete the second requirement.
       •	Two output files “mars_articles.json” and “mars_data.csv” are in “Output” folder.

             
