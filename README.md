# SQL-Deforestation-Study
Analyze world deforestation data using SQL
ForestQuery is on a mission to combat deforestation around the world and to raise awareness about this topic and its impact on the environment. The data analysis team at ForestQuery has obtained data from the World Bank that includes forest area and total land area by country and year from 1990 to 2016, as well as a table of countries and the regions to which they belong.

The data analysis team has used SQL to bring these tables together and to query them in an effort to find areas of concern as well as areas that present an opportunity to learn from successes.

1. GLOBAL SITUATION
According to the World Bank, the total forest area of the world was 41282694.9 sqkm in 1990. As of 2016, the most recent year for which data was available, that number had fallen to 39958245.9 sqkm, a loss of 1324449 sqkm, or 3.21 %.

The forest area lost over this time period is slightly more than the entire land area of Peru listed for the year 2016 (which is 1279999.99 sqkm).

2. REGIONAL OUTLOOK
In 2016, the percent of the total land area of the world designated as forest was 31.38 %. The region with the highest relative forestation was Latin America & Caribbean, with 46.16%, and the region with the lowest relative forestation was Middle East, with 2.07% forestation.

In 1990, the percent of the total land area of the world designated as forest was 32.42%. The region with the highest relative forestation was Latin America & Caribbean, with 51.03%, and the region with the lowest relative forestation was Middle East, with 1.78 % forestation.

Table 2.1: Percent Forest Area by Region, 1990 & 2016:

Region	1990 Forest Percentage	2016 Forest Percentage
Latin America & Caribbean	51.03
46.16

Sub-Saharan Africa	32.19	27.56
World 	32.42	31.38
Middle East & North Africa	1.78	2.07
North America	35.65	36.04
East Asia & Pacific	25.77	26.36
Europe & Central Asia	37.27	38.06
South Asia	16.51	17.05

The only regions of the world that decreased in percent forest area from 1990 to 2016 were Latin America & Caribbean (dropped from 51.03% to 46.16%) and Sub-Saharan Africa (32.19% to 27.56%). All other regions actually increased in forest area over this time period. However, the drop in forest area in the two aforementioned regions was so large, the percent forest area of the world decreased over this time period from 32.42% to 31.38%. 

3. COUNTRY-LEVEL DETAIL
A.	SUCCESS STORIES
There is one particularly bright spot in the data at the country level, China. This country actually increased in forest area from 1990 to 2016 by 527229.06. It would be interesting to study what has changed in this country over this time to drive this figure in the data higher. The country with the next largest increase in forest area from 1990 to 2016 was the United States, but it only saw an increase of 79200, much lower than the figure for China.

China and United States are of course very large countries in total land area, so when we look at the largest percent change in forest area from 1990 to 2016, we aren’t surprised to find a much smaller country listed at the top. Iceland increased in forest area by 213.66% from 1990 to 2016. 

B.	LARGEST CONCERNS
Which countries are seeing deforestation to the largest degree? We can answer this question in two ways. First, we can look at the absolute square kilometer decrease in forest area from 1990 to 2016. The following 3 countries had the largest decrease in forest area over the time period under consideration:

Table 3.1: Top 5 Amount Decrease in Forest Area by Country, 1990 & 2016:

Country	Region	Absolute Forest Area Change
Brazil	Latin America & Caribbean	541510
Indonesia	East Asia & Pacific	282193
Myanmar	East Asian & Pacific 	107234
Nigeria	Sub-Saharan Africa	106506.00
Tanzania	Sub-Saharan Africa	102320


The second way to consider which countries are of concern is to analyze the data by percent decrease.

Table 3.2: Top 5 Percent Decrease in Forest Area by Country, 1990 & 2016:

Country	Region	Pct Forest Area Change
Togo	Sub-Saharan Africa	75.45
Nigeria	Sub-Saharan Africa	61.80
Uganda	Sub-Saharan Africa	59.13
Mauritania	Sub-Saharan Africa 	46.75
Honduras	Latin America & Caribbean	45.03


When we consider countries that decreased in forest area the most between 1990 and 2016, we find that four of the top 5 countries on the list are in the region of Sub-Saharan Africa. The countries are Togo, Nigeria, Uganda, and Mauritania. The 5th country on the list is Honduras, which is in the Latin America & Caribbean region. 

From the above analysis, we see that Nigeria is the only country that ranks in the top 5 both in terms of absolute square kilometer decrease in forest as well as percent decrease in forest area from 1990 to 2016. Therefore, this country has a significant opportunity ahead to stop the decline and hopefully spearhead remedial efforts.

C.	QUARTILES

Table 3.3: Count of Countries Grouped by Forestation Percent Quartiles, 2016:

Quartile	Number of Countries
0-25%	85
25-50%	73
50-75%	38
75-100%	9

The largest number of countries in 2016 were found in the 0-25% quartile.

There were 9 countries in the top quartile in 2016. These are countries with a very high percentage of their land area designated as forest. The following is a list of countries and their respective forest land, denoted as a percentage.

Table 3.4: Top Quartile Countries, 2016:
 
Country	Region	Pct Designated as Forest
American Samoa	East Asia & Pacific	87.50
Micronesia, Fed. Sts.	East Asia & Pacific	91.86
Gabon	Sub-Saharan Africa	90.04
Guyana	Latin America & Caribbean	83.90
Lao PDR	East Asia & Pacific	82.11
Palau	East Asia & Pacific	87.61
Solomon Islands	East Asian & Pacific 	77.86
Suriname	Latin America & Caribbean	98.26
Seychelles	Sub-Saharan Africa	88.41

5. RECOMMENDATIONS
It is unfortunate that most of the percent forest decline happened in the Sub-Sahara Africa; these are smaller countries with smaller land area. The biggest lost in forest area was Brazil, Indonesia and Myanmar. A very surprising finding was that two of the world’s largest polluters of Carbon (China and United States) saw an increase in forest area.  It will be recommended for team to further investigate the reason for this improvement and what kind of green initiatives have led to this.  For instance, what has led to Iceland’s whopping 213.66% percent forest increase from 1990 to 2016. 

Further, the team should focus on understanding the reason for a significant decline in percent forestation in the Sub-Saharan African countries especially Togo, Nigeria, Uganda and Mauritania. Nigeria for instance was on both the list for decline in forest area and percent forestation. Nigeria therefore will be a good candidate to implement any new policies or programs due to its smaller land area compared to a country like Brazil.  

The team should look into reasons for loss of significant forestation in Brazil, Indonesia  and Myanmar. Brazil especially saw the most significant decline in forestation – recent wild fires in the Amazon is probably a significant contributing factor to this observation. 

Lastly, although China and United States have done considerably well in improving forestation on their lands, there are still over 94 countries which have more percent forestation that the United States. It is recommended that the team looks at countries like Iceland and then expand their assessment to other 93 countries that sill doing reasonably well in preserving their natural habitat. 
