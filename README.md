# Loan-Default-Prediction-base-on-Backpropagation
AI/Predict/BackPropation

# Abstract
With the growing popularity of internet-based loans, accurately predicting defaults on these loans is crucial. P2P (peer-to-peer) online lending platforms that utilize internet technology have significantly reduced borrowers' financing costs and improved capital utilization efficiency. The main focus for the future will be making better use of data from online lending platforms, integrating third-party data, and improving the ability to predict user default behavior.

This paper examines a default prediction model for online loans based on a Deep Neural Network (DPNN). It first analyzes the issues and risks faced by P2P lending platforms, then details the principles and characteristics of the Backpropagation Neural Network (BPNN) approach, and defines a credit risk rating process for online lending using BPNN. After cleaning and selecting customer data provided by lending clubs, the paper develops a BPNN-based model to evaluate default risk for online borrowers.

The paper simulates the BPNN-based default assessment model and compares it to support vector machines and regression models. The results show the BPNN model has the highest accuracy at 98.01% and the highest recall rate at 99.82%, outperforming the other two models. The BPNN model also has a significantly higher AUC value of 0.79 compared to the other models. These findings demonstrate the high practical value of the DPNN-based online loan default prediction model. Forecasting customer default risk can help P2P lenders and platforms reduce risks, improve competitiveness, and promote more stable development of the domestic P2P lending industry.

## Table of contents
* [Abstract](#Abstract)
* [Technologies](#technologies)
* [Setup](#setup)

## General info
This project present Backpropagation algorithm and applied to the problem of financial loan prediction.
	
## Technologies
Project is created with:
Python: latest version

## Proposed method to solve the problem
As mentioned above, using BPNN method will be more effective than Logistic Regression, so I will install the Backpropagation algorithm and apply it to the financial loan prediction problem. 
Characteristics of P2P online lending are as follows: direct and transparent, the lender and the borrower directly sign a personal loan contract with each other; credit screening, lenders can evaluate and select the creditworthiness of borrowers; and spread risk, lenders distribute capital to many types of borrowers.
BPNN promotes the advantages of biological neural networks so it has the following characteristics:
(1) High degree of parallelism. BPNN has a parallel structure so it can process a large amount of information in the network. For many problems with unclear cause-and-effect relationships, the ability to parallel process this huge amount of information can make the final analysis results more accurate.
(2) Distributed storage capacity and fault tolerance. BPNN is implemented through weights. For complex calculus problems, through the process of training the NN, rules and experiences are accumulated and all are distributed and stored in the weights of the whole NN. Even if stored information is lost, the system can still be analyzed to make it fault-tolerant.
(3) Self-learning, Self-organization and Self-adaptation. BPNN is reflected in the variability of its structure. The weight of each neuron is adjusted by training its self-organization to adapt to changes in external conditions. By learning a large amount of data, NN can adapt to the solution of different problems according to the model and has a certain adaptability to the data.
(4) Global nonlinear output. In general, the entire operation process of BPNN is the joint operation of all neurons to produce nonlinear output so that the output of BPNN is not disturbed by individual factors. The analysis results of this network are global.

## flowchart
 ![image](https://github.com/DieterHoang-AI/Loan-Default-Prediction-base-on-Backpropagation/assets/172985518/15672785-9ee3-4cf4-9d36-c9b56a760ca4)

