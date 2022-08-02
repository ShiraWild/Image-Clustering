**About the assignemnt:** This assignemnt was given in the course "Decision Trees and Cluster Analysis" including extracting features from given photos,
clustering the photos using Embedding Model. The goal is to classify human faces. 

**Main Parts:**
1. Preprocessing the Data - Extract faces from each image. Then, extract Vector Features 
from each "face" (np.array) using open-CV and Face recognition libraries on python. 
2. Create a dataframe from the extracted features 
3. Apply K-means on the data and K-medoids, calculating silhouette score according to different k-values in order to select the best k value. 
4. Predict clusters, each cluster is suppposed to represent a specific person and each point in the dataframe represents a photo of a face of this person.  
5. Saves the different photos of each cluster in Google Drive in organized libraries. 
6. Evaluating the models - Visualize K-means and K-medoids clusters using PCA (for dimensionality reduction), Compare the results.
