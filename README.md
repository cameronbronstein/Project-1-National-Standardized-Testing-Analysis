#General Assembly DSI-6 ~ Cameron Bronstein
##Project 1: Standardized Testing, Statistical Summaries and Inference

### **Problem Statement:**
The College Board, best known as the company that creates and hosts the Scholastic Aptitude Test (SAT), is currently facing increased competition from American College Testing (ACT). The ACT has more recently implemented itself as a comparable standardized test for college admissions, and has formed contracts with different state governments to serve as a substitute for mandated state testing for Junior and Senior high school students. However, with new reformatting of the SAT, the College Board has been working to show that the SAT is still a relevant and top level standardized test to prepare high school students for higher education.

I am part of a team tasked to analyze the National SAT and ACT data from 2017 and 2018, organized by state average participation and scores for each test. I will be presenting my findings to College Board staff, a non-technical audience, to provide my recommendations for how best direct marketing and strategy funding to boost SAT participation and scores in states with lower participation rates.


###Executive Summary:

#####Contents:
- 2017 Data Import & Cleaning
- 2018 Data Import and Cleaning
- Exploratory Data Analysis
- Data Visualization
- Descriptive and Inferential Statistics
- Outside Research
- Conclusions and Recommendations

###Data Dictionary
|Feature|Type|Dataset|Description|
|---|---|---|---|
| State | object | ACT/SAT | List of States and Territories |
| act_participation | float | ACT | Participation per State |
| act_english | float | ACT | Average score for the English section, from 1-36  |
| act_math | float | ACT | Average score for the Math section, from 1-36 |
| act_reading | float | ACT | Average score for the Reading section, from 1-36 |
| act_science | float | ACT | Average score for the Science section, from 1-36 |
| act_composite | float | ACT | Average Composite score, from 1-36 |
| sat_participation | float | SAT | Participation per State |
| sat_ebrw | int | SAT | Average score for the Evidence-based Reading and Writing section, from 200-800 |
| sat_math | int | SAT | Average score for the Math section, from 200-800 |
| sat_total | int | SAT | Average total score, from 400-1600 |


###Conclusions:

#### State of Choice: **Pennsylvania** []()

- **New SAT Contracts:** Florida, Illinois, New Jersey, Rhode Island
- **East Coast SAT Contracts:** Connecticut, Delaware, District of Columbia, Maine, New Hampshire, New Jersery, Rhode Island

I chose Pennsylvania as my target state because it is one of those "middle" states, in that it does not have a contract with either the SAT or ACT, thus making it the perfect target candidate. Pennsylvania borders New York State, which has also shown an increase in [SAT testing.](https://www.applerouth.com/blog/2016/01/13/how-the-sat-got-its-groove-back/). Pennsylvania is also regionally connected to many other states that have inked contracts with the college board (see **East Coast SAT Contracts** above).

Likewise, Pennsylvania has a significantly large population, ranked [5th Nationally](https://en.wikipedia.org/wiki/List_of_states_and_territories_of_the_United_States_by_population#State_rankings). Contracting with Pennsylvania would result in considerable profits.

Between 2017 and 2018, Pennsylvania saw a slight jump in participation rate, from 65 to 70 percent, and ACT participation dipped marginally. However, with this jump in SAT participation, the average scores also increased by 15 points, counter to typically observed pattern. This is evidence that Pennsylvania students are seeking out the SAT over ACT - a pattern that we could leverage to the Pennsylvania Department of Education.

View the [presentation](https://docs.google.com/presentation/d/13fkTyxX2n7V8SGO4u9mrtJBNxtmD9K3tKg1MpkRMQ4w/edit?usp=sharing)
