# panda-demo
Contains list of programs to experiment Pandas package and other Python packages. These programs were written using Jupyter Notebook. 
The data sources for testing these programs were taken from https://github.com/chendaniely/2016-pydata-carolinas-pandas

## [panda-basics-01.ipynb](python/panda-basics-01.ipynb)
Use Pandas dataframe to the contents of a .csv file and observe various properties.

## pandas-concat-demo.ipynb
Lists the directory contents from "data" folder to identify files having naming patterns "concat*.csv". A dataframe will be initialized for each file listed which will be concatenated rowwise (axis=0, by default) and column wise (axis=1)

## pandas-filter-agg-ops-demo.ipynb
Demostrates different operations like filtering and aggregation operations like group by, count functions using the dataset survey_visited.csv and to answer questions like: 
1. Number of times a site has been visited
2. Site that has been first visited 
3. Site that has been last visited 
4. How many times a site has been visited in a given year (yet to complete)

# License
Licensed under [MIT License](LICENSE).
