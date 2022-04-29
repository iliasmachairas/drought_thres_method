Drought Threshold Method
===============

<div align="center">
  <img src="https://github.com/iliasmachairas/iliasmachairas/blob/main/Images/water_droplet.jpg?raw=true"><br>
</div>

What is it?
===============
---
drought_thres_method is a package used to indentify drought events' duration and deficit using threshold method. It is worth mentioning methodology for threshold functions were derived by Beyene (2014)

Main features
------
---
For the time being, the package includes three thresholds:
* fixed threshold,
* moving average of monthly quantile (variable threshold for short)
* 30-day moving window quantile (moving window for short).


## Input
The main input is a dataframe which contains daily data of a hydrological state variable (such as soil moisture, groundwater level). The index type should be date.
## Output
The main output of this package is to create a dataframe which contains the drought events indentified and its main characteristics (onset, end, deficit, duration). It also provides a plot of the drought events and some basic statistics of them.

How to get it?
----
---
It is very easy to install it. For the time being, it has only be checked for Windows.
```python
pip install grought_thre_method
```

Dependencies
----
----
Numpy - https://numpy.org/ <br>
Pandas - https://pandas.pydata.org/ <br>
Matplotlib - https://matplotlib.org/


Documentation
----
----
For further explanation, read the docs at this [link](https://draft-docs.readthedocs.io/en/latest/#beyene)

License
----
----
All droufgt_thres_method wheels distributed on PyPI are BSD licensed.

Author
----
----
Ilias Machairas (More info can be found at https://iliasmachairas.com/en/homepage/)

References
------
----
Beyene, B. S., Van Loon, A. F., Van Lanen, H. A. J., & Torfs, P. J. J. F. (2014).
Investigation of variable threshold level approaches for hydrological drought identification.
Hydrology and Earth System Sciences Discussions, 11(11), 12765-12797.



