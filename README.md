# WWT SLED West Intern Project 2019
## Two Concurrent Projects Include:
1) [Quote Reader](http://ec2-34-219-167-147.us-west-2.compute.amazonaws.com/WWTSLEDWestInternProject/QuoteReader/): An internal web app tool for WWT sales team that normalizes quote files from vendors into one csv file according to WWT ISR format standards. We used a front-end R ShinyApp to select files to convert, display, and download. The ShinyApp leverages our Python program on the back-end to re-format the data. 
![Quote_Reader_Home_Page](/QuoteReader/images/home.PNG)


2) Internal web app tool for Matthew Jenkins, SLED West Director, and his Account Managers. This app is an R ShinyApp that reads in data from a raw Backlog Order Summary csv file and creates an interactive pie chart that displays only the most important data in a simple design for quick information gathering. There are future possibilities for visualizing the data and performing analytics.

Both projects are deployed on AWS for cost-effectiveness and easy access.

_Note: The Quote Reader documentation can be found in_ [HowToUseCSVReader.md](https://github.com/jeremiahkramer/WWTSLEDWestInternProject/blob/master/QuoteReader/HowToUseCSVReader.md)
