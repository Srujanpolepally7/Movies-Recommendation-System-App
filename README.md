# Movies-Recommendation-System-App
Building a Movie Recommendation System web application using Flask and Recommendation technique called Collaborative Filtering


### Technologies Used
#### Web Technologies
- Python
- HTML 
- CSS

#### Python Packages 
- Flask
- Numpy
- Pandas 
- Scipy

#### Database
SQLite

##### Requirements
```
python 3.6
pip3
virtualenv
```

##### Setup to run

- Download zip file to your local machine
- Extract the zip file
- Open terminal/cmd promt
- Goto that Path

Example

```
cd ~/Destop/Movie-Recommender-System-Web-Application-master
```

Create a new virtual environment in that directory
```
python3.6 -m pip install virtualenv
virtualenv venv -p python3.6
```

Activate virtual environment
```
source venv/bin/activate
```

Command line to install all dependencies
```
pip install -r requirements.txt
```

Then
```
cd ../Movie-Recommender-System/MovieRecommendationApp
```

Command line to run your program
```
python manage.py runserver
```

Now open your browser and go to this address
```
http://127.0.0.1:8000
```
