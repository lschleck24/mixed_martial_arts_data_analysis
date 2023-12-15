# mixed_martial_arts_data_analysis

This is a data visualization project on a mixed martial arts dataset that contains data on all of the UFC fights starting from 1993. My project aim was to show what fighting styles were effective when the UFC started, what fighting styles win today in the modern UFC, what kinds of fighting techniques correlate with one another, and what makes certain dominant UFC fighters so effective. 

I created all of the visualizations in the project using plotly express and plotly graph objects. I used pandas dataframes in order to manipulate the data I was working with. I wrote my python code in a Jupyter Noteboook. 

The first set of visualizations that I created were a set of histograms that showed the relative victory methods for the first 150 UFC fights and then for the entire dataset. I also created a stacked bar chart that showed the relative victory methods for each of the weight classes for both men and women.

The next type of visualization I created was a correlation matrix that compared the usage of attempted techniques against eachother. I first scaled the data using SKLEARN preprocessing and then created a 7 x 7 matrix to see which techniques correlated with which. 

The last set of visualizations that I created was a set of boxplots that showed the quartile ranges for the number of times that certain techniques were used in fighting and used them to make an argument about fighters being considerd excpetional in regards to these techniques.
