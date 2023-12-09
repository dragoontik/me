---
title: Interquartile Range (IQR)
description: 'An Article about interquartile range (IQR) written by Pratik'
date: "2020-08-22T19:47:09+02:00"
---

<img alt="" class="bg ki ym c" width="700" height="467" loading="eager" role="presentation" src="https://miro.medium.com/v2/resize:fit:875/0*TA6axschjlIZsnrC">

*Photo by Annie Spratt*

## What is IQR?


IQR or InterQuartile Range is probably one of the most widely taught statistics in introductory courses, however it is in our opinion one of the least utilized in analysis. For those that haven’t heard or seldom use IQR, it is basically similar to the range being that it is a difference (subtraction) of two numbers, but instead of subtracting the maximum from the minimum we minus the 75th percentile by the 25th percentile of the numeric variable we are working with.

Percentiles are a separate topic, but basically you get the 25th percentile from the “median” of the true median of all the data and the minimum and that number becomes your 25th percentile. Your median of the maximum and the true median of all the variable values becomes the 75th percentile. And then your take their difference.

## Why Use IQR?

So to make this short article even shorter we will list the key points of why I think an IQR is a good statistic to really evaluate and consider in your analysis.

- The IQR contains 50% of your data centered around your median. (that is between 25th to 75th percentile centered around the median)


- The IQR is used in one simple but commonly taught method for detecting outliers (another topic for outliers)

- You can use the IQR to get an idea of how the values close to the median are spread out.

Overall, IQR is great for inspection and univariate analysis of your data when you don’t want to invoke a distributional assumption. For instance, if you think the data doesn’t quite fit a normal distribution the IQR can give you details about the data without relying on normality being assumed.

## When Should You Use IQR?

I am just going to give my list for when you should use it when you do data analysis.

1. When you’re not sure of a distribution your data fits
2. When you want to look at the data without any assumptions of the distribution
3. When you want a measure of spread about the median
4. When you want to know which range of values make up the center half of your numeric variable
5. When you do basic summary statistics analysis

Okay, so the last one is probably the most all-encompassing. IQR is actually commonly computed in most standard software as a summary statistic.

Well that’s all for this simple topic. Until next time guys. Happy mining!

*For more articles and content check out my <a href="https://www.youtube.com/channel/UCcPnyv1HXYEGxFsP6Z4P7yQ" target="_blank">YouTube Channel</a> if you like what I have to offer then please show your support and connect with me on <a href="https://www.facebook.com/ppatelfootball/" target="_blank">Facebook</a> and follow me on <a href="https://twitter.com/@dragoontik" target="_blank">Twitter</a>*
