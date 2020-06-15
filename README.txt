README.txt

The following is a description of all data contained within this folder:


	Code:
	- 40-60-80 rule model.ipynb <- Main code used to build bayesian hierarchical model
	- BR_Cots_Glue.ipynb <- Used to connect all data into one file, plus some of the heavier cleaning tasks
	- BR_Names_Scraper.ipynb <- Used to pull full names and Baseball-Reference keycodes from www.baseball-reference.com


	Data:
	- BR_name_code.csv <- Result of BR_Names_Scraper.ipynb, lists full names and Baseball-Reference keycodes for players
	- Cots_name_fixes.csv <- Adjusts names that come from MLB-Salaries 2005-20.xlsx, aligns them with Baseball-Reference keycodes
	- HitterValue08-19.csv <- Data pulled from FanGraphs.com on hitters 
	- MLB-Salaries 2005-20.xlsx <- Salary and MLB service time data pulled from Baseball Prospectus' Cots Contracts
	- ST_data_clean.csv <- Result of BR_Cots_Glue.ipynb, main data after all data sources are joined together
	- SuperTwoCutoff.csv <- MLB service time cutoff for every Year, 2010-2019


	Unused Data:
	- PitcherValue08-19.csv <- Data pulled from FanGraphs.com on pitchers, can be incorporated in the future for a pitcher model