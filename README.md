Welcome to the Scene Adaptable Anomaly Detection (SAAD) Dataset!

In most of the video anomaly approaches, a deep neural network model is trained on one or more datasets, and it is assumed that the resulting model can be used in all different environments monitored by the surveillance system. However, the dynamics of a street scene where people or cars pass are very different from the scene dynamics of a quiet area in a building. If an anomaly detection model working on a surveillance system is adjusted according to dynamics of the quiet area inside the building, it will generally generate false anomaly alerts for the street environment. On the other hand, if an anomaly detection model can adapt itself to the dynamics of an observed area for the normal situations, the model can make more successful anomaly decisions.

For this purpose, we proposed Scene Adaptable Anomaly Detection (SAAD) Dataset. The selected videos in the dataset were chosen to include at least 5 seconds of normal situation at the start of the video. Thus, an anomaly detection model that can observe at least 5 seconds (approximately 100 frames) of normal state will be able to acquire information about the dynamics/patterns of the scene and update its parameters based on this information, making more accurate decisions about the scene. It is considered that the dataset created will be useful in the future for the development and testing of scene-adaptable anomaly detection methods.


The annotations of this dataset can be found on this Google Excel sheet: https://docs.google.com/spreadsheets/d/1l3vGeiajX9XikW7tRRXhmrGujEEJ8McptlvfpGp8RvY/edit?usp=drive_link

The collected videos can be downloaded from here: https://drive.google.com/drive/folders/1IWbLeVfD9suelA2CshMYqR-UK8ZOITMt?usp=drive_link

