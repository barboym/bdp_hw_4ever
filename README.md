
# Final project in Big Data Platform course by Jiayu Guan, Moshe Barboy, Roey Gadot 

This study was performed in google colab notebook. 

Some parts of the notebook rely on access to a drive with the data (in our case google drive was mounted with the data in).

The zip containing the data can be downloaded from:

https://msropendata.com/datasets/3b8d1783-2c4f-4bdf-aa58-db777d0fd037

We saved the data in a "/content/drive/MyDrive/Big Data project/Data" location accessible from the notebook. 

To rerun it you should download the data to some location accessible to your machine and change all the URLs in the notebook accordingly 

The notebook has several sections: 

### Configurations 
This section downloads and installs pyspark 

### Preprocessing 
The schema of the data is defined, the data is loaded and saved in parquet files for faster retrieval 

### Apply some distributed algorithms
In this section a filter is applied for the beijing area, and the data is categorized into 4 "time of day" categories. 
Two clustering algorithms are run on the whole data and each of its categories 

### Comparison of user 0 trajectory to kmeans clustering 
This section deals with the visualisation of the data and the clusters on a map. 

### Result evaluation
In this section the clustering results are evaluated by comparison to popular locations on the map 


