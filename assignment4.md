**Dataset Link**
[US Presidential Statewide Election Returns Data 1976-2020](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/42MVDX)

**Three Specific Questions**

1. Between 1976 and 2020, how many non-write-in candidates have their been from each party? / Has that number been even between Dems/Reps? **Answers: 12 Democrat, 12 Republican, 11 Liberatarian, 38 Other / Yes**

2. In 2020, which state cast the most votes overall? / Is this proportional to population? **Answers: California / Yes. California had the largest state population in 2020 and the largest number of votes cast in 2020 were from California.**

3. Was the ranking of which states cast in 2016 the most votes proportional to which states had the largest population that year? **Answer: For this question, I also used [this Census Bureau Data](https://www.census.gov/data/tables/time-series/demo/popest/2010s-state-total.html) to compare the rankings. I found that this was only somewhat true. California had both the largest population and the most total votes cast, but Florida with the third-highest population cast the second-most votes. Pennsylvania with the sixth-highest population had the fifth-most votes, swapped with Illinois. With the 20th-highest population, Wisconsin cast the 15th-most votes. With the second-lowest population, Vermont voted ahead of three states.**

**Analysis Steps**

1. **For question 1:** Since the data offers a candidate count for each state, and since the presidential election is nationwide, we need only examine one state as a case study to answer this question. Filter>From column B, filter out all but a random state (California)>Take turns filtering column O for the different available party designations>Highlight column to count remaining rows

2. **For question 2:** Filter>From column A, filter out all years but 2020>Sort column L from largest to smallest

3. **For question 3:** For Election Returns Data: Filter>From column A, filter out all years but 2016>Sort column L from largest to smallest 

For Census Data: Delete geographic area rows>Delete columns for non-2016 years>Delete overall header for filtering clarity>Edit header to remove merge for filtering clarity>Filter>From the new column B, sort largest to smallest.

**Sample Headline & Nut Graf**

**Smaller states cast competitive ballot numbers in 2016 election**

The 2016 election broke records for voter turnout nationwide, and new data shows that states with lower populations jockeyed with more populated states for total ballots cast. 
