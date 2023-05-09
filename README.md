<h1 align="center"> Blueberry Fruitmass prediction </h1>

<p align="center">
<img src="http://img.shields.io/static/v1?label=STATUS&message=Complete&color=GREEN&style=for-the-badge"/>
</p>

First, i created a heatmap with seaborn to check which variables to consider in the training dataframe.

![image](https://github.com/aurelioferrari/blueberry_yield/assets/105679141/864e3865-ff98-4f41-91c9-7e819dab58e4)

So I considered using ['clonesize', 'honeybee', 'bumbles', 'andrena', 'AverageRainingDays', 'fruitset'] as my training data. </p>

Appling RandomForestRegressor, I got a mean absolute error of: 0.008718054471511548

As the mean is 0.44634470253502057, the mean absolute error means 1.9%.
