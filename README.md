# assi4
from pandas import read_csv
import numpy
dataset = read_csv('Average_Daily_Traffic_Counts.csv')
mean1 = dataset['Boundaries - ZIP Codes'].mean()
max1 = dataset['Boundaries - ZIP Codes'].max()
dataset1 = dataset.replace(numpy.NaN,mean1)
print(dataset)
print(dataset1)
output:
 ID ... :@computed_region_awaf_s7ux
0 414.0 ... 52.0
1 176.0 ... 31.0
2 715.0 ... 22.0
3 316.0 ... 48.0
4 1294.0 ... 47.0
... ... ... ...
1274 NaN ... NaN
1275 NaN ... NaN
1276 NaN ... NaN
1277 NaN ... NaN
1278 NaN ... NaN
[1279 rows x 15 columns]
 ID ... :@computed_region_awaf_s7ux
0 414.000000 ... 52.000000
1 176.000000 ... 31.000000
2 715.000000 ... 22.000000
3 316.000000 ... 48.000000
4 1294.000000 ... 47.000000
... ... ... ...
1274 33.892105 ... 33.892105
1275 33.892105 ... 33.892105
1276 33.892105 ... 33.892105
1277 33.892105 ... 33.892105
1278 33.892105 ... 33.892105
[1279 rows x 15 columns]
