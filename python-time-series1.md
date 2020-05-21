```python
import pandas as pd
import numpy as np
 
data = {"name" : ["dhans", "kutti"], "phno": [1234, 5678]}
index = ["aaaa", "bbbb"]
df = pd.DataFrame(data=data, index=index)
df
	    nam     phno
aaaa	dhans	1234
bbbb	kutti	5678


data = np.random.randn(6,4) 
index = ["A", "B", "C", "D", "E", "F"]
df = pd.DataFrame(data=data, index=index)
df

    0       	1	        2	        3   
A	1.241157	0.912899	0.235226	0.249771
B	-0.107771	0.702585	0.088645	-0.811368
C	-0.316395	-0.598464	1.151727	-0.699930
D	0.846542	-0.879045	-0.687689	-0.717599
E	2.407197	-0.421678	-1.782477	-0.352161
F	0.270575	0.815944	1.248444	-0.924187

df = pd.DataFrame(data=data, index=index, columns=list('ABCD'))
df 

    A	        B	        C	        D
A	1.241157	0.912899	0.235226	0.249771
B	-0.107771	0.702585	0.088645	-0.811368
C	-0.316395	-0.598464	1.151727	-0.699930
D	0.846542	-0.879045	-0.687689	-0.717599
E	2.407197	-0.421678	-1.782477	-0.352161
F	0.270575	0.815944	1.248444	-0.924187
```
