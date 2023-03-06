# ACT as a Strategy for CA High School Students

## Background

One of the most important parts of the job of a guidance counselor is to help their students gain admission to the college of their dreams.  
Although their importance is gradually waning, the two primary standardized tests for college admission - the ACT and the SAT - remain as a significant step in the admissions process.
Especially in larger colleges, these tests are helpful for admissions departments to sort through their growing stacks of application files.

The SAT is the more common choice for college applicants nationwide, but many states (particularly those in the heartland of the country) encourage their students to take the ACT instead.
California is *not* one of those states, but this study will consider whether it should be.

The SAT and ACT test different skill sets, and have scoring scales that are difficult to compare.  The ACT has a scale from 1 to 36, with a mean of 21, and the SAT has a total scale (not including the writing test) of 400 to 1600, with a mean of 1060.

As a result, it is difficult to intuitively compare these scores, especially when the mean score of the ACT is higher than the middle of the range of its extremes.  

The College Board (the organization responsible for the administration of the SAT) provides a comparison guide for SAT and ACT scores, which matches scores from each test based on percentiles.  Although it is not a part of this study, the College Board's comparison guide does match with other sources for percentile data (e.g. the Prep Scholar Blog).

# Problem Statement

Applying the College Board's comparison guide to 25th and 75th percentile scores of admitted students at a list of approximately 400 nationally recognized colleges, it appears that students are gaining admission with comparably lower ACT scores than SAT scores.

If this is in fact true, we should examine the success of California high school students on the ACTs.  If California students can perform at least as well on the ACTs as the SATs, this could provide a significant advantage in college applications.

# Data Sources

## 2017 ACT Scores by State (act_2017) 

Source:  Collegevine blog<p>
Relevant Columns:

* State:  50 states plus District of Columbia
* Participation_act:  Percent of eligible High School students in the state who took the ACT in 2017

## 2017 SAT Scores by State (sat_2017)

Source:  Collegevine blog<p>
Relevant Columns:

* State:  50 states plus District of Columbia
* Participation_act:  Percent of eligible High School students in the state who took the SAT in 2017


## 2019 College Data (sat_act_by_college)

Source:   Compass Prep blog<p>
Relevant Columns:

* School:  List of approximately 400 nationally recognized colleges
* SAT_25:  25th percentile SAT score of students admitted to the college
* SAT_75:  75th percentile SAT score of students admitted to the college
* ACT_25:  25th percentile ACT score of students admitted to the college
* ACT_75:  75th percentile ACT score of students admitted to the college

## 2019 California Data (act_2019_ca, sat_2019_ca)

Source:   California Dept of Education (cde.ca.gov - archived)<p>
Relevant Columns:

* School:  List of approximately 1900 CA high schools, of which just under 1000 have data for all columns.
* ca_enroll_sat and ca_enroll_act:  Number of students in the school's 12th grade class (these columns should and do match)
* ca_num_sat:  Number of students in the school's 12th grade class who took the SAT 
* ca_per_sat:  Percent of students in the school's 12th grade class who took the SAT
* ca_num_act:  Number of students in the school's 12th grade class who took the ACT 
* ca_per_act:  Percent of students in the school's 12th grade class who took the ACT
  
## Percentiles 
  
Source:  2018 ACT/SAT Comparison from the College Board<p>
Relevant Columns:

*  act_score:  Composite ACT score, range 1 to 36
*  act_percent:  Corresponding percentile of ACT score
*  sat_score:  Composite SAT score, range 400 to 1600
*  sat_percent:  Corresponding percentile of SAT score
