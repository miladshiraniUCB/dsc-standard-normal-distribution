
# Standard Normal Distribution

In this lesson, we will introduce a special case of normal distributions called "The Standard Normal Distribution".

## Objectives
Students would be able to :
* Compare and contrast the normal and the standard normal distribution
* Understand the process for normalizing data by converting it to the standard normal distribution

### Introduction

Previously, we talked about normal (or gaussian) distribution characterized by a bell shape curve. We also identified the mean and standard deviation to be the defining parameters of a normal distribution. As discussed, normal distributions do not necessarily have the same means and standard deviations. 

The standard normal distribution is a special case of the normal distribution. A normal distribution with a mean of 0 and a standard deviation of 1 is called a standard normal distribution as shown below:
<img src = "snorm2.png" width = 500>

IF we plot a continuous cumulative distribution function as we saw earlier, for a standard normal distrubtion, the cdf would look like this. 
<img src = "snorm1.png" width = 300>

Thinking back to the standard deviation rule, since the standard deviation is equal to one, we can say that
* 68% of the area lies between +1 and ‐1 sd
* 95% of the area lies between +2 and ‐2 sd
* 99% of the area lies between +3 and ‐3 sd

## z-Scores
Any normal distribution can be converted to a standard normal and vice versa using these
equations. The standard normal distribution is used to calculate standard score (more commonly referred to as a z-score). These distributions and calculated z-score are particularly useful because these:

1. Allow us to calculate the probability of an observation occurring within our normal distribution and 
2. Enable us to compare two observations that are from different normal distributions. 

Normal distributions can be transformed to standard normal distributions by the formula:
<img src="zform.gif" width = 200>

> Here X is a score from the original normal distribution, μ is the mean of the original normal distribution, and σ is the standard deviation of original normal distribution. 

The standard normal distribution is sometimes called the z distribution. A z score always reflects the number of standard deviations above or below the mean a particular score is. 

### An example 

For instance, if a person scored a 70 on a test with a mean of 50 and a standard deviation of 10, then they scored 2 standard deviations above the mean. Converting the test scores to z scores, an X of 70 would be:

#### z = (70 - 50) / 10  = 2

So, a z score of 2 means the original score was 2 standard deviations above the mean. Note that the z distribution will only be a normal distribution if the original distribution (X) is normal. 

Thinking on these lines, you can also convert a z-score back to a original score (X) by using same formula as:

<img src="rev.png" width = 200>


For above exmaple, this would work out as:
#### X = 50 + 2(10) = 70

So you see , as we mentioned initially, a standard normal distribution can be a power way to analyze observations in terms of their distance from mean and can also identify actual value of an observation - all based on z-score and standard normal distributions. 

## Summary

In this lesson we looked at a special case of normal distribution called the standrd normal distribution. We also saw how to convert any normal distribution to standrd normal distribution using the z-score. We shall continue on working on this notion in the following labs. 