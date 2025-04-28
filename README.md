# Benchmark of Python data manipulation libraries

## 📌 Project Overview
Use python libraries for data manipulation in order to test the speed of each one when performing tasks.
For the tests used, some day to day operations like data ingestion, grouping, filtering, multiple column operation and data offload are being employed.
The libraires selected for testing are:
- Polars
- Pandas
- DuckDb

## Expected results
It is expected to obtain graphs for each test showing the speed performance and a final recopilation. This in order to provide a useful index on which libreray fits best some functionalities like analytic procedures or register augmentation.

## Future Work
- Add Pyspark to the benchmark
- Add Vaex
- Add Ibis
- Add Dask

## Results:
### Reading Speed
![alt text](images/reading.png)
### Increment dataset vertical length
![alt text](images/population.png)
### Data grouping speed
![alt text](images/grouping.png)
### Data sorting speed
![alt text](images/sorting.png)
### Data filtering speed
![alt text](images/filtering.png)
### Memory usage while incrementing dataset size
![alt text](images/memory.png)
### Data offloading into parquet file speed
![alt text](images/offload.png)
