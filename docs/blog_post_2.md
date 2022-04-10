# House Flipping in Washington State's King's County

On my journey to become a full time data scientist, I will be creating five unique projects, each more complex than the last. This blog post is about my second project.

We were given a data set of about 15,000 homes in King's County, WA that were sold in 2014-15. My group decided to approach our project with the stakeholder of a real estate investor in mind, specifically one that wanted to flip houses. 

Our data set contained massive amounts of information about each home: year built, condition, square footage, bedrooms, bathrooms, etc. Our hypothetical investor wants to determine which homes are best to flip. Our task was to use our newfound statistical knowledge to answer this question based on our data

I'm very proud of the methodology we came up with. We noticed in our exploratory analysis that homes in poor and fair condition had a much lower median sell price than average and up homes. So, we decided to split the data into two groups: one containing homes in above average conditions, and another containing homes in below average conditions. We then trained a linear regression model on our homes with above average conditions. After we improved our model's accuracy to a satisfactory level (87% to be exact), we fed the poor condition homes to it. Our model assumed that those homes were in good condition (because it was trained independent of condtion) and estimated a sell price based on all the other factors of those homes.

Whichever homes had the greatest profit margin (our model's predicted price minus its actual price and an estimated renovation cost) were the homes that we recommended to our theoretical house flipper. This project was a lot of fun and was a great first step into predictive modeling! I am excited to learn ways to more accurately predict variables in the machine learning section.