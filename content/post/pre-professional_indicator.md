+++
date = "2017-03-29T19:32:31-04:00"
categories = ["Analysis"]
tags = ["Sports", "Hockey", "NHL"]
description = "A look at production before and after the ELC."
title = "Does pre-professional success predict success in the show?"
author = "JD Angerhofer"
+++


```python
import pandas as pd
import numpy as np
%matplotlib inline
```


```python
ts = pd.Series(np.random.randn(1000), index=pd.date_range('1/1/2000', periods=1000))
ts = ts.cumsum()
ts.plot()
```




    <matplotlib.axes._subplots.AxesSubplot at 0x1128737f0>




![png](/static/pre-professional_indicator/Untitled_1_1.png)
