# 🐼Pandas vs 🐻‍❄️Polars: A Data Workflow Showdown

If you've ever handled data operations in Python, you’ve likely used the pandas package for your data manipulation needs. Whether it's reading data, storing it in convenient DataFrames, or performing various data exploration tasks, pandas has been a key tool in all your data projects. However, have you heard of Polars? It can handle almost everything that pandas does, but it’s designed to be significantly faster and more optimised. This can save you a lot of time, especially when working with large datasets.

Is it genuinely that fast, and is it worth switching from pandas, which has become muscle memory for us and is almost synonymous with data manipulation in Python?

| Operation                | Pandas                      | Polars                      |
|--------------------------|------------------------------|-----------------------------|
| **Reading Data**         | 461 ms ± 78.2 ms             | 208 ms ± 56.1 ms            |
| **Joining Data**         | 684 ms ± 50.4 ms             | 290 ms ± 48.7 ms            |
| **Writing Data**         | 5.97 s ± 142 ms              | 1.52 s ± 50.3 ms            |
| **Selecting Data Columns**| 49.9 ms ± 1.43 ms           | 13.8 µs ± 5.2 µs            |
| **Filtering**            | 80.1 ms ± 19.5 ms            | 41.9 ms ± 1.66 ms           |
| **Grouping and Aggregation** | 170 ms ± 33.3 ms         | 46.2 ms ± 1.06 ms           |
| **Changing Data Types**  | 1.48 ms ± 124 µs             | 46.1 µs ± 12.7 µs           |
| **Sorting**              | 317 ms ± 53.9 ms             | 388 ms ± 57.1 ms            |


