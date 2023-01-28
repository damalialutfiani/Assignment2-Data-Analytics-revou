# Data-Cleaning-NYC-AirBnB-2019-Project

How to do Data Cleaning on NYC-AirBnB dataset step by step using python
-----------------------------------------------------------------------------------
AirBnB is a place to rent homes or vacation spots in New York City.

> Context

Since 2008, guests and hosts have used Airbnb to expand on traveling possibilities and present more unique, personalized way of experiencing the world. This dataset describes the listing activity and metrics in NYC, NY for 2019.

> Content

This data file includes all needed information to find out more about hosts, geographical availability, necessary metrics to make predictions and draw conclusions.

Taken from [kaggle.com by DGOMONOV](https://id.traasgpu.com/cara-menggunakan-bay-area-bike-share/)
-----------------------------------------------------------------------------------

In the work on the AirBnB NYC 2019 Project, the focus is on how the **Data exploration** steps are carried out, starting from **Previewing Data**, doing **Data Cleaning**, until the data is **ready to be used for visualization**.

The following is a description of the file used :
1. Cleaning data using python as in the **studycase_minicourse.py** file.
2. Same as using python regarding the data exploration steps, only the file extension is different, where the file **Studycase_minicourse.ipynb** can be used for Jupyter Notebook.
3. The file with the Power Point extension (**ASSIGNMENT2.pptx**) contains the steps and the results of the work that has been done.
4. The file with the Portable Document Format (PDF) extension (**ASSIGNMENT2.pdf**) contains the steps and the results of the work same as the PPT file, that has been done.

The steps for Data Cleaning are as follows :
1. Change data type : *last_review* column become datetime, *latitude and longitude* colume become objects
2. Remove duplicated data
3. Remove empty data : Delete null data so the number of data becomes 48858
4. Remove outliers : Delete data that has a value that exceeds the upper and lower limits (*data outliers*) in the 'price' column, so that the total data becomes 45882
5. Remove unnecessary data

-- In this project, we use Jupyter Notebook with python for Data Exploration --

-- THANK YOU [@damalialutfiani](https://www.linkedin.com/in/damalialutfiani/) --
