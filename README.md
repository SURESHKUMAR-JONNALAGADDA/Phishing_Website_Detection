<h1>DETECTION OF PHISHING WEBSITES USING MACHINE LEARNING ALGORITHMS</h1>
<br>
<center>PYTHON--------JUPYTER--------FRONTEND-HTML---------DEPLOYMENT-PYTHON(FLASK)</center>
<br>
<BR>
<H2>ABOUT</H2>
<H2>Phishing is an online fraud through which phisher gains unauthorized access to the user system to lure the personal credentials. </H2>
<H4>IN THIS APPLICATION WE DETECT THE PHISHING WEBSITES BY USING MACHINE LEARNING MODELS.</H4>
<h4>In this project we are given a dataset of URLs along with the label of 0 and 1 which are classified into original website and phishing website. we had trained the given dataset by using NLP methods and machine learning algorithms.<h4>
<H4>ENVIROMENT USED IS JUPYTER</H4>
<h3><b>Libraries used for the project</b></h3>
<h3>
<ul type=disk>
<li>pandas</li>
<li>svm</li>
<li>GaussianNB</li>
<li>MultinomialNB</li>
<li>DecisionTreeClassifier</li>
<li>KNeighborsClassifier</li>
<li>RandomForestClassifier</li>
<li>LogisticRegression</li>
<li>TfidfVectorizer</li>
</ul>
<H3>This application uses URLS as the datasets, to find the legitimate website among the fake websites.
 </h3>
 <h2>Feature Extraction</h2>
 <h4>Feature extraction involves reducing the number of resources required to describe a large set of data. When performing analysis of complex data one of the major problems stems from the number of variables involved. Analysis with a large number of variables generally requires a large amount of memory and computation power, also it may cause a classification algorithm to overfit to training samples and generalize poorly to new samples.</h4>
<h3>Steps done for Preprocesing</h3>
<h4>The given dataset is first preprocessed by removing and spliting them based on the some of parameters like "/" ,":" ,"//".
and then tokenized the urls to extract the domain and the sub domain names from the urls</h4>
<h3>Algorithms</h3>
<ul type=disk>
<li>count vectorisation</li>
<li>TF-IDF</li>
</ul>
<DL><DT><B>COUNT VECTORISATION</B></DT>
<DD>CountVectorizer is a great tool provided by the scikit-learn library in Python. It is used to transform a given text into a vector on the basis of the frequency (count) of each word that occurs in the entire text.</DD></DL>
<DL><DT><B>TF-IDF</B></DT>
<DD>Tf-idf is one of the best metrics to determine how significant a term is to a text in a series or a corpus. tf-idf is a weighting system that assigns a weight to each word in a document based on its term frequency (tf) and the reciprocal document frequency (tf) (idf).</DD></DL>
<h4>Now it is converted into vector form having values of term frequency and inverse term frequency. Where now the vector is trained model where we use different Classifiers and differnt Metrics for the evalution</h4>
<H2>RESULTS</H2>
 <br>
  <h3>USED CLASSIFIERS ARE:</h3>
  <table>
    <tr>
    <td>Classifier</td>
    <td>Metrics-MCC</td>
    <td>Metrics-ACCURACY</td>
    </tr>
    <TR>
      <td>MultinomialNB</td>
      <td>85.76719103708573</td>
      <td>93.87930464670501</td>
     </tr>
    <TR>
      <td>LogisticRegression</td>
      <td>78.84875639270138</td>
      <td>90.92471412519004</td>
     </tr>
    <TR>
      <td>KNeighborsClassifier</td>
      <td>79.35970411705305</td>
      <td>91.09656950228039</td>
     </tr>
    <TR>
      <td>GradientBoostingClassifier</td>
      <td>59.30651210477634</td>
      <td>82.89378015731377</td>
     </tr>
    <TR>
      <td>CatBoostClassifier</td>
      <td>72.72581200169554</td>
      <td>88.32044418005156</td>
     </tr>
  </table>
 <H3>FINALLY WE USED THE CLASSIFIER NAIVE BAYES THAT IS MULTINOMIALNB GOT AN MCC OF 85.7</H3>
 <H3>DEPLOYED BY USING FLASK</H3>
  <H3>HOPE YOU UNDERSTAND</H3>  
     

