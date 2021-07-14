# Twitter Data Analysis for Illinois Hospitals

This project performs a state wide analysis to determine the COVID-19 precautions taken by hospitals in Illinois via twitter data. A total of 46 Illinois hospitals both rural and urban were taken into consideration. The total tweet dataset was about 11,000 dated from January 2020 to September 2020. The tools and techniques used were Twint for twitter data scraping, CorEx for topic modelling to find coherent meaningful topics measured across a corpus of text and finally an in depth exploratory analysis was performed to find the significant correlation between topics. A tweeting pattern that has made a considerable impact in generating awareness during COVID-19 by the hospitals is analysed.  
  
You can access the Jupyter Notebooks online by clicking on the corresponding hyperlinks for <a href ="https://dataplatform.cloud.ibm.com/analytics/notebooks/v2/2e633e89-9514-4225-932c-69ef6f5c388c/view?access_token=7efc7906e84821212a1d79e4f93f2771b851042fa876a5249d8638f446b87446">Twint</a> and <a href ="https://dataplatform.cloud.ibm.com/analytics/notebooks/v2/aa648df5-eff8-4c37-b989-9e74e3505572/view?access_token=871f2fc862360fb0764873011f7b0fe358bac78660d6d046bd39706b4f9a793d">CorEx</a> respectively.  
  
Please find the description of the files in the repository as below:  
<ol>
<li><b>Twint.ipynb</b> - Jupyter Notebook with the code for twint package using which tweets were scraped  
<li><b>Corex.ipynb</b> - Jupyter Notebook with the code for CorEx package for topic modelling, univariate analysis and Linear regression to predict Likes & Retweets  
<li><b>Tweets Data.xlsx</b> - Excel workbook with tweets of Illinois hospitals from January 2020 to September 2020 (Output of Twint.ipynb)  
<li><b>Illinois Hospital Tweets.xlsx</b> - Data concatenated from <b>Tweets Data</b> excel file used for analysis in <b>Corex</b> jupyter notebook  
<li><b>Final Project Presentation.pptx</b> - Presentation on the findings of the project  
<li><b>Final Project Report.pdf</b> - A detailed report of the entire project  
</ol>
