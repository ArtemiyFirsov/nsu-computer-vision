# nsu-computer-vision

## [Progress](https://docs.google.com/spreadsheets/d/1fe0GOq8ySP3Gu1T1UhyPUNxVhF8ymiEvxQxQyRnQu1U/edit?usp=sharing)

## Lectures plan
<details>
  <summary>Introduction to CV</summary>
  
1. What is computer vision?
2. What types of issues are solved with computer vision?
* Digit recognition
* Object recognition
* Recognition of places
* Character Recognition
* Creating new images
* Definition of distance and shape
* etc.
3. Computer vision history
* Pinhole camera (camera obscura) - nautilus pompilius eye
* Van eyck drawings - why so precise?
* Camera lucida
* First photo (1825, 1826)
* First video (1878, 1888, 1895)
* Prokudin-Gorskiy photo's technology
* Stereophotogrammetry
* Whirlwind computer (1951)
* 3D solids in ciomputer (1963)
* Sketchpad (1963)
* David Marr (1971)
* Yann lecunn MNIST (1989)
* Viola Jones face detector (2001)
* TODO: Something else, modern?))
4. Why computer vision is complex?
* Angle of rotation
* Scale
* Lighting
* Incomplete coverage
* 3D -> 2D is ambiguous
* Perspective
* Diversity of objects
* Aberrations
5. What helps us to determine object?
* Edges 
* A priori knowledge
6. Physical basics
* Light == wave + visible spectrum
7. Human eye
* Why our eye sucks
* Why octopus eye is better than ours
* Why our ear is better than eye
8. Optical systems
* Schema of taking a photo
* Lenses
* Light sensitive elements
* Digitization of a signal
9. Image as a matrix/3D matrix
10. Convert light to number of values (RGB)
* What is color?
* Trichromatic theory
* Grassmans law
* LMS, RGB, HSV, CMYK
</details>


<details>
  <summary>CV Basics 1.0</summary>
 
1. Mathematical issue statement
2. Examples of bad photos
* Noisy
* Bad color
* Bad ligthing
2. Tone correction
* Linear histogram transformation
* Stable linear histogram transformation
* Gamma correction 
* Hist eq
3. Color correction
* White template 
* Many colors template
* Grayworld
* White balance recognition
3. Noise reduction
* Example of noise
* Noise types (random + salt n pepper)
* Noise reduction metrics (MSE, PSNR, SSIM)
* Averaging several images
* Averaging images regions
4. Convolution
* Definition (integral + discrete)
* Examples
* Mathematical properties
* How to deal with edges
* Not gaussian filter problem
* Gaussian filter 1/2D
* Gaussian filter as low frequency filter
* Median filter
5. Edge detection
* Gradient
* Derivative 
* Derivative convolution
* Algorithms for edge detection
* Canny detector algorithm
</details>

<details>
  <summary>CV Basics 2.0</summary>
 
1. Images matching
* What it is?
* Find Yann game
2. Local features
* What it is?
* Local features characteristics
* Types of local features
* Edge feature
3. Harris detector algorithm
* Algorithm
* Formula, Taylors series, derivatives matrix, eigenvalues of derivatives matrix
* Properties of Harris detector
4. Scale accounting - Laplassian for spot detection
* First, second order derivatives
* Attenuation problem
* How to find spots of different sizes with Laplassian
* Difference of Gaussians
5. Local fearures descriptors
* What to choose?
* Properties
* Mathcing algorithm
* SIFT


</details>

To be ccontinued ...

