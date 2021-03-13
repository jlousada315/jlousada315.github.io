## Data Science Portfolio

#### [Take a look at my CV!](/pdf/CV_JoaoLousada__public__.pdf)

---

### Project 1: Identifying File-Test Links

- **Context**: [Continuous Integration](https://en.wikipedia.org/wiki/Continuous_integration) is used in software versioning systems like GitHub or SVN, where developers frequently commit code changes. Then, to make ensure proper code functioning, software tests are run. However in fast-paced industrial environments,  as teams and projects grow, testing strategies have to be optimized to not compromise performance. 
- **Goal**: To cherry-pick which tests are more relevant in a given commit, by finding links between the files that were modified in a commit with the tests that were affected by those modifications, using machine learning (ML) algorithms.
- **ML Model**: Supervised Learning Task - *Neural Network Embeddings*, implemented using Keras using real-world data.
- **Results**: An expressive increase in performance relative to Random Testing. 
- **Impact**: Detecting failing commits early-on saves a company a lot of time or significantly reduces costs related with computer power, having ecological impact. Moreover, there is also a human component: developers can commit with more confidence, knowing the probability of jeopardizing someone else's work is minimized, thus boosting productivity.
- **Technology**: Keras, scikit-learn, numpy, pandas, SQL, T-SNE and UMAP, matplotlib and seaborn.

<img src="images/software.jpg?raw=true"/>


- [Identifying File-Test Links Notebook](https://www.kaggle.com/joolousada/identifying-file-test-links)

---

### Project 2: Song-Recommendation Engine

- **Context**: This is framework for a Song Recommendation Engine based on Spotify playlists, on the assumption that songs that appear in the same playlists are likely to be related. This end-to-end project starts by scrapping data from [Spotify's API](https://developer.spotify.com/documentation/web-api/), collecting over 200k playlists and 8.411.437 songs, creating a sqlite database to store them. After that, an off-the-shelf model [Word2Vec](https://radimrehurek.com/gensim/models/word2vec.html) is trained so that songs that appear on the same context (i.e. same playlists) will have similar vector representations, much like words in sentences. Finally, a web application is deployed using [Streamlit](https://www.streamlit.io), where the recommendation engine can be tested. 
- **Goal**: The goal is to, given a song provided by the user, recommend other songs based on similarity. 
- **ML Model**: Word2Vec converts elements, e.g. words or songs, into high dimensional vectors and based on the context that they appear, these vectors are squeezed together based on similarity. For example, jazz songs are likely to have vectors that point in the same direction of the song space. 
- **Results**: Given that a considerable amount of data was collected, recommendations seems to work very well, specially for popular songs that tend to be part of more playlists. To improve recommendation quality, more data should be collected from Spotify's API.
- **Ready to Deploy**: Additionally, to simulate an industrial environment, this framework can be deployed to production as a web application, developed using Streamlit.
- **Technology**: Word2Vec, streamlit, sqlite3, spotipy, json and matplotlib.



<img src="images/spotify.jpg?raw=true"/>


- [Song-Recommender Repo](https://github.com/jlousada315/song-recommendation-engine)
- [Check out some Recommendation Examples!](/images/merge_from_ofoct.jpg)

---

### Dataset Contributions

- To enrich and contribute to broaden data availability, I published on Kaggle a Public Domain Dataset of File-Test Links in Continuous Integration Systems, along with a template notebook with my implementation.

- [Identify File-Test Links](https://www.kaggle.com/joolousada/filetest-links-in-regression-testing)

<img src="images/link.jpg?raw=true"/>

---

### Master-Thesis: Test Case Prioritization with Machine Learning

- [Master-Thesis](/sample_page)

---

#### Paper Publications
- [Neural Network Embeddings for Test Case Prioritization](https://arxiv.org/abs/2012.10154)
- [Reinforcement Learning for Test Case Prioritization](https://arxiv.org/abs/2012.11364)

---

### Kaggle Competitions

- [Titanic](https://www.kaggle.com/joolousada/titanic-predictions)
- [House Price Prediction](https://www.kaggle.com/joolousada/house-prices-prediction)
- [Disaster Tweets](https://www.kaggle.com/joolousada/nlp-disaster-tweets-tf-idf-linearsvc)

---

### Online Courses

1. [Deep Learning A-Z](/pdf/deep_learning_certificate.pdf)
2. [R Programming](/pdf/R_certificate.pdf)
3. [NLP Course](/pdf/nlp_certificate.pdf)
4. [SQL Bootcamp 2021](/images/sql.pdf)

---
