# Lane-Detection-for-ADAS
This project introduces a novel deep learning approach for lane detection, pivotal in autonomous 
driving systems development. Leveraging convolutional neural networks (CNNs), our model 
efficiently segments lane markings from diverse road images, proving effective in varied 
environmental conditions. Utilizing Keras' ImageDataGenerator, we preprocessed and augmented 
the dataset, enhancing the model's robustness. The CNN architecture features convolutional, maxpooling, and upsampling layers, optimized to detect lane markings intricacies. Compiled with the 
Adam optimizer and binary cross-entropy loss, the model underwent rigorous training. The model 
attained an impressive accuracy of 96.58%, showcasing its precision in distinguishing lane pixels. 
However, precision at 68.87% and recall at 39.19%, alongside an F1 score of 49.95% and IoU of 
33.29%, indicate potential areas for improvement, particularly in accurately identifying lane 
markings and balancing false positives. Future efforts will focus on rectifying data imbalance, 
experimenting with advanced architectures, refining hyperparameters, enhancing data 
augmentation, and testing alternative loss functions. This project lays a substantial groundwork for 
ongoing research in autonomous vehicle navigation, marking a significant stride towards 
developing safer, more efficient autonomous driving technologies.

