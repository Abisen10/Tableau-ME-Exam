# Tableau-ME-Exam

DATA SCIENCE 6TH MODULE END EXAM- TABLEAU 
QUESTION
1:-  Explain in detail the area graphs and line graphs in tableau and how to create them with examples. (With the help of an example create one in tableau?
ANSWER
Area Graphs :- Area graphs are a type of chart that illustrate how larger and smaller values compare to each other over a period of time, by displaying them as areas shaded on a graph. Area graphs are commonly used to show trends in a dataset over time. 
To create an area graph in Tableau, start by dragging a measure to the Columns shelf. Then drag a dimension to the Rows shelf. Next, select Show Me from the top right corner of the Tableau window and choose Area from the drop-down menu.  
Line Graphs :- Line graphs are a type of chart that display data as a series of points connected by straight lines. Line graphs are commonly used to show trends in a dataset over time.
To create a line graph in Tableau, start by dragging a measure to the Columns shelf. Then drag a dimension to the Rows shelf. Next, select Show Me from the top right corner of the Tableau window and choose Line from the drop-down menu. 

![ss](https://user-images.githubusercontent.com/87488680/227709355-3f757efa-d4b2-42f7-9b43-5b001b310bcc.png)

__________________________________________________________________________________________
QUESTION
2 :- What are the different steps in grouping fields and combining tables in tableau ? Explain with examples. (With the help of an example create one in tableau)?
ANSWER
1. Create a Primary Table: The first step in grouping fields and combining tables is to create a primary table. This table should contain all of the fields that you want to use in your analysis.
2. Group Fields: Once you have your primary table, you can group fields together. This is done by selecting the fields that you want to group and then right-clicking and selecting “Group” from the context menu. 
3. Combine Tables: Once you have grouped fields together, you can combine tables. This is done by selecting the tables you want to combine and then right-clicking and selecting “Join” from the context menu.
4. Create a Custom View: You can create a custom view in Tableau by dragging and dropping fields into the view. For example, you can create a custom view of the Sample Superstore to analyze the sales performance of each region.
Example:
Let's say we want to group the fields “Product Category”, “Sub-Category”, and “Product Name” together in order to analyze sales performance of each product. To do this, we first need to select the fields and drag them into the same group. We can do this by selecting the fields in the data pane and dragging them into the same group in the view. Once the fields are grouped together, we can then analyze the sales performance of each product by using the “Sales” and “Profit”.
 



_________________________________________________________________________________________
QUESTION
3 :-  What is the use of color and size options in the marks cart of tableau ? (With the help of an example create one in tableau) ?
ANSWER
The Color and Size options in the Marks Card of Tableau are used to differentiate between different data points in a graph


 










__________________________________________________________________________________________
QUESTION
4 :- What are the different joins supported by tableau? (With the help of an example create one in tableau)?
ANSWER
Tableau supports the following types of joins:
1. Inner Join: This join returns only the records that have matching values in both the tables
2. Left Join: This join returns all the records from the left table and only those records from the right table which have matching values in the common field. 
3. Right Join: This join returns all the records from the right table and only those records from the left table which have matching values in the common field. 
4. Full Join: This join returns all the records from both the tables, regardless of whether the other table has a matching record or not.
 

 









QUESTION
5:- Explain the steps to create dashboard in tableau with example (With the help of an example create one in tableau)?
ANSWER
Step 1: Launch Tableau Desktop 
To begin, launch Tableau Desktop. This will open the Tableau Interface.
Step 2: Connect to a Data Source 
Next, connect to the data source you would like to visualize. To do this, go to the “Connect” tab in the left-hand menu and select the type of data source you want to connect to.
Step 3: Prepare and Cleanse Data 
Once the data is connected, you can begin preparing your data. This may include making calculations, performing data cleansing, and organizing your data.
Step 4: Create Visualizations 
Now, you can create visualizations for your dashboard. To do this, select the visualization type you would like to use from the list of options. You can also customize your visualizations using the formatting options available.
Step 5: Assemble Your Dashboard 
Once you have created your visualizations, you can assemble them into a dashboard. To do this, drag each visualization onto the dashboard canvas. You can arrange the visualizations as desired, and add titles, legends, and other elements.
Step 6: Publish Your Dashboard 
When your dashboard is complete, you can publish
 


__________________________________________________________________________________________
QUESTION
6 :- Explain in detail the heat maps and scatter plot and how to create them with example (With the help of an example create one in tableau)?
ANSWER
Heat Maps:
A heat map is a graphical representation of data where the individual values contained in a matrix are represented as colors. This type of visualization is useful for understanding and comparing large amounts of data, as it allows the viewer to quickly spot patterns, trends, and outliers. Heat maps can be used to compare and contrast different data sets, identify correlations, and highlight areas of interest.
Scatter Plots:
A scatter plot is a type of graph used to show the relationship between two variables. It is a two-dimensional chart that plots each data point as a point along the two axes. The points are then connected with a line or a curve to show the relationship between the two variables. Scatter plots can be used to compare and contrast different data sets, identify correlations, and highlight areas of interest.
Example in Tableau:
In this example, we will create a heat map and a scatter plot in Tableau.
Heat Map:
1. In Tableau, select the "Sheet" tab and select the "Add" button.
2. From the drop-down menu, select "Heat Map".
3. Select the data set you'd like to use for the heat map.
4. Select the columns you wish to use for the x-axis and y-axis of the heat map.
5. Select the column you'd like to use for the color of the heat map.
6. Click "Apply" to create the heat map. 


Scatter Plot:
1. In Tableau, select the "Sheet" tab and select the "Add" button.
2. From the drop-down menu, select "Scatter Plot".
3. Select the data set you'd like to use for the scatter plot.
4. Select the columns you wish to use for the x-axis and y-axis of the scatter plot.
5. Select the column you'd like to use for the color of the scatter plot.
6. Click "Apply" to create the scatter plot.
 














__________________________________________________________________________________________
QUESTION
7 :- How to create table calculations in tableau with examples . (With the help of an example create one in tableau)
ANSWER
Table calculations are calculations that are applied to the values in the view, after the data has been aggregated. Table calculations are calculated across the entire table, not just within a partition. 
To create a table calculation, you first need to add the relevant measure to the view. To create a table calculation in Tableau, follow the steps below. 
1) Create a view with the measure and dimensions you want to analyze. 
2) Right click on the measure field and select “Quick Table Calculation” from the menu.
3) Select the type of calculation you would like to perform from the list of available table calculations.
For example, to calculate the running total of a measure, select “Running Total” from the list.
4) Select the field you would like to calculate the table calculation on.
5) Select the “Compute Using” field and select either “Table (across)” or “Table (down)” depending on the direction you want the calculation to go.
6) Click “OK” and the table calculation will be applied to the view.


 


