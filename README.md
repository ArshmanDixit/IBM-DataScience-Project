# IBM-DataScience-Project

Capstone Project for IBM Data Science Professional Certificate. This project encapsulates all the data scientist responsibility and provide a brief introduction to world of Data Science.

![Rocket Landing](https://camo.githubusercontent.com/a0184ea6ee7174857c755b964345c82ec9556f17e74fd5f6a49b5937711fd60f/68747470733a2f2f63662d636f75727365732d646174612e73332e75732e636c6f75642d6f626a6563742d73746f726167652e617070646f6d61696e2e636c6f75642f49424d446576656c6f706572536b696c6c734e6574776f726b2d445330373031454e2d536b696c6c734e6574776f726b2f6170692f496d616765732f6c616e64696e675f312e676966)

## Background
SpaceX, a leader in the space industry, strives to make space travel affordable for everyone. Its accomplishments include sending spacecraft to the international space station, launching a satellite constellation that provides internet access and sending manned missions to space. SpaceX can do this because the rocket launches are relatively inexpensive \\$62 million per launch due to its novel reuse of the first stage of its Falcon 9 rocket. Other providers, which are not able to reuse the first stage, cost upwards of \\$165 million each. By determining if the first stage will land, we can determine the price of the launch. To do this, we can use public data and machine learning models to predict whether SpaceX – or a competing company – can reuse the first stage.

## Executive Summary
The research attempts to identify the factors for a successful rocket landing. To make this determination, the following methodologies where used:

1. Collect data using SpaceX REST API and web scraping techniques
2. Wrangle data to create success/fail outcome variable
3. Explore data with data visualization techniques, considering the following factors: payload, launch site, flight number and yearly trend
4. Analyze the data with SQL, calculating the following statistics: total payload, payload range for successful launches, and total # of successful and failed outcomes
5. Explore launch site success rates and proximity to geographical markers
6. Visualize the launch sites with the most success and successful payload ranges
7. Build Models to predict landing outcomes using logistic regression, support vector machine (SVM), decision tree and K-nearest neighbor (KNN)


## Conclusion of Project

1. Model Performance: Decision Tree slightly outperformed other models on the given data. It may be different if we had more data points for training.
2. Equator: Most of the launch sites are near the equator for an additional natural boost - due to the rotational speed of earth - which helps save the cost of putting in extra fuel and boosters
3. Coast: All the launch sites are close to the coast
4. Launch Success increased over time. They learned from their mistakes!!
5. KSC LC-39A: Has the highest success rate among launch sites. Has a 100% success rate for launches less than 5,500 kg. (But we can't make this as a fact since the count of launches were not the same for each launch site)
6. Orbits: ES-L1, GEO, HEO, and SSO have a 100% success rate
7. Payload Mass: Across all launch sites, the higher the payload mass (kg), the higher the success rate
