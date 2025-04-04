# Face-Mask-Detection
Our project detects face masks in images and videos using a fast and accurate deep learning model called SSD. By applying transfer learning, we achieved 100% precision and 99% recall, showing excellent performance.
# INTRODUCTION
2020 has brought about an astounding array of events for humanity, the most significant of which has been the global outbreak of the COVID-19 pandemic from the year's inception. With COVID-19 affecting millions of people's lives and health, it is imperative that stringent steps be taken to stop the illness from spreading. Face masks are one piece of personal protective equipment that individuals use to protect themselves and the rest of society from basic hygiene standards to medical procedures. People wear face masks when they leave their houses, and face mask use in public areas and in groups is strongly enforced by the government. It is important to devise a plan to ensure that individuals are adhering to this fundamental safety guideline. To verify this, a face mask detection system can be used. Face mask detection is the process of determining whether or not a person is wearing a mask. The technique is split into two parts: detecting faces and detecting masks on those faces. The first stage in determining if a mask is on a face is to detect the face. One usage for object detection is face detection, which has several applications in fields like security, biometrics, law enforcement, and more. Numerous detecting systems are being developed and put into use globally. The goal of this project is to create a face mask detector that can discriminate between faces that have masks on and ones that don't. In this paper, we present a detector that uses a neural network to identify the existence of a face mask and an SSD for face identification. The algorithm is used to live video feeds, photos, and movies. The report's remaining sections are arranged as follows.
# Problem Statement
Motion has been the key step in the global struggle against the epidemic, which has been fought with much zeal. Now more than ever, it is important to take initiative. Governments from all across the world now understand how powerful AI and machine learning may be in the fight against the virus. Until immunization becomes widely available, the only known ways to prevent infection are by social separation and mask wear. Mask detection in computer vision is a life-saving technique that helps people get back on track. In regions with dense populations, MASK DETECTION SECURITY can provide a solution to the monitoring problem.
# Objective
Face mask detection is the process of determining whether or not a person is wearing a mask. The actual issue is reverse engineering face detection, which finds faces using various machine learning techniques for monitoring, security, and authentication. In the fields of computer vision and pattern recognition, face detection is crucial. In the past, a substantial amount of research has advanced face identification systems.
# Requirements
Hardware Requirement
Monitoring Automation Screen
Integrated CCTV camera
Admin Database Setup
Software Requirement
Front-End
Database Handler
Back-End
PYTHON 3.11
PyCharm\ VScode \ “Or Any Python IDE”
CMD
PowerShell
# Dataset
The dataset we utilized has 3835 total photos, 1916 of which show individuals wearing masks and 1919 of which show people not wearing them.
Figures 3.1.1 and 3.1.2 illustrate Every image is a real image that was taken from the RMFD dataset, the Kaggle dataset, and the Bing Search API. The ratio of the photos is the same throughout the three sources. Asian, Caucasian, and other racial groups are shown in the photos. The dataset's balance is determined by the ratio of masked to unmasked faces.
# Dataset
The dataset used can be downloaded from here the GitHub Repository Link This dataset consists of 3339 images belonging to two class:
1. with_mask – 1755 images
2. without_mask – 1584 images
# Conclusion
To mitigate the spread of COVID-19 pandemic, measures must be taken. We have modelled a face mask detector using SSD architecture and transfer learning methods in neural networks. To train, validate and test the model, we used the dataset that consisted of 1916 masked faces images and 1919 unmasked faces images. These images were taken from various resources like Kaggle and RMFD datasets. The model was inferred on images and live video streams. To select a base model, we evaluated the metrics like accuracy, precision and recall and selected MobileNetV2 architecture with the best performance having 100% precision and 99% recall. It is also computationally efficient using MobileNetV2 which makes it easier to install the model to embedded systems. This face mask detector can be deployed in many areas like shopping malls, airports and other heavy traffic places to monitor the public and to avoid the spread of the disease by checking who is following basic rules and who is not.
