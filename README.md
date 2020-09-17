# Donald Trump's 2019 Fundraising

A visualization of Donald Trump's fundraising throughout the 2019 year. This was my part of a final group project for a masters course on python and data visualization. 

NOTE: This project does not involve any political commentary one way or another. It was simply a look at trends in Presidential fundraising. We chose the topic becuase we had access to the data and thought it would be interesting to investigate.

NOTE: The size of the original csv holding Trump's campaign data is too large for github at almost 500 MB. Therefore, I have included a smaller csv file holding only the first 1000 rows. Unfortunately the graphs will not show up correctly. If you would like the see the graph functionality please reach out and I will get you the entire dataset.

The goal of the visualizations in this notebook was to look at Trump's fundraising amounts in relation to his rally dates. We were looking to see if the 'spikes' in his fundraising occurred on or near dates of his rallies across various states and cities. 

We webscraped for a list of Trump's rally dates and imported some previously cleaned data on donations to his campaign. As this is part of a final academic project, I have not included those notebooks for academic integrity. I then utilized matplotlib to visualize the number of contributions to his campaign over time (data spans Jan 19 to Oct 19). The count of contributions seemed to be a better measure for the trend than dollar value, as dollar value could be skewed by a few significant donations. 

One top of the contribution data, I added red dashed lines to indicate the dates of his rallies in the respective city/state. I then used IPython and ipywidgets to make these two graphs (there is a city graph and state graph) interactive, and to allow the user to look at all the different cities and states in the dataset.

Conclusion
There are a few cities and states where the spike in contributions obviously coincides with a rally. However, we investigated these dates further and found that they were dates of national campaign pushes. Therefore, we concluded that donation spikes for Donald Trump in 2019 seemed to coincide more with national events and marketing pushes (such as accepting the GOP nomination) rather than local rallies. 

