# Temperature prediction using a DCNN (Regression Task)

This repository contains the files for the project - Temperature prediction using Deep Learning. Tradionally, LSTMs or Bi-LSTMs are used for time series data to make accurate predictions. As an alternative approach, we decided to convert time series data to images using Gramian Angular Field encoding. We were then able to train a convolutional neural network to predict the temperature for the city of Delhi, India. The model was able to learn all the patterns associated with the time series data and gave a Mean Absolute Error (MAE) of 2 degrees. The CNN used is essentially the VGG16 model (we do not use transfer learning).

### Contributors:
- Sarthak Bhargava (https://github.com/Sarthak0211)
- Arunit Maity (https://github.com/arunitmaity)
