
# Shaolin


## Framework for interactive widget-based dashboards programming. Feedback is really appreciated


**Shaolin**(**S**tructure **H**elper for d**A**shb**O**ard **LIN**king) is an ipywidgets based framework that allows to create interactive dashboards that can be linked with each other to build complex  applications.

Its still in a alpha alpha version, the beta version will be realeased before 17 july.

PLEASE HELP! I have not been able to upload it to pypi correctly, if someone told me whats wrong with my code it would be really appreciated.
Anyway, it can be installed using the setup script included in the code typing "python setup.py install" inside the project folder, or if you have the dependencies installed you can just download the folder and improt it on runtime to the python path. (The first cell in every example notebook does that.)

### Dependencies:
- six.
- numpy.
- pandas.
- planarity.
- networkx.
- bokeh.
- seaborn.
- vpython (not yet, but really soon)



# Main features


The documentation is located in the [examples](https://github.com/HCsoft-RD/shaolin/tree/master/examples) folder.

### ipywidgets based and pydata compatible

This framework is build on top of standard pydata libraries like pandas and numpy and uses only the ipywidgets package for the interface management, although
shaolin provides a simplified interface that extends the ipywidgets capabilities.

### Own syntax for quickly defining new Dashboards 

Shaolin has a simplified syntax that allows to program dashboards consisting on multiple widgets more quickly.

- [Syntax for defining widgets](https://github.com/HCsoft-RD/shaolin/blob/master/examples/Shaolin%20syntax.ipynb)
- [Dashboard introduction](https://github.com/HCsoft-RD/shaolin/blob/master/examples/Dashboards.ipynb)

### Link different Dashboard to create complex applications

It is possible to combine multiple dashboards into a new one in order to perform complex tasks like data analysis or plotting.

- [Dashboard programming tutorial](https://github.com/HCsoft-RD/shaolin/blob/master/examples/Creating%20complex%20Dashboards.ipynb)

### Save and share your dashboards easily

You can load and save the state of a dashboard easily with no additional effort.

### No more writing widgets css

Modify any visual property of a dashboard interactively using widgets.


*********************
# Sample Dashboards

Shaolin comes batteries included with Dashboard created for performing various standard data analysis tasks that you can use as a base to build your own applications.

### Colormap creation
Use a colormap picker capable of creating any matplotlib and seaborn colormap or palette.

- [Colormap tutorial](https://github.com/HCsoft-RD/shaolin/blob/master/examples/Shaolin%20Colors.ipynb)

### Full customizable scatter plot

Plot an interactive bokeh scatter plot with tooltips from any pandas DataFrame, Panel or Panel4D. You will be able to modify any visual property of the plot with just a few clicks. I bet you wont need to program another scatter plot after trying this ;)

- [Scatter plot introduction](https://github.com/HCsoft-RD/shaolin/blob/master/examples/Scatter%20Plot%20introduction.ipynb)

### Networkx compatibility
We have dashboards that map the networkx interface to calculate any graph metric, any graph layout and the capability of converting time series correlation matrices into graphs.
You will also be able to plot any graph using the networkx capabilities in a fully customizable bokeh plot.

- [Shaolin GraphCalculator tutorial] (https://github.com/HCsoft-RD/shaolin/blob/master/examples/GraphCalculator.ipynb)
- [Shaolin Bokeh GraphPlot tutorial] (https://github.com/HCsoft-RD/shaolin/blob/master/examples/GraphPlot.ipynb)

### Slicers
Widgets for slicing any pandas structure or numpy array.

###plot mappers
These Dashboards provide everything you need to create new interactive plots with almost no code.



# Upcoming features

I hope most of there are available in the beta release.

###Walkers

It will extend the capabilities of the GraphCalculator for making interactive animated graphs in real time. This is really usefull for visualizing correlation matrix time series. 


### VPython support

It will be possible to replicate the capabilities of any plot using VPython as a plotting engine. This will make very easy visualizing interactive 3D scatter plotsand graphs in the notebook. 

### Seaborn plots

Compatibility for displaying seaborn plots will be added shortly. 

### MplD3

Compatibility for mapping data to interactive matplotlib plots using MplD3.

