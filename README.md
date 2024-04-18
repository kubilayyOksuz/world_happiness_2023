# World Happiness Report - 2023

In this project, I used two datasets from Kaggle, <a href="https://www.kaggle.com/datasets/ajaypalsinghlo/world-happiness-report-2023">World Happiness Report 2023</a> and <a href="https://www.kaggle.com/datasets/andradaolteanu/country-mapping-iso-continent-region">Country Mapping</a> to take a look at the report and visualize the results using Matplotlib and Plotly.

The dataset is the World Happiness Report, published by United Nations Sustainable Development Solutions Network. This data was collected by the Gallup World Poll. Each country around the world is given a ladder score, a happiness score, based on some criterias like,
* GDP per capita
* Social support
* Healthy life expectancy
* Freedom
* Generosity
* Perceptions of corruptance

### What is the World Happiness Report?
The World Happiness Report reflects a worldwide demand for more attention to happiness and well-being as criteria for government policy. It reviews the state of happiness in the world today and shows how the science of happiness explains personal and national variations in happiness.

More can be found here: <a href="https://worldhappiness.report/about/">Source</a>

### Which libraries are used?
* Pandas (for creating dataframes)
* Matplotlib (for basic plotting)
* Plotly (for advanced plotting like World Map)

### How did I use the datasets?
1. I downloaded the datasets from Kaggle.
2. Imported them as Dataframes using Pandas.
3. Cleaned both dataframes, for example, I dropped the columns I didn't need. Then, I renamed the remaining columns for readability.
4. Created a new column called "rank" that represents the ranking of the countries according to their ladder score.
5. Merged two dataframes.
6. Searched for any null values, then rearranged some values because they didn't match.
7. Filled those null values properly, then merged the dataframes again.
8. Used Matplotlib to show how many happy/unhappy countries there are using bar plot.
9. Used horizontal bar plot to show top 10 and bottom 10 happiest countries and their ladder scores. Also, added a vertical line that shows the mean of the ladder score.
10. Grouped the merged dataframe on region using Pandas groupby() function.
11. Used bar plot to show every region's ladder score.
12. Finally, used Plotly to visualise ladder score ranking on the World map, Europe map, Asia map and Africa map.
