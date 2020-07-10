NOTES - AG-INCENTIVES.org NRP FILE 
Version 2018_1

Copyright: 
The dataset and the visualizations provided on the Ag-Incentives.org website are protected by the Creative Commons Attribution-NonCommercial 
license (CC BY-NC) [https://creativecommons.org/licenses/by-nc/3.0/].

Additional copyrights on primary data may still be applied depending on initial data provider.

Category - Filter by level of aggregation COUNTRY/PRODUCT
		COUNTRY_PRODUCT - Country and product level
		COUNTRY_TOTAL - Individual country and aggregate product
		ALL_PRODUCT - Aggregate country and individual product
		ALL_TOTAL - Aggregate country and aggregate product
Source - OECD, Agrimonitor (IDB), MAFAP, World Bank (SA), Ag-Incentives Consortium (our calculations) 	
CountryCode - ISO ALPHA-3 Code or 'ALL' for aggregate of all countries
CountryName - Country Name or 'ALL' for aggregate of all countries	
WBIncomeGroup - World Bank defined Income Groups or 'ALL' for aggregate of all countries	
NumberProducts - Number of products represented	
NumberCountries	- Number of countries represented
NumberCommodities - Number of commodities represented
Year - (2005-2016)	
ProductCode - Ag-Incentives Consortium Nomenclature or 'TOTAL' for aggregate of all products	
ProductName - Product Name or 'TOTAL' for aggregate of all products		
Quantity - Quantity	
PhysicalUnit - MT or AG (for aggregated commodities, indices are used)	
ReferencePriceAtFGL - Reference Price at Farm Gate Level 	
ProducerPriceAtFGL - Producer Price at Farm Gate Level 	
ValueProduction_PP - Value of Production for Producer Price at Farm Gate Level (Quantity * ProducerPriceAtFGL) 	
ValueProduction_Ref - Value of Production for Reference Price at Farm Gate Level (Quantity * ReferencePriceAtFGL) 	
MonetaryUnit - USD	
NRP - Nominal Rate of Protection ((ValueProduction_PP / ValueProduction_Ref) - 1)*100	
NRP_SimpleAverage - NRP aggregated with a simple arithmetic average
ValueDistortion	- Distortion Value (Quantity * (ProducerPriceAtFGL - ReferencePriceAtFGL)
CoverageRatio - Coverage Ratio (for Totals only) (Sum[ValueProduction_PP for identified products] / Total ValueProduction_PP )
Notes - Notes  (multiple numbers signify multiple modifications): 
	0 No changes
	1 Production quantity modified by the consortium
	2 Producer Price at farm gate computed by the consortium
	3 Reference Price at farm gate computed by the consortium
	4 Reference Price at farm gate modified by the consortium when no policy assumed (MPD=0)
	5 Producer Price at farm gate provided by the consortium using external sources
	6 Reference Price at farm gate provided by the consortium using external sources
	7 Monetary units corrected by the consortium
	8 Preliminary Results for India. OECD update forthcoming
	9 Aggregate computed by the Consortium
	10 Exchange rate modified for computation of the reference price
	11 Exchange rate modified for all conversion in USD
	12 Consumption quantity computed by the consortium using external sources
	13 MPS set to 0 when IO experts consider it as irrelevant
	14 SugarBeet price used
	15 Raw Sugar price used
	16 Sugarcane price used

All central information regarding Reference and Farmgate prices are based on each International Organization’s database. 
The Consortium adds or modifies the information only to guarantee comparability between sources, completeness of the consolidated database, 
and consistency of the methodology.