# Final_Project IronHack DA


## Natural Language Processing: Note-based Wine Recommender
In this project we aim to create a wine recommender that accepts notes or flavour wishes of the user and makes appropriate suggestions 


### Dataset 
- Link: https://www.kaggle.com/zynicide/wine-reviews
- Features: 14
- Records: 129971


Each record represents a different wine and each column contains different information on the wine. 
The features are; country, description, designation (place), points, price, province, region 1, region 2, taster name, taster twitter handel, titel, variety, winery.


Goal: Build a wine recommender using K-Modes clustering that recommends wines based on flavours and notes entered by user. 

Framework: Perform EDA on the types of wines and regions considered in our data set and then use natural language processing library NLTK to extract the notes from the description column and generate flavour profiles and categories and associate them with clusters. 
