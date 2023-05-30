# Home Sales!!!

<img width="100%" alt="Haverford Real Estate" src="https://github.com/equitymarkets/Home_Sales/assets/49753517/75aa9c56-c11c-4123-b215-db0ef302fa61">

Working with Big Data in the real estate market is challenging, so for this project I first created a PySpark dataframe, then used SQL queries to retrieve the desired data. After several SQL queries relating to amount of rooms and price (see notebook file), I cached the data and tested the runtime. Runtime mostly clocks in a bit faster, but usually only by about 30% or less. Next I used parquet to create a temp table and partition the data. Running a timer for the same query (average view score for houses >= 350,000 dollars) returned a similar value to the uncached query at the beginning (see notebook file). 

At the end of the analysis I made sure to uncache the data. 
