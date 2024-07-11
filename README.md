# air-quality-data-analysis

Jupyter notebooks containing a wide array of various analysis techniques on the data provided by
[arduino-air-state-server](https://github.com/straightchlorine/arduino-air-state-server) and
[async-httpd-data-collector](https://github.com/straightchlorine/async-httpd-data-collector) as database interface.

In the `analysis_notebook.zip` package there are some large heatmaps(considerable size, that's why archive is added) and other types of graphs.
In the `prediction.ipynb`, however, there is some experimentation with `SARIMAX` model and forecasting future parameters on a pretty small 
dataset, due to the lack of computational power.

It was part of a university project, so I used [plotly](https://github.com/plotly/plotly.py) for interactive graphs.
