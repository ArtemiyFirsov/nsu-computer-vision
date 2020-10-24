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
* Why our eye is bad
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

<details>
  <summary>Introduction to CNNs</summary>
 
1. Convolutional Neural Network (CNN) definition
* Convolutional layer
* MaxPooling
* Average Pooling 
* Stide and Padding
2. Dataset
* Tiny Images, CIFAR-N, ImageNet
* How to gather your dataset
3. Training problems
* Dead neurons
* Saturation
* Overfitting
4. Data from CNN
* Features
* Filter visualization
* Activation visualization
* Maximal neuron activation
* Visualization of important data
* tSNE
* Reconstruction of the image
5. CNN frameworks


</details>

<details>
  <summary>CNNs architectures</summary>
 
1. Alexnet
2. ZF Net
3. VGG Net
4. GoogleNet
5. RESNET
6. Semantic Segmentation
7. DetectNet
* Fully connected conditional random fields
* R-CNN
* Segnet
* Upsampling layer
7. Style transfer
8. GANs
9. Capsule Networks
10. CNNs tips

</details>

## Seminars plan

<details>
  <summary>openCV seminar</summary>
 
https://colab.research.google.com/drive/1M4FLYZnx-n5g03hcyGllxNuesEXOKL9D?usp=sharing

</details>

<details>
  <summary>CNN seminar</summary>
 
https://colab.research.google.com/drive/1Wb-BHpLmzVR40DbMa6UD2rw-4KE_D4s6?usp=sharing

</details>

## Additional materials:
https://github.com/kulikovv/ostrov2018
