# Plant_disease_prediction

This project uses a transfer learning technique to perform disease prediction on plant leaves

The dataset contains 39 different classes

Each class contains multiple images of leaves, including both original and augmented images

The dataset can be downloaded for reference from: https://data.mendeley.com/datasets/tywbtsjrjv/1/files/b4e3a32f-c0bd-4060-81e9-6144231f2520. Here, it is directly fetched from online.

The model is trained on ResNet50 using transfer learning. It is later fine-tuned for certain epochs after freezing the layer.

The attained accuracy of the model is 96%
