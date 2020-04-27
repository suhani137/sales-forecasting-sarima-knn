Weekly sales forecasting with SARIMA and KNN
This project contains data for daily sales. which were later grouped into weekly sales to forecast better results.
There were about 13 categories of products, which were further sub-divided into more than 4000 items.
The aim was to forecast weekly sales for each item.
It required a lot of preprocessing by grouping data and determining active items that sell frequently.
SARIMA was applied on all items, but KNN was used on only active items. Active items were determined on the basis of threshold values.
Threshold for an item was calculated by calculating coefficient of variance for an item. Items with coefficient of variance in the range (0,4.5) were considered active.
