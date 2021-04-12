# Assessment 1 - Stock trend graph for last 30 days 
# Assessment 2 - Upload any image on to your Web Application and interact with the image. Provide specific details at individual points.

****
# Assessment 1:
 *  This application provides last 30 days graph for a stock. eg: AAPL etc.,.
 *  This application provides Max, Min trading amount for the specific stock.
 *  Please find the output screenshot at Li_Assessment/Assessment_1/output/ 
 
 ****
# Assessment 2:
 *  While executing the code make sure you put the code in a webserver. As most of the major browsers block cross origin requests, using any web server for testing the code is         advised. We can try a work around by passing * into the header of CORS but I feel this is more appropriate way to do it.
 *  Easiest way to check is to download web server. Open the software, select the folder of the code and click on the link(http://127.0.0.1:8887) provided below the "select           folder" button. 
 *  I used data from the last 30 days and as the data is a daily data and not continuous, I placed dots for each day. On hover of the dot, you will be able to see the information      of that particular stock for the day.
 *  I used D3 V5 as I am more familiar with it.
