# Data_Journalism_Final_Project
This repository documents my analysis on salaries in the United States based on regions, majors, and school types.

## Analysis 1 : Average Salary Increase by Type of School
!['1_Github','Percentage Increase by School Type'](/1_Github.jpg)
### Sheet Used: Salaries_by_college_type
__Data Analysis Process :__<br>
1. Created a pivot table for school type, starting salary, and mid-career salary.<br>
2. Calculated the average of starting salary and mid-career salary for each school type (using “Add Values” option).<br>
3. Copied the result to a new sheet and filtered the required values.<br>
4. Calculated the percent change of starting salary and mid-career salary using a formula (C2 - B2)/B2.<br>
<br/>


## Analysis 2 : Majors that have the highest percentage increase in salary.
!['2_Github','Majors that gets you increments'](/2_Github.jpg)
### Sheet Used: degrees-that-pay-back
__Data Analysis Process :__<br>
1. Created a new sheet with Major, starting salary, and mid-career salary.<br>
2. Used the formula = (C2-B2)/B2 to calculate the percentage increase of starting and mid-career salary.<br>
3. Sorted the sheet in descending order by percentage.<br>
<br/>


## Analysis 3 : Which schools have the highest starting salary, which schools have the highest mid-career salary, which schools have the highest mid-career 90th percentile salaries. Which regions are the schools from?

* CIT has the highest starting salary. It is from the California region.</br>
* Dartmouth College has the highest mid-career salary. It is from the Northeastern region.</br>
* Yale University has the highest mid-career 90th percentile salary.</br>
<br/>

!['3_Github1','Schools with Highest Starting Salary'](/3_Github1.jpg)</br>
!['3_Github2','Schools with Highest Mid-Career Salary'](/3_Github2.jpg)</br>
!['3_Github3','Schools with Highest 90th Percentile Mid-Career Salary'](/3_Github3.jpg)</br>

### Sheets used: <br/>
* Salaries_by_college_type<br/>
* salaries_by_region

__Data Analysis Process :__<br>
1. Used VLOOKUP from Salaries_by_college sheet to region sheet and included region as a new column in the Salaries_by_college_type sheet.<br/>
2. Used sorting option to find out the schools that have the highest starting and mid-career salaries and checked in which region each of the schools are.<br/>
<br/>


## Analysis 4 : Disparity of salaries for each region.
### _This data is analyzed to check the difference between least and highest salaries._

!['4_Github','Disparity of salaries for each region'](/4_Github.jpg)
### Sheet Used: salaries_by_region

__Data Analysis Process :__<br>
1. Created a pivot table for Region, Mid-career 10th percentile salary, and Mid-career 90th percentile salary.<br/>
2. Separated the values region wise.<br/>
3. Calculated the MIN of 10th percentile salary for every region. — Calculated the MAX of 90th percentile salary for every region.<br/>
4. Copied the values into a new table and calculated the percentage difference (C2 - B2)/B2<br/>
<br/>


## Analysis 5 : List of schools which are more than 1 school type.
### _This data is analyzed to check what schools come under more than 1 category of school type._

!['5_Github3','School which are more than 1 type'](/5_Github3.jpg)
### Sheet Used: Salaries_by_college_type

__Data Analysis Process :__<br>
1. Created a pivot table for school name and school type.<br/>
2. Used COUNTA function to count the school types for each school name.<br/>
3. Copied the result to a new sheet.<br/>
4. Used IF() to extract the school names and school types for the schools that have a COUNTA of more than 1 school type.<br/>
5. Filtered the sheet and extracted the data.<br/>
<br/>


## Analysis 6 : Average of Mid-Career salary for each region.
### _This data is analyzed to understand the mid-career salary approximate for each region._

!['6_Github2','Average Mid-Career salaries for each region'](/6_Github2.png)<br/>
<br/>
!['6_Github','Infogram for Average Mid-Career salaries for each region'](/6_Github.png)
### Sheet Used: salaries_by_region
__Data Analysis Process :__<br>
1. Created a pivot table for Region and Mid-Career Medians.<br/>
2. For each region, calculated the AVERAGE of the mid-career median.<br/>
3. Copied the result into a new sheet and filtered the required data (by color option).<br/>
<br/>


## Analysis 7 : Count of schools for each school type (also counted by region).
### _This data is analyzed to understand how many schools are there under each school type. What regions does these schools belong to._

!['7_Github1','Number of schools under each school type'](/7_Github1.jpg)
!['7_Github2','Number of schools under each school type1'](/7_Github2.png)

### Sheets used: <br/>
* Salaries_by_college_type<br/>
* salaries_by_region
<br/>

__Data Analysis Process :__<br>
1. Used VLOOKUP from Salaries_by_college sheet to region sheet and included region as a new column in the Salaries_by_college_type sheet.<br/>
2. Created a pivot table for School type and Region.<br/>
3. Used COUNTA and TOTALS options to get the count of schools for each school type.<br/>
<br/>

#### _Ivy League school type has the least number of schools (7 schools) and all the schools are in only Northeastern region._
#### _State school type has the highest number of schools._
<br/>

!['7_Github1','School count under each school type'](/7_Github.jpg)
<br/>
<br/>

# Story Pitch : 
### _Engineering might be in high demand as a whole. But is there any other field that is in more demand in individual regions? Is there a field that generates more revenue to that particular region? What is the field? What are the factors(like background, climate, educational revolutions, etc) of that region that makes it suitable for that field._<br/>
<br/>

!['Engineering','Engineering is the dominated field of the United States in terms of Salary'](/Engineering.jpg)
<br/>

### __Additional Sources Required :__<br/>
* Salaries that each Major can get in each of the regions is the data that we might want to have here. I would like to use the data to analyze which field or study is in more demand in each region.<br/>
* We also will need the data that supports the theory of a field or a study being on demand in that particular region. I would like to analyze the background as to why a particular field or study is on demand in a particular region. The reasons could be climatic conditions, type of immigrants, etc.<br/>
* We would also need the ratings of the best colleges in the US. This could lead us to the regions as to what that particular place is good for and why. 
https://www.niche.com/colleges/search/all-colleges/<br/>
<br/>

### __Real People I would like to interview :__<br/>

1. I would like to interview the staff of Betsy Devos, Secretary of Education, USA. 
I would like to interview and understand the diversity of various kinds of colleges in various regions of the United States and why the kind of distribution was implemented.<br/>

* Education email address: betsy.devos@ed.gov<br/>
* The Secretary's office phone number is: 202-401-3000<br/>
* According to her website, www.betsydevos.com<br/>
* Other valid emails for reaching out to her include:
  * contact@betsydevos.com
  * contact@windquest.com
  * media@windquest.com
  * betsy@betsydevos.com
<br/>
2. The Education Publications Center (ED Pubs) is the Department's one-stop center for access to ED information. Use the ED Pubs On-Line Ordering System (https://www.edpubs.gov/) <br/>
<br/>
* Toll-free number 1-877-4-ED-PUBS (877-433-7827). <br/>
* Email: edpubs@edpubs.ed.gov.<br/>
<br/>
The National Library of Education in the Institute of Education Sciences maintains a telephone line staffed by trained information specialists. Members of the public, including educators and researchers, typically call this number for information about education statistics and education research information. 
<br/>

* The number is 202-205-5015.
<br/>
* The National Library of Education can also answer questions on research and statistics by email at AskaLibrarian@ed.gov<br/>
<br/>

I believe I could get the insights and a detailed understanding of the kinds of Majors which are on demand in various regions of the United States.
