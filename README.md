# FYPUCC
Generative Adversarial Networks for time series forecasting

Financial Time series Data is incredibly hard to model due to the non-linear complexity of
financial markets. This study explores the potential of deep learning in capturing market dy-
namics, proposing a Generative Adversarial Network which positions Long Short Term Memory
networks as the generator and Convolutional Neural Networks as the discriminator, leveraging
their strengths to capture the trends and patterns in the data. The research examines the
use of variants for GANs, with Wassterstein GAN (WGAN) and Metropolis Hastings GAN
(MHGAN). WGAN uses the Wassterstein distance as a loss function with the goal of enhanc-
ing training stability while MHGAN incorporates Metropolis Hastings sampling into GANs,
refining the sample selection process. The investigation into GAN variants, as contrasted
with the LSTM model, underscores the potential benefits of employing GANs for time series
forecasting. This comparison aims to highlight the robustness of GANS in a domain that is
notoriously hard to predict.

In this repo it pre processes the data adds new features, and structures the data. It then trains 4 models,
LSTM, GAN, Wassterstein GAN and Metropolis Hastings GAN and compares the models to see if they are statistically significant.


References

https://github.com/ChickenBenny/Stock-prediction-with-GAN-and-WGAN/tree/main

https://github.com/ChickenBenny/Metropolis-Hasting-WGAN-on-stock-prediction/tree/main

https://github.com/hungchun-lin/Stock-price-prediction-using-GAN/tree/master

https://github.com/borisbanushev/stockpredictionai

https://github.com/deshpandenu/Time-Series-Forecasting-of-Amazon-Stock-Prices-using-Neural-Networks-LSTM-and-GAN-/tree/master
