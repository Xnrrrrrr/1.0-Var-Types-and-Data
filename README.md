# 1.0-Var-Types-and-Data

Independent vs. Dependent Variables
![image](https://github.com/Xnrrrrrr/1.0-Var-Types-and-Data/assets/133546385/427f1b6b-eb35-4cf1-a495-54d259473943)


Typically before we run any inferential analysis we have a research question or hypothesis that we are trying to test. Examples of such research questions within the context of Security may include:

Is there a relationship between the number of people affected in a cyber attack and the financial loss incurred by an organization?
Does the type of cyber attack used have an impact on the number of records breached?
Can the number of records breached be predicted by the number of controls used by the organization?
When determining how to test these questions, you’ll first need to know what your independent and dependent variables are in your research question.

Independent Variable (also known as the IV, predictor, or X variable) is the variable we identify as the potential cause. It is used as the input for determining relationships between variables, and its value does not depend on the other variable.
Dependent Variable (also known as the DV, outcome, or Y variable) is the variable we identify as the effect. Its value is influenced by (i.e. dependent on) the IV.
In the first research question provided above, the independent variable is the number of people affected in a cyber attack and the dependent variable is the financial loss incurred by an organization. Essentially we are proposing that changes in the financial loss (DV) will be dependent on how many people are affected (IV). In the second research question, the independent variable is the type of cyber attack and the dependent variable is the number of records breached. The independent variable is not always stated before the dependent variable. For example, in the third research question, the independent variable is the number of controls used and the dependent variable is the number of records breached.

The specific circumstances of the situation will likely dictate which variable should be the IV and which should be the DV. To determine which is which, ask yourself what am I trying to predict? Whichever variable you choose as the answer to that question will be classified as the dependent variable. If there is a chronological order to when each variable’s value is determined, the IV will usually occur first. For example, if accounts were compromised and then money was stolen from them, it makes sense for the number of accounts compromised to be the IV, but if the system processes were compromised and then accounts were affected by them it may make more sense to use the financial loss as the IV. So in the first example above, the IV and DV would switch if we were trying to predict if the number of people affected was dependent on the financial loss.

Categorical vs. Continuous Variables
Take a moment to think about how you would classify each of the following variables:

Gender
Age
Ethnicity
Height
Shoe Size
At this point you may have made the following classifications. Gender, ethnicity, and shoe size are categorical, whereas age and height are continuous. However, the classifications could really vary based on how the data were collected. Some researchers discuss gender in the context of range of masculinity and femininity, this does not break down into discrete categories of genders but rather varies on a continuous scale. We can also discuss age based on age groups 0-10, 11-18, 19-25, 26-35, etc, as opposed to the number of years the person has been alive. That would make the data categorical as opposed to being continuous. Shoe size is another ambiguous variable in this list, we could discuss the actual length of the shoe which would be different from the categories of shoe sizes available. Given these nuances, what rules of thumb can we use to determine whether or not data is categorical or continuous?

This question may seem difficult to answer but a key guideline that can help us differentiate between these two variable types is that categorical variables have values that consist of separate indivisible categories whereas continuous do not. This essentially means that you are able to interpret fractions between whole numbers for a continuous variable but not for a categorical variable. So assigning people to age groups such as 0-9, 10-19, 20-29, etc is categorical, but classifying the same data as ‘number of decades lived’ with values of 0, 1, 2, etc would be continuous because 1.5 decades is interpretable, but halfway between 0-9 and 10-19 is not. It is important to note that whether a categorical variable has two categories or a thousand it is still categorical if this property of the data exists.

Levels of Measurement

Categorical and continuous variables form the broad classifications of variables. We can fine-tune our descriptions of these data even further by discussing levels of measurement.

It is important to be able to differentiate among these because the level of measurement of the variable you are examining will influence the types of descriptive and inferential statistics that you are able to conduct.

There are four main types of levels of measurement. These build on each other such that as we go along the spectrum the scales become more precise.

![image](https://github.com/Xnrrrrrr/1.0-Var-Types-and-Data/assets/133546385/f5e518e6-b218-4f0c-9bae-f5207d499bc5)

Nominal - At the lowest end of the continuum is a nominal scale. With nominal scales, as the name suggests, numbers are assigned mainly to name or identify the variable. The value of the number is not meaningful nor is the distance between the numbers. A common example of this is gender. If we assign a 1 for male and a 2 for female in a data set, we cannot interpret that women are better because the value assigned to them is higher. We also cannot interpret fractions between the categories of male and female.

Ordinal - Ordinal scales are more precise than nominal scales. With such scales you are able to interpret the value of the number but not the distances between the numbers. A classic example of this can be found in the context of sports. Athletes that are placed first and second in a race during the Olympics have only fractions of seconds in the difference between their times. As opposed to athletes that are placed first and second in a high school race who would have seconds and maybe minutes in the difference between their times. Ordinal scales treat these two cases the same because they don’t take into account the distances between the numbers. These scales only take into account the position or rank of the number. Both nominal and ordinal scales are considered to be categorical variables because in both scales the distance between the values is NOT interpretable.

Interval and Ratio - On the other end of the spectrum, interval and ratio scales are more precise, with ratio scales being the more precise of the two. Both scales are considered to be continuous because it is possible to interpret the distances between the values. The difference between an interval and ratio scale is that a ratio scale has a true 0 point whereas an interval scale doesn’t. An example of this can be seen with the measurement of temperature in which a Fahrenheit or a Celsius scale are both considered interval scales because a 0 on that scale does not reflect the absence of heat. However, on a Kelvin scale, there is a true 0 point in which 0 indicates no heat. Teasing apart the differences between interval and ratio scales can be difficult. Throughout the rest of the course we will be collapsing these two scales of measurement into one. However, it is important to know that there is an underlying difference between these two.


Take a moment to think about how you would match the scale of measurement on the left to the variables represented on the right:

Measurement Type	Type of Variable
1. Nominal	A. Country of Birth
2. Ordinal	B. IQ scores
3. Interval	C. Weight, Height, Temperature
4. Ratio	D. Faculty Position (Assistant, Associate, Full)
 

 Descriptive vs. Inferential Statistics
Before discussing descriptive statistics, we first need to have a shared understanding of what it is. In this course, I’ll make references to both descriptive and inferential statistics. The key differences between these two:

Descriptive statistics help us understand general trends in the data by providing summary statistics of its shape, average, or the spread of the scores.
Inferential statistics allow us to take the data analyses a step further by using our sample data to make inferences about the broader population.
We’ll talk more about inferential statistics later on in the course but for now let’s explore what is meant by descriptive statistics.

 

Ways to Describe Data
Describing Data
There are 3 main ways to describe data:

![image](https://github.com/Xnrrrrrr/1.0-Var-Types-and-Data/assets/133546385/58a74125-4627-4747-8955-52645f6842e7)


Shape – How the data looks when it is graphed
Central tendency – The average of the data (i.e. the mean, median, and mode)
Variability – The spread of the data
Shape
By now, you should have heard a lot of discussion around the normal distribution, sometimes called a bell-shaped curve. The normal distribution is something that we rely a lot on in statistics. It was discovered by a Belgian mathematician in 1870. He was collecting information from soldiers in World War 1 on height, age, IQ scores, and chest sizes and noticed that a consistent theme kept emerging in the frequency of the information, in which there would be a clear peak in the values and a consistent dip in the numbers on either side of the most frequent number. This pattern was referred to as the normal distribution. Since then we have assumed that most continuous variables are in theory normally distributed.

![image](https://github.com/Xnrrrrrr/1.0-Var-Types-and-Data/assets/133546385/c4e53ff4-807f-44a5-b61d-ab77cf007c63)


Source: Kranzler, J. H. (2006). Statistics for the Terrified (4th ed.). Prentice Hall.

The importance of this assumption is that if most continuous variables are normally distributed then just by knowing the mean and standard deviation of the distribution, we can predict where most of the scores in the distribution will lie.

![image](https://github.com/Xnrrrrrr/1.0-Var-Types-and-Data/assets/133546385/3f67203b-4a3b-4442-935d-4b4260bb1fa3)

Graph showing a normal distribution divided into standard deviations with 34.13% from 0 to +1, 13.59% from +1 to +2, and 2.28% beyond +2

Source: Gravetter, F. J., Wallnau, L. B. (2010). Essentials of Statistics for the Behavioral Sciences (7th ed.). Wadsworth.

As shown in the graphic above, in a normal distribution 34.13% of the scores would fall within 1 standard deviation above (or below) the mean (µ), an additional 13.59% of the scores in the distribution would fall within 2 standard deviations above (or below) the mean, and an additional 2.28% of the scores would fall (i.e., almost all the data) within 3 standard deviations above (or below) the mean.

The spread of the data in the normal distribution based on the mean and standard deviation is what we rely on when we run an inferential statistics test and discuss statistical significance. For some analyses, if the shape of the distribution departs from normal, one of the statistical assumptions of the test gets violated and we can reach erroneous conclusions. It is therefore important to be able to recognize the correct shape of the normal distribution and to be aware of the abnormalities that can occur in its shape.

The normal distribution has three key features

Its symmetric
If you cut it down the middle vertically, then the half on the left-hand side would be a mirror image of the half on the right-hand side
Its unimodal
It has one clear peak in the shape of the distribution
Its asymptomatic
The distribution approaches 0 on the x-axis but never touches it
Types of Abnormalities
Positive and Negative Skew
![image](https://github.com/Xnrrrrrr/1.0-Var-Types-and-Data/assets/133546385/8de11a2a-d0e4-475c-95aa-36d352bcb3d0)

Skewness refers to the pull of the scores to one side of the distribution, which can cause the shape to become asymmetric.

The shape of the distribution could become asymmetric due to the presence of extreme scores (or outliers) on the right side of the x-axis, your distribution would then be described as being positively skewed. You are likely to find positively skewed distributions in a variety of situations. In a classroom, a student who scores much higher than the rest of the class is likely to make the distribution become positively skewed. On the other hand, the presence of extreme scores on the left side of the x-axis would cause your distribution to be negatively skewed. An example of a negatively skewed distribution could also be seen in a classroom setting when a student scores much lower than the rest of the class. Both positively and negatively skewed distributions are considered to be non-normal.
graph of positive skew with the right side of the distribution curve stretched out further than the left sidegraph of negative skew with the left side of the distribution curve stretched out further than the right side

Positive and Negative Kurtosis

Kurtosis refers to how peaked or flat the distribution is.

If the distribution is too peaked (meaning that there is very little variability in the data) then the distribution is said to be leptokurtic or having positive kurtosis. An example of a context in which you would find a peaked distribution would be in the ages of students in a college freshman class. In this context, there would be very little variability in the range of ages. Another example of when you would find a peaked distribution would be in the heights of individuals on a basketball team, such individuals are likely to be very similar in how tall they are. In essence, contexts in which you are likely to find very homogenous entities lend themselves to having leptokurtic distributions.

If the distribution is too flat (such that there is too much variability in the data) then the distribution is said to be platykurtic or having negative kurtosis. Examples of platykurtic distributions are hard to find but they occur when it’s difficult to find a clear mode in the distribution or when there are extreme scores on both ends of the distribution.
![image](https://github.com/Xnrrrrrr/1.0-Var-Types-and-Data/assets/133546385/e76dc3f5-075f-4f22-ba01-bfbab33f0fc8)


Bimodal refers to a curve with two peaks.


This typically happens when you take two normal distributions and put them together in the same dataset. Let’s say for example, I had a set of data from which I was only interested in the results from the top half and bottom half of the distribution. I went ahead and pulled the top ten performing individuals and bottom 10 performing individuals and started running parametric analyses on the data. This is problematic because each distribution is likely to have its own normal curve with its own mode. This variable would have two clear modes and two completely different distributions. By cutting out the middle values, I have created a bimodal distribution that is likely to produce inaccurate results in my statistical analyses.
![image](https://github.com/Xnrrrrrr/1.0-Var-Types-and-Data/assets/133546385/a0e4134b-6d0b-4696-a257-62d6eb5587b6)

Central Tendency
The second way to describe data is through discussing its central tendency or average. The three main types of central tendency are

Mean - which is the arithmetic average
Median - which is the central most score in the distribution
Mode - which is the most frequent score in the distribution
Determining these types of central tendencies should be a review for you from your earlier statistics classes. What is important to note about these measures is that even though our default average is often the mean, there are several situations in which the use of the mean would give us inaccurate results. These situations are discussed in the section that follows below.

Measures of central tendency can also give you a quick indication of the shape of your distribution. In a positively skewed distribution you will often find that your mean > median > mode. In a negatively skewed distribution, you will often find the opposite, in which your mean < median < mode. In a normal distribution, it is often common that the values for your mean, median, and mode are equal or fairly close to each other. 

Reasons for Using the Median Instead of the Mean

Some examples of when we should use the median instead of the mean:

When extreme scores are in your data set. In these situations the mean provides an inflated estimate of the average. In such situations it is best to use the median, which takes into account the presence of the extreme score but is not impacted by its extreme value.
![image](https://github.com/Xnrrrrrr/1.0-Var-Types-and-Data/assets/133546385/6bf4c152-2300-49e6-958b-914f10100dc8)

Source: Kranzler, J. H. (2006). Statistics for the Terrified (4th ed.). Prentice Hall.

When we have missing values in our distribution. In such situations, we rely on the median because we are not clear on the size of the missing value. Given that the median accounts for the presence of the value but not the magnitude of the value, it would be the best estimate in such an instance.
When we are not clear on what the tail ends of the distribution are. For example, a study classifying the frequency of video game usage per week along a scale of 1 hour, 2 hours, 3 hours, and 4 or more hours would be using an open ended distribution. In such a situation, it would be misleading to calculate the average video game usage using the mean because we do not know exactly what values are included in the “or more” category.
When we have an ordinal scale of measurement. With such scales, the value of the number indicates the position or rank of the scores but the distance between the numbers is not interpretable. In such a case, the median is the best estimate of central tendency because it takes into account the ordering of the numbers without being influenced by the magnitude of the numbers.
Reasons for Using the Mode Instead of the Mean or Median
There are also situations in which the use of the mean or median would produce inaccurate results. These situations include:

When your data is at a nominal level, meaning that the value of the number is only used to name the variable and should be interpreted to represent rankings. We often see this with gender in datasets in which they are coded as 1 being male and 2 being female. However, these numbers are solely for labeling purposes it does not mean that a woman is ranked higher than a man because the value of the number is larger. With this kind of data the mode is the best measure of central tendency to use.
When we are dealing with data that should represent a whole number. These types of variables are referred to as being discrete. The most common discrete variable that you may run into is the number of people. For example, when discussing the average number of students in different classes, it is best to quote the mode and not the mean because the mean is likely to give you a decimal figure or fraction that is not interpretable.
When we want to get a quick approximation of the shape of a distribution. In a normal distribution, there are exceptions to this, but typically the mean is equal to the median, which is equal to the mode. Therefore, instead of having to use a calculator to determine the mean of a distribution you can quickly scan the data, identify the most frequent number, and get a better sense of what the mean and median would be.
Variability
The third way to describe data that we’ll discuss is its variability, which refers to how spread out the scores are. Note that variability can only be discussed in relation to continuous data which can only occur with data at the interval and ratio scales of measurement.

The most efficient way to get a sense of the spread of scores in a distribution is to compute the range. The range is essentially the lowest score subtracted from the highest score in the distribution.

![image](https://github.com/Xnrrrrrr/1.0-Var-Types-and-Data/assets/133546385/607abf7b-6276-4986-8b46-ff051b3b308b)

However one of the problems with using this estimate is that it is heavily influenced by outliers and it doesn’t really take into account which other scores are in the distribution. To get a more accurate estimate of the spread of scores you can compute the deviation scores.
![image](https://github.com/Xnrrrrrr/1.0-Var-Types-and-Data/assets/133546385/d0260137-47de-4904-a0db-2532f8d3825c)


The advantage of these scores over the range is that it gives you information on how much each score in the distribution deviates from the mean. The main disadvantage of deviation scores is that if you summed all the deviation scores up you would get a sum of zero. To get around this problem, we can square each set of deviations and then sum them. This is referred to as the sum of squares, which I’m sure was discussed quite a bit in your previous statistics classes.
![image](https://github.com/Xnrrrrrr/1.0-Var-Types-and-Data/assets/133546385/74f79282-3549-42a6-a1d8-5a3e471bb4f8)


To account for the total number of scores in the distribution, we can divide the sums of squares by the sample size. This would produce an estimate of the variance.
![image](https://github.com/Xnrrrrrr/1.0-Var-Types-and-Data/assets/133546385/5ed3bdf0-9929-4347-9862-141b4d04b24b)


Finally, to change the estimate of variability back to the original scale of the values used to compute it, we need to take the square root of the estimate. This is how we end up with the standard deviation.
![image](https://github.com/Xnrrrrrr/1.0-Var-Types-and-Data/assets/133546385/dc34f50f-ed02-4988-9bab-ac4dcefce676)


The mean and standard deviation form the foundation of several statistical concepts that we’ll discuss in this course. If you look at some of the most common inferential statistics discussed in the course, you can see that the equations are made up of calculations of the sums of squares or the mean and standard deviation.

