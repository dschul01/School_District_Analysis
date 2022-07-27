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
* Average Scores changed minimally due to changing to NaN rather than 0's
* % Passing Math decreased significantly from 93% to 67%
* % Passing Reading decreased significantly from 97% to 70%
* % Overall Passing decreased significantly from 91% to 65%
* Total Student counts weren't impacted
* Budget was not impacted as a result of dishonesty 

The images also show the significant impact from removing THS ninth grade scores when comparing to the other schools.  THS had the second highest Overall % Passing and then decreased to eighth Overall % Passing

All School Data:
![School_Summary_Orig.png](https://github.com/dschul01/School_District_Analysis/blob/main/Resources/School_Summary_Orig.png)

Updated School Data:
![School_Summary_Updated.png](https://github.com/dschul01/School_District_Analysis/blob/main/Resources/School_Summary_Updated.png)


### Other Impacts
When comparing scores by grade, the only impact from replacing the ninth grade scores is that THS ninth grade scores change from an Integer to NaN as seen in the image below which is after the updated scores are calculated.

<img src="https://github.com/dschul01/School_District_Analysis/blob/main/Resources/School_Grade_Updated.png" width="400" height="400" />

The adjustment of THS ninth grade scores only have a nominal impact when looking across the bins for school spending & size as well as by school type.


## Summary 
### Overall Impact Removing Thomas High's Ninth Grade Scores

1. THS drops significantly from second to eighth in the overall passing percentage compared to the other schools in the districts.
2. Overall district scores are not majorily impacted from the change in score.
3. Scores by grade are only impacted for ninth grade as the scores were updated from integers to NaN.
4. Scores by budget bin groupings are only nominallyimpacted by the adjustment in scores.
