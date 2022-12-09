Resume parsing with Named Entity Clustering: 
# Resume-NER

# About

This repository applies BERT for named entity recognition on resumes dataset. Intially KNN, SVM and Navies algorithms are used for classification and prediction from the ResumeData set. However in Real words application we see the Resume that Job seekers use while apllying to certain job differs from format to format. So we will have labelled data but in different format. Hence, I moved to BERT Tansformer where we first implement Named Entity Recognition and then predict the accuracy. The goal is to find useful information present in resume.
<h2>Introduction :-</h2><br>
<b>
  <ul>
  <li>Resume screening is the process of determining whether a candidate is qualified for a role based on his or her education, experience, and other information captured on their resume.</li>
  <li>It’s a form of pattern matching between a job’s requirements and the qualifications of a candidate based on their resume.</li>
  <li>The goal of screening resumes is to decide whether to move a candidate forward – usually onto an interview – or to reject them.</li>
  </ul>
  <h2>Modules & Libraries Description</h2>
  <ul>
    <h4>Modules :-</h4>
    Algong with the libraries that are described below, BERT, TORCH are used in execution of this project.
    <ul>
    <li>KNN</li>
      <dl>
      <dd>- It's supervised technique, used for classification. "K" in the KNN repersent the number of nearest neighbours used to classify or predict in case of continuous variable.</dd>
      </dl>
    <li>NLP</li>
      <dl>
      <dd>- NLP is a field in machine learning with the ability of a computer to understand, analyze, manipulate, and potentially generate human language.</dd>
      </dl>
    </ul> 
  </ul>
  <ul>
    <h4>Libraries :-</h4>
    <ul>
    <li>NumPy</li>
      <dl>
      <dd>- NumPy is one of the fundamental packages for Python providing support for large multidimensional arrays and matrices</dd>
      </dl>
    <li>Pandas</li>
      <dl>
      <dd>- It is an open-source, Python library. Pandas enable the provision of easy data structure and quicker data analysis for Python. For operations like data analysis and             modelling, </dd>
      </dl>
    <li>Matplotlib</li>
      <dl>
      <dd>- This open-source library in Python is widely used for publication of quality figures in a variety of hard copy formats and interactive environments across platforms.             You can design charts, graphs, pie charts, scatterplots, histograms, error charts, etc. with just a few lines of code.</dd>
      </dl>
    <li>Seaborn</li>
      <dl>
      <dd>- When it comes to visualisation of statistical models like heat maps, Seaborn is among the reliable sources. This Python library is derived from Matplotlib and                   closely integrated with Pandas data structures.</dd>
      </dl>
    
    <li>Scikit-learn</li>
      <dl>
      <dd>- It is a free software machine learning library for the Python programming language and can be effectively used for a variety of applications which include                       classification, regression, clustering, model selection, naive Bayes’, grade boosting, K-means, and preprocessing.</dd>
      </dl>
      <li>Nltk</li>
      <dl>
      <dd>- Natural Language toolkit or NLTK is said to be one among the popular Python NLP Libraries. It contains a set of processing libraries that provide processing                     solutions for numerical and symbolic language processing in English only.</dd>
      </dl>
    </ul>
  </ul>
<h4>References:-</h4> 
  <dl>
<dd>https://colab.research.google.com/github/jalammar/jalammar.github.io/blob/master/notebooks/bert/A_Visual_Notebook_to_Using_BERT_for_the_First_Time.ipynb
  </dl>  
