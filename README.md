# UCI_Student_Data
This a repo using Dask ML on continuous and categorical values to predict student performance. 

Using the UCI student-performance dataset, I will demonstrate several of Dask's best features. At a high level, Dask allows for a user to scale the machine learning and data structure packages within Python to multi-core computers and distributed computing clusters. There are three main advantages to Dask...

1. It can store data larger than what fits in RAM.
2. It executes computations in parallel.
3. It includes a task scheduler.

The specific objectives are as follows...
1. Demonstrate delayed dask execution (reads, aggregations, etc...)
2. Demonstrate Dask reading in multiple files at once.
3. Construct 3 dask machine learning models
  - Linear Regression
  - Random Forest
  - Kmeans Clustering
4. Use dask grid search to identify ideal parameters in parallel
