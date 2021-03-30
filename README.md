# Data-Acquisition
Acquisition of data related to poverty for all the countries using Beautiful Soup and Selenium

-------------
Data Sources: 
-------------

We have collected/extracted most of our data using webscrapping from below sources
https://www.worldbank.org/ 
http://iresearch.worldbank.org/PovcalNet/data.aspx 

--------------------------------------------------------
Below are the indicators that we have used in our data:
--------------------------------------------------------

Poverty-I.csv have below attributes:
....................................

Country: 

We have taken the countries listed on world bank 
http://iresearch.worldbank.org/PovcalNet/data.aspx

Year:

We have extracted data from 2010 to 2019. 

Population (in million):

Total population is based on the de facto definition of population, which counts all residents regardless of legal status or citizenship. The values shown are midyear estimates.

Per_Capita_Expenditure (PCE):

The personal consumption expenditure (PCE) measure is the component statistic for consumption in gross domestic product (GDP). It consists of the actual and imputed expenditures of households and includes data pertaining to durable and non-durable goods and services. It is essentially a measure of goods and services targeted towards individuals and consumed by individuals.

GDP:

GDP per capita is gross domestic product divided by midyear population. GDP at purchaser's prices is the sum of gross value added by all resident producers in the economy plus any product taxes and minus any subsidies not included in the value of the products. It is calculated without making deductions for depreciation of fabricated assets or for depletion and degradation of natural resources. Data are in constant local currency.

Consumer_Price_Index (CPI):

The Consumer Price Index (CPI) is a measure of the average change over time in the prices paid by urban consumers for a market basket of consumer goods and services. Indexes are available for the U.S. and various geographic areas. Average price data for select utility, automotive fuel, and food items are also available.

Currency conversion:

The impact of alternative exchange rate regimes on growth, inflation and the balance of payments and discusses the choice of the exchange rate regime that minimizes poverty under normal conditions and crisis periods.

Poverty-II.csv have below attributes:
.....................................

Country: 

We have taken the countries listed on world bank 
https://www.worldbank.org/

Year:

We have extracted data from 2010 to 2019. 
Population (total):

Total population is based on the de facto definition of population, which counts all residents regardless of legal status or citizenship. The values shown are midyear estimates

Unemployment Rate (total (% of total labor force) (modeled ILO estimate)):

Unemployment refers to the share of the labor force that is without work but available for and seeking employment. 
The standard definition of unemployed persons is those individuals without work, seeking work in a recent past period, and currently available for work, including people who have lost their jobs or who have voluntarily left work. Persons who did not look for work but have an arrangement for a future job are also counted as unemployed and unemployment status can play a major role while identifying the poverty rate. 

Literacy Rate (adult total (% of people ages 15 and above)):

Adult literacy rate is the percentage of people ages 15 and above who can both read and write with understanding a short simple statement about their everyday life.

Primary Education completion rate:

Primary completion rate, or gross intake ratio to the last grade of primary education, is the number of new entrants (enrollments minus repeaters) in the last grade of primary education, regardless of age, divided by the population at the entrance age for the last grade of primary education. Data limitations preclude adjusting for students who drop out during the final year of primary education.

GDP Growth Rate (annual %):

Annual percentage growth rate of GDP at market prices based on constant local currency. Aggregates are based on constant 2010 U.S. dollars. GDP is the sum of gross value added by all resident producers in the economy plus any product taxes and minus any subsidies not included in the value of the products. It is calculated without making deductions for depreciation of fabricated assets or for depletion and degradation of natural resources.

GDP (current US$):

GDP at purchaser's prices is the sum of gross value added by all resident producers in the economy plus any product taxes and minus any subsidies not included in the value of the products. It is calculated without making deductions for depreciation of fabricated assets or for depletion and degradation of natural resources. Data are in current U.S. dollars. Dollar figures for GDP are converted from domestic currencies using single year official exchange rates. For a few countries where the official exchange rate does not reflect the rate effectively applied to actual foreign exchange transactions, an alternative conversion factor is used.

External Debt stocks (total (DOD, current US$)):

Total external debt is debt owed to nonresidents repayable in currency, goods, or services. It is the sum of public, publicly guaranteed, and private nonguaranteed long-term debt, short-term debt, and use of IMF credit. Data are in current U.S. dollars.

Poverty headcount ratio (at national poverty lines (% of population)):

Long definition	National poverty headcount ratio is the percentage of the population living below the national poverty lines. National estimates are based on population-weighted subgroup estimates from household surveys.

Poverty gap at $1.90 a day (2011 PPP)(%):

Poverty gap at $1.90 a day (2011 PPP) is the mean shortfall in income or consumption from the poverty line $1.90 a day (counting the nonpoor as having zero shortfall), expressed as a percentage of the poverty line. This measure reflects the depth of poverty as well as its incidence. As a result of revisions in PPP exchange rates, poverty rates for individual countries cannot be compared with poverty rates reported in earlier editions.

