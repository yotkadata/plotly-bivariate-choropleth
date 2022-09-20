![Header image: Example of a bivariate map of EU countries](https://github.com/yotkadata/plotly-bivariate-choropleth/raw/main/img/header.png)

# Bivariate choropleth map using Plotly Choropleth Mapbox

Based on an example by [empet](https://chart-studio.plotly.com/~empet/15191/texas-bivariate-choropleth-assoc/#/), this Jupyter Notebook shows a method to create a bivariate choropleth map using Plotly.

**Choropleth** maps are a great way to visualize values in maps. But sometimes we not only want to show one variable, but the relationship of two. That's where **bivariate maps** come in. They show values of two variables using colors or symbols for each one of them. In the case of this example, we are using two colors that are blended together. That way, we can see areas were both variables are high or low and also those where one value is high and the other one is low.

When searching for ways to create bivariate maps using Plotly, I was surprised to find little information on how to do it. What helped me a lot, was the example that [_empet_ published on plotly.com](https://chart-studio.plotly.com/~empet/15191/texas-bivariate-choropleth-assoc/#/). I built on that and tried to make it more generic and reuseable. I hope it worked. This notebook walks you through the whole process.
