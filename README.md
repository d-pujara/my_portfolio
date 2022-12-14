# Portfolio 

This repository contains a coollection of a few machine learning and deep learning projects I have developed. Projects have all been developed using Python, Node.js and the deployed projects were developed using Flask and Heroku. Tech kits used -- tensorFlow, sci-kit, pytorch, opencv. 

Feel free to contact me at [dishantpujara@gmail.com](dishantpujara@gmail.com). 

[Resume](https://drive.google.com/file/d/1JlLLRwF8fccoq8aaO-Qy4vQ834qKv6WM/view?usp=share_link)

__________________________________________
 ### [Tweets Climate Change Sentiment Analysis](https://github.com/d-pujara/my_portfolio/tree/main/twitter_sentiment_analysis)
 
With climate change being a widespread global challenge, it has become increasingly important to filter information that is deseminated to the wider public for accuracy to avoid any disinformation. For many, Twitter has become a priamry outlet for news and tweets with misinformation on climate change not being a man-made phenomenon can quickly spread however fragmented and inconsitent it may be. 

This sentiment analysis model breaks down the individual words that lie within a tweet using tokenization, stemming, and vectorizatioon methoods. The developed model than assimilates words into vectoried quantities that give weights in phrases that lead to a specific sentiment. 

- -1 : Climate change is not a man-made phenomenon and is a hoax. 
- 0 : Neutral opinion 
- 1: Climate change is a man-made phenomenon and is very real.
- 2: Factual news story

Model has been pre-trained using Logistic Regression, Decision Tree and K-Means with Logistic Regression prooviding the highest accuracy at 74%.

[Link to Kaggle Dataset](https://www.kaggle.com/datasets/edqian/twitter-climate-change-sentiment-dataset)

__________________________________________

### [Face Mask Detection using 50-Layer MobileNet CNN](https://github.com/d-pujara/my_portfolio/tree/main/face_mask_realtime_detector) 

COVID-19 exposed the effectiveness of mask-wearing as a tool to curb the spread of viral infections. Unfortunately, like many other issues, mask wearing quickly became a political statement and people grew weary of it's true efficacy and deliberately stopped wearing them. Businesses like hospitals and convenience stores among other locations of frequent group gatherings have the diffuclt task of monitoring indivduals with face masks on. 

With the advance of ComputerVision technology, we can pair any camera with openCV and a image rendering CNN to depict in real time individuals with and without masks. To run the model, run the .ipynb file on any code platform and allow access to your devices camera. 

__________________________________________

### [Liver Cirrhosis Predictive Tool](https://github.com/d-pujara/my_portfolio/tree/main/liver_cirrhosis_prediction)

Liver Cirrhosis . An adverse impact of excessive alcohol consumption can be the development of Liver Cirrhosis. Having had family members who have been diagnosed with liver cirrhosis following decades of unhealthy levels of alcohol consumptioon, I believe that liver cirrhosis needs to be diagnosed as early as possible. 

This predictive model uses a random forest algorithm and takes the feature variables listed below and outputs a prediction for the patient's current stage of liver disease development.

| Featured Variables| Description of Correlation to LC |
| --- | --- | 
| `N-Days` | Number of Days between Regestration and Analysis |
| `Status` | Status of Patient (Death (D), Censored (C,CL)) | 
| `Drug` | D-penicillamine (D.p) or Placebo (P) |
| `Sex` | Male or Female | 
| `Ascites` | Presence of Fluid Buildup in Abdomen (Y/N) | 
| `Hepatomegaly` | Liver Enlarged (Y/N) |  
| `Spiders` | Prescense of Visual Spidering on Liver Tissue (Y/N) | 
| `Edema` | Presence of Fluid Buildup in Legs (Y/N)|  
| `Blirubin` | Increased Levels in Blood (mg/dl) |  
| `Cholestrol` | Decreased Levels in blood (mg/dl) |  
| `Albumin` | Decreased Levels in Blood (g/dl) |  
| `Copper` | Increased Levels in Urine (ug/day) |  
| `Alk_Phos` | Increased Levels of Alklaline Phosphotase in Liver Tissue (U/L) |  
| `SGOT` | >2 High indication of LC Development (U/mL) |  
| `Tryglicerides` | Increased Levels of ALT/ATS (mg/dl) |  
| `Platelets` | Decreased Levels of Platelet Count (mL/1000) |  
| `Prothrombin` | Time of Prothrombin (s)  |  
| `Stage` | Stage of LD Development (1,2,3,4) // 4 being Cirrhosis |  

Access the tool using this [link]().

__________________________________________

### [Real Estate and Mortgage Expenses Analytics for Loan Demand Prediction ]()

Banking institutions requires actionable insights into mortgage-backed securities, geographic business investment, and real estate analysis to make predictions on the demand for region-based loans. This hypothetical mortgage bank would like to identify potential monthly mortgage expenses for each region based on monthly family income and rental of the real estate. 

The prediction model was trained using a multi-variate linear regression algorithm and can predict the potential demand in dollars amount of loan for each of the region in the USA. I have also created a dashboard to display the data using Tableau. 

[Dashboard](https://public.tableau.com/app/profile/dishant.pujara/viz/RealEstateProject-1_16687205203490/boxplot?publish=yes)





