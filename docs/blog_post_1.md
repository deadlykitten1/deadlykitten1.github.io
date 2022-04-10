# Z-Tests vs. T-tests: Statistical Analysis on Normal Distributions

Everyone, statistically edjucated or not, has heard of Normal Distributions. They are ubiquitous in statistics and in many real life datasets. That said, without understanding how to analyze normal distributions, they will not lead to any additional insights.

There is where Z-Testing and T-testing come in. Both of these testing frameworks allow you to perform statistical analysis on a normally distributed set to understand whether said set is part of a larger population. One common use for a test like this is comparing a certain experimental set (volunteers in a experiment for pharmaceuticals, voters in a specific county, etc.) is part of a larger population of which you understand more (people who have not had the experimental drug, voters in the whole country, etc.). 

Z-tests are only applicable if you know the population's mean, and can directly create a normally distributed probability density graph based on that mean. T-tests are more flexible, as they approximate the population's mean with your subsets mean. Because of this, they are also less precise, and lead to a higher probability of false positives.

Both of these tests would fail if averages over population subsets were not normally distributed. This is known as the central limit theorem: even though a certain subset of data is not normal, it's aggregates are.