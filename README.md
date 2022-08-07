# Cryptocurrencies

Overview:  
Using Unsupervised Machine learning to predict Crytocurrency investment trends for new and less prominent currencies.  Unsupervised learning is the best way forward for this dataset because  looking for any groupings, trends, or other information help identify cryptocurrencies to investment firms.

### Preprocessing the Data for PCA

![cleandf](https://user-images.githubusercontent.com/102183530/183299187-8c35b11f-23de-4bcb-884c-e809c787a88b.png)

###### Cleaned dataframe, dropped null and n/a values, dropped "Is Trading" column

![scaleddata](https://user-images.githubusercontent.com/102183530/183299282-adee0a47-1fb3-44d7-b5b9-d3725f3f71fc.png)

###### scaled data to run using PCA

### Reducing Data Dimensions Using PCA


### Clustering Cryptocurrencies Using K-means

![Elbow Curve](https://user-images.githubusercontent.com/102183530/183298890-14f4e6ea-d019-4fd0-9306-d73cb167b21d.png)

![Del3Kmeansdf](https://user-images.githubusercontent.com/102183530/183299026-85b0e8ab-cc8b-4ba9-8813-b475e06392ed.png)

### Visualizing Cryptocurrencies Results

![d4scat3d](https://user-images.githubusercontent.com/102183530/183299037-c2b172be-e658-4c02-abe6-1c3fe493ef12.png)

![d4scatplot](https://user-images.githubusercontent.com/102183530/183299061-c6fb2663-fd8c-44ea-aab6-81d11f42cec4.png)

Looking at the outliers in this scatterplot would make a difference if there was a reason to drop them from the data set and take a closer look at the rest of the cluster in more detail.
