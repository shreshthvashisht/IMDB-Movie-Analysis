# IMDB-Movie-Analysis

## You are required to provide a detailed report for the below data record mentioning the answers of the questions that follows:

1. Cleaning the data:: PThis is one of the most important step to perform before moving forward with the analysis. Use your knowledge learned till now to do this. (Dropping columns, removing null values, etc.)
    - *Your task: Clean the data*
2. Movies with highest profit: Create a new column called profit which contains the difference of the two columns: gross and budget. Sort the column using the profit column as reference. Plot profit (y-axis) vs budget (x- axis) and observe the outliers using the appropriate chart type.
    - *Your task: Find the movies with the highest profit?*
3. Top 250: Create a new column IMDb_Top_250 and store the top 250 movies with the highest IMDb Rating (corresponding to the column: imdb_score). Also make sure that for all of these movies, the num_voted_users is greater than 25,000. Also add a Rank column containing the values 1 to 250 indicating the ranks of the corresponding films.
4. Extract all the movies in the IMDb_Top_250 column which are not in the English language and store them in a new column named Top_Foreign_Lang_Film. You can use your own imagination also!
    - *Your task: Find IMDB Top 250*
5. Best Directors: Group the column using the director_name column.Find out the top 10 directors for whom the mean of imdb_score is the highest and store them in a new column top10director. In case of a tie in IMDb score between two directors, sort them alphabetically.
    - *Your task: Find the best directors*
6. Popular Genres: Perform this step using the knowledge gained while performing previous steps.
    - *Your task: Find popular genres*
7. Charts: Create three new columns namely, Meryl_Streep, Leo_Caprio, and Brad_Pitt which contain the movies in which the actors: 'Meryl Streep', 'Leonardo DiCaprio', and 'Brad Pitt' are the lead actors. Use only the actor_1_name column for extraction. Also, make sure that you use the names 'Meryl Streep', 'Leonardo DiCaprio', and 'Brad Pitt' for the said extraction.Append the rows of all these columns and store them in a new column named Combined.Group the combined column using the actor_1_name column.
8. Find the mean of the num_critic_for_reviews and num_users_for_review and identify the actors which have the highest mean.Observe the change in number of voted users over decades using a bar chart. 
9. Create a column called decade which represents the decade to which every movie belongs to. For example, the title_year year 1923, 1925 should be stored as 1920s. Sort the column based on the column decade, group it by decade and find the sum of users voted in each decade. Store this in a new data frame called df_by_decade.
10. Your task: Find the critic-favorite and audience-favorite actors

## [Link to dataset](https://drive.google.com/file/d/1XpGThHzLnXxL_7aQo2sCpYL3SeB18MMB/view?usp=sharing)
