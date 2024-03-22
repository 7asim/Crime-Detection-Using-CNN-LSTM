# Crime-Detection-Using-CNN-LSTM


**Introduction**
In this project, we developed a crime detection system using Convolutional Neural Networks (CNN) and Long Short-Term Memory (LSTM) networks. We trained our model on the UCF Crime Dataset, which contains videos of various criminal activities captured in different environments.

**Dataset**
We utilized the [UCF Crime Dataset](https://www.kaggle.com/datasets/odins0n/ucf-crime-dataset) from Kaggle, which consists of video clips categorized into different classes of criminal activities such as abuse, arson, assault, burglary, and more. Each video clip is labeled with one of the 14 crime categories.

**Model Architecture**
Our crime detection model comprises two main components: a CNN for processing image frames extracted from video clips and an LSTM for analyzing textual descriptions associated with the videos. The CNN processes the visual information, while the LSTM handles the textual data.

**Implementation**
- We used TensorFlow and Keras to build and train our model.
- For the CNN, we designed a deep architecture consisting of multiple convolutional layers followed by max-pooling layers. We also included dropout layers for regularization.
- The LSTM model was designed to process textual descriptions associated with each video clip. We tokenized and padded the text sequences before feeding them into the LSTM.
- We trained the combined CNN-LSTM model on both image and text data to learn features from both modalities simultaneously.

**Results**
- The trained model achieved satisfactory performance in detecting various criminal activities.
- We evaluated the model's performance using metrics such as accuracy, precision, recall, and F1 score.
- The model showed promising results in distinguishing between different classes of criminal activities.

**Future Work**
- Further fine-tuning of hyperparameters and model architecture could potentially improve performance.
- Experimentation with advanced techniques such as attention mechanisms and multi-modal fusion could enhance the model's ability to capture complex relationships between image and text data.

**Conclusion**
Our crime detection model demonstrates the effectiveness of combining CNN and LSTM networks for analyzing multi-modal data. By leveraging both visual and textual information, our model can effectively detect criminal activities from video data, offering valuable insights for law enforcement and public safety applications.

*************

**Feel free to customize and expand upon this template to provide more detailed information about your project, implementation details, results, and future directions. Additionally, include relevant code snippets, visualizations, and links to the dataset and code repository for reference.**
