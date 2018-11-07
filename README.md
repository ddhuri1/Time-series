# Time-series
Trend Prediction


The specific problem in this project is about the time-series data trend prediction. The specific application scenario is in e-commerce. You are given a real dataset obtained from a real-world e-commerce application where there were 1000 products and 31490 customers (i.e., buyers) who bought these products. Of these 1000 products there are 100 key products (popular products). Also these 1000 products are in 15 categories. The specific data are given in the seven files and the specific details of these files are given below. The time window of this dataset is in 118 days with data documentation for each day. Hence, the time unit is one day where the timeline goes from the 0-th day to the 117-th day (17 weeks less one day in total). Now you are asked to do the sale quantity prediction for the 100 key products for each day between the 118-th day and the 146-th day (29 days).

•	buyer_basic_info.txt: the basic attribute information of the buyers; in particular, the column names of this table are "buyer_id", "registration_time", "seller_level", "buyer_level", "age", and "gender". If we do not know the gender of a buyer, we set this buyer’s gender attribute as -1.

•	buyer_historical_category15_quantity.txt: the consumption quantities in the 15 categories for the buyers; in particular, the column names of this table are "buyer_id", "consumption quantity in the 1st category", ..., and "consumption quantity in the 15th category". The 15 categories are the ones of the products the customers bought in this dataset.

•	buyer_historical_category15_money.txt: the consumption amounts in the 15 categories for the buyers; in particular, the column names of this table are "buyer_id", "consumption amount in the 1st category", ..., and "consumption amount in the 15th category".

•	product_features.txt: the basic attribute information of the products; in particular, the column names of this table are "product_id", "attribute_1", "attribute_2", and "original price".

•	Key_product_IDs.txt: the key product IDs

•	trade_info_training.txt: the trade information between the key products and the buyers from the 0-th day to the 117-th day; in particular, the column names of this table are "product_id", "buyer_id", "trade_time", "trade_quantity", and "trade_price".

•	product_distribution_training_set.txt: there are 119 columns, where the 1-st column shows the "product_id" and the 2-nd to the 119-th columns show the "quantities" of the key products from the 0-th day to the 117-th day; for example, the element at the 5-th row and the 10-th column in this table shows the quantity of the 5-th product at the 8-th day.


Find the prediction for the overall sale quantity of the 100 key products for each day of the time window from the 118-th day to the 146-th day, and for the sale quantity for each key product for each day of the time window. 
