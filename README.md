# School_District_Analysis
Analysis on state test scores for a city school district utilizing Python and Jupyter Notebook. 

## Overview of School District Analysis
### Purpose
The purpose of this project is to utilize Python and Jupyter Notebook to automate the task of analyzing state-testing scores across a city school district in order to determine future budget allocation. The score results are reviewed by grade, school, school type, school size, and current budget per student to determine if any of those factors impact scores.  During the analysis of data, the school board found evidence there was academic dishonesty associated to Thomas High School ninth graders.  The analysis takes this into consideration to determine the overall impacts so proper budgeting can occur.
The data utilized for the analysis can be accessed through the following links: ![schools_complete.csv](https://github.com/dschul01/School_District_Analysis/blob/main/Resources/schools_complete.csv) and ![students_complete.csv](https://github.com/dschul01/School_District_Analysis/blob/main/Resources/students_complete.csv)

## Results from Thomas High School (THS) Academic Dishonesty
The analysis below shows the impact of the potential Thomas High School (THS) ninth grade academic dishonesty on the district metrics. 

### Impact to District
There are minimal impacts to the district from the THS issue due to the small count of THS ninth graders in comparison to the total district's student body count.  Images below show all district scores vs replacing THS ninth grade scores with 'Not a Number' (NaN).  
* Average Math Score decreased by 0.1%
* % Passing Math decreased by 0.2%
* % Passing Reading decreased by 0.1%
* % Overall Passing decreased by 0.3%
* Total Student counts weren't impacted as instructions indicated to include all in denominators for district comparison
* Budget was not impacted as a result of dishonesty 

All District Data:
![District_Summary_Orig.png](https://github.com/dschul01/School_District_Analysis/blob/main/Resources/District_Summary_Orig.png)

Updated District Data:
![District_Summary_Updated.png](https://github.com/dschul01/School_District_Analysis/blob/main/Resources/District_Summary_Updated.png)

### Impact to Schools
The impact to THS scores are impactful as a result of the dishonesty.  Images below show score all scores by school vs replacing THS ninth grade scores with 'Not a Number' (NaN). 
* Average Math Score decreased by 0.1%
* % Passing Math decreased by 0.2%
* % Passing Reading decreased by 0.1%
* % Overall Passing decreased by 0.3%
* Total Student counts weren't impacted as instructions indicated to include all in denominators for district comparison
* Budget was not impacted as a result of dishonesty 

The images also show the significant impact from removing THS ninth grade scores when comparing to the other schools.  THS had the second highest Overall % Passing and then decreased to eighth Overall % Passing

All School Data:
![School_Summary_Orig.png](https://github.com/dschul01/School_District_Analysis/blob/main/Resources/School_Summary_Orig.png)

Updated School Data:
![School_Summary_Updated.png](https://github.com/dschul01/School_District_Analysis/blob/main/Resources/School_Summary_Updated.png)

The impact to THS compared to other schools is also illustrated by the images above.  There is very little impact


### Other Impacts
#### 	Comparing Grades 

#### Comparing School Spending


#### Comparing School Size


#### Comparing School Type


## Summary 
### Overall Impact Removing Thomas High's Ninth Grade Scores

1.
2.
3.
4. 
