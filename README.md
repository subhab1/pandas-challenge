# Title 
# pandas-challenge(PyCity Schools)

## Objective:
 The goal of this analysis is to merge and import two datasets in csv format and then present a series of panda Dataframes of various results to obtain apparent trends in school performance. The results provide various information on the statistics of the school district which will give them opportunities to evaluate their budget and priorities.

## Process: 
*  Used the Pandas library for data construction and analysis.
*  Two external csv files are imported, merged, and the combined data is shown into python pandas dataframe.
*  Used the unique()  and len() method to calculated the total number of unique schools in the school_data_complete DataFrame. 
*  Used mean(), count(), sum() and percentage method to create a dataframe like “district_summary”.
*  The set_index() method is used to set the 'school_name' column as the index .
*  Used the groupby() function to construct a DataFrame. Once the the groupby() method is used to create a grouped object we can use various group of functions like mean(), count(), sum () etc. 
*  The sort_values() method is used to sort the DataFrame . For example, the "% Overall Passing" column in descending order.
*  The pd.cut () function adds a new column to the Dataframe and the new column is populated based on the specifics provided in ‘spending_bins’ and its labels.

## Observable Trends: 
*  The Dataframe of ‘per_school_summary’ states that when the number of students sizes is higher in schools the average math scores, average reading scores, passing math, passing reading, and overall passing is lower. So, we can assume that, when there is a larger classroom size, it adversely affects students’ performance in studies. Therefore, schools, districts, and charters should work on building appropriate class sizes allowing students to get more individual attention.
*  After reflecting on the school_data, it was clear that out of 15 schools in the dataset 7 of them are found at the district level, and the other 8 of them found at the charter level. The highest performing schools (top 5) are all from charter and the 5 lowest performing schools are from district. The Dataframe called ‘type summary’ also provides a comparative view of how the two school types, "Charter" and "District," perform on academic measures. Charter schools have a higher overall passing percentage (90.43%) compared to District schools (53.67%). The difference in the percentage values says that various measures should be taken into consideration to understand the gap between the two types of school’s performance.
## Reference:
*  https://datagy.io/python-count-unique-values-list/
*  https://www.geeksforgeeks.org/python-pandas-dataframe-groupby/#
*  https://www.statology.org/pandas-count-unique-values/
*  https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.sort_values.html





