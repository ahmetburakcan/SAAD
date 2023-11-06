# Welcome to the Scene Adaptable Anomaly Detection (SAAD) Dataset!

In most of the video anomaly approaches, a deep neural network model is trained on one or more datasets, and it is assumed that the resulting model can be used in all different environments monitored by the surveillance system. However, the dynamics of a street scene where people or cars pass are very different from the scene dynamics of a quiet area in a building. If an anomaly detection model working on a surveillance system is adjusted according to dynamics of the quiet area inside the building, it will generally generate false anomaly alerts for the street environment. On the other hand, if an anomaly detection model can adapt itself to the dynamics of an observed area for the normal situations, the model can make more successful anomaly decisions.

For this purpose, we proposed Scene Adaptable Anomaly Detection (SAAD) Dataset. The videos in the dataset are selected from UCF-Crime[1], UBI-Fights[2], and CamNuvem[3] datasets. The selected videos in the dataset were chosen to include at least 5 seconds of normal state at the start of the video. Thus, an anomaly detection model that can observe at least 5 seconds (approximately 100 frames) of normal state will be able to acquire information about the dynamics/patterns of the scene and update its parameters based on this information, making more accurate decisions about the scene. It is considered that this dataset  will be useful for the development and testing of scene-adaptable anomaly detection methods in the future.

# Annotations
The annotations of this dataset can be found on this Google Excel sheet: 

https://docs.google.com/spreadsheets/d/1l3vGeiajX9XikW7tRRXhmrGujEEJ8McptlvfpGp8RvY/edit?usp=drive_link

# Download
To download the videos, please fill the below Google form. The download link will be sent to your email address.

https://forms.gle/kMsCuZq5nGF94Ncq5


# Acknowledgements
We thank to Hüseyin Can Yılmaz and Veli Toprak Güngör, who did the data selection and annotation tasks of this dataset.  

We thank to the Scientific and Technological Research Council of Turkey (TUBITAK). This work was supported by TUBITAK under Grant No. 119E098

#References

1. Sultani, W., Chen, C., & Shah, M. (2018). Real-world anomaly detection in surveillance videos. In Proceedings of the IEEE conference on computer vision and pattern recognition (pp. 6479-6488).
2. Degardin, Bruno, and Hugo Proença. "Human Activity Analysis: Iterative Weak/Self-Supervised Learning Frameworks for Detecting Abnormal Events." 2020 IEEE International Joint Conference on Biometrics (IJCB). IEEE.
3. de Paula, D. D., Salvadeo, D. H., & de Araujo, D. M. (2022). CamNuvem: A robbery dataset for video anomaly detection. Sensors, 22(24), 10016.
