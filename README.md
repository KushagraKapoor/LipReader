# LipReader
# LipReader

LipReader is a lip-reading model built using a **bi-directional LSTM** architecture in **PyTorch**. This model is designed to predict the next character in a sequence based on lip movements, trained on clean videos with focus on the lip region. The project is aimed at real-time lip-reading applications.

The model uses **CTC loss** to predict characters from a series of frames. It is deployed with a Streamlit interface where users can upload videos for real-time predictions.

## Features

- **Character-Level Prediction**: Predicts the next character in a sequence based on the lip movements.
- **Bi-LSTM Architecture**: Uses a two-layer bi-directional LSTM to capture context from both past and future frames.
- **3D Convolutional Layers**: Uses 3D convolutions to extract spatial and temporal features from video frames.
- **CTC Loss**: Utilizes **Connectionist Temporal Classification** (CTC) loss for sequence-to-sequence tasks where alignment is unknown.
- **Real-Time Demo**: Deployed with Streamlit for easy interaction and testing.

## Dependencies

- Python 3.x
- PyTorch
- OpenCV
- Numpy
- WandB (for experiment tracking)

To install the required dependencies, use the following:

```bash
pip install -r requirements.txt
