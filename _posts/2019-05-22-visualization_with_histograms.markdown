---
layout: post
title:      "Visualization with Histograms"
date:       2019-05-22 16:47:41 +0000
permalink:  visualization_with_histograms
---


A histogram is a widely used graph that visualizes the distribution of data over a continuous interval or a certain period. The data is collected on the outcome of the process. A histogram is composed of bars along either the x or y axis. Each bar represents the frequency at each interval, commonly referred to as a bin. Histograms show the spread of the data. It also shows the frequency of a specific category in a data distribution. Like anything, there are pros and cons to using it. Some of the positives of a histogram is that you can easily see the mean, median, mode and range of a given dataset. This is useful to know when using a new data set to start a new project. By quickly creating a histogram you have a better idea of what you are working with. Another pro when using a histogram is you can see which factor(s) has a relatively higher frequency than others. This can help you ask questions about why this may be happening. 

When using histograms, it is important to understand the different type of distribution. This will help you interpret your data. The most common type of distribution is normal distribution. This will have a bell shape, meaning the mode is in the middle, similar to the median, and both sides tail off evenly. A similar histogram is a skewed distribution, which has an asymmetrical shape. This means the mode is either on the far right or far left and the other side tails off. A double-peaked distribution has two modes. This is often the outcome when two processes with different distributions are combined. A plateau is when there are multiple modes all having a similar value, giving the shape of a flat distribution. There are other types of distributions, but these are the most common.

If you want to create a histogram plot in python you can follow the steps below.

How to plot a histogram:
1. Download your dataset
2. Set your x value to one of the features in your dataset
3. Use the function plt.hist(x, bins=50, label=‘Square Feet’
4. Change you bins depending on what works for your data

