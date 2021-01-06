# Rainfall-Predictions-in-India
## To Predict Rainfall in Towns of India

**Author** : SHAILESH DHAMA

Study and classify the 9 categories of most common Northern European mushrooms genuses.
                
### Dataset :

    It contains monthly rainfall detail of 36 meteorological sub-divisions of India.

#### Content of Dataset:

    1.Time Period: 1901 - 2015

    2.Granularity: Monthly

    3.Location: 36 meteorological sub-divisions in India

    4.Rainfall unit: mm

## Approach:

### Data processing & Exploratory Data Analysis:

    1.Import Libraries
    2.Loading and processing data
    3.Predictions
        3.1 Linear Model
        3.2 Support Vector Machine
        3.3 Artificial Neural Networks
        
#### 3.1 Linear Model      
Linear model is used in different ways according to the context. The most common occurrence is in connection with regression models and the term is often taken as synonymous with linear regression model. However, the term is also used in time series analysis with a different meaning. In each case, the designation "linear" is used to identify a subclass of models for which substantial reduction in the complexity of the related statistical theory is possible.

#### 3.2 Support Vector Machine
Support Vector Machine (SVM) is a supervised machine learning algorithm which can be used for both classification and regression challenges. We plot each data item as a point in n-dimensional space (where n is number of features) with the value of each feature being the value of a particular coordinate. Then, we perform classification by finding the hyper-plane that differentiates the two classes very well. A Support Vector Machine models the situation by creating a feature space, which is a finite-dimensional vector space, each dimension of which represents a "feature" of a particular object. The goal of the SVM is to train a model that assigns new unseen objects into a particular category. It achieves this by creating a linear partition of the feature space into two categories. Based on the features in the new unseen objects, it places an object "above" or "below" the separation plane, leading to a categorization. It is non-probabilistic, because the features in the new objects fully determine its location in feature space and there is no stochastic element involved. A subset of training data lies on Biased and Unbiased Hyper planes

#### 3.3 Artificial Neural Networks
A neural network is a series of algorithms that endeavors to recognize underlying relationships in a set of data through a process that mimics the way the human brain operates. In this sense, neural networks refer to systems of neurons, either organic or artificial in nature. Neural networks can adapt to changing input; so the network generates the best possible result without needing to redesign the output criteria.
           
## RESULTS :

#### Displaying images from each class
![Displaying images from each class](./MUSHROOM_1.png)

#### Res-Net50 model summary
![Res-Net50 model summary](./MUSHROOM_2.png)
![Res-Net50 model summary](./MUSHROOM_3.png)

#### Sequential model with the final dense layer
![Sequential model with the final dense layer](./MUSHROOM_4.png)

#### Sequential model training
![Sequential model training](./MUSHROOM_5.png)
![Sequential model training](./MUSHROOM_6.png)

#### Results of Model performance
![Results of Model performance](./MUSHROOM_7.png)

#### Loss during training
![Loss during training](./MUSHROOM_8.png)

#### Accuracy during training
![Accuracy during training](./MUSHROOM_9.png)

#### Accuracy on test set
![Accuracy on test set](./MUSHROOM_10.png)

### For further information:

Please review the narrative of our analysis in [our jupyter notebook](./Classification%20of%20Agaricus%20Bisporus%20Genuses.ipynb)

For any additional questions, please contact **shaileshettyd@gmail.com)

##### Repository Structure:

```
├── README.md                                                                                                   <- The top-level README for reviewers
├── Classification of Agaricus Bisporus Genuses.ipynb                                                           <- narrative documentation of analysis
├── https://www.kaggle.com/maysee/mushrooms-classification-common-genuss-images                                 <- Dataset
└── images                                                                                                      <- generated from code
```
## Citing :

```
@misc{Shailesh:2020,
  Author = {Shailesh Dhama},
  Title = {Classification-of-Agaricus-Bisporus-Genuses},
  Year = {2020},
  Publisher = {GitHub},
  Journal = {GitHub repository},
  Howpublished = {\url{https://github.com/ShaileshDhama/Classification-of-Agaricus-Bisporus-Genuses}}
}
```
