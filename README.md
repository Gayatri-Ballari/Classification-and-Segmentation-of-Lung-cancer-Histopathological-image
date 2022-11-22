# Classification-and-Segmentation-of-Lung-cancer-Histopathological-image
Detection of lung cancer using deep learning methods by performing classification and segmentation.


This dataset contains 15,000 histopathological images with three classes. All images are 768 x 768 pixels in size and in JPEG file format. The images were created from  original samples from HIPAA-compliant validated sources and consisted of a total of 750  images of lung tissue (250 benign lung tissue, 250 lung adenocarcinoma, and 250 lung squamous cell carcinoma), Augmented to 15,000 with Augmenter package. The dataset contains three classes, each with 5,000 images.
•	Lung benign tissue
•	Lung adenocarcinoma
•	Lung squamous cell carcinoma
The dataset is extracted from kaggle competition by Borkowski AA 2019(15).


CLASSIFICATION RESULTS
This section describes the results of classification and segmentation techniques. This will help you understand your model better and understand how to further improve your model's performance. The basic idea is to understand why a machine learning model predicts that an instance (image) belongs to a certain class.


Segmentation
Segmentation is the separation of one or more regions or objects in an image supported by separation or similarity criteria. A region in an image is defined by its boundary (edge) or interior, and the representation of the two unit regions is the same. If it recognizes the inside, it continuously outlines the border. And vice versa. Additional pixels are added to the selected chunk, or additional chunk points are reduced to smaller segments and merged with other smaller chunk points. Therefore, there is an additional basic technique in Unit 2 that supports this method. Mainly region-based and edge-based and rendering. As a result, image segmentation approaches generally fall into two categories. Edge and region primary based strategy.



Our results show that the proposed study, InceptionresNetV2 architecture for solving lung cancer and edge- and region-based segmentation, provides the results of histopathological image dataset experiments with sufficient accuracy of 99.46%. This suggests that the Therefore, the work presented will enable developers to develop and use methods with even more security, which in turn will give users more security and trust.  Segmentation is therefore used to separate the object of interest from the image in order to perform object analysis. CNN is a good approach for image segmentation, but it can take a long time to train if the dataset is huge. Clustering-based segmentation is computationally expensive. Edge-based segmentation is suitable for images with good contrast between objects. 
