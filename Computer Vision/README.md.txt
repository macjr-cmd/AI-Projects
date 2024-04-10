# Computer Vision - 3D Object Detection Projects

=======

Author: Simo Ulrich Emmanuel Anagho
Date: 29.07.2021
Master Thesis: Stereo Vision based 3D Object detection

This repo only includes state of the art results. My thesis repo can be made available
on request. My performance results can be found in this repo.

Description:

The goal of these scripts is to present a few usecases showcasing the application
and comparison of different 3d object detection methods with Python 3.7.
This repo contains a few examplary scripts from my master's thesis on stereo vision 
based 3d object detection. This represents just a little fraction of the work done within
this thesis. The dataset used here was the Kitti dataset. Ground truth information was 
already provided by Kitti. The goal in general is to observe the performance of the applied
algorithms by comparing the results against the ground truth information. Several images
were used to test the algorithms. Also different variations of these images were created to 
experiment the robustness of the algorithms. A solution to increase the robustness against
changes in lighting variations was developed based on the central limit theory. The
results obtained surpassed state of the art performance (sota) algorithms at the time this thesis
was written. RCNN and SOTA were used as sota algorithms for comparison. Yolov4 was used
as 2d object detection algorithm while stereo vision was applied to add the 3rd dimension
to calculate depth (3d).



Dependencies

Python 3.7

Recommendation: 

Install Anaconda
or mini conda
Install python 3 
create an environment ##*your env*##

activate the created environment
conda activate *your env*    
and 
Install these packages in your environment:


Packages:

Opencv-python and Opencv-contrib-python
 Numpy 1.19.3
 Matplotlib
 Ipykernel
 Seaborn
 Pandas
 Pip
 Jupyter notebook
 Scikit-learn
 ipython
 ipykernel
 PyMaxflow
 Cython
 Scipy
 Numpy
 pip
 Tensorflow
 yolov4
 open3d (optional - for point clouds)

Sota:
@article{qin2019tlnet, 
  title={Triangulation Learning Network: from Monocular to Stereo 3D Object Detection}, 
  author={Zengyi Qin and Jinglu Wang and Yan Lu},
  journal={IEEE Conference on Computer Vision and Pattern Recognition (CVPR)},
  year={2019}
}

Kim, J. A. ; Sung, J. Y. ; Park, S. H.: Comparison of Faster-RCNN,
YOLO, and SSD for Real-Time Vehicle Type Recognition. In: 2020 IEEE
International Conference on Consumer Electronics - Asia, ICCE-Asia 2020
(2020), S. 1{4. ISBN 9781728161648
yolov4 · PyPI. https://pypi.org/project/yolov4/1.2.1/. { (Accessed
on 18/01/2021)

Central limit theorem - Wikipedia. https://en.wikipedia.org/wiki/
Central_limit_theorem.

Dataset:
The KITTI Vision Benchmark Suite. http://www.cvlibs.net/datasets/
kitti/setup.php. { (Accessed on 14/06/2021)
Geiger, A. ; Lenz, P. ; Urtasun, R.: Are we ready for autonomous
driving? The KITTI vision benchmark suite. In: 2012 IEEE Conference on
Computer Vision and Pattern Recognition (CVPR), 2012, S. 3354{3361
