# Spotify 
Doing some analytical preprocesses and implementing some supervised and unsupervised algorithms on the Spotify dataset.

## Dataset
The project's dataset consists of about 12000 songs and their information which is collected and represented in Kaggle.
Dataset link: https://www.kaggle.com/datasets/paradisejoy/top-hits-spotify-from-20002019

## Implementation

### Preprocessing
In the first stage, we checked and removed noisy or duplicate rows. Then, we tried to normalize the dataset to have a better understanding of what was going on in the dataset. After that, some outlier detection methods have been used to check and remove potential outliers. In the final stage, some analytical observations have been made by using analytical tools such as histograms and heat maps.

### Classification
The main goal of this part of the project is to use classification algorithms to classify songs. As the major algorithm, we tried MLKNN (Multi-label KNN) to classify songs due to the possibility of a song having different genres. 

### Clustering
In this part of the project, we used clustering algorithms to divide songs into different groups. K-means and Hierarchical clustering are the major algorithms used in this section.
