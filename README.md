# Data Utils
Utility functions for Pandas and Data Analysis

## Installations
This project was created using Python 3.
```
pip install data-utils-mt
```
Scipy and Numpy are required.

## Project Motivation
This package was uploaded as part of the

## How to interact with the project
Below are some examples of usage:

```
from data_utils_mt import utils as u

u.common_values(series1, series2)
u.cluster_corr(ts)
u.apply_parallel(df, func)

@u.pandify
def my_fun(scalar):
  return 2 * scalar
```

## Licensing, Authors, Acknowledgements
Code released under the [MIT](https://opensource.org/licenses/MIT) license.

This project was authored by Miguel Tasende.
