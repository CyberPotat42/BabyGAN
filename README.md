# BabyGAN

**Зацените как это работает:** [![Colab](https://camo.githubusercontent.com/52feade06f2fecbf006889a904d221e6a730c194/68747470733a2f2f636f6c61622e72657365617263682e676f6f676c652e636f6d2f6173736574732f636f6c61622d62616467652e737667)](https://colab.research.google.com/github/DenCoder618/BabyGAN/blob/master/Best-BabyGAN.ipynb)

<p>
Средство прогнозирования лиц детей на основе StyleGAN по фотографиям теоретических родителей. Скрытые векторы извлекаются из входных изображений, после чего алгоритм смешивает их в определенных пропорциях. Модель нейронной сети основана на архитектуре GAN. Играя с латентным пространством, вы можете изменять различные параметры: возраст, положение лица, эмоции и пол
</p>  

**Основано на:** [StyleGAN](https://github.com/NVlabs/stylegan)

**Encoder:** [StyleGAN-Encoder](https://github.com/pbaylies/stylegan-encoder)

## Системные требования
* 64-bit Python 3.6 installation
* TensorFlow 1.10.0 with GPU support
* One or more high-end NVIDIA GPUs with at least 11GB of DRAM
* NVIDIA driver 391.35 or newer, CUDA toolkit 9.0 or newer, cuDNN 7.3.1 or newer
