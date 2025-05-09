Speech Emotion Recognition presents a deep learning project focused on classifying human emotions from speech audio. This project utilizes the Toronto Emotional Speech Set (TESS) dataset, which comprises 2,800 audio recordings of 200 target words spoken by two actresses (aged 26 and 64) portraying seven emotions: anger, disgust, fear, happiness, pleasant surprise, sadness, and neutral.

Key Components:

Data Preprocessing: The notebook employs the librosa library to extract audio features such as Mel-frequency cepstral coefficients (MFCCs), which are instrumental in capturing the timbral aspects of speech.

Model Architecture: A Long Short-Term Memory (LSTM) neural network is implemented using Keras and TensorFlow. LSTMs are adept at handling sequential data, making them suitable for modeling temporal dependencies in speech signals.

Performance: The model achieves an accuracy of approximately 67% in classifying the seven emotional states. 

Libraries Used: The project leverages several Python libraries, including pandas for data manipulation, matplotlib for visualization, keras and tensorflow for building and training the neural network, and librosa for audio processing.