_________________________________________________________________________________________
QUESTION
8 :- Explain in detail the distribution bands in tableau and how to create them with example (With the help of an example create one in tableau)
ANSWER
Distribution bands in Tableau are used to identify abnormal data points in a visualization. They are created by plotting a standard deviation or percentile line on a chart. This line will show where data points are located above or below the average.


 












__________________________________________________________________________________________
QUESTION
9:- Explain the steps to create bar chart and pie diagram in tableau with example (With the help of an example create one in tableau)
ANSWER
Creating a Bar Chart in Tableau
1. Launch Tableau and connect to a data source.
2. Drag a dimension to the Columns shelf and a measure to the Rows shelf.
3. Select the Show Me tab at the top of the screen.
4. Select the Bar chart icon from the Show Me tab.
5. Your bar chart will appear.
6. To format your chart, select the Marks card and choose the type of mark you would like to use
7. To adjust the chart’s title, select the Title card and type the title you would like to use.
8. To edit the axes, select the Axes card and adjust the scale and label settings.
9. To adjust the colors of the bars, select the Color card and choose the color palette you would like to use.
Creating a Pie Chart in Tableau
1. Launch Tableau and connect to a data source.
2. Drag a dimension to the Columns shelf and a measure to the Rows shelf.
3. Select the Show Me tab at the top of the screen.
4. Select the Pie chart icon from the Show Me tab.
5. Your pie chart will appear.
6. To format your chart, select the Marks card and choose the type of mark you would like to use.
7. To adjust the chart’s title, select the Title card and type the title you would like to use.
8. To adjust the colors of the sections, select the Color card and choose the color palette you would like to use.
9. To adjust the angle of the sections, select the Angle card and select the angle you would like to use.
 
__________________________________________________________________________________________
QUESTION
10 :- How to add story points on the dashboard (With the help of an example create one in tableau)
ANSWER
Step 1: Open Tableau software and connect to a data source.
Step 2: Drag and drop the Story Points field from the data source to the Rows shelf.
Step 3: Drag and drop the Task Name field from the data source to the Columns shelf.
Step 4: Right click on the Story Points field in the Rows shelf and select Measure > Count.
Step 5: Right click on the Task Name field in the Columns shelf and select Measure > Average.
Step 6: To add a chart to the dashboard, select a chart type from the Show Me drop-down list.
Step 7: To create a customized chart, select the chart type from the drop-down list, then customize the chart by selecting the chart type, number of series, and labels.
Step 8: Drag and drop the chart to the dashboard canvas.
Step 9: To add additional charts and/or dashboard elements, repeat steps 2-7.
Step 10: To save the dashboard, click File > Save As. 


 