Poverty gap at $3.20 a day (2011 PPP)(%):

Poverty gap at $3.20 a day (2011 PPP) is the mean shortfall in income or consumption from the poverty line $3.20 a day (counting the nonpoor as having zero shortfall), expressed as a percentage of the poverty line. This measure reflects the depth of poverty as well as its incidence.
    
Poverty gap at $5.50 a day (2011 PPP)(%):

Poverty gap at $5.50 a day (2011 PPP) is the mean shortfall in income or consumption from the poverty line $5.50 a day (counting the nonpoor as having zero shortfall), expressed as a percentage of the poverty line. This measure reflects the depth of poverty as well as its incidence

Primary Education Completion Rate(total(% of relevant age group)):

Primary completion rate, or gross intake ratio to the last grade of primary education, is the number of new entrants (enrollments minus repeaters) in the last grade of primary education, regardless of age, divided by the population at the entrance age for the last grade of primary education. Data limitations preclude adjusting for students who drop out during the final year of primary education.

GNI Per Capita (PPP (current international $)) :

GNI per capita based on purchasing power parity (PPP). PPP GNI is gross national income (GNI) converted to international dollars using purchasing power parity rates. An international dollar has the same purchasing power over GNI as a U.S. dollar has in the United States. GNI is the sum of value added by all resident producers plus any product taxes (less subsidies) not included in the valuation of output plus net receipts of primary income (compensation of employees and property income) from abroad. Data are in current international dollars based on the 2011 ICP round.

Current Health Expenditure:

GNI per capita based on purchasing power parity (PPP). PPP GNI is gross national income (GNI) converted to international dollars using purchasing power parity rates. An international dollar has the same purchasing power over GNI as a U.S. dollar has in the United States. GNI is the sum of value added by all resident producers plus any product taxes (less subsidies) not included in the valuation of output plus net receipts of primary income (compensation of employees and property income) from abroad. Data are in current international dollars based on the 2011 ICP round.

Death Rate(Malnutrition):

Cause of death refers to the share of all deaths for all ages by underlying causes. Communicable diseases and maternal, prenatal and nutrition conditions include infectious and parasitic diseases, respiratory infections, and nutritional deficiencies such as underweight and stunting.

Employment in Agriculture (%of total employment):

Employment is defined as persons of working age who were engaged in any activity to produce goods or provide services for pay or profit, whether at work during the reference period or not at work due to temporary absence from a job, or to working-time arrangement. The agriculture sector consists of activities in agriculture, hunting, forestry and fishing, in accordance with division 1 (ISIC 2) or categories A-B (ISIC 3) or category A (ISIC 4).

Employment in Industry (%of total employment)::

Employment is defined as persons of working age who were engaged in any activity to produce goods or provide services for pay or profit, whether at work during the reference period or not at work due to temporary absence from a job, or to working-time arrangement. The industry sector consists of mining and quarrying, manufacturing, construction, and public utilities (electricity, gas, and water), in accordance with divisions 2-5 (ISIC 2) or categories C-F (ISIC 3) or categories B-F (ISIC 4).

Employment in Services:

Employment is defined as persons of working age who were engaged in any activity to produce goods or provide services for pay or profit, whether at work during the reference period or not at work due to temporary absence from a job, or to working-time arrangement. The services sector consists of wholesale and retail trade and restaurants and hotels; transport, storage, and communications; financing, insurance, real estate, and business services; and community, social, and personal services, in accordance with divisions 6-9 (ISIC 2) or categories G-Q (ISIC 3) or categories G-U (ISIC 4).

------------------
Expected Analysis:
------------------

Any individual/organization that is interested in eradicating poverty for example:  Government organizations, NGOs, UNO, charity foundations etc. would like to have a look at our studies and learn more about the analysis.
We can analyze how population and poverty are related.
Year-wise data helps us to find the trends in poverty rate.
How does the indicators like Literacy rate & unemployment rate look in under-developed countries?
Is external debt increasing/decreasing over years.

-----------
Challenges:
-----------

The main challenge during our extraction is to handle the java-script response which we got from many websites when we try to web scrap using “request.get” function. Below is in example of .aspx website.
http://iresearch.worldbank.org/PovcalNet/data.aspx
So we used HTMLSession to get the correct HTML with data and selenium tool for Web Scrapping.

The data in which we are interested is not available on single website, hence extracting data from different website having different layout was also one of the challenge we faced.

Missing values - Data not available for few countries & years, for few indicators.

Merging the different tables and combined to make a single dataset. 

There are some website from which we weren't able to scrap anything even after using selenium, HTML session eg. http://hdr.undp.org/en/indicators/137506  
 
Missing values in the data can be a challenge/limitation for further analysis.

