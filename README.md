# Matcha_Cafes
Find the best locations for a new brand of Matcha Cafes

# Client / Background
- A commercial real estate company wants to capitalize on the growing trend of Matcha by way of creating a brand of high end matcha cafes. 
- In 2019 the North America Matcha market share was valued at approximately $750 million USD. The industry is expected to gain 7.5% by 2026. 
- To be able to meet the expenses and profit expectations, client believes they need to develop cafes in high wealth geographies. Customers need to be able to afford a premium priced matcha drink. Initially sketched projections have outlined the price points at $8-$10 per drink.
- There’s considerable science linking Matcha to potential health benefits. https://www.webmd.com/food-recipes/ss/slideshow-all-about-matcha.  https://www.forbes.com/health/body/matcha-tea-health-benefits/

# Business Question 
**Where do we put matcha stores to best drive business success?**

# Impact Hypothesis Statement
Identifying geographic locations where people have higher income, and pursue healthy lifestyles, will increase the likelihood for sales of matcha drinks. 

# Data to Answer the Question
- [Personal Income by County 2020 ](https://www.bea.gov/data/income-saving/personal-income-county-metro-and-other-areas)
- [Number of Fitness and Recreational Sports Centers by County 2020](https://www.naics.com/naics-code-description/?code=713940)
- [County Population Totals 2020](https://www.census.gov/data/tables/time-series/demo/popest/2020s-counties-total.html)

# Solution Path
1. Filter Personal Income Data by > Median HHI $67,500 to get resulting counties that fall within that parameter
2. Within the filtered personal income data overlay number of fitness centers by county
3. Determine concentration of fitness centers by county population

# Criteria for Success
A list of counties that meet the personal income filter and contain a high concentration of fitness centers

# Assumptions and Risks 
- Greater than Median HHI is a starting point. More research and thinking will need to be done around this criteria. 
- The number of gyms and recreational sports centers serves to gage how important health is to a county. It’s assumed that the higher concentration of these types of businesses the higher the county values health and are actively participating in making their health better.  Which means that matcha may be also be something they’re actively interested in. 
- Matcha = better health  + feeling better (taste, experience) 

# Findings
Check out the presentation [here](https://github.com/Jenni-Hawk/Matcha_Cafes/blob/main/Matcha_Presentation.pdf)
<br>Check out the Tableau interactive charts: 
- [Resulting Counties Mapped on US Map](https://public.tableau.com/app/profile/jenni2472/viz/MatchaWork/Counties)
- [Top 20 Counties by Population](https://public.tableau.com/app/profile/jenni2472/viz/MatchaWork/Top20CountiesByPopulation)
- [Fitness Centers Per 1000 People By Income](https://public.tableau.com/app/profile/jenni2472/viz/FitnessCentersIncome/FitnessIncome)

# Tech Tools Used
- Excel
- Pandas
- Tableau









