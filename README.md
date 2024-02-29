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
 

 

