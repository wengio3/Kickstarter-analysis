# Kickstarting with Excel
## Overview of Project

This project-based is crowdfunding data from different projects to help an up-and-coming playwright named Louisa.


### Purpose

Louisa is trying to get her play Fever crowdfunded. Still, since her current project budget estimate is over 10,000$, she needs to see if this is an attainable goal by looking at previous crowdfunded projects.


## Analysis and Challenges

Whenever working with data of this size, challenges are avoidable; there were two major obstacles for this specific dataset:

1) A few errors occurred in creating a new column to find each row's average donation. The errors occurred because a few cells used in the formula (=ROUND) had zero value. Since division by zero is not permitted, the cells in the newly created column had errors in multiple cells that needed to be corrected. Since the problem occurred in numerous column cells, the best solution was to use the formula (=IFERROR) to the whole column to correct the errored cells. 

2) The size of the data was another major problem in this project. The data we need had to be filtered multiple times to find the data that can actually be used to help Louise figure out her strategy for her project.



### Analysis of Outcomes Based on Launch Date

The two conclusions drawn from this data are: first, the months between March to August are the best performing months hitting the highest in May second; although September through October didn't perform well, there were zero canceled projects.


### Analysis of Outcomes Based on Goals

Most projects with goals between 1,000 to 5000 performed the best, while projects with over 45,000 achieved the lowest. This information concludes projects with lower goals perform better than those with larger goals.

### Challenges and Difficulties Encountered

The data size made it difficult to find the data that was relevant to the task at hand.

## Results


