# SQL To Snowflake DDL Converter
This converter is built with .NET Core. It converts SQL Server Table definitions to Snowflake DDL Syntax. 

# Steps Performed by the Converter
	1. Connects to a SQL Server database (connection string is provided in appsettings.json)
	2. Extracts the T-SQL definition of tables specified in Converter\ObjectList.txt file
		2.1. Format of ObjectList file: Comma separated table names. E.g. schema.tablename1,schema.tablename2
	3. T-SQL definitions are stored in InputScripts folder at the root
	4. Converts the T-SQL DDL statements to Snowflake compatible syntax and stores them in OutputScipts folder
	
# Before running the tool
	1. Set the DB connection in appsettings.json
	2. Add the table names to Converter\ObjectList.txt file
	3. Run the SQLToSF.exe
	4. Select Option 1
	5. Check the OutputScripts folder for converted scripts
	
	
Happy Conversion!!! :)
	





