# Hackathon-16
Question:
Assume, you want to buy a DSLR camera but you are not sure which model to buy. You search the web for reviews on various models being sold by retailers. You come across this huge set of reviews by experts on various online review sites and those posted by consumers of the product on the sites of various online retailers. More often than not, going through all the reviews is exhausting and confusing, if not overwhelming. Won't it be useful if we had a tool or web-interface, which could do this for us and offer us an opinion on a given product. The tool or web-interface does not necessarily need to do real-time data collection and analysis. You can use the various dataset of product reviews available online, like the one here (http://jmcauley.ucsd.edu/data/amazon/). You can approach this problem as a design problem. Given the dataset of reviews, think what features would a make this tool useful to users, e.g, how would a user interact with this tool and the type of opinions that he would like to receive from the tool. If you can't access the data from the given link above. Either send request to Julian McAuley (julian.mcauley@gmail.com) or use the dataset from http://times.cs.uiuc.edu/~wang296/Data/  							

Solution steps:

In this project we had used data given by linkk(http://jmcauley.ucsd.edu/data/amazon/links.html).
Then we have downloaded two files meta_Electronics and reviews_Electronics. These files were in loose json type.
We have then converted them into strong json by using python code.
The resultant files were then taken and using IntelliJ IDEA 15 software to write Queries in Scala based on the availbe json data.
We then executed the queries and the output of the queries is stored in JSON file.
This JSON file input is then converted into csv files and this files are used for further steps.
For visualization we used d3.js, which is a html, css and svg code which give the graphical visualization in the form of various graphs and charts.
The csv generated eaarlier were used as input to the d3.js code for each visualization.

Youtube link:

https://youtu.be/EKcHBLNYm4c





