**from-months-to-weeks-and-vice-versa-converter**

This function allocates any time series values in monthly/weekly periodicity into weekly/monthly periodicity respectively. 
The main idea of this function is to compute a value per 1 day for each month/week and then return any aggregation you want.

The best case for this function is when you have a time series with monthly periodicity
and you want to convert this time series into weeks (see example in the notebook)

This function supports ISO calendar system (https://docs.python.org/3/library/datetime.html#datetime.date.isocalendar)
