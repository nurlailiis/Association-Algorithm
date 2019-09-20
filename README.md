# Market Basket Analysis and Recommendation System
## 1. Market Basket Analysis
[**Market Basket Analysis**](https://towardsdatascience.com/a-gentle-introduction-on-market-basket-analysis-association-rules-fa4b986a40ce#targetText=Market%20Basket%20Analysis%20is%20one,the%20items%20that%20people%20buy) is techniques used by large retailers to uncover associations between items. It works by looking for combinations of items that occur together frequently in transactions. To put it another way, it allows retailers to identify relationships between the items that people buy.
![Market Basket Analysis](https://miro.medium.com/max/1067/1*--iUPe_DtzKdongjqZ2lOg.png)
Kind of market basket analysis is [Apriori algorithm](https://en.wikipedia.org/wiki/Apriori_algorithm#targetText=Apriori%20is%20an%20algorithm%20for,sufficiently%20often%20in%20the%20database.) is an algorithm for frequent item set mining and association rule learning over transactional databases. It proceeds by identifying the frequent individual items in the database and extending them to larger and larger item sets as long as those item sets appear sufficiently often in the database.
## 2. Recommendation System
A recommender system is a simple algorithm whose aim is to provide the most relevant information to a user by discovering patterns in a dataset. The algorithm rates the items and shows the user the items that they would rate highly. An example of recommendation in action is when you visit Amazon and you notice that some items are being recommended to you or when Netflix recommends certain movies to you. They are also used by Music streaming applications such as Spotify and Deezer to recommend music that you might like.<br>
Below is a very simple illustration of how recommender systems work in the context of an e-commerce site.
![Recommendation System](https://miro.medium.com/max/1200/1*yYFoZKYpp7MT_iAqoE1lRw.png)
### Different Types of recommendation engines
In this kernel will give some techniques to recommendation engines in some study case. There are three main categories of recommendation system which is practice in this kernel:
#### 2.1 Content Based Algorithm
[**Content-based filtering**](http://recommender-systems.org/content-based-filtering/#targetText=The%20user%20profile%20is%20represented,be%20assigned%20automatically%20or%20manually.), also referred to as cognitive filtering, recommends items based on a comparison between the content of the items and a user profile. The content of each item is represented as a set of descriptors or terms, typically the words that occur in a document. The user profile is represented with the same terms and built up by analyzing the content of items which have been seen by the user.
#### 2.2 Collaborative Filtering Algorithm
[**Collaborative Filtering**](https://www.techopedia.com/definition/1439/collaborative-filtering-cf#targetText=Collaborative%20filtering%20(CF)%20is%20a,%2C%20LastFM%2C%20Delicious%20and%20StumbleUpon.) is the process of information filtering by collecting human judgments (ratings) “word of mouth”. Collaborative filtering (CF) is a technique commonly used to build personalized recommendations on the Web.
#### 2.3 Hybrid Filtering Algorithm
Hybrid Filtering Algorithm is a combination between content based filtering and collaborative filtering.

---
# Get Started
Technologies Used
- Libraries: numpy, pandas, matplotlib, math, statsModels, scipy, nltk, ast, sklearn, surprise, pyodbc
- Web scraping: bs4, requests
- Notepad, OpenOffice 
- Jupyter Notebook
---
# Algorithms and Dataset
The table below lists the recommender algorithms currently available in the repository. 

Type                  | Algorithm                         | Dataset             
----------------------|-----------------------------------|---------------------
Market Basket Analysis| Apriori                           | GroceryStoreDataSet 
Content Based         | Cosine Similarity                 | Web Scraping        
Collaborative         | Singular Value Decomposition (SVD)| rating_small.csv    
Hybrid                |           0                       |                     
A/B testing           | Z-test                            | ab-test kaggle      

--
## Story Data
Story data in this kernel is describe in each practice case to make a recommendation engine for every recommender algorithm.
