# Winnie Wines

A data analysis project, aiming to provide a better understanding of the wine market based on wine consumption data from wine aggregator company Wiwino.

![image](https://github.com/emsuru/winnie-wines/assets/141214124/03ae3960-483f-4ba9-934f-3a55ebfcabf1)


## Project Instructions (to be removed later)

### Crunch the numbers to arrive at a complete market analysis. Questions to answer for the client, Wiwino (use these as story points):

1. We want to highlight 10 wines to increase our sales. Which ones should we choose and why?
2. We have a limited marketing budget for this year. Which country should we prioritise and why?
3. We would like to give awards to the best wineries. Come up with 3 relevant ones. Which wineries should we choose and why?
4. We detected that a big cluster of customers likes a specific combination of tastes. We identified a few keywords that match these tastes: coffee, toast, green apple, cream, and citrus (note that these keywords are case sensitive ⚠️). We would like you to find all the wines that are related to these keywords. Check that at least 10 users confirm those keywords, to ensure the accuracy of the selection. Additionally, identify an appropriate group name for this cluster.
5. We would like to select wines that are easy to find all over the world. Find the top 3 most common grapes all over the world and for each grape, give us the the 5 best rated wines.
6. We would like to create a country leaderboard. Come up with a visual that shows the average wine rating for each country. Do the same for the vintages.
7. One of our VIP clients likes Cabernet Sauvignon and would like our top 5 recommendations. Which wines would you recommend to him?
8. Give us any other useful insights you found in the data. Be creative! 😉

If a certain question is hard or not possible to answer with the data you have been given, document what is missing. This can always happen...

### Known issues

- The wineries table doesn't link properly to the wines table. Match only gives four items so not useful.
- The wineries name is (probably) the wine name.
- The wines_count variable is instead in the most_used_grapes_per_country table and it doesn't make sense because it is the same for all (so probably a worldwide figure and not per country).
- The regions_count variable from the countries table doesn't correspond to the actual number of regions found in the database (e.g. way less regions in France than the count variable indicates).
- Not clear what the user_structure_count variable means.
- It is not possible to find the exact grape for an individual wine. With string matching you can try to circumvent this, but the matching rate is not very high (due to many wines not referencing the name of their grape).


### Nice-to-have features
- Optimise your queries to obtain the results as fast as possible.
- How would you improve the data (quality), the database schema, or the typing?
- Implement visualization best practices
- Data storytelling, nice design, relevancy to the questions asked, ...

### Constraints
- You are not allowed to use pandas or similar tools for the data analysis, you should use SQL and SQL only
- For instance, use SQL JOINs to cross-reference tables, not pd.merge()
- But you can of course use a Python ORM library if you like
- Write your queries in dedicated .sql files or a queries.py file with the queries as strings

### Deliverables
- Publish your source code in a GitHub repository
- Pimp the README file
- Include the main insights in it
- Show us your results in a nice presentation
- Can be with PowerPoint, a smooth Jupyter notebook & Markdown, a printout, ...
- Data engineers will deliver a Streamlit app and Data analysts a Tableau dashboard

### Steps
- Create the repository
- Study the project brief (Who? Why? What?)
- Identify the technical challenges (How?)
- Start exploring the data
- Answer the questions with clear queries
- Create a presentation with your findings
- Clean your code and finish up your repository
- Again: be creative in both the analysis and delivery!!! Try to impress us.
