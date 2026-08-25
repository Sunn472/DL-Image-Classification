# DL-Image-Classification
Image classification is a computer vision task where a deep learning model looks at an image and assigns it to one or more predefined classes/categories.

<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/4dda3319-9400-44d9-9b71-1de9fd28385b" />


1. LeNet
Introduced by: Yann LeCun
One of the earliest successful CNN architectures.
Mainly used for handwritten digit recognition.
Architecture: Convolution → Pooling → Fully Connected

Key idea: Simple CNN for image recognition.

2. AlexNet
Introduced: 2012
Won the ImageNet 2012 competition.
Popularized ReLU activation and Dropout in deep CNNs.
Used GPUs for faster training.

Key idea: A deeper CNN that greatly improved image classification performance.

3. VGG
Developed by the Visual Geometry Group (VGG).
Famous versions: VGG16 and VGG19.
Uses mostly 3×3 convolution filters.
Simple and uniform architecture.

Key idea: More layers + small 3×3 filters → better feature extraction.

4. Transfer Learning
Not a specific architecture.
It is a technique where we use a model already trained on a large dataset.
Examples: VGG, ResNet, Xception can all be used for transfer learning.

Pre-trained Model
       ↓
Learned Features
       ↓
Replace Final Layer
       ↓
Your Dataset
       ↓
New Classes

Key idea: Reuse knowledge from a large dataset instead of training from scratch.

5. ResNet
Introduced Residual/Skip Connections.
Famous versions: ResNet18, 34, 50, 101, 152.
Helps solve the vanishing/degradation problem in very deep networks.

Key idea:

Input ───────────────→ +
  ↓                   ↓
Conv → Conv → Conv →  +

The shortcut allows information and gradients to flow more easily.

6. InceptionNet / GoogLeNet
Introduced the Inception Module.
Performs different operations in parallel:
1×1 convolution
3×3 convolution
5×5 convolution
Pooling
Captures features at different scales.

Key idea: Multiple filter sizes work in parallel.

7. Xception

Xception = Extreme Inception.
Uses Depthwise Separable Convolution.
More computationally efficient than standard convolution.
Provides strong image classification performance.

Key idea: Separate spatial filtering and channel-wise feature extraction.
<img width="995" height="772" alt="image" src="https://github.com/user-attachments/assets/166b227c-90f9-4efa-9917-e88eea09fb11" />
