
# Sampling and Descriptive Statistics
**[Statistics](https://en.wikipedia.org/wiki/Statistics)** is a branch of mathematics that concerns data collection, organization, analysis, interpretation, and presentation. Inferential statistics specializes in inferring the characteristics of a given **[statistical population](https://en.wikipedia.org/wiki/Statistical_population)** by analyzing a relatively small **[statistical sample](https://en.wikipedia.org/wiki/Sampling_%28statistics%29)** of the whole population. *Statistics to date is a core science for a Data Scientist.*

> A **data point or item or object** is an observation or an event that is somehow measurable. 
> A **population** is the whole collection of items (might be finite or infinite).
> A **sample** is a subset of the population containing the observed data points.

A population if it is finite it is called **tangible population** while if a population is infinite or virtually infinite it is called **conceptual population**.

## Sampling
There are different ways to sample data points from a population and not all of them are interchangeable for a good outcome of a specific statistical analysis; indeed, the sample of a population has to be chosen/extracted in an appropriate way. The most common sampling method is **random sampling** and the most basic one is called **Simple Random Sampling** (SRS).

> A **Simple Random Sample** (**SRS**) of size *n* is a sample created by a procedure in which any set of *n* data points (sampled from the population) is equally likely to make up a sample. 

In some circumstances, it's not possible to perform a real SRS, if so the sample it's called a **sample of convenience**. 
> A **sample of convenience** is a sample that is not drawn by a well-defined random method.

An SRS it's not guaranteed to represent the whole population perfectly, indeed, an SRS always differs in some ways from the population, and rarely it substantially differs. Given this premise, we can logically affirm also that two different SRS drawn from the same population are somehow different this phenomenon is called **Sampling Variation**. 

There is another characteristic to note when performing sampling: **independency**. When the sample is drawn from a **tangible population** the items of an SRS are not strictly independent because the sampling of one item is changing the population itself and might give some information regarding the next sample, namely: 
> The samples of a population are said **independent samples** if knowing the value of some of the sampled items does not provide information to predict the values of other items.

This phenomenon often arises when the population is relatively small. While if the population is relatively big this change in the population is negligible and the samples might be considered independent. To contravene this issue comes into help the **sampling with replacement** to virtually handle the population as a conceptual population making sure that the samples are truly independent.

Sampling from one population means there is only one population of interest (**one-sample** experiment) while a **multi-sample** experiment observes multiple populations at the same time and a sample is drawn from each population each time.

**Other sampling techniques than SRS**: weighted sampling, stratified random sampling, cluster sampling.

## Descriptive Statistics
Descriptive statistics aim is that of describing features of a data set by generating summaries about data samples. But.. not all data is the same...

### Types of Data
Data can be very different in its representation and its nature, and because of this reasons data types can belong to at least two macro-categories:
- **Numerical (Quantitative)** 
	- *Discrete* (integer numbers)
	- *Continuous* (real numbers) 
- **Categorical (Qualitative)**
	- *Ordinal* (rating stars on a website)
	- *Nominal* (ethnicity or gender) 

**Numerical data** has several properties such as an implicit *natural order* and it is possible to define some *mathematical operations* over it. While **Categorical data** it's not granted to hold some implicit natural order and often it's not possible to define mathematical operations over it. ("YOUNG" and "OLD" categorical are ordinal attributes and might have an order but "MALE" and "FEMALE" do not have an implicit order, even though both attributes are categorical and thus are called categorical nominal).

### Summary Statistics
Summary statistics apply more to *Quantitative Data* but some can be applied to *Qualitative Data* as well...
