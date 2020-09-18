


I am Tianyuan (Noah) Zhou. Currently I am a third year PhD student in Statistics at Department of Statistics, University of Virginia. My research interest is mainly about statistical learning. 

# Academic Experience

## Working Projects

#### Coastal Red Tides Forecast (In Progression)                                         
Co-Supervisor: Prof. Scott Doney from Department of Environmental Sciences, University of Virginia.
•	Working on purposing a new time series forecasting method to predict the coastal red tides, stochastic chaotic phenomena which is very harmful to different aspects of the society. 
•	Analyzed existing methods for this task including empirical dynamic modeling, State-space modeling and Bayesian non-parametric time series forecasting methods. 

#### Basis-expansion Random-Projection Ensemble (BRPE)                               
Co-Supervisor: Prof. Jinzhu Jia from Peking University.
*	Proposed Basis-expansion Random-Projection Ensemble (BRPE) to extend Random Projection Ensemble for regression problems, which works as follows: (1) randomly project the original data into lower dimension, and fit a low dimensional regression problem on it to get a regressor; (2) repeat the previous process to get a series of regressors, and combine them using a regularized linear regression to get the estimated function;
*	Studied BRPE’s theoretical properties and experimentally demonstrated that it outperformed linear regressions, kNN, SVR, CART and RF in a wide range of classic nonlinear regression problems;
*	Prepared a python package and a paper “Basis-expansion Random-Projection Ensemble” (first author), which will be submitted to Journal of Computational and Graphical Statistics (JCGS).

#### Locally Hierarchical Graphical Models (LHGM)                                  
Collaborator: Xiaoyuan Ma (PhD student) from Department of Statistics at University of Virginia.
*	Proposed a novel Bayesian method, LHGM, to address the problems of Graphical Lasso by adding the penalty on the sparsity. We proved that LHGM is a generalization of AIC and BIC;
*	Conducted a comprehensive analysis on both simulated and real-world datasets to show that our method can recover the underlying true graph with higher accuracy and sensitivity, and can obtain a more informative graphical model than Graphical Lasso;
*	Prepared an R package and a paper “Locally Hierarchical Graphical Models” (co-first author), which will be submitted to The Annals of Applied Statistics (AoAS).

#### Matrix Factorization Research                                               
Collaborator: Xiaoyuan Ma (PhD student) from Department of Statistics at University of Virginia.
*	Proposed a method called Random Ensemble Matrix Factorization (REMF) to apply the bootstrapping and bagging method for matrix factorization and obtained its upper risk bound;
*	Proposed a new form of Multiple Canonical Correlation Analysis (MCCA) called Subspace-Regularized MCCA (SR-MCCA) which allows adding regularization on the output subspaces and showed its consistency;
*	Conducted a comprehensive real data analysis (an RNA-seq dataset and a user-rating movie recommender system dataset) to show the validity of REMF;
*	Prepared two papers “Subspace-Regularized Multiple Canonical Correlation Analysis” (first author) and “Random Ensemble for Matrix Factorization” (first author), which will be submitted to Journal of the Royal Statistical Society: Series B (JRSSB).

## Published Projects

#### Word Embedding Research    

Co-Supervisor: Prof. João Sedoc from Johns Hopkins University.
*	Theoretically showed that the performances on downstream Natural Language Processing tasks of the aligned word embeddings depend on the isotropy of the target embedding;
*	Conducted a comprehensive analysis of the aligned word embeddings’ performance, including word2vec, GloVe, FastText, Latent Semantic Analysis, Eigenwords, Dependency word Embedding; 
*	Published a paper [Getting in shape: word embedding subspaces](https://jrodu.github.io/files/IJCAI_2019_Word_Embedding_Subspaces.pdf) in International Joint Conference on Artificial Intelligence (IJCAI). 

## Teaching

#### STAT1100: Chance: An Introduction to Statistics
The introductory statistics course for students not majoring in Statistics. 
* Designed all materials for this course.
* Taught this course for 2020 Spring and 2020 Fall semesters. 


# Working Experience
Before coming to University of Virginia, I have worked for Solutionlab Co. Ltd, a start-up in consulting, as lead data scientist, from Oct 2014 to Mar 2018. Here are a part of my projects. 

#### Consumer Insight High Definition (CIHD)
A system that predicted consumer profiles using broadband internet data. 
*	Developed a learning model to leverage a combination of manual feature construction and L2-regularized Logistic Regression to predict demographic profiles of online users;
* Proposed and performed Sigmoid Normalization and Importance Factor Evaluation as feature engineering to improve accuracy; 
*	Achieved an accuracy rate greater than 75%, 5% better than the state-of-art results published by Tencent; 
*	Companies adopting this system: PepsiCo. Inc., P&G, Nestle, Maxwell House, Estee Lauder, LG, Fonterra, Starcom Media Group, Lvmama and Hainan Airlines.

#### DIStribution Planning Optimization (DisPO)                                     
A system that used GPS data to index and evaluate different locations on a map.
*	Proposed and implemented a new method DisPO, which is a variant of the PageRank algorithm; 
*	DisPO’s results nearly doubled performance-index compared with original PageRank algorithm, which measures the correlation between the importance index and the real estate price of different locations; 
*	Companies adopting this system: PepsiCo. Inc., Samsung and Giti.

#### Target Audience Finder (TA Finder)                                            
A system used survey data to help companies target consumers and understand their behavior, adopted by Eral.
*	Designed and implemented a clustering model specific to this task. Under this model, the distance between each pair of samples is well-defined, and t-SNE is used as the main dimensionality reduction and visualization technique; 
*	Achieved the best consumer segmentation known to Eral, evident from the large number of features used and the high correlation of the behavior inside each cluster.






