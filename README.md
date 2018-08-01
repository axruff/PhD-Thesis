# PhD thesis: "Automated Analysis of Time-resolved X-ray Data using Optical Flow Methods" by Alexey Ershov

[Full text (pdf)](../master/PhD_Thesis_Ershov.pdf)

[Full text on Karlsruhe Institute of Technology Library](https://publikationen.bibliothek.kit.edu/1000055519)




## Abstract


*X-ray imaging* is a genuine tool to reveal internal structures of opaque objects. This is possible due to the penetration properties of its probe - X-ray radiation.
Modern synchrotron facilities, equipped with high-resolution detector systems, provide  X-ray radiation of unique quality and allow to investigate a broad range of *dynamical* processes, both in materials and biological specimens.
To perform *automated* and *quantitative* analysis of *time-resolved* X-ray data, a method capable to retrieve dynamical information is required. In this work we develop a general-purpose framework for X-ray data analysis based on *optical flow*.


*Optical flow* methods traditionally belong to the field of Computer Vision. Finding correspondences between time-lapse images is a key problem in a variety of applications such as robot vision, tracking systems and video analysis.
In the scope of this work we adapt  *variational* optical flow methods - a specific class of approaches used to determine the optical flow - to the task of X-ray data analysis.


The quality of time-resolved X-ray data is diverse, ranging from high-resolution datasets to low-contrast, noisy images with artifacts. We provide a detailed classification of X-ray data. This taxonomy serves as a reference point for the development of image preprocessing, motion estimation and data analysis techniques. Image preprocessing is employed to enhance the original (raw) X-ray data in order to improve the accuracy of optical flow estimation for the case of challenging data.
 

To develop an accurate and *robust* motion estimation model, we perform a systematic evaluation of state-of-the-art optical flow techniques and make quantitative performance analysis of their components. 


On the top of the optical flow estimation we provide an extensive *data analysis toolkit* including automated tracking, flow analysis, motion-based segmentation, image registration and detection of temporal changes. All the devised techniques can be applied in 4D (3D + time) to enable analysis of tomographic data.
The implementation of the developed techniques incorporates advanced numerical schemes and computations on GPU. Thereby, the processing of a vast amount of X-ray data is feasible. 


Finally, we present the application of the optical flow methods to a number of scientific problems from various research fields. These examples include flow analysis and particle segmentation in semi-solid alloys, analysis of morphogenesis in living frog embryos, coalescence events estimation and stability studies during the foaming process, and tracking of morphological dynamics in living insects.

## Preview Figures

![alt text](https://github.com/axruff/PhD-Thesis/raw/master/figures/app_embryo_setup.png "X-ray Experimental Setup")
Figure: Experimental setup for phase-contrast X-ray microtomography.



![alt text](https://github.com/axruff/PhD-Thesis/raw/master/figures/app_embryo_velocity.png "Cell motion analysis")
Figure: Cell motion analysis from 3D time-lapse series of Xenopus laevis embryo during mid-gastrulation.



![alt text](https://github.com/axruff/PhD-Thesis/raw/master/figures/app_bug_motion_seg.png "Morphological dynamics and Kinematics")
Figure: Morphological dynamics and kinematics analysis of the screw joint during defensive movement.



## Table of Content


1. Introduction
   - 1.1. Motivation
   - 1.2 Outline 
   - 1.3 X-ray Imaging 
   - 1.4 Variational Optical Flow
   - 1.5 Aims of the Work
2. Optical Flow Methods
   - 2.1 Modeling
   - 2.2 Numerical Solution
3. Data Analysis Framework
   - 3.1 Data Preprocessing 
   - 3.2 Analysis Based on Optical Flow
4. Computational Framework 
   - 4.1 Software Framework 
   - 4.2 High Performance Computing
   - 4.3 Visualization
5. Evaluation on Synthetic Data
   - 5.1 Data Taxonomy 
   - 5.2 Experimental Data
   - 5.3 Optimization of Parameters
   - 5.4 Quantitative Evaluation
   - 5.5 Models Comparison
   - 5.6 Evaluation Summary
6. Applications in X-ray Imaging
   - 6.1 Motion Analysis
   - 6.2 Temporal Changes Detection
   - 6.3 Tracking
7. Summary and Outlook
   - 7.1 Conclusions
   - 7.2 Further work
8. List of Publications
