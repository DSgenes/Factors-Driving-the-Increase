# Factors-Driving-the-Increase

# Overview :

In this excercise you were asked to use the Analyze feature in Microsoft Power BI to explain unexpected increases in sales totals and provide insights on the reasons for these increases. 

More specifically, you were asked to:

   • Use clustering in a Scatter chart to add product clusters that would assist the Analyze feature.

   • Create a Line chart from the sales figures to identify the dates where a sales surge occurred, and then use the Analyze feature to detect the reason for these increases.

   • Add to the report all the relevant visualizations based on the insights generated by the Explain the increase tool in Power BI.

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

# "Analyzing the Growth"

# Step 1: Download the Data

  Download the Power BI report file Adventure Works Sales Report.pbix and open it in Power BI Desktop.

# Step 2: Identify Key Sales Spikes

  1. Navigate to the Data View in Power BI, select the Sales table, and familiarize yourself with the dataset.

  2. Find the Order Date column and the Order Total column in the Sales table. Additionally, identify an attribute column suitable for clustering. In this case, the Product Name column has high cardinality (a large number of distinct 

     values) and is a good candidate for clustering.

  3. Switch to the Report View in Power BI. Then, create a Line Chart visualization with Order Date on the X-axis and Order Total on the Y-axis.

  4. Using the Line Chart created in the previous step, identify the 3rd and 7th of March as the two distinct days when there was a noticeable spike in sales.

![image_alt](https://github.com/DSgenes/Factors-Driving-the-Increase/blob/f819fc43dc0ea7e7c7775ee12dd97142e32cf886/Screenshot%201.png)

# Step 3: Utilize Clustering to Enhance Analysis

  1. Add a Scatter Chart with Product Name in the Values field, Order Total on the X-axis, and Product Price on the Y-axis. Due to the presence of outliers in the dataset, applying a clustering technique will help refine your analysis.

  2. Click the ellipsis in the top-right corner of the chart and select Automatically find clusters to enable clustering.

![image_alt](https://github.com/DSgenes/Factors-Driving-the-Increase/blob/72690e6d79e87870932c7cbf35d0c06b858ec0d3/Screenshot%202.png)

  3. Assign names and descriptions to the clusters based on your analysis. Then, set the Number of Clusters to 3 to define the segmentation.

![image_alt](https://github.com/DSgenes/Factors-Driving-the-Increase/blob/84d74b50d6b9db00396ca2ee4a344920702cfd3a/Screenshot%203.png)

![image_alt](https://github.com/DSgenes/Factors-Driving-the-Increase/blob/26082ac8e095ef7c0e71ea37ec1926a3606dc7f8/Screenshot%204.png)

# Step 4: Use Analyze to Generate Visualizations

  1. On the Line Chart, identify and right-click on the 7th of March. From the context menu, select Analyze and then choose Explain the increase to automatically generate visualizations for that specific day.

![image_alt](https://github.com/DSgenes/Factors-Driving-the-Increase/blob/8d35fc7e1ab10c354d21c2ad74073bad17f2cd51/Screenshot%205.png)

  2. In the Explain the Increase pop-up window, identify the fields that had the most influence on the sales spike for the 7th of March. These fields include Product Size, Product Category, Product Cluster, Payment Method, and Location, 
 
     which all contributed to the highest sales spike for that day.

  3. Close the pop-up window, then right-click on the 3rd of March on the Line Chart. Use the Analyze feature again to open the Explain the Increase window for that specific day.

![image_alt](https://github.com/DSgenes/Factors-Driving-the-Increase/blob/b890f6897d08932f92dceecb293f21ed953113b7/Screenshot%207.png)

  4. Scroll through the visualizations in the Explain the Increase window to identify the positive factors contributing to the sales spike on the 3rd of March. The fields Product Size, 
 
     Product Category, and Product Cluster appear to have the most significant impact on the spike in sales for that day.


