# python-api-challenge

## Notes: 
When evaluating the linear regression models in the WeatherPy.ipynb file, the line_eq might not show on the graph depending on the sample cities the code at the start chose. 
I did not account for this when I initially set up my code and I had selected positions for the labeling specific to the outputs I had been given on a specific run of the data. When I re-ran the code before submission I noticed the new subset of data sihfted the graph and in some instances dropped the label of "y = __x + __" it also changed the coefficient for the linear regressions. This impacts the evaluations and conclusions I drew in the report un tehe sections "Discussion about the linear relationship". 
The broad generalizations should remain true, however the strength of the correlation that I made notes on will likely not match the outputs given. Overall, you should see the relationships trend in the same direction but depending on the subset of data, the strength of the correlation will eb and flow. 

#### Resources:
hvplot documentation: https://hvplot.holoviz.org/reference/tabular/scatter.html
cmap color scales: https://holoviews.org/user_guide/Colormaps.html
locating API url taxonomy: https://apidocs.geoapify.com/playground/places/
correlation strength: https://statisticsbyjim.com/regression/interpret-coefficients-p-values-regression/