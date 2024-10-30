# Coursera Course Dataset Analysis

## Introduction
This project aims to generate actionable insights for Coursera to help increase student enrollment. The analysis includes various factors that could impact enrollment numbers, such as ratings, certificate types, and difficulty levels. Separate analyses were conducted for outliers to avoid skewed results.

## License

This project is licensed under the GNU General Public License v3.0 (GPLv3). You can find the full text in the ["License"](https://github.com/TuringCollegeSubmissions/avabal-PYDA.3.5/blob/main/License.txt) file. 

## Dataset

This project uses the Coursera Course Dataset from [Kaggle](https://www.kaggle.com/datasets/siddharthm1698/coursera-course-dataset). The dataset is licensed under the [GNU General Public License v2 (GPL 2)](https://www.gnu.org/licenses/old-licenses/gpl-2.0.en.html).

## Objectives

**Goal of this analysis**  is to provide useful insight to Coursera organization on how to increase student enrolment numbers. I sought to answer these research questions based on the data available:
- Do organizations which offer more education products on Coursera attract more students? 
- How do ratings correlate with the number of students enrolled?
- What are the enrollment patterns associated with different certificate types?
- How does difficulty relate to the number of students enrolled?

## Methodology
The analysis employed:

- **Data Visualization:** violin, scatter plots, bar charts and histograms.
- **Statistical Testing:** non-parametric tests (Mann-Whitney U, Kruskal-Wallis) due to non-normal data distribution.
- **Correlation Analysis:** Pearson correlation.


## Conclusions

1. **Amount of offers and enrollment.** While larger organizations with more offerings are common on Coursera, simply offering more products does not guarantee higher average enrollments. The correlation between the number of offerings and student enrollment was weak, suggesting that the volume of offerings alone is not a key driver of student interest. 
2. **Ratings and enrollment.** There is almost no correlation between ratings and the number of students enrolled. Most offered learning material already have high ratings (4.6+), meaning that incremental improvements in ratings might not significantly impact enrollments. 
3. **Certificate Types and enrollment.** Courses tend to attract significantly more students than specializations, as shown by the higher median enrollments. This suggests that students may find individual courses more appealing. However, since specializations are made out of multiple courses themselves, it's very normal to have more students always enrolled in courses than specializations. 
4. **Course Difficulty and enrollment.** Products labeled as mixed difficulty tend to have significantly higher enrollments than beginner or intermediate ones, despite comprising a smaller percentage of offerings. This may indicate that students prefer offerings that cater to a broader range of skills. 
5. **Outliers in enrollments.** Outliers, which had disproportionately high enrollments compared to others, were noticed to include  top-tier universities (e.g., Yale, Stanford) and popular subjects like programming, data science, and psychology. Also, here moderate positive correlation was found when it came to number of products offered. It suggests that institutional reputation and learning material topic may be worthy to be considered. However, further research would need to be conducted to confirm that. 

## Recommendations
1. Investing time to analyze what impact prestigious institutions and learning topics have on student enrolment. It could help to decide if more recourses should be invested in creating new or expanding old partnerships with top tier universities. Also, what topics should be recommended for all institutions to work on as they benefit from higher number of enrollments as well and will know what is worth to invest the time in. 
2. Consider recommending organizations to prioritize working on mixed-level offerings, especially in popular fields, as they seem to have the most appeal. 
3. Create targeted marketing campaigns. Courses with exceptionally high enrollments, especially those from top-ranked universities or institutions, show strong student interest. To increase student enrolment, it may be worthwhile to focus on increasing visibility for these offerings through targeted ads, email marketing, or partnerships to reach a larger global audience. 
4. Investing time to analyze which programs were completed by students and which were not. It could help to spot possible areas of improvements. Also, for people who already finished them, similar next level programs can be recommended via marketing channels to encourage expanding knowledge in the area students were already interested in. It would make marketing efforts more efficient focusing on people who finished what they enrolled in before.  
5. Focusing on more often requesting students who enrolled in programs with lower ratings than 4.6 to rate them. It could allow some already existing programs to have a chance to bounce back and look more appealing to the audience. 

## Possible analysis improvements
1. Using more advanced statistical techniques. Explore generalized linear models (GLMs), or non-parametric multivariate analyses to see if combining several factors (like ratings, difficulty, and certificate type) provides a more holistic understanding of enrollment patterns. 
2. Expanding analysis to extract and analyze subject themes. For example, coding, wellbeing, etc. As some themes may be more popular than others. 
3. Including additional datasets to access official ratings of learning institutions present. It would allow to access if their popularity/prestige had an effect on results. 
4. Explore affects of on different data attributes. Now, main focus was student enrolment. Thus, areas like ratings vs product difficulty were not analyzed. 

## How to Use This Repository
1. **Data:** Load the dataset from the provided [Kaggle link](https://www.kaggle.com/datasets/siddharthm1698/coursera-course-dataset) or [this repository](https://github.com/TuringCollegeSubmissions/avabal-PYDA.3.5/blob/main/coursea_data.csv).
2. **Install Dependencies:** install required packages using [requirements.txt](https://github.com/TuringCollegeSubmissions/avabal-PYDA.3.5/blob/main/requirements.txt).
3. **Code Execution:** Download and run [the notebook](https://github.com/TuringCollegeSubmissions/avabal-PYDA.3.5/blob/main/Graded_task_sprint_3.ipynb) to your local machine to view interactive Plotly graphs. 
4. **Results Visualization:** View static visualizations in the [images folder](https://github.com/TuringCollegeSubmissions/avabal-PYDA.3.5/tree/main/images).

## Contact
LinkedIn - [Agnė Vabalaitė](www.linkedin.com/in/agnė-vabalaitė).
Gmail - vab.agne@gmail.com
