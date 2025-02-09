# deeploycv
This is a project I did under the google developers guild during my winter break in the first semester.
We created a GAN model that was used for traffic data imputation. 

The dataset used for this was: https://www.kaggle.com/datasets/aryashah2k/highway-traffic-videos-dataset

We first measured the traffic volume for various timestamps in the video, and then created a GASF matrix for each array. This was the data on whcih the GAN was trained on after masking 20% of the matrix. 

here is an example of the GASF matrix 
![image](https://github.com/user-attachments/assets/5cb36192-a8c9-4659-9edb-7fdcbb2bfb0c)


