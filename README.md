 # Travel Review Segmentation - Using Hierarchical Clustering Algorithm
  
  This project leverages the Hierarchical Clustering Algorithm to analyze and segment travel reviews. The primary objective is to group reviews based on their similarity, providing insights into customer sentiments, preferences, and behavior patterns.

#  Abstract: 
  Understanding the tastes of each user and the characteristics of each product is necessary to predict how a user will respond to a new product. This latent user and product dimensions can be discovered with the help of user feedback. A numeric rating and its accompanying text review is the most widely available form of user feedback. A measure which encapsulates the contents of such reviews is often necessary as they have been found to significantly influence the shopping behaviour of users. A fine-grained form of such measure that could act as perfect feedback about the product is a star rating. The review rating prediction tries to predict a rating corresponding to the given review. 

# Problem Statement: 
Given the google rating data, use a hierarchical clustering algorithm to cluster reviews. 

# Dataset Information: 
This data set is populated by capturing user ratings from Google reviews. 
1) **User** Unique user id 

2) **Attribute 1:** Average ratings on churches 

3) **Attribute 2:** Average ratings on resorts  

Reviews on attractions from 24 categories across Europe are considered. Google user rating ranges from 1 to 5 and the average user rating per category is calculated.  

### Variable Description: 

4) **Attribute 3:** Average ratings on beaches  

5) **Attribute 4:** Average ratings on parks  

6) **Attribute 5:** Average ratings on theatres  

7) **Attribute 6:** Average ratings on museums  

8) **Attribute 7:** Average ratings on malls  

9) **Attribute 8:** Average ratings on zoo  

10) **Attribute 9:** Average ratings on restaurants  

11) **Attribute 10:** Average ratings on pubs/bars  

12) **Attribute 11:** Average ratings on local services  

13) **Attribute 12:** Average ratings on burger/pizza shops  

14) **Attribute 13:** Average ratings on hotels/other lodgings  

15) **Attribute 14:** Average ratings on juice bars  

16) **Attribute 15:** Average ratings on art galleries 

17) **Attribute 16:** Average ratings on dance clubs  

18) **Attribute 17:** Average ratings on swimming pools  

19) **Attribute 18:** Average ratings on gyms  

20) **Attribute 19:** Average ratings on bakeries  

21) **Attribute 20:** Average ratings on beauty & spas  

22) **Attribute 21:** Average ratings on cafes  

23) **Attribute 22:** Average ratings on view points  

24) **Attribute 23:** Average ratings on monuments  

25) **Attribute 24:** Average ratings on gardens 


# Scope: 
  ●	Analysing the existing data and getting valuable insights about the review pattern 
  ●	Data pre-processing including missing value treatment 
  ●	Cluster the reviews based on the optimum number of clusters (‘k’) with the help of dendrogram  

## Table of Content
1. **[Import Packages](#import_packages)**
2. **[Read Data](#Read_Data)**
3. **[Data Types and Dimensions](#Data_Types)**
4. **[Data Manipulation](#Data_Manipulation)**
5. **[Statistical Summary](#Statistical_Summary)**    
6. **[Handling Missing Values](#Handling_Missing_Values)**    
7. **[Exploratory Data Analysis](#Exploratory_Data_Analysis)**   
8. **[Hierarchical Clustering](#Hierarchical_Clustering)**
9. **[Conclusion](#Conclusion)**  

# Key Features:
  •	Data Preprocessing: Cleaning and preparing raw travel review data for analysis.
  •	Text Analysis: Converting textual reviews into meaningful numerical representations using NLP techniques.
  •	Clustering: Applying Hierarchical Clustering to segment reviews into distinct groups.
  •	Visualization: Generating dendrograms and other plots to interpret clustering results effectively.
  •	Insights: Identifying key themes and patterns in customer feedback.

# Tools & Technologies:
  •	Python (NumPy, Pandas, Scikit-learn, Matplotlib, Seaborn)
  •	Natural Language Processing (NLP) for text analysis
  •	Hierarchical Clustering methods
# Use Case:
  This project can be applied in travel industries to enhance customer experience by tailoring services based on segmented review groups. It can also aid in identifying critical areas for service improvement.

# Conclusion:
  The Travel Review Segmentation project successfully demonstrates the application of the Hierarchical Clustering Algorithm in segmenting customer reviews from the travel industry. By grouping similar reviews, we were able to uncover patterns in customer sentiments and preferences, providing valuable insights for improving service quality and enhancing customer satisfaction.
  ### Key takeaways include:
  
  •	The effectiveness of text preprocessing and feature engineering in preparing unstructured data for clustering.
  
  •	The ability of hierarchical clustering to identify distinct segments and visualize relationships using dendrograms.
  
  •	The potential to use these segments for targeted marketing, personalized experiences, and feedback-driven improvements.
  
  This approach can be further extended by integrating more sophisticated NLP techniques or exploring hybrid clustering methods for more nuanced segmentation. Overall, this project highlights the importance of data-driven insights in improving customer experience in the travel industry.

 # Feedback and Suggestions:

I’d love to hear your thoughts, feedback, and suggestions! Feel free to connect with me:

 *LinkedIn*: [Shivanand Nashi](https://www.linkedin.com/in/shivanand-s-nashi-79579821a)
 
 *Email*: shivanandnashi97@gmail.com


Looking forward to connecting and exchanging ideas!
