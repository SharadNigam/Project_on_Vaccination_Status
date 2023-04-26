<h1>Project on Vaccination Status</h1>


<h3>BACKGROUND</h3> 

This project shows the current (as of 26.04.2023) vaccination status of Indian populace.
The folder contains the following files:
* Cleaned Dataset (_this is the data i cleaned and formed from the main dataset file_)
* Dataset (_this is the dataset directly pulled from open sharing indian government website, here is the link for the site: https://www.mohfw.gov.in/  [P.S a special thanks to them! for hosting this updated data]_)

<h3>METHODOLGOY/WORKFLOW</h3>


1.Started by downloading the dataset from the government site : https://www.mohfw.gov.in/


2.Since this dataset was in PDF format, imported it into excel.


3.Cleaned the dataset and formed a new sheet with data i required to run my analysis, this lead to me making my Cleaned Dataset.csv file.


4.Proceeded to gain insights by creating visualizations in Tableau Public, here is the link to check it out:
https://public.tableau.com/views/IndiaVaccinationStatusDataanalysis_16825064846730/SummaryDashboard?:language=en-US&:display_count=n&:origin=viz_share_link

<h3>CHALLENGES FACED</h3>


There was a major issue which i faced here which was that eventhough everything was proper for some reason tableau was not plotting the values on the map of India. 
This became frustrating very quickly as even after spending 4-5hrs finding why this was happening online and using all the suggestions and methods, none of them worked for me.
But after doing lots of trials and errors (and i mean A LOT) i finally figured out the issue,


**ISSUE :** Tableau does not understand your states data if it's not belonging to USA.


**SOLUTION :** You first need to create an additional column in your excel with Country as well as State ( as i have done in my cleaned Dataset) and then upload it to tableau,
once uploaded and you switch to your sheet there, you need to create a hierarchy with your Country and State in it so as for it to finally work and show you the values you are after.This resolved the issue i was having.


<h3>RESULTS and ANALYSIS</h3>


Best viewed on tableau here: https://public.tableau.com/views/IndiaVaccinationStatusDataanalysis_16825064846730/SummaryDashboard?:language=en-US&:display_count=n&:origin=viz_share_link

But here are the images:


![GRAPH(18+)](https://user-images.githubusercontent.com/131772248/234581520-49958c19-fe1d-4727-bc6b-18299818c5e2.png)


This bar chart represents that the Most vaccinated state in India is Uttar Pradesh and the least is Sikkim for the Age Group above 18 years of age.


![GRAPH(12-18)](https://user-images.githubusercontent.com/131772248/234581544-33a3cb90-b7ef-4a7e-bdf0-70fc71f1bbe0.png)


This bar chart represents that the Most vaccinated state in India is Uttar Pradesh and the least is Sikkim for the Age Group 18 and below years of age.


![MAP](https://user-images.githubusercontent.com/131772248/234581556-edf58bec-cebf-4534-8e29-8da97dda5ce6.png)


The map here is indicating which state has the highest fully vaccinated people ( which have taken both 1st and 2nd dose and are from age 12 to 60 plus)
As we can see, its Uttar Pradesh (its color coded to Green Color)


![Summary Dashboard](https://user-images.githubusercontent.com/131772248/234581572-bab7972c-d7d4-483a-8d84-2fd4092d97d9.png)


All in all it was quite educational and fun!
