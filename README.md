# White wine quality exploratory data analysis (EDA)
## R code to explore ~5k white wines dataset and initial regression analysis

## R project summary

- Conducted visual and statistical analyses of variables' univariate attributes
- Visualized potential relations between variables in bi- and multivariate plots
- Applied linear regression techniques to confirm assumed relations in the dataset


## Univariate commented plots section
Several variables of the dataset will be plotted in histograms to assess their fit for subsequent analysis. Where required, variables will be transformed in order to meet normal distribution targets. Boxplots will also be used to visualize distributions where needed. Variables in scope for this section include white wine quality, white wine fixed acidity, white wine volatily acidity, white wine citric acid, white wine residual sugar, white wine chlorides, white wine free sulfur dioxide, white wine total sulfur dioxide, white wine density, white wine pH value, white wine sulfates and white wine alcohol.

The plots can be viewed along with the full R code based output in the html file of this repository.

## Univariate analysis
After getting a visual impression of the dataset variables, key statistics are calculated. These include the range and the mean for the potential independent variables and a closer look at min, 1st quartile, median, mean, 3rd quartile and max for the potential dependent variable white wine quality.

Further observations made during the univariate analysis will be noted in the html output file.

## Bivariate commented plots section
Next step will be to explore relations between variables of the dataset. This section will be kicked off with a correlation matrix including as many variables as possible. Depending on the results, box-, scatter-, line- and smootherplots will be created to visualize the relation of certain variables.

## Multivariate commented plots section
Key bivariate plots will be enriched by added further variables to the graphics, e.g. via color coding. These will add new perspectives to the relation between dataset variables.

## Multivariate regression commented analysis
Once the plots have been obtained, a linear regression model will be build to confirm the relations in the dataset, especially the impact of independent variables on the dependent variable (white wine quality). Correlation coefficients will help interpreting the impact strength, regression model quality metrics such as r2 or adjusted r2 will be calculated to help understand the overall model strength. Where applicable and based on the univariate plots analysis, transformed variables, e.g. on log10 scale, will be used to check if they lead to increased model performance compared to their pre-transformed versions.

## Final plots, summary and reflection
Closing part for the project will be the final plots, summary and reflections sections. Key results will be visualized and discussed, the final regression model summarized. The reflection will cover specific methodological findings and an outlook on potential further use cases for the developed approach.
