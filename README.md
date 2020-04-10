# The Ever-changing Standardized Test: SAT

The SAT has been around for as long as we can remember and continues to be a significant benchmark used by college's and universities to select each year's incoming freshman class. However, over the years the test has evolved to better meet educational standards and to reflect the material emphasized by the majority of high schools. In terms of content, the recent change in 2016 has been the most dramatic. 


Most evidently, the biggest change was scoring from a max score of 2400 down to a max score of 1600. In addition, the reading and writing sections are joined with the essay being an optional section. Finally, there is no longer a score penalty for incorrect answers, therefore allowing students to answer all the questions, even if they have to guess on some of them.

My goal is to examine the SAT scores from 2005-2015 to see if there was any merit in their decision to drastically change such an important piece of college admission process.

### Data Source & Data Prep

The data for this project included multiple datasets from the National Center for Educational Statistics. The SAT data for each State was easily accessed by excel file, although a tedious process to clean, separate, and merge as each excel file had years that were skipped. 


Each year that were separated contained reading, writing, and math columns. Two datasets were created for this analysis, one being the first 6 years from when they started implementing the old scoring of 2400 from 2005-2010 and the last 5 years from 2011-2015.

#### EDA

The average SAT score for all states over the mentioned time periods are presented separately. Notably, all 10 states that held the top average from 2005-2010 also held the top 10 in 2011-2015.



![alt text](https://github.com/phamc4/SAT_/blob/master/img/AverageSAT2005_2010.png)

![alt text](https://github.com/phamc4/SAT_/blob/master/img/AverageSAT2011_2015.png)


Initially, I was looking into how average test scores changed as time passed and things like SAT specfic tutoring courses and books became more abundant.I was set on comparing the first 6 years to the last 5 the 2400 score was implemented but exploratory analysis of each block of years shows the non normal and similar distributions that wasn't what I expected.

![alt text](https://github.com/phamc4/SAT_/blob/master/img/Comparison.png)

There a couple conclusion we can draw from looking at the overall spread: -The average scores from each block of years do not significantly change as time passes. Average scores are not clustered around the average but tend towards the ends of the distribution.



Exploratory data on SAT scores by ethnicity to gain insight into the bimodal like shape of the data. As a first instinct, ethnicity and socialeconomic status were the first to come to mind when considering the bimodal skewness. 

![alt text](https://github.com/phamc4/SAT_/blob/master/img/ethnicity_comparison.png)

Checking for possible correlation between subjects. Evident between the distribution of subject scores, writing holds a broader range of scores. 

![alt text](https://github.com/phamc4/SAT_/blob/master/img/subject_comparison.png)

Further exploration through pairwise relationships with seaborn pairplot. Did this give enough merit to consider the merge of writing and reading in the latest SAT changes?

![alt text](https://github.com/phamc4/SAT_/blob/master/img/pairwise_compare_3_subjects.png)


### How does it compare to the new SAT

The 2017 and 2018 were the only readily available datasets. Albeit a small dataset, comparing the distribution of scores per subject can shed some light on how the immediate effectiveness of the new changes have been.

![alt text](https://github.com/phamc4/SAT_/blob/master/img/2017_2018_Comparison.png)

![alt text](https://github.com/phamc4/SAT_/blob/master/img/pairwise_relationship_latest.png)



### Future Steps:

-Further investigate other factors that prompted the extreme change, such as household income, percentage taking SAT vs ACT, number of people in each ethnicity taking it, etc.

-Implement more complex hypothesis testing on other interesting aspects.

-Consider population density's of states and be more granular with the data such as looking at only a specific state. Can we get more than just averages?



