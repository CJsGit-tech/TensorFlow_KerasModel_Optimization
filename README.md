# TensorFlow_KerasModel_Optimization

### Summary
Briefly introduce Keras models optimization toolkit and some demonstrations that I built for exploration. <br>
Most of the codes are borrowed from the official TensorFlow Tutorials. However, the notebooks also contains a lot of self-studied notes and modifications in models.

### References
Inside TensorFlow: TF Model Optimization Toolkit (Quantization and Pruning): https://www.youtube.com/watch?v=4iq-d2AmfRU<br>
Optimize machine learning models: https://www.tensorflow.org/model_optimization <br>

### Results
Model Size Reduction
<img source='images/ResNet.png'>

Infernce Time and Model Loading Time
<img source='images/ResNet2.png'>

<b>Note: <br> While I was researching and implementing optimization techniques, I realized that "Running a TFLite Model using PC or Laptop CPUs can result in very very very poor inference time performance!"</b> <br>
<b><i>It seems to be that TensorFlow Lite models are designed to run on Mobile CPUs and other specific hardware. Therefore, if one tries to make an inference on PC CPUs, you get terrible results!</i></b>

<br>
TF Lite Model Inference results
<img source='images/CM.png'>
