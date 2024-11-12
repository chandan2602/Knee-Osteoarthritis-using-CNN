# Knee-Osteoarthritis-using-CNN
<h2>Objective :</h2>
This project applies Convolutional Neural Networks (CNNs) to detect knee osteoarthritis from X-ray images. The model is trained on medical imaging data to accurately classify the presence and severity of osteoarthritis, helping in early diagnosis and treatment planning.
<h3>Dataset : </h3>
The model is trained on the dataset, containing X-ray images of knee joints labeled with different grades of osteoarthritis.<br>
Link - https://data.mendeley.com/datasets/t9ndx37v5h/1
<ul>
<li><strong>Data Classes : </strong> Normal, Doubtful, Mild, Moderate, Severe</li>
<li><strong>Format : </strong>X-ray images .png format</li> 
</ul>
<h3>Model Architecture : </h3>
The CNN model used in this project includes multiple convolutional and pooling layers, followed by fully connected layers for classification. Key details include :-
<ul>
  <li><strong>Input shape : </strong> 256x256 grayscale images</li>
  <li><strong>Layers : </strong> Three convolutional layers with ReLU activations and max-pooling, followed by a dense layer with softmax activation for classification</li>
  <li><strong>Loss function : </strong> Categorical Cross-Entropy</li>
  <li><strong>Optimizer : </strong> Adam</li>
</ul>
<h3>Technology Used : </h3>
<ul>
  <li>Python</li>
  <li>TensorFlow/Keras</li>
  <li>OpenCV</li>
  <li>NumPy</li>
  <li>Matplotlib</li>
  <li>Scikit-Learn</li>
</ul>
<h3>Result :</h3>
<ul>
  <li><strong>Test Loss : </strong> 71%</li>
  <li><strong>Test Accuracy : </strong> 90%</li>
</ul>
