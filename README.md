# Final_Project


## Natural Language Processing: Note-based Wine Recommender
In this project we aim to create a wine recommender that accepts notes or flavour wishes of the user and makes appropriate suggestions 


### Dataset 
- Link: https://www.kaggle.com/zynicide/wine-reviews
- Features: 14
- Records: 129971


Each record represents a different wine and each column contains different information on the wine. 
The features are; country, description, designation (place), points, price, province, region 1, region 2, taster name, taster twitter handel, titel, variety, winery.


Goal: Build a wine recommender using K-Means clustering and KNN modelling that recommends wines based on flavours and notes entered by user. 

Framework: Perform EDA on the types of wines and regions considered in our data set and then use natural language processing to extract the notes from the description column and generate flavour profiles and categories and associate them with clusters. 

## Timetable

### Week 1
- Tuesday: Choose data frame. Set up plan and github. Clean data. Make pitch. 
- Wednesday: Finish data cleaning. Begin EDA. Begin language processing using nltk. 
- Thursday: Finish EDA. Create columns with notes extracted from description column. CLustering.
- Friday: Build function that can recommend a wine based on the flavour / note. Modelling.


### Week 2
- Monday: Fine-tune recommender. Possible visualizations with tableau.
- Tuesday: Project progress check. If enough time work on front end design for recommender using stringlit.io / flak. 
- Wednesday: Begin presentation assembly. 
- Thursday: Practice.
- Friday: 

Side ideas: adding purchasing possibility of recommendation. recommender based on grape variety. recommendation based on wine type. 
