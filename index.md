## My projects

---

### Wine recommender powered by NLP

Unsupervised Learning / NLP / Tensorflow / Data Engineering


[![](https://img.shields.io/badge/Website-API-blueviolet)](https://winerecomander-wagon.herokuapp.com/)
<details>


  <iframe src="https://docs.google.com/presentation/d/e/2PACX-1vR5SeuAsFeZkL-cFsQwQYTT8vFVD5o5Zg6BHARVBQMggn5YrMxQPIGs43PnkEYJgGMcTVKTsPTpF8aB/embed? start=false&loop=false&delayms=15000" frameborder="0" width="480" height="299" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>

  <div style="text-align: justify">This project is a wine recommender, based on user tastes, expressed either through other wines, or through description. It is therefore an NLP based machine learning solution. Unsupervised learning was used to clusterise 120K vectorised wine reviews. Using distance computing, nearest wines are found.

    
  </div>
</details>
Testing of the solution has been made throught T-SNE visualization : [here](https://projector.tensorflow.org/?config=https://gist.githubusercontent.com/arthurchiquet/7a34ec908855cd6729d15a71ed25a812/raw/7f7468821b0a5d4e77f6fe7d29245ae159ddf388/Embeddings)







---

### NYC Taxifare API

Neural networks / API building / Docker / Google Cloud


[![](https://img.shields.io/badge/Website-API-blueviolet)](https://ny-taxifare-ahbis.herokuapp.com/)
[![](https://img.shields.io/badge/Doc-API-informational)](https://image-taxifare-mbkpe2fzia-ew.a.run.app/docs)
<details>

  <div style="text-align: justify">
  <img src="images/NYC.png?raw=true"/>


  NYC Taxifare is a an API and web interface able to predict with very high accuracy, the price of taxi rides in New-York. the platform uses google cloud compute and MLflow for training, Docker and FastAPI. Lifecircle is automated through Prefect and interface is built on Heroku. The model is training neural networks over 500K entries. MAE is around 1$.
  </div>
</details>


 


---

### Attrition and customer satisfaction for Shinkansen

Prediction / Machine Learning / Neural Networks


[![](https://img.shields.io/badge/Github-code-color?logo=github)](https://github.com/Ahbis/shinkanzen)
<details>

  <div style="text-align: justify">
  <img src="images/importance_features.png?raw=true"/>


  This project was based on the Shinkansen Bullet Train in Japan, and passengers experiences with that mode of travel. This machine learning problem aims to determine the relative importance of each parameter with regards to their contribution to the passengers overall travel experience. 


  The goal of the project was to predict whether a passenger was satisfied or not considering his/her overall experience of traveling on the Shinkansen Bullet Train. This project was part of the 2022 Hackaton hosted by MIT IDSS. This more business oriented project is fully available on GITHUB.


  <img src="images/xgboost_accuracy.png?raw=true"/>

  </div>
</details>

---
### Street View Housing Number Digit Recognition

Image-recognition / Neural Networks

[![](https://img.shields.io/badge/Github-code-color?logo=github)](https://github.com/Ahbis/notebooks/blob/master/street_digits.ipynb)
<details>

  <img src="images/street-number.jpeg?raw=true"/>
  <div style="text-align: justify">

  The SVHN dataset contains over 600,000 labeled digits cropped from street-level photos. It is one of the most popular image recognition datasets. It has been used in neural networks created by Google to improve the map quality by automatically transcribing the address numbers from a patch of pixels. The transcribed number with a known street address helps pinpoint the location of the building it represents.
  
  
  Model is using neural networks and detailed results matrix is presented bellow:


  <img src="images/digits_confusion.png?raw=true"/>

  </div>
</details>

---

### 3D Location tracking

Kalman Filters


[![](https://img.shields.io/badge/Github-code-color?logo=github)](https://github.com/Ahbis/notebooks/blob/master/KALMAN+FILTER-3D+Location+Tracking.ipynb)

 <details>
 
  <div style="text-align: justify">
  The goal was to track the location (and velocity) of a moving object (ball) in a 3-dimensional space. Taking into account gravity that acts on the ball, the initial position and velocities are assumed to be known. The algorithm is using noisy location estimates using a (simulated) sensor. The objective was therefore to estimate the true location (and velocity) of the ball in a 3D space.
  </div>

  <img src="images/kalman.png?raw=true"/>

</details>


--- 
### Stock Portfolio Optimization

Networking / Graphical Modelling


[![](https://img.shields.io/badge/Github-code-color?logo=github)](https://github.com/Ahbis/notebooks/blob/master/Network_Stock_Portfolio_Optimization.ipynb)

<details>

  <img src="images/network-portfolio.png?raw=true"/>

  <div style="text-align: justify">
  Active investing in the asset management industry aims to beat the stock market’s average returns, for which portfolio managers track a particular index and try to beat that index by creating their own portfolios.

  Portfolio construction involves selection of stocks that have a higher probability of giving better returns in comparison to the tracking index, like S&P 500. In this project, the concept of Network Analysis is used to select a basket of stocks and create two portfolios. those portfolio are then being simulated by investing a certain amount, keeping the portfolio for an entire year, it will then be compared against the S&P 500 index.


  </div>


  <img src="images/portfolio.png?raw=true"/>

</details>

--- 

### Attrition and customer satisfaction for OLIST

Data analysis / regression
<details>
  <div style="text-align: justify">


  Olist is a leading e-commerce service that connects merchants to main marketplaces in Brazil. They provide a wide range of offers including inventory management, dealing with reviews and customer contacts to logistic services.

  The dataset consists of ~100k orders from 2016 and 2018 that were made on the Olist store, available as 9 csv files. Recommandations have been made, concerning sellers and products sold, on how to increase customer satisfaction (so as to increase profit margin) while maintaining a healthy order volume.



  <img src="images/olist.png?raw=true"/>
  </div>
</details>





---
