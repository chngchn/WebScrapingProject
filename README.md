# Web Scraping Project: Scraping scores from SquareTrade Labs
This is a personal project created by myself to better understand the materials taught in Udacity's Data Analyst Nanodegree, specifically in the Data Wrangling section.
The end outcome of this project is to output into a CSV file, a table that contains all the scores and its relevant tests, scrapped from various SquareTrade Labs pages.

It so happens that this project could be potentially useful for my team's use as it would save quite a bit of time collecting the scores manually.

## Brief overview of notebook
For this project, I created a simple tool to first grab the .html file from designated URLs, which are stored as a variable in `durability_urls`.
Once the html file is downloaded, I did a quick review on one of the html file to understand how the sites are set up and the important tags. 
After I note down the important parent-child tags I need to find, I created `for` loops to grab the necessary scores and its related tests. 
Next, I craeted two dataframes to house the scores and I eventually combined the two dataframes into one and output the final table into a CSV file.

## Future work
Based on conversation with a colleague, I understand the current process is probably not the most efficient. In the next iteration, I will look at how to make the process 
even more efficient and streamlined. 
For the moment though, this tool works for my purpose by grabbing the scores from the few pages I specified (users can input more if necessary) and summarize the scores in a simple
table.
