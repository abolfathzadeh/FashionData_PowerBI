# FashionData_PowerBI
A PowerBI dashboard to show the Fashion Data

Visualization
Data virtualization is a technique for data management that allows applications to represent and depict data without forcing the technical details about the data. There are various data visualization tools as software for visualizing data. Each tool has a different function, but basically it allows data scientists to input a dataset and depict it visually. kind of these tools are:
-	Google Charts
-	Tableau
-	Zoho Analytics
-	Datawrapper
-	Infogram
-	Power BI
1. Preparing the data
In this report, to visualize the fashion dataset, PowerBI was used. in this regard, in the PowerBI desktop, after creating new project by clicking on ‘Get Data’ on welcome window or home tab, the structure of dataset (CSV) was selected and then it was opened to show the template and data .
  ![image](https://user-images.githubusercontent.com/9671082/213888889-d530f6aa-860c-4f29-b8a4-0f1d125d1ce4.png)
Figure- import data into PowerBI
2. Visualizing the data
After selecting dataset to be loaded, one new column, called ‘rate’ was generated. In this column the integer value of rate was kept .

![image](https://user-images.githubusercontent.com/9671082/213888903-3cebae60-de1f-4bf6-88e0-0b04406b32fd.png)
Figure- create rate column

After loading dataset into the PowerBI, in each sheet, one or more diagram was drawn as they are listed below:
1-	A scatter chart, to show the relationship between average of rate and maximum price
2-	A bar chart to depict the count of Occasions
3-	A bar chart to show the count of sustainable types
4-	A pie chart to show the count od closures
5-	A funnel diagram to show the count of Body or Garment Size 
6-	A donate chart to illustrate the count of wash care types
 
 ![image](https://user-images.githubusercontent.com/9671082/213888914-808c88cf-5e8a-4edc-aa6f-9ad17fe206b5.png)

Figure - PowerBI diagrams

7-	A 100% stacked bar chart to show the count of product by Wash Care types and Occasion
8-	A clustered column chart to illustrate the count of product per rates (1 to 5)
9-	A treemap, to depict the diversity of using colours
 ![image](https://user-images.githubusercontent.com/9671082/213888925-9ec371c9-6d28-4eca-9263-6bbf7a2cc6ed.png)

Figure - PowerBI diagrams- series2
10-	An area chart to show the comparison of maximum, average and minimum of price by brands
 ![image](https://user-images.githubusercontent.com/9671082/213888940-87d89ce0-2f30-434f-8547-42daf6ffc2c4.png)

Figure - PowerBI diagrams- series3- Area Chart

11-	A stacked column chart to show the counts of products per brand by their share of rates
 ![image](https://user-images.githubusercontent.com/9671082/213888946-547ec6a7-3b54-4af7-9aa2-371073158515.png)

Figure - PowerBI diagrams-series4 - Stacked column

12-	A pie chart to depict the body or Garment size of all products
13-	A Question & Answer box to prepare the facility for runtime queries
14-	A word cloud map to show the popularity of brands

 ![image](https://user-images.githubusercontent.com/9671082/213888963-e0619be6-d1cb-4293-bfe4-2e5c22e08167.png)

Figure 3- PowerBI diagrams- series5

Additionally, to have an advance depict, the tooltip was changed, to be shown when a brand could be passed as a parameter.in this tooltip, the brand title, count of products, distinct count of colour and average of rating were shown. Also, by a simple bar chart, maximum, average and minimum of the price of products for each brand were illustrated. However, a star card to show the rate of the brand was used.

 ![image](https://user-images.githubusercontent.com/9671082/213888977-15837e73-53b6-4c84-926f-59a012c28b35.png)

Figure - PowerBI customised tooltip

To support this star card, a new calculated column, called ‘avg_rating_star_rating’ was created.

 ![image](https://user-images.githubusercontent.com/9671082/213888982-44f6b20c-150c-452c-82d5-4538112e4f51.png)

Figure - code to support star card
3. Publish the result
Finally, the result was published in PowerBI web Version to have a better view of visualization:

 ![image](https://user-images.githubusercontent.com/9671082/213888988-1e6c4762-1ce1-45ff-88a4-927279432a02.png)
![image](https://user-images.githubusercontent.com/9671082/213888993-d3e9d9cd-c99b-41d7-a023-1882a86e5a3a.png)
![image](https://user-images.githubusercontent.com/9671082/213888999-efca9909-bf42-42b1-9908-2e7f3a3e27cf.png)

![image](https://user-images.githubusercontent.com/9671082/213889001-ea031d40-2885-47b2-8bb1-c7116d1d1bd2.png)
![image](https://user-images.githubusercontent.com/9671082/213889004-f23afc9c-6a1c-488d-a5ec-c5cd702fbaf1.png)



 
