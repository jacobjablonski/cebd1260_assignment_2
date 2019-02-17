# cebd1260_assignment_2

# Data analysis using Pandas and Jupyter Notebooks

This blog post will outline several methods and techniques for choosing a data set, methods of uploading and extraction as well as analysis of the data set. 

For this particular exercise, I decided on a topic that was a little bit outside my comfort zone and area of expertise. The chosen set was a 500mb excel file of world development indicators. The shape of this data was 5656458 rows and 6 columns, which featured items such as country name, indicator code, year and value (with respect to the indicator code). 

## Method

The initial problem with my data set was that, although it was featured on Kaggle and contained about 2.2 gb of information; the only way to access was via GoogleBigQuery or via a Kaggle kernel. This was an interesting experience as I never had used big query before. After many failed attempts to access the cluster, I never did manage to access the data set. Although I did find out what Kaggle kernels are, and that will definitely be of interest for future projects.

My method of upload and extraction initially began with attempting to upload the data set to amazon s3 services. Another road block occurred, in that I could not successfully access the bucket with the jupyter notebook so I decided the store the file locally to eleviate further headaches.
  
## Problem

A potential business problem revealed itself towards the end of the analysis. Given all of these economic indicators I found it very difficult to classify their importance with respect to each another. The problem would be to classify these indicators into ‘bins’ and giving these bins a certain ‘weight’ or ‘score’, this way NGO’s and governmental agencies could have more of a live snapshot of their economic problems. Although I did not infect get to this portion of the data I would definitely like to revisit it in the future and see if its possible. In this analysis I mostly looked at a few world development indicators of larger countries.

## Analysis

My first analysis will be of the percentage of parliamentary seats held by women in Russia from 1960-2013.

This analysis was the first graph that looked like it had a story behind it. Reading the data it seemed as though 15% of the parliamentary seats were held by women in 1990 and the same percentage in the 2010’s. However, in the early 2000’s it looks as though that number was halved. To put this in perspective there are currently 620 seats in total, 15% being around 90 seats belonging to women. It is very interesting to note that at the turn of the millennium, Russia’s newest president was in fact Vladimir Putin. It is hard to say whether this is a positive correlation or just a causation but interesting nonetheless.

The second analysis will be the fertility rate and GDP in china from 1960-2013.


This plot showed an upwards trend in China’s GDP with a steep increase in the at the turn of the millennium. With a bit of research I found out that the reason for China’s massive success, was due to the fact that China is a mixed economy based on capitalism and command economics. Furthermore China’s biggest companies are actually owned by the state itself. They also have legislature in place basically stating that, if you want to sell products in the Chinese market, you have to have a factory in china, as well as, employ Chinese citizens. My next development indicator was fertility rate in china (per 1000 women). This was perhaps the most interesting find of all, as when I looked at the fertility rate fall, it reminded me of the GDP rising very quickly in the previous analysis. I was not mistaken in thinking these two variables were related as it was partly because Deng Xiaoping enlisted overpopulation as one of his Four Modernizations, setting a goal to keep the population at 1.2 billion by 2000 as part of the formula for quadrupling China’s GDP within the same period. This is very interesting because in the above graph, it is clear he has accomplished this colossal feat.

