# Web Visualization using KNIME Javascript nodes

JavaScript is a programming language that is one of the core technologies of the internet, along with HTML and CSS.  Using Javascript and the [D3.js](https://d3js.org) library it is possible to create very powerful interactive web visualizations.   

One of the nice features of KNIME is that it allows one to create Javascript visualizations, that can be easilly published to the Web, using a small number of nodes.  A number of nice examples can be found on the [KNIME web site](https://www.knime.com/nodeguide/visualization/javascript)

In this class we will dive deeply into programming with JavaScript.  Of course if you are interested in programming with Javascript it is acceptable to learn a bit about it on your own and do [assignment 4](https://bnorthan.github.io/inf-428-data-analytics-online/Module4/Assignment) with pure Javascript.  

## KNIME Class examples

As mentioned above there are some very good examples [here](https://www.knime.com/nodeguide/visualization/javascript)

There is also an example on the class KNIME Server called VisualizeBasketballJavaScript.  


### Choose the Javascript Barchart
In the node repository search for 'bar chart' then choose the Javascript bar chart (not the JFreeChart bar chart)

<img src="ChooseBarChart_.jpg" width="300"> 

### Configure
Read a file using the File Reader and connect it to the bar chart.  In this case we read a file containing basketball stats.  Then right click on the bar chart node and choose configure.  

1.  Check generate image  
2.  Choose category collumn.  In this case we choose 'Pos' so we can chart different basketball stats per position.  
3.  Then choose which stats to plot.  In this case we choose 'TRB', 'AST', and 'PTS'.  
<img src="BarChartConfigure.jpg" width="300"> 

### Interactive View  

Right click on the bar chart node and choose 'Interactive View Grouped Bar Chart'  

The interactive view will display 'pop ups' when you hover over a bar, so you can inspect the exact values.  When you click on the 'menu' control (the upper rightmost control) you get a popup that controls more aspects of the chart.  

<img src="InteractiveViewBarChart.jpg" width="300">   

### Export to HTML 

To export as an HTML file

1.  Open the 'Interactive View Grouped Bar Chart' 
2.  A menu should appear. 
3.  Choose 'save as' from the menu  
4.  You now have an HTML file which can be viewed in a web browser and or uploaded to a web server.  

<img src="InteractiveViewSave.jpg" width="300">   