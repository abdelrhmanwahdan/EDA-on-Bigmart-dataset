# Bigmart EDA

![Analysis](images/analysis.jpg "Analysis")

The data scientists at BigMart have collected sales data for 1559 products across 10 stores in different cities for the year 2013. Now each product has certain attributes that sets it apart from other products. Same is the case with each store.
The aim is to build a predictive model to find out the sales of each product at a particular store so that it would help the decision makers at BigMart to find out the properties of any product or store, which play a key role in increasing the overall sales.

# Contents
0. **About Data**

1. **Import Libraries and data**

2. **Data Inspection**

3. **Data Cleaning :**

    - Missing values imputation

    - Dealing with inconsistent values

4. **Data Visualization**

![fat_itemtype](images/fat_itemtype.png "fat_itemtype")


![store_outletlocation](images/store_outletlocation.png "store_outletlocation")


![item_MRP](images/item_MRP.png "item_MRP")


![item_type](images/item_type.png "item_type")



5. **Feature Engineering**

6. **Feature Scaling**

7. **Building Models**

8. **Conclusion**

# About the data

### FEATURES:

- Item_Identifier : Unique product ID

- Item_Weight : Weight of product

- Item_Fat_Content : Whether the product is low fat or not

- Item_Visibility : The % of total display area of all products in a store allocated to the particular product

- Item_Type : The category to which the product belongs

- Item_MRP : Maximum Retail Price (list price) of the product

- Outlet_Identifier : Unique store ID

- Outlet_Establishment_Year : The year in which store was established

- Outlet_Size : The size of the store in terms of ground area covered

- Outlet_Location_Type : The type of city in which the store is located

- Outlet_Type : Whether the outlet is just a grocery store or some sort of supermarket

- Item_Outlet_Sales : Sales of the product in the particular store.
