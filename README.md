# Advancements in Automated Brain Tumor Detection 
Using Deep Learning on MRI Imagery 
The goal of this thesis is to solve the significant problem of inter-observer variability-induced 
diagnostic delays by presenting a sophisticated deep learning system for automated brain tumor 
diagnosis utilizing MRI imagery. Pituitary adenoma, extra-axial meningioma, infiltrative glioma, 
and no-tumor controls are the four classes of brain tumors that are represented in the 7,143 T1
weighted MRI images taken from Kaggle Brain Tumor Dataset and various hospitals in 
Bangladesh, including Ibn Sina Medical College, Dhaka Medical College, and Comilla Medical 
College. Using three pretrained convolutional neural network (CNN) architectures; MobileNetV2, 
EfficientNetB0, and VGG16 optimized through selective layer unfreezing and on-the-fly data 
augmentation, including random brightness and contrast adjustments to mitigate scanner artifacts, 
the study applies transfer learning to improve diagnostic accuracy. With a test accuracy of 98.5%, 
a macro F1-score of 0.98, and an area under the curve (AUC) ≥0.99, MobileNetV2 outperformed 
the other models after being trained on 5,832 photos. Particularly noteworthy was the 
MobileNetV2 model's real-time inference ability (<50 ms), which qualifies it for clinical 
applications that demand low-latency performance. It has the potential to increase early detection 
rates by up to 25% due to its high sensitivity (recall >0.97) and quick processing times, especially 
in low-resource settings where prompt diagnosis can have a major impact on survival outcomes. 
The study highlights the clinical viability of applying AI-assisted diagnostics in various contexts, 
enhancing access to superior radiological evaluations and possibly cutting down on diagnostic 
delays in practical applications. 

Keywords: Brain tumor, Convolutional Neural Networks, Deep Learning, Transfer Learning, 
MRI Classification 
