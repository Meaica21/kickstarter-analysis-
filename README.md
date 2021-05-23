# **An Analysis of Kickstarter Campaigns**-
Perfoming analysis on Kickstarter data for Louise’s Fundraising Methods

## **Overview of Project:**
* Given a short amount of time, Louise organized a fundraising campaign using two different techniques.  These two methods will help compare different perspectives to the   successes of theatre fundraising based on time and money.

## **Analysis and Challenges:**
* Using pivot tables and line charts I could easily visualize the success rate of the two different methods.  However, I ran into a challenge of having to convert the launch date column to a readable format.  There is a certain formula in EXCEL which measure time as the number of seconds since midnight of January 1, 1970. For example =(((J2/60)/60)/24)+DATE(1970,1,1) using this will formula I can interpret and use YEARS() function to explicitly  create pivot table based by launch date.

## **Results:**
### Outcomes Based on Launch Date
* In figure 1, I have created a line chart of total count per outcome in every single month. Noticeable spikes in May with a total of 166 count which has a highest count for successful outcome in line chart below. It appears more people are going to theater during spring and summer season specifically for the month of May and June.
* Another conclusion that can be made is that throughout the year, people much more likely fail to attend without canceling.

![Figure 1](https://user-images.githubusercontent.com/83877498/119268993-6e640e80-bbc3-11eb-80df-2788a11e865d.png)

**Figure 1:** Line chart of successful count based on launch date.

### Outcome Based on Funding Goals
* Another method performed was based on goals as shown in figure 2 where 76% of people donated less than $1000 under subcategory of plays. In addition, 73% contributed $1000-$4999.  Based on this, we conclude that more people are willing to contribute under $5000 since many less people give a contribution of over $4999.

![Figure 2](https://user-images.githubusercontent.com/83877498/119269105-02ce7100-bbc4-11eb-97ef-9a598e5188da.png)

**Figure 2:** Line chart of successful count based on goals.

### Data Set Limitations
* Some noted limitations regarding the data set based on launch date is that most of the sample size data was gathered between years 2015-2017.  The other years had much smaller samples recorded.
* The limitations of the data set based on funding goals is that the amount of people contributing decreases as the goal amount increases.

### Other
* A histogram would be useful to compare months or donation amounts to each other.  It also gives a quick visualization to the distribution of the data

