
<h1 align="center"> Movie Recommendation System </h1>
</br>


<!-- TABLE OF CONTENTS -->
<h2 id="table-of-contents"> :book: Table of Contents</h2>

<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#about-the-project"> ➤ About The Project</a></li>
    <li><a href="#prerequisites"> ➤ Prerequisites</a></li>
    <li><a href="#dataset"> ➤ Dataset</a></li>
    <li><a href="#roadmap"> ➤ Roadmap</a></li>
    <!--<li><a href="#experiments">Experiments</a></li>-->
    <li><a href="#contributors"> ➤ Contributors</a></li>
  </ol>
</details>

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/water.png)

<!-- ABOUT THE PROJECT -->
<h2 id="about-the-project"> :pencil: About The Project</h2>

<p align="justify"> 
  This project implements a movie recommendation system which is an ML-based approach to filtering or predicting the users film preferences based on their past choices and behavior. 
  The primary goal of movie recommendation systems is to filter and predict only those movies that a corresponding user is most likely to want to watch, based on their preference.
 We focused on designing such a system using various text to vector conversion techniques and cosine similarity.
</p>

<!--
<p align="center">
  <img src="logo.png" alt="Baby Sign Language" width="70%" height="70%">        
  <!--figcaption>Caption goes here</figcaption-->
<!-- </p> -->

 **Text-to-Vector Techniques Used:**

 - **TF-IDF:** Term Frequency-Inverse Document Frequency
 -  **Count Vectorizer:** Converts text to a bag-of-words representation
 -  **Hash Vectorizer:** Converts text to a hashed representation
 -  **Word2Vec:** Word embeddings for text representation
 -  **Doc2Vec:** Document embeddings for text representationù
 -  **GloVe:** Global Vectors for Word Representation

 </p>

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/water.png)

<!-- PREREQUISITES -->
<h2 id="prerequisites"> :fork_and_knife: Prerequisites</h2>

[![made-with-python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)](https://www.python.org/) <br>
[![Made with Jupyter](https://img.shields.io/badge/Made%20with-Jupyter-orange?style=for-the-badge&logo=Jupyter)](https://jupyter.org/try) <br>

<!--This project is written in Python programming language. <br>-->
The following open source packages are used in this project:
* Numpy
* Pandas
* Difflib
* Matplotlib
* Gensim-Models ( Word2Vec, Doc2Vec )
* Sklearn (TfIdVectorizer, CountVectorizer, HashVectorizer, cosine_similarity)
* Scikit-Learn
* Nltk
* Fuzzywuzzy

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/water.png)

<!-- DATASET -->
<h2 id="dataset"> :floppy_disk: Dataset</h2>
<p> 
   Our dataset, labeled as the "TMBD 5000 Movie Dataset", has been obtained from Kaggle and it includes 4803 items. Spanning 24 features, this dataset offers a comprehensive range of details, including movie ID, title, cast members, producers, release year, and assorted attributes.

<!--
<p align="center">
  <img src="images/Baby Sign Language Dataset.png" alt="Baby Sign Language Dataset" display="inline-block" width="60%" height="50%">
</p> -->

</p>

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/water.png)

<!-- ROADMAP -->
<h2 id="roadmap"> :dart: Roadmap</h2>

<p align="justify"> 
  This roadmap outlines the journey from collecting data to creating the recommendation system: 
<ol>
  <li>
    <p align="justify"> 
      Data Preprocessing: This inclused collecting the dataset needed and then applying feature extraction on it.
    </p>
  </li>
  <li>
    <p align="justify"> 
      Testing different text-to-vector conversion: We explored 6 different techniques in order to figure out which one has the best accuracy. 
    </p>
  </li>
  <li>
    <p align="justify"> 
      Generating recommendations: Based on a movie input, we generated 30 recommendations and this was possible by applying cosine similarity between movie vectors to determine similarity and recommend similar movies.
    </p>
  </li>
</ol>
</p>


![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/water.png)

<!-- CONTRIBUTORS -->

<h2 id="contributors"> :scroll: Contributors</h2>

<p>
  :mortar_board: <i>All participants in this project are undergraduate students of <a href="https://acsai.di.uniroma1.it/">Applied Computer Science and Artificial Intelligence</a> <b>@</b> <a href="https://www.uniroma1.it/en/">Sapienza University of Rome</a></i> <br> <br>
  
  :woman: <b>Rokshana Ahmed</b> <br>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Email: <a>ahmed.1994927@studenti.uniroma1.it</a> <br>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; GitHub: <a href="https://github.com/RoxyDiya">@RoxyDiya</a> <br>
  
  :woman: <b>Elena Martellucci</b> <br>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Email: <a>martellucci.1988602@studenti.uniroma1.it</a> <br>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; GitHub: <a href="https://github.com/elena-martellucci">@elena-martellucci</a> <br>

  :woman: <b>Firdaous Hajjaji</b> <br>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Email: <a>hajjaji.2006406@studenti.uniroma1.it</a> <br>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; GitHub: <a href="https://github.com/Firdaous2002">@Firdaous2002</a> <br>

</p>

<br>
✤ <i>This was the final project for the course Deep Learning at <a href="https://www.uniroma1.it/en/">Sapienza University of Rome</a><i>
