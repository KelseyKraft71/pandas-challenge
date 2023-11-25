# Pandas Challenge UTA Data Analysis/Visualization

In this challenge, we were tasked with analyzing district-wide test results for a school district. We were given every student's math and reading scores, as well as various info about the schools the students attend. 

My full analysis can be found below as well as in the Jupyter Notebook file.

I had to search the internet for some help for one of my cells. As I was attempting to bin the Per Student Budgets, I kept getting an error for trying to bin string values based on numerical bins. I had to go back into the Per Student Budget column and remove the $ as well as convert the values to numeric values in order for the binning to work. I found my solution at https://www.statology.org/pandas-remove-special-characters/

# PyCity Schools Analysis

- District Summary

	- Overall, 65.17% of students are passing<br>
	- Higher % passing reading (85.81%) than math (74.98%)<br><br>
- District vs. Charter
	- Overall, Charter schools exhibit better results than District schools<br>
		- Charter = 90.43% passing 
		- District = 53.67% passing<br><br>

	- Charter schools are also better at Math than District schools
		- Charter = 93.62%
		- District = 66.55%<br><br>

	- The % passing gap is MUCH smaller for Reading (this will continue to be a trend!!!)
		- Charter = 96.59%
		- District = 80.8%<br><br>
		
- Top/Bottom 5 Performing Schools
	- All top schools are Charter schools and all bottom schools are District schools<br><br>
- Grades by School Year
	- ALL average reading grades across all school years are above 80(!!!)<br><Br>
	- Math scores dip below 80 for District schools (all Charter school averages are above 80 across all grades)<br><br>
- Spending per Student
	- Less money per student translates to better grades<br><Br>
		- This seems to be because all the highest spending schools are District schools which we know are, overall, worse than Charter schools
		- Charter schools spend less money per student on average<br><br>
	- Once again, we see the trend of Math passing % having a larger variation across groups than Reading passing %<br><br>
		- <$585 % passing Math &emsp;&emsp;= 93.46%&emsp;&emsp;<$585 % passing Reading &emsp;&emsp;= 96.61%
		- $585-$630 % passing Math = 87.13%&emsp;&emsp;$585-$630 % passing Reading = 92.72%
		- $630-$645 % passing Math = 73.48%&emsp;&emsp;$630-$645 % passing Reading = 84.39%
		- $645-$680 % passing Math = 66.16%&emsp;&emsp;$645-$680 % passing Reading = 81.13%<br><br>
- Size
	- All District schools are 'Large' schools, Charter schools fill the 'Medium' and 'Small' categories<Br><br>
	- 'Large' schools have a much worse % overall passing rate than 'Small' and 'Medium' schools<br><br>
		- 'Small' % overall passing &emsp;&nbsp;= 89.88%
		- 'Medium' % overall passing = 90.62%
		- 'Large' % overall passing &emsp;&nbsp;= 58.23%<br><br>
	- The gap is, once again, much smaller for Reading than Math<br><br>
		- 'Small' % passing Math   &ensp;&ensp;&nbsp;= 93.55%&emsp;&emsp;'Small' % passing Reading&ensp;&ensp;&nbsp;&nbsp;= 96.1%
		- 'Medium' % passing Math = 93.6%&emsp;&emsp;&nbsp;&nbsp;'Medium' % passing Reading = 96.79%
		- 'Large' % passing Math   &ensp;&ensp;&nbsp;= 69.96%&emsp;&emsp;'Large' % passing Reading &ensp;&ensp;&nbsp;= 82.77%<br><br>
	- The ONE 'Large' Charter school, Wilson High School, has grades consistent with other Charter schools. Every other 'Large' school (the District schools) has results consistent with what we expect from District schools (worse).<br><Br>
		- This suggest that Charter school methods and practices make up for the apparent negative effect that a large student body has on overall performance. This also aligns with Charter schools being overall better than their District counterparts.
