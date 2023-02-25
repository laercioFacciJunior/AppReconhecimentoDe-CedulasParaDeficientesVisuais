# Aplicativo Android Detector cedulas usando a classificação de imagens do TensorFlow Lite

## Visão geral

Este é um exemplo de aplicação para [TensorFlow Lite](https://tensorflow.org/lite)
no Android. Ele usa
[Image classification](https://www.tensorflow.org/lite/models/image_classification/overview)
para classificar continuamente imagens da câmera traseira do dispositivo.
A inferência é realizada, usando a API Java do TensorFlow Lite. O aplicativo
classifica frames em tempo real, exibindo os resultados mais prováveis a 
classificações. Permite ao usuário escolher entre um ponto flutuante ou
[quantized](https://www.tensorflow.org/lite/performance/post_training_quantization)
modelo, selecione a contagem de threads e decida se deseja executar CPU, GPU, ou via
[NNAPI](https://developer.android.com/ndk/guides/neuralnetworks).

Estas instruções orientam com fazer a construção e executando a demonstração em um dispositivo Android. 
Para obter uma explicação sobre a fonte, consulte
[TensorFlow Lite Android image classification example](https://www.tensorflow.org/lite/models/image_classification/android).

<!-- TODO(b/124116863): Add app screenshot. -->



