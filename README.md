# ProbabilisticMachineLearning
Probablistic Machine Learning course projects related to topic Modelling using LDA, Variational Inference and Autoencoders

**Lab1**: Finding clusters in Twitter data, i.e. grouping tweets with similar content. For this purpose, we first describe a mixture model for categorical data.
Secondly, we use the expectation-maximization (EM) algorithm to find the maximum likelihood (ML) estimate of the parameters of our model

**Lab2**: We continue working with the CMM and Twitter data-set presented in Lab 1. We will use different versions of the Gibbs sampling algorithm to find the posterior distribution of the cluster assignments ![first](http://www.sciweavers.org/upload/Tex2Img_1612947607/render.png) and model parameters ![second](http://www.sciweavers.org/upload/Tex2Img_1612947701/render.png)

**Lab3**: We  continue working with the CMM and Twitter data-set presented in Lab1. We will use Bayesian nonparametric (BNP) to assume (a priori) infinite number of mixture
components K. In practice, we will only be able to ”see” a finite number, K+, of components K+ < N - 1 << 1 which is constrained by the number of observations in our data-set. Again,we will rely on the Gibbs sampling algorithm to infer the posterior distribution of the unknownvariables and parameters in our model

**Lab4**: We explore two different applications of Hidden Markov Models (HMMs) i)Part-Of-Speech (POS) tagging and ii) Human Activity Recognition (HAR). We will learn how to
obtain the MLE of the parameters ![third](http://www.sciweavers.org/upload/Tex2Img_1612948134/render.png) in both tasks

**Lab5**: In this Lab we implement  Coordinate acsent Mean-field Variational inference (CAVI) and derive Evidence Lower bound for Gaussian Mixture model. Specifically we
  1.Generate a synthetic dataset from a GMM with 3 clusters and 1000 datapoints per cluster.
  
  2.Derive the formula of the ELBO for this model.
  
  3.Implement the CAVI updates for the model.
  
  4.Run the algorithm and plot the results at convergence.
