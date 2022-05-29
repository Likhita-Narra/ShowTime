# **SHOWTIME** - A movie recommendation system
**Description**: Showtime is a movie recommender website that can recommend similar movies based on the movie searched by the user or filters set by the user
**Website**: View the website [here](https://share.streamlit.io/likhita-narra/showtimeapp/main/ShowTime.py)

### **Setup**

#### Step 1: Fetching the source code:
Method 1: Download the zip file of the code and extract the files.

Method 2: Dowload git lfs from [here](https://git-lfs.github.com/) and enter the following commands in command prompt:
```
> git lfs install
> git lfs fetch
> git lfs pull
```

#### Step 2: Installing dependencies:
Run the following command to install all requiremnts
```
> pip install -r requirements.txt
```

#### Step 3: Running the application:
Navigate to the application directory and run the following command in the terminal:
```
> streamlit run ShowTime.py
```
The following message will be displayed on the terminal

![Screenshot](https://user-images.githubusercontent.com/76270840/170884797-34493067-1adf-4013-974a-22bbfd60a1bd.png)

and a webpage will be opened in your default browser.

### **Functionalities**
**Search for movies**: To look for movies in the database

![Screenshot (418)](https://user-images.githubusercontent.com/76270840/170885685-b54ec372-3d92-4250-a030-c1e65817b5c7.png)

**Recommend similar movies based on search**: Suggest movies similar to the searched movie based on cosine similarity algorithm

![Screenshot (419)](https://user-images.githubusercontent.com/76270840/170885746-cb6d9563-05dc-4f00-923b-9fec22de90d7.png)

**Filter movies**: Set filters like genre of the movie, language, year of release, director or cast of the movie to view personalised movies.

![Screenshot (420)](https://user-images.githubusercontent.com/76270840/170885818-6249b1c0-c91e-46e7-8b41-fd0f7e5f88d2.png)

![Screenshot (422)](https://user-images.githubusercontent.com/76270840/170885830-1885b20a-6094-477f-bee1-cf672b8c7609.png)

**Sort results**: View top movies based on averaging rating or popularity

![Screenshot (421)](https://user-images.githubusercontent.com/76270840/170885871-1f1e8a2e-9230-49ff-83f0-b55d6bc81b50.png)

**The surprise me button!**: Suggests a random movie to watch!

![Screenshot (423)](https://user-images.githubusercontent.com/76270840/170885975-b0b4c518-e8b8-4757-a282-ae08fd71e428.png)

### **Credits**
I have used the following resources to build this project:
1. [CampusX - Movie recommender system project](https://youtu.be/1xtrIEwY_zY)
2. [Kaggle - TMDB 5000 Movie Dataset](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata?select=tmdb_5000_movies.csv)
3. [How recommender systems work](https://youtu.be/n3RKsY2H-NE)
4. [Streamlit API](https://streamlit.io/)

### **License**

MIT License

Copyright (c) 2022 Likhita Narra

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
