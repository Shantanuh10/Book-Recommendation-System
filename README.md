<h1 align="center"> Book Recommendation System </h1>

<p align="center">
  <img src="Book Recommender System Files/BookRecommendationsPlease_MEME1.jpg" width="300px" height="250px">
</p>

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<h2>:scroll: Objective </h2>

The main objective is to create a book recommendation system for users. Recommender systems are really critical in some industries as they can generate a huge
amount of income when they are efficient or also be a way to stand out significantly from competitors. 


### Methods Used
* Descriptive Statistics
* Data Visualization
* Machine Learning

<h2> :floppy_disk: Data </h2>

The Book-Crossing dataset comprises 3 files (Click [here](https://drive.google.com/drive/folders/184irGJPi73xYu_eMgI3JBCc-okIOTUIF?usp=sharing) to access the Data)

* Users : 
Contains the users. Note that user IDs (User-ID) have been anonymized and map to
integers. Demographic data is provided (Location, Age) if available. Otherwise, these
fields contain NULL values.

* Books : 
Books are identified by their respective ISBN. Invalid ISBNs have already been removed
from the dataset. Moreover, some content-based information is given (Book-Title,
Book-Author, Year-Of-Publication, Publisher), obtained from Amazon Web
Services. Note that in the case of several authors, only the first is provided. URLs linking
to cover images are also given, appearing in three different flavors (Image-URL-S,
Image-URL-M, Image-URL-L), i.e., small, medium, large. These URLs point to the
Amazon website.

* Ratings :
Contains the book rating information. Ratings (Book-Rating) are either explicit,
expressed on a scale from 1-10 (higher values denoting higher appreciation), or implicit,
expressed by 0.

<h2> :clipboard: Project Description </h2>

* EDA - Performed exploratory data analysis on numerical and categorical data.
* Data Cleaning - Missing value imputation,Outlier Treatment
* Feature Selection - Used User-ID,ISBN and Books-Rating for model development.
* Model development - Tried Popularity based model and Collaborative filtering.

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<h2> :book: Popularity Based Recommender </h2>

It is a type of recommendation system which works on the principle of popularity and or anything
which is in trend. These systems check about the books which are in trend or are most popular
among the users and directly recommend them.

<h2> :book: Collaborative-based Filtering </h2>

Collaborative based filtering recommender systems are based on past interactions of users and
target items. In simple words here, we try to search for the look-alike customers and offer products
based on what his or her lookalike has chosen. Let us understand with an example. X and Y are
two similar users and X user has watched A, B, and C movie. And Y user has watched B, C, and D
movie then we will recommend A movie to Y user and D movie to X user.

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<h2>✉ Contact me for Data Science Project Collaborations </h2>


[![LinkedIn Badge](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/shantanuh10/)
[![GitHub Badge](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Shantanuh10)
[![Resume Badge](https://img.shields.io/badge/resume-0077B5?style=for-the-badge&logo=resume&logoColor=white)](https://drive.google.com/file/d/1py39Zv76lRab9dZAdkSjeYB8A3EkejSW/view?usp=sharing)


<h2> :books: References</h2>
<ul>
  <li><p>Shivam Baldha, 'Introduction to Collaborative Filtering'. [Online].</p>
      <p>Available: https://www.analyticsvidhya.com/blog/2022/02/introduction-to-collaborative-filtering/</p>
  </li>
  <li><p>Alexandre Wrg, 'An overview of several recommendation systems'. [Online].</p>
      <p>Available: https://towardsdatascience.com/an-overview-of-several-recommendation-systems-f9f8afbf00ea/</p>
  </li>
    <li><p>Youtube.com, 'Book Recommender System'. [Online].</p>
      <p>Available: https://www.youtube.com/watch?v=1YoD0fg3_EM&t=1s/</p>
  </li>
</ul>

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

Deployed Project to this Webpage: https://book-recommendersystem.herokuapp.com/ 
