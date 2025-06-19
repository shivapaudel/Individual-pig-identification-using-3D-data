# Individual-pig-identification-using-3D-data
This repository contains the code and dataset used in our project for identifying 8 individual pigs using 3D point cloud data and the PointNet architecture.

The project is based on our paper:
Paudel, Shiva, et al. "Deep learning algorithms to identify individual finishing pigs using 3D data." Biosystems Engineering 255 (2025): 104143.


#Abstract
The application of precision livestock farming technology is heavily reliant on the identification of individuals.
However, due to the cost and time constraints, finishing pigs are rarely tagged or otherwise identified. Therefore,
the objectives of this study were to determine the feasibility of using deep learning on 3D spatial data to identify
individual finishing pigs and to quantify the amount of data required, image resolution needed, and frequency of
retraining for continuous identification using two different architectures: PointNet (which utilises point clouds
directly) and 3D convolution neural network (3D CNN). Digital/depth images were collected using ToF (Time of
Flight) camera positioned over RFID (Radio Frequency Identification) instrumented drinkers. A subset of this
data were used for this initial validation study, which included 31976 images from eight pigs over 14 days. The
data were then processed to create different sets of training and testing data with varying point sets (1500, 3000,
6000, 12000, 24000, and 48000) for point clouds and voxel sizes (50, 35, 25, and 15 mm) for 3D CNN. The
findings revealed that the 3D CNN model achieved the highest F1 score of 0.91 after the sixth training session
with a point voxel size of 15 mm. PointNet achieved its highest F1 score of 0.90 after five training sessions with a
point set size of 1500 points. This study underscores the potential of utilising deep learning techniques for the
purpose of individual pig identification within actual barn environments, including those with natural lighting
conditions.
