# MobileNetV1 from scratch : 


![1667665727255](https://user-images.githubusercontent.com/99510125/204151339-21d0cebc-b9aa-498b-b8d2-9842e49a7ca1.jpeg)



MobileNet is an efficient and portable CNN architecture that is used in real-world applications. MobileNets primarily use depthwise separable convolutions in place of the standard convolutions used in earlier architectures to build lighter models. MobileNets introduce two new global hyperparameters (width multiplier and resolution multiplier) that allow model developers to trade off latency or accuracy for speed and low size depending on their requirements.



MobileNet Architecture :


MobileNets are built on depthwise separable convolution layers. Each depthwise separable convolution layer consists of a depthwise convolution and a pointwise convolution. Counting depthwise and pointwise convolutions as separate layers, a MobileNet has 28 layers. A standard MobileNet has 4.2 million parameters which can be further reduced by tuning the width multiplier hyperparameter appropriately.
The size of the input image is 224 × 224 × 3.


![1667298133943](https://user-images.githubusercontent.com/99510125/204151398-d20e2292-f7a0-46bf-a811-64d50a9b2307.png)


For more information visit : https://www.linkedin.com/pulse/mobilenets-efficient-convolutional-neural-networks-mobile-kirouane
