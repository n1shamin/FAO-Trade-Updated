# FAO-Trade-Updated
In 2025, the item scheme for the eight FAO Trade and Livestock tables were updates, which meant huge changes between the historical and new data. The attached script processes a bulk download from the FAO and organizes it into excels for easy proccessing into IFs but it also contains an option to directly put the data in a SQL table.

# Country Concordance
The file Country.xlsx contains the country concordance between IFs and FAO. CountryWB.xlsx contains country concordance for the World Bank and IFs for the four % of GDP tables. During each update, it is suggested that users use the scritps to double check if entity names under the Excel file are up to date.

# Item Scheme
This contains the new item scheme. It is also found in this wiki: https://pardeewiki.du.edu/index.php?title=FAOSTAT_Trade_Crops_and_livestock_products 

# Python Scripts
All data processing scripts are in Python under the Jupyter Notebook. 
FAO Trade.ipynb contains the script to complete the aggregation for both crop and meat and export/import quantity and value. Simply # out the item codes you are not using (ie # out crop related lines in order to agreggate meat. 

FAO GDP Trade.ipynb contains the script for 

If you wish to bypass the IFs interface, FAO Trade Bypass.ipynb does this for you. 
