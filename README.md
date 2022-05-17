# NeuralNetworkClustering-MilanAerialView
In this project, Neural Networks are used to perform Clustering on the Aerial View of the city of Milan. The final goal is to explore how different areas of the city are clustered together and explore what are the most important architectural features leveraged when performing such clustering. The most important architectural patterns found were buildings' density, presence of internal yards, buildings' shapes and presence of roads and squares.  

Since the dataset was very limited, Transfer Learning was used to extract the main features from images, representing them through dense vectors.
Then, the compact representation was fed to three Clustering Algorithms (K-Means, K-Medoids, Agglomerative Clustering) and their results were analysed through silhouette and elbow analysis. 
