# Model Viewer
Visual Studio Tools for AI has integrated Netron, a viewer for neural network, deep learning and machine learning models. The viewer supports ONNX (.onnx, .pb), Keras (.h5, .keras), CoreML (.mlmodel) and TensorFlow Lite (.tflite). It also has experimental support for Caffe (.caffemodel), Caffe2 (predict_net.pb), MXNet (-symbol.json), TensorFlow.js (model.json, .pb) and TensorFlow (.pb, .meta).

## Prerequisites
Before viewing a model, make sure Netron is installed. To install Netron, download the latest version from [Netron release page](https://github.com/lutzroeder/Netron/releases) .

## Launch Model Viewer
There two entries to launch model viewer:
- Launch Visual Studio and select **AI Tools > Model Tools > View Model...**.
- Right click a supported model file from model inference library project or deep learning application project in solution explorer, click **View Model**.

![View Model](./media/model-viewer/launch.png)