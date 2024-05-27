# Classification of camera trap images with a convolutional neural network

## Abstract

Biodiversity studies involve direct field observation or image analysis, demanding significant time and effort from specialists. In this context, this Bachelor's Thesis addresses the design and application of a classification model tailored for camera trap images.

For its development, we used an 8000-image dataset classified by species, including horses, deer, roe deer, humans, wild boars, cows, emptiness, and foxes. Two convolutional neural networks were employed as classification models: "MobileNetV2" (with 3,088,680 parameters) and another network called the "Crohn Architecture" (with 599,168 parameters). The training, validation, and evaluation of these networks were conducted with an 80%, 10%, and 10% data distribution, respectively. The networks achieved an accuracy rate of approximately 70%.

However, various tests analyzing the results revealed that the primary cause of this lower performance was the inherent difficulty in extracting knowledge from the processed images, compounded by the limited number of available images. This conclusion was reached after applying the networks to a new benchmark dataset consisting of 21,000 images and 15 different classes, where the elements of interest were presented more prominently in a confined environment. The accuracy of the networks on this reference dataset exceeded 95%.

In summary, this study emphasizes the crucial role of having a high-quality dataset, as it directly and significantly impacts the performance of neural networks. The results achievable with a network are intrinsically linked to the dataset's quality and available annotations.
