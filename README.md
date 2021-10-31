# Movies-Recommendation-System-App
Building a Movie Recommendation System web application using Flask and Recommendation technique called Collaborative Filtering. Content Based Recommender System recommends movies similar to the movie user likes and analyses the sentiments on the reviews given by the user for that movie.


### Technologies Used
#### Web Technologies
- Python
- HTML 

#### Python Packages 
- Flask
- Numpy
- Pandas 
- Scipy

##### Requirements
```
python 3.6
pip3
```
### How to run the project?
Clone or download this repository to your local machine.
Install all the libraries mentioned in the requirements.txt file with the command pip install -r requirements.txt
Open your terminal/command prompt from your project directory and run the file movie.py by executing the command python movie.py.
Go to your browser and type http://127.0.0.1:5000/ in the address bar.
Hurray! That's it.

## What is similirity score
Sentiment similarity indicates the similarity between two words from their underlying sentiments. 
Our approach is built on a model which maps from senses of words to vectors of twelve basic emotions. 
The emotional vectors are used to measure the sentiment similarity of word pairs.

## How cosine similarity works
Cosine similarity is a metric used to measure how similar the documents are irrespective of their size. Mathematically, it measures the cosine of the angle between two vectors projected in a multi-dimensional space. The cosine similarity is advantageous because even if the two similar documents are far apart by the Euclidean distance (due to the size of the document), chances are they may still be oriented closer together. The smaller the angle, higher the cosine similarity.
