O scrip should be used in the following order.

1) Importing libraries
Example

import pandas as pd

2) Import database
Example

data=pd.read_csv ('Import database.csv')

3) Generate Taylor diagram

Defining the data table column that is the comparison reference data
Example
observations = data.reference

Defining the column of the data table that is the estimated data for comparison
Example

simulations =  {"Subtitle": data.estimated}


```python

```
