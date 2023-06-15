
# ML Capstone Project
## About The Project

This is the Tensorflow model we created for image classification in our application TrashSort. The model will classify images to two different categories which are organic and inorganic/non organic.

We use transfer learning using [EfficientNetV2](https://github.com/google/automl/tree/master/efficientnetv2) and [EfficientNet-lite](https://github.com/tensorflow/tpu/tree/master/models/official/efficientnet/lite) as base to optimise our model training time and performance.

The dataset used is public dataset called [Waste Classification data](https://www.kaggle.com/datasets/techsash/waste-classification-data) from kaggle.

## Getting Started

We provide two models for different deployment schema:  

- First, for edge device deployment (smartphone), to get the model run the ProjectCapstone_EfficientNetLite notebook on Google Colab. We already include instructions inside the notebook for ease of use.
- Second, for GCP Vertex AI deployment, to get the model run the ProjectCapstone_EfficientNetV2 notebook on Google Colab. We already include instructions inside the notebook for ease of use.

### Prerequisites

As we fully run the notebook on Google Colab, no additional prerequisites needed asides from kaggle account for the API.

Follow the steps below to get your kaggle API:
- Go to your kaggle account, Scroll to API section and Click Expire API Token to remove previous tokens
- Click on Create New API Token - It will download kaggle.json file on your machine.

If you want to run the notebook locally then you need to have suitable enviroment to run Jupyter notebook on your machine including Python, Tensorflow, Matplotlib, Numpy, and kaggle.  
PLEASE NOTE, that we do not guarantee a successful run of the notebook this way without modifying some of the codes as we recommended to run it on Google Colab.

### Usage
The usage of our model for TrashSort is through the Android apps or GCP Vertex AI, as such please kindly refer to these detailed documents or the respective repositories:
- https://www.tensorflow.org/lite/android
- https://www.tensorflow.org/lite/android/quickstart
- https://www.tensorflow.org/lite/examples/image_classification/overview
- https://codelabs.developers.google.com/vertex-image-deploy
- https://github.com/GoogleCloudPlatform/vertex-ai-samples/blob/main/notebooks/community/ml_ops/stage6/get_started_with_tf_serving_function.ipynb 

