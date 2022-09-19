# Belly Button Biodiversity

This project creates a dashboard including various types of charts to visualize different parameters in the dataset. 

It has a drop-down menu to choose the ID of a data point. According to that ID value, it creates a bar chart, bubble chart and a gauge plot. 

The **bar plot** represents the top 10 bacteria cultures found on the data ID point. 

The **bubble plot** shows the details about all the bacteria cultures found in that sample.

The **gauge plot** shows the washing frequency.


## For the purpose of Deliverable 4 the following Customisations were offered:

1. Background image added to the jumbotron

2. Added background color to rgb(207, 240, 199) vs. default white 

3. Used custom font; Verdana, Geneva, Tahoma, sans-serif

4. The webpage is mobile-responsive


When the dashboard is first opened in a browser, ID 940’s data is displayed in the dashboard as seen below:

![image](https://user-images.githubusercontent.com/102870991/190952819-15f86b1e-87a0-450a-9867-0ce8ddbefff6.png)



Besides the Web page is interactive and displays the data in the panel and all three charts according to their requirements. The output changes with the cange in filtered value. For instance for fitered ID 962, below is the result:

![image](https://user-images.githubusercontent.com/102870991/190952865-f1261160-0d6c-45a5-9072-c0717cecaf3e.png)



## How to run the program at local host

To run the program, first we need to navigate to the main project directory, where the **data** folder, **js** folder and the **index.html** file present. Then need run the following command on command prompt terminal.

python -m http.server

Then copy following command and paste it on the browser as an url.

localhost:8000


