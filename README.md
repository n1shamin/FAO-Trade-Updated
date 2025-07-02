# FAO-Trade-Updated
In 2025, the item scheme for the eight FAO Trade and Livestock tables were updates, which meant huge changes between the historical and new data. The attached script processes a bulk download from the FAO and organizes it into excels for easy proccessing into IFs but it also contains an option to directly put the data in a SQL table.

# Item Scheme
This contains the new item scheme. It is found in this wiki: https://pardeewiki.du.edu/index.php?title=FAOSTAT_Trade_Crops_and_livestock_products 

# Python Scripts
All data processing scripts are in Python under the Jupyter Notebook. 
FAO Trade.ipynb contains the script to complete the aggregation for both crop and meat and export/import quantity and value. Simply # out the item codes you are not using (ie # out crop related lines in order to agreggate meat. 

Once you have the Excel sheets you can use the IFs interface to input it into .db. 
