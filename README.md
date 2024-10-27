My latest project in the field of medical AI is Parkinson’s Disease Detection leveraging Inception & Xception architectures with an integrated Attention Mechanism

**Dataset:-** 
Used a dataset of spiral drawings from healthy individuals and Parkinson’s patients to train the model. The dataset was preprocessed to balance classes and enhance interpretability with visualizations. The images are further divided into training and testing groups for comparing (or reproducing) the results of the original publication.
he data came from the paper: Zham P, Kumar DK, Dabnichki P, Poosapadi Arjunan S and Raghav S (2017) Distinguishing Different Stages of Parkinson’s Disease Using Composite Index of Speed and Pen-Pressure of Sketching a Spiral. Front. Neurol. 8:435. doi: 10.3389/fneur.2017.00435

**Deep Learning Models: -**
Implemented InceptionV3 and Xception, high-performing CNN architectures, as the base models. These setups extract complex features while leveraging transfer learning.

**Attention Mechanism: -**
Integrated a Multi-Head Attention layer, enabling the models to focus on critical patterns in drawings associated with Parkinson’s symptoms, improving classification Accuracy.

**Training and Validation: -**
Achieved high Accuracy and minimized loss through early stopping and robust regularization techniques, including Batch Normalization and Gaussian Noise Layers.

**Results: -**
•	For the InceptionV3 + Attention Model, the Precision, Recall and F1-Score for healthy individuals were all 1.00.
The same metrics for Perkinson’s patients were also 1.00.
The Macro Average and Weighted Average metrics were both 1.00 across Precision, Recall and F1-Score
•	For Xception + Attention model, the precision for healthy individuals was 0.80, while the Recall was 1.00, resulting in an F1-Score of 0.89.
For Perkinson’s patients, the Precision was 1.00, the Recall was 0.75 and the F1-Score was 0.86. The Macro Average precision was 0.90, Recall 0.88 and F1-Score 0.87, while the Weighted Average showed the same Precision of 0.90, Recall of 0.88 and F1-Score of 0.87.

**Tools and Libraries: -**
•	TensorFlow
•	Keras 
•	OpenCV, 
•	Matplotlib 
•	 Seaborn
