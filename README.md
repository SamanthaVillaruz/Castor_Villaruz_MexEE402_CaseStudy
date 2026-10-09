# Castor_Villaruz_MexEE402_CaseStudy

# MexEE 402: Data Preprocessing Case Study

MexEE Elective 2: Data Science and Machine Learning
Batangas State University, Alangilan Campus
1st Semester, AY 2026-2027

## Members

| Name | Student Number | Section |
|---|---|---|
| Castor, Vien Melvin |22-03687 |Mexe - 4103 |
| Villaruz, Samantha |22-07711 |Mexe - 4103 |

## Notebook links

| Chapter | Castor | Villaruz |
|---|---|---|
| Ch1_2_3 | https://colab.research.google.com/drive/14c6LMMYxg-W-r7JvkNpbFq4g8eB5DY9C?usp=sharing| [link]() |
| Ch4 | https://colab.research.google.com/drive/1u9jzDgPQMeH5jUQz-cuyJfyu-IgcZfMh?usp=sharing | [link]() |
| Ch5 | [https://colab.research.google.com/drive/1EQOvWZjZ9droSd6y02_09XyF7zPFe_YG?usp=sharing | [link]() |
| Ch6 | [link]() | https://colab.research.google.com/drive/1SWbZQ2Szbr0Wibl4wKhyGhnyz1m2_F9M#scrollTo=uaupq_BxozTj|
| Ch7 | [link]() | https://colab.research.google.com/drive/179zlcQDrc6IJ17QNVuHGiMz568rXS_58#scrollTo=bziYNjO667DU |
| Ch8 | [link]() | https://colab.research.google.com/drive/1rAMHE_28vu_PWNXngj1fGcKFCknkFBQX#scrollTo=M0Yu2eku7md0|
| Ch9 | [link]() | https://colab.research.google.com/drive/1frXUAVo5GsghLVUmDvqEX6d4YzHbCOMA#scrollTo=q4JEm18Z_XO5|

## What we learned

Chapters 1, 2, and 3 taught us that before using data for machine learning, we need to understand, organize, and clean it first. We learned how to explore a dataset using head(), info(), and describe(), identify missing values, handle duplicates, and remove irrelevant data. One thing more is that missing values can be handled through imputation, deletion, or prediction, while duplicate entries, irrelevant features, and noisy data should be checked to remove redundancies and improve data quality. What surprised us was that even when a dataset has many entries, they can still contain missing or inconsistent information that may affect the accuracy of the results.

What we've learned from chapter 4 is that raw data can be improved in many ways including creating new features, grouping numerical values, and converting categories into numbers. We also learned that binning, interaction features, polynomial features, one-hot encoding, and ordinal encoding are used to transform and improve data so machine learning models can understand patterns, relationships, and categories more effectively. What surprised us was that creating a new feature, for example the Lemonade per Degree, it helps us reveal useful relationships in the data that may not be obvious from the original features.

Chapter 5 taught us that data scaling and normalization helps in making features with different numerical ranges or values more comparable. We also learned that StandardScaler adjusts the data to have a mean of 0 and a standard deviation of 1, while MinMaxScaler scales values between 0 and 1. What surprised us was that a feature with larger numerical values could influence a machine learning model more than a feature with smaller values, even when both features are important.

In Chapter 6, we learned the meaning of outliners then how to use the Z-score method and Interquartile Ranges (IQR). Also the strategies of capping & flooring went about boundaries, Log Transformation resulting into quality data and removing outliners which is important so the date will not have discrepancy.

In chapter 7, we  understood the distinction between scoring features independently (Filter), feature as a problem and testing subsets recursively with a model (Wrapper), and the regularization method (Embedded). We also learned what RFEVC and LassoCV does in the data.

In Chapter 8, we learned how constructing a preprocessing pipeline can be compared to a conveyor belt. Then it's important to remember the reason why we use pipelines in preprocessing. Then we also learned the steps inside it which are the imputation and scaling and the assurances that identical transformation parameters are applied consistently during evaluation.

In chapter 9, we learned how to do the data processing that can be used in real world applications. It has its own techniques that start in data cleaning for missing values, data transformation to apply log transform, data reduction to drop irrelevant features, data discretization or also called binning and last is encoding to convert categorical features.


## Errors we found

In Chapter 6, the Z-score method didn't flag 100 as an outlier at first because the cutoff was set to 3. In this small dataset, 100 only calculated out to a Z-score of 2.615, so the code completely ignored it. To fix this and get the correct outliners, we adjusted the threshold from 3.0 down to 2.5. And in the chapter 7, 8, and 9 we didn't found any error.

## Note on AI tools

Castor:    I used AI as a supplementary tool to help me verify my understanding of the topics, clarify concepts that I found confusing. However, the wordings on my answers was all originally from me, because I referred from the notebooks and used them as my primary source of information to make sure my answers were consistent with what was discussed in each chapter. I reviewed and adjusted the responses based on my own understanding rather than simply copying them, allowing me to use AI as a guide to support my learning and improve my uderstanding from the lessons.

Villaruz:    I used AI tools like ChatGPT and Gemini to ask for explanations about the codes and other terms that are not familiar to me. For example in chapter 7 I used gemini to help me explain the step by step process of RFECV and the way LassoCV works. It also helps me to identify the error in some chapters then i just used it to be my guide in answering the questions.

## References

McKinney, W. (2021). Python for Data Analysis, 3rd ed. O'Reilly.
VanderPlas, J. Python Data Science Handbook.
Any other page or article you used.
