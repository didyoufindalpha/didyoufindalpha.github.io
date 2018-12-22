---
layout: post
title: Statistics-101 for Data Noobs!
---

It’s a fact that you can’t play around with data if you can’t do statistics. Though statistics is not the most important part of learning and doing Data Science, but it is needed and plays a major role in making you a better data scientist who moves forward with a structured approach.
So, here are some descriptive statistics key terms that I think that every data-guy should know and their python code brewed in the easiest of manners.

1. **Descriptive statistics**

**Descriptive statistics** give information that describes the data in some manner. For example, suppose a pet shop sells cats, dogs, birds and fish. If 100 pets are sold, and 40 out of the 100 were dogs, then one description of the data on the pets sold would be that 40% were dogs. A graphical representation of data is another method of descriptive statistics.

2. **Population**

A population is a selected individual or group representing the full set of members of a certain group of interest.

**3. Sample**

A sample is a subset drawn from a larger population. If this drawing is accomplished in such a manner that each member of the population has an equitable chance of selection, the result is referred to as a **random sample**.

4. **Parameter**

A parameter is a value which is generated from a population. If I had all the data of all humans on Earth and generated the mean age, this value would be a parameter.

5. **Statistic**

A **statistic **or **sample statistic** is a single measure of some attribute of a sample (e.g., its arithmetic mean value). It is calculated by applying a function (statistical algorithm) to the values of the items of the sample, which are known together as a set of data.

**6. Generalisability**

Generalisability can be described as the ability to draw conclusions about the characteristics of the population as a whole based on the results of data collected from a ‘sample’. This is ability is not a given, and depends heavily on the nature of sample collection, sample size, and various other factors.

7. **Distribution**

A distribution is best described as the arrangement of data by the values of one variable in order, from low to high. This arrangement, and its characteristics such as shape and spread, provide information about the underlying sample.

**8. Mean**

Mean, along with median and mode, is one of the 3 major measures of central tendency, which collectively evaluate an important and basic aspect of a distribution. The simple arithmetic average of a distribution of variable values (or scores), the mean provides a single, concise numerical summary of a distribution. The mean is also likely the most common statistics encountered in general research. Population mean is denoted μ, while sample mean is denoted x̄.

**9. Median**

Median is the score of a distribution residing at the 50th percentile, separating the top and bottom 50 percent of scores. The median is useful for both splitting a set of distribution scores in half and helping to identify the skew of a distribution.

**10. Mode**

The mode is simply the score which appears most frequently in the distribution. Multimodal refers to a distribution with more than one mode; bimodal refers to a distribution with 2 modes.

**11. Skew**

When there are more scores toward one end of the distribution than the other, this results in **skew**. When the scores of a distribution are more clustered at the high end, the relatively fewer number of scores on the low end result in a tail, with the scenario being referred to as negative skew. Positive skew is when a distribution shows a tail at its high end. So basically, in a negatively skewed distribution, we would expect the mean to be less than the median, while in a positively skewed distribution, we would expect the mean to be greater than the median.

**12. Range**

When dealing with dispersion dispersion, the range is the difference between the maximum and minimum values of a distribution.

**13. Variance**

Variance is the statistical average of the dispersion of scores in a distribution. Variance is not often used on its own, but can be a useful calculation on the way to a more descriptive statistical measurement, such as standard deviation.

**14. Standard Deviation**

The standard deviation of a distribution is the average deviation between individual distribution scores and the distribution’s mean. Individually, the standard deviation provides a good measure of how spread out a disquisitions scores are. When considered alongside the mean, these 2 measures provides a good overview of the distribution of scores.

**15. Interquartile Range (IQR)**

The IQR is the difference between the score delineating the 75th percentile and the 25th percentile, the third and first quartiles, respectively.

**Mathematically, IQR = Q3 — Q1**

> Python representations of some of these terms:

<script src="https://gist.github.com/debuggermalhotra/7671faae2dac62fc8181a5af1e55fbf8.js"></script>
