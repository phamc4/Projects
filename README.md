###### The Ever-changing Standardized Test: SAT

The SAT has been around for as long as we can remember and continues to be a significant benchmark used by college's and universities to select each year's incoming freshman class. However, over the years the test has evolved to better meet educational standards and to reflect the material emphasized by the majority of high schools. In terms of content, the recent change in 2016 has been the most dramatic. 

Most evidently, the biggest change was scoring from a max score of 2400 down to a max score of 1600. In addition, the reading and writing sections are joined with the essay being an optional section. Finally, there is no longer a score penalty for incorrect answers, therefore allowing students to answer all the questions, even if they have to guess on some of them. My goal is to examine the SAT scores from 2005-2015 to see if there was any merit in their decision to drastically change such an important piece of college admission process.

### Data Source & Data Prep

The data for this project included multiple datasets from the National Center for Educational Statistics. The SAT data for each State was easily accessed by excel file, although a tedious process to clean, separate, and merge as each excel file had years that were skipped. 

Each year that were separated contained reading, writing, and math columns. Two datasets were created for this analysis, one being the first 6 years from when they started implementing the old scoring of 2400 from 2005-2010 and the last 5 years from 2011-2015.

#### EDA

The average SAT score for all states over the mentioned time periods are presented separately. Notably, all 10 states that held the top average from 2005-2010 also held the top 10 in 2011-2015.

![alt text](https://github.com/phamc4/SAT_/blob/master/img/AverageSAT2005_2010.png)

![alt text](https://github.com/phamc4/SAT_/blob/master/img/AverageSAT2011_2015.png)

Exploratory analysis of each block of years shows the non normal and similar distributions. 

![alt text](https://github.com/phamc4/SAT_/blob/master/img/Comparison.png)

Checking for possible correlation between subjects. Evident between the distribution of subject scores, writing holds a broader range of scores.

![alt text](https://github.com/phamc4/SAT_/blob/master/img/subject_comparison.png)

