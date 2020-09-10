# LEAPS Datasets for 2003 and 2004: The Impoverished and School
Springboard Data Science Career Track, First Capstone Project
LEAPS Dataset
Links to presentation slides, etc.:
https://docs.google.com/document/d/1n384SW7NEobIuTC0Ksa9_CiBGLLgfe38joBsn8z6Ms8/edit?usp=sharing



<!-- TABLE OF CONTENTS -->
## Table of Contents

* [General Information](#general-information)
* [Purpose and Hypothesis](#purpose-and-hypothesis)
  * [Overview of What Follows](#overview-of-what-follows:)
* [Data Collection](#data-collection)

* [Roadmap](#roadmap)
* [Contributing](#contributing)
* [License](#license)
* [Contact](#contact)
* [Acknowledgements](#acknowledgements)
* [link]



<!-- ABOUT THE PROJECT -->
## General Information
I choose to work with the LEAPS datasets because I know that entry-level Data Scientist and Data Analysts jobs primarily deal with dirty data, and the LEAPS datasets had valuable and trivial data (as I have come to think after studying it) that requires much work to compose into one useful dataset per year. I was also intrigued to find that many suffering from indigence in the poorest parts of the world are able and willing to send their children to private schools. Already looking for a project that has not been performed by several people, I chose the unknown path of predicting the grades of elementary school students in Punjab, the poorest province of Pakistan. Consider this brochure for more information: https://epod.cid.harvard.edu/sites/default/files/2018-11/LEAPS%20Brochure.pdf

I use the Learning and Education Achievements in Punjab Schools (LEAPS) datasets for each year from 2003 to 2004 to build a model that predicts which students will succeed in school in Pakistan’s poorest province, i.e., Punjab. Pakistan has been striving to compel every citizen-child to attend school, and as it reaches that goal, its attention is shifting to how well students learn. Compounding Pakistan’s truancy is that there is both that not sufficient data on student success and that the usable data we do have indicates low levels of learning among students, as measured by various tests (the accuracy or legitimacy of which I do not explore in this project except to assume those of my datasets are equally and sufficiently legitimate).*

My theoretical clients are the political leaders of Punjab and the host of capable researchers and aids helping them. If my work were to inform them of relevant factors, they could save resources by allotting them properly instead of investing in fruitless options.

* _For a detailed analysis of the LEAPS assessments, see Andabi et al., Learning and Education Achievements in Punjab Schools (LEAPS), 2007, pp. 130-42._

## Purpose and Hypothesis
I aim to solve the problem of what factors predict academic success in order to foster those factors, thereby maximizing student success in Punjab students. Academic success comprises the median of all grades in each subject (math, Urdu, English) from 2003 and 2004.

Although having the target variable for each year as an aggregate function (median) over three columns, each is a good predictor of student success. In fact, research psychologists studying intelligence have found strong evidence for the unromantic, non-egalitarian notion that intelligence cannot be broken up into demonstrably different parts. Those who are intelligent in one area, say shapes, tend to be intelligent in other areas that constitute IQ and the g factor.* As we see in the EDA section, the teacher’s belief in the student’s intelligence is significantly, positively correlated with high grades, perhaps reminding my audience of the power of teacher expectations.** Test-taking itself is a skill, of course, which I assume affects the student’s grade evenly across the three subjects. I hypothesize, then, that students who perform well in one subject, such as Urdu (the local language), will do better in the other two aspects.

* https://quillette.com/2017/12/24/neuroscience-intelligence-interview-richard-haier/.
** https://www.educationnext.org/power-of-teacher-expectations-racial-bias-hinders-student-attainment/.

### Overview of What Follows:
1. Data Collection
2. Form a DataFrame of variables with predictive power for each year: df2003, df2004, df2005.
3. Perform EDA in order to test which variables have the most predictive power, modifying the DataFrames should it be appropriate. 
4. Form a model using parts of what I learn from the ML portion of the curriculum and discussion with my mentor.

## Data Collection
As of mid-2020, the website from which one can download the LEAPS datasets as CSV files is down, yet some of the summarized features are available on the WorldBank website (worldbank.org): 

2003 (labeled as 2003-2006), https://microdata.worldbank.org/index.php/catalog/440/data-dictionary/F6?file_name=public_master_children; 2004, https://microdata.worldbank.org/index.php/catalog/439/variable/V1530/. 

I requested the CSV files from Ayi Chang (ayichang@worldbank.org), who promptly responded with data from 2003-2005.



http://github.com - automatic!
[GitHub](http://github.com)

## link
