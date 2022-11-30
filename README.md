# Explainable-AI-for-Pneumonia-Classification
<h1 align="center">  Explainable AI for Pneumonia Classification </h1>
<br/>

 
## Dataset
**Chest X-Ray Images (Pneumonia)** 
The dataset is organized into 3 folders (train, test, val) and contains subfolders for each image category (Pneumonia/Normal). There are 5,863 X-Ray images (JPEG) and 2 categories (Pneumonia/Normal).

Chest X-ray images (anterior-posterior) were selected from retrospective cohorts of pediatric patients of one to five years old from Guangzhou Women and Children’s Medical Center, Guangzhou. All chest X-ray imaging was performed as part of patients’ routine clinical care.

<img  width=50% alt="image" src="https://user-images.githubusercontent.com/96674419/202986286-958093b4-6438-4a74-ac13-fbc7c03f982c.png">

Kaggle link to Download the dataset: [Chest X-Ray Images(pneumonia)](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia)

## Convolutional Neural Networks
The CNN-based deep neural system is widely used in the medical classification task. CNN is an excellent feature extractor, therefore utilizing it to classify medical images can avoid complicated and expensive feature engineering.
<p align="center"><br>
  <img src="https://user-images.githubusercontent.com/96674419/204122119-957e08ca-bb73-4e97-bd8b-00646370d5b5.png" width=50% ><p/>
<p>

### Sample output
<p align="center" width="100%">
    <img width="30%" src="https://github.com/Manishankar9977/Expainable-AI-for-Pneunomia-Classification/blob/main/test/Normal/IM-0009-0001.jpeg?raw=true">
    <img width="30%" src="https://user-images.githubusercontent.com/96674419/204122201-32d0f004-6c2d-420e-b5cc-804a40035c22.png">
</p>

### Better understanding using Explainable AI
<table>
 <tr>
    <td><p > Explainable AI is a set of tools and frameworks to help you understand and interpret predictions made by your machine learning models. With it, you can debug and improve model performance </p></td>
    <td><img src="https://user-images.githubusercontent.com/96674419/204122823-3a63d1eb-f31b-4f37-9d95-e7cc237dbdf8.gif"></td>
 </tr>
</table>
 
**LIME Explanations**
 
LIME perturbs the features in an example and fits a linear model to approximate the neural network at the local region in the feature space surrounding the example. It then uses the linear model to determine which features were most contributory to the model’s prediction for that example.

In our project, explanations are visually represented as an overlay of the superpixels deemed by LIME as most contributory to a prediction onto the original image. Superpixels coloured green indicate regions that were most contributory toward the predicted class. Conversely, superpixels coloured red indicate regions that were most contributory against the predicted class.
<p align="center"><br>
  <img src="https://user-images.githubusercontent.com/96674419/204123301-6ac9d81b-c020-42dd-a91d-841ba1a7ea77.png" ><p/>
<p>


## Contributors
<a href="https://github.com/SaiSwarup27/SaiSwarup27/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=SaiSwarup27/SaiSwarup27" />
</a>
<a href="https://github.com/Manishankar9977/Manishankar9977/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=Manishankar9977/Manishankar9977" />
</a>


## License
[![License](http://img.shields.io/:license-mit-blue.svg?style=flat-square)](http://badges.mit-license.org)