## Additional materials:
### Courses:
1. [Courser Machine Learning](http://coursera.org/learn/machine-learning/)
2. [Udacity DeepLearning](https://classroom.udacity.com/courses/ud730)
3. [Stanford CS201n](https://www.youtube.com/watch?v=vT1JzLTH4G4)

### Datasets:
1. [PASCAL VOC 2012 Segmentation Competition](http://host.robots.ox.ac.uk/pascal/VOC/voc2012/index.html)
2. [COCO 2018 Stuff Segmentation Task](http://cocodataset.org/#stuff-2018)
3. [BDD100K: A Large-scale Diverse Driving Video Database](http://bair.berkeley.edu/blog/2018/05/30/bdd/)
4. [Cambridge-driving Labeled Video Database (CamVid)](http://mi.eng.cam.ac.uk/research/projects/VideoRec/CamVid/)
5. [Cityscapes Dataset](https://www.cityscapes-dataset.com/)
6. [Mapillary Vistas Dataset](https://www.mapillary.com/dataset/vistas)
7. [ApolloScape Scene Parsing](http://apolloscape.auto/scene.html)
8. [CVPPP dataset](https://www.plant-phenotyping.org/CVPPP2017)

### Blogs
1. https://ai.googleblog.com/
2. https://research.fb.com/category/computer-vision/
3. https://www.jeremyjordan.me/
4. http://www.computervisionblog.com/
5. http://mccormickml.com/
6. http://www.cs.ox.ac.uk/people/yarin.gal/website/blog.html
7. http://colah.github.io/
8. http://karpathy.github.io/

### Fun
https://experiments.withgoogle.com/collection/ai

### Research Article:
#### Convolutional neural networks
- Yann LeCun, Bernhard E. Boser, John S. Denker, Donnie Henderson, R. E. Howard, Wayne E. Hubbard,Lawrence D. Jackel:
Handwritten Digit Recognition with a Back-Propagation Network. NIPS 1989: 396-404

- Alex Krizhevsky, Ilya Sutskever, Geoffrey E. Hinton:
ImageNet Classification with Deep Convolutional Neural Networks. NIPS 2012: 1106-1114

- Joan Bruna, Wojciech Zaremba, Arthur Szlam, Yann LeCun:
Spectral Networks and Locally Connected Networks on Graphs. ICLR 2014

- Kumar Chellapilla and Sidd Puri and Patrice Simard, High Performance Convolutional Neural Networks for Document Processing

- Karen Simonyan, Andrea Vedaldi, Andrew Zisserman:
Deep Inside Convolutional Networks: Visualising Image Classification Models and Saliency Maps.CoRR abs/1312.6034 (2013)

- Karen Simonyan, Andrew Zisserman:
Very Deep Convolutional Networks for Large-Scale Image Recognition. CoRR abs/1409.1556 (2014)

- Christian Szegedy, Wei Liu, Yangqing Jia, Pierre Sermanet, Scott Reed, Dragomir Anguelov, Dumitru Erhan,Vincent Vanhoucke, Andrew Rabinovich:
Going deeper with convolutions. CVPR 2015: 1-9

- Kaiming He, Xiangyu Zhang, Shaoqing Ren, Jian Sun:
Deep Residual Learning for Image Recognition. CoRR abs/1512.03385 (2015)

- Gao Huang, Zhuang Liu, Laurens van der Maaten, Kilian Q. Weinberger:
Densely Connected Convolutional Networks. CVPR 2017: 2261-2269

- Kaiming He, Xiangyu Zhang, Shaoqing Ren, Jian Sun:
Deep Residual Learning for Image Recognition. CoRR abs/1512.03385 (2015)

- Alex Krizhevsky, Ilya Sutskever, Geoffrey E. Hinton:
ImageNet Classification with Deep Convolutional Neural Networks. NIPS 2012

- Karen Simonyan, Andrea Vedaldi, Andrew Zisserman:
Deep Inside Convolutional Networks: Visualising Image Classification Models and Saliency Maps.CoRR abs/1312.6034 (2013)

- Karen Simonyan, Andrew Zisserman:
Very Deep Convolutional Networks for Large-Scale Image Recognition. CoRR abs/1409.1556 (2014)

- Christian Szegedy, Wei Liu, Yangqing Jia, Pierre Sermanet, Scott Reed, Dragomir Anguelov, Dumitru Erhan,Vincent Vanhoucke, Andrew Rabinovich:
Going deeper with convolutions. CVPR 2015: 1-9

- Christian Szegedy, Wojciech Zaremba, Ilya Sutskever, Joan Bruna, Dumitru Erhan, Ian J. Goodfellow, Rob Fergus:
Intriguing properties of neural networks. CoRR abs/1312.6199 (2013)

- Christian Szegedy, Sergey Ioffe, Vincent Vanhoucke:
Inception-v4, Inception-ResNet and the Impact of Residual Connections on Learning. CoRRabs/1602.07261 (2016)

- Olga Russakovsky, Jia Deng, Hao Su, Jonathan Krause, Sanjeev Satheesh, Sean Ma, Zhiheng Huang, Andrej Karpathy, Aditya Khosla, Michael S. Bernstein, Alexander C. Berg, Fei-Fei Li:
ImageNet Large Scale Visual Recognition Challenge. CoRR abs/1409.0575 (2014)

#### Computer Vision 
- Jonathan Long, Evan Shelhamer, Trevor Darrell:
Fully convolutional networks for semantic segmentation. CVPR 2015

- Olaf Ronneberger, Philipp Fischer, Thomas Brox:
U-Net: Convolutional Networks for Biomedical Image Segmentation. MICCAI (3) 2015

- Fisher Yu, Vladlen Koltun:
Multi-Scale Context Aggregation by Dilated Convolutions. ICLR 2016

- Ross B. Girshick:
Fast R-CNN. ICCV 2015

- Ross B. Girshick, Jeff Donahue, Trevor Darrell, Jitendra Malik:
Rich Feature Hierarchies for Accurate Object Detection and Semantic Segmentation. CVPR 2014

- Shaoqing Ren, Kaiming He, Ross B. Girshick, Xiangyu Zhang, Jian Sun:
Object Detection Networks on Convolutional Feature Maps. NIPS 2015

- Kaiming He, Xiangyu Zhang, Shaoqing Ren, Jian Sun:
Spatial Pyramid Pooling in Deep Convolutional Networks for Visual Recognition. ECCV (3) 2014

- Koen E. A. van de Sande, Jasper R. R. Uijlings, Theo Gevers, Arnold W. M. Smeulders:
Segmentation as selective search for object recognition. ICCV 2011

- Dumitru Erhan, Christian Szegedy, Alexander Toshev, Dragomir Anguelov:
Scalable Object Detection Using Deep Neural Networks. CVPR 2014

- Spyros Gidaris, Nikos Komodakis:
LocNet: Improving Localization Accuracy for Object Detection. CoRR abs/1511.07763

- Wei Liu, Dragomir Anguelov, Dumitru Erhan, Christian Szegedy, Scott E. Reed, Cheng-Yang Fu, Alexander C. Berg:
SSD: Single Shot MultiBox Detector. ECCV (1) 2016: 21-37

- Marius Cordts, Mohamed Omran, Sebastian Ramos, Timo Rehfeld, Markus Enzweiler, Rodrigo Benenson, Uwe Franke, Stefan Roth, Bernt Schiele:
The Cityscapes Dataset for Semantic Urban Scene Understanding. CVPR 2016: 3213-3223

- Kaiming He, Georgia Gkioxari, Piotr Dollár, Ross Girshick
Mask R-CNN, ArXiV 2017

- Hengshuang Zhao, Jianping Shi, Xiaojuan Qi, Xiaogang Wang, Jiaya Jia:
Pyramid Scene Parsing Network. CVPR 2017: 6230-6239

- Eduardo Romera, Jose M. Alvarez, Luis Miguel Bergasa, Roberto Arroyo:
ERFNet: Efficient Residual Factorized ConvNet for Real-Time Semantic Segmentation. IEEE Trans. Intelligent Transportation Systems 19(1): 263-272 (2018)

- Redmon, Joseph, et al. "You only look once: Unified, real-time object detection." Proceedings of the IEEE conference on computer vision and pattern recognition. 2016.


