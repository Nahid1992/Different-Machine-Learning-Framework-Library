# Different-Machine-Learning-Framework & Library

### Scikit Library:
	link: http://scikit-learn.org/stable/
* Supports more or less most of the general machine learning algorithm
* Does not support Neural Network
* Does not support GPU

### CAFFE Framework:
link: http://caffe.berkeleyvision.org/
	Not very Flexible
	Each Nodes are considered Layer
	Building Blocks are larger and extra work needed for Feed Forward as well as Backprop
	Extra Functions needed for CPU and GPU usages
	Define Model using Plain Text
	
### TensorFlow Framework:
link: https://www.tensorflow.org/
  Supports Multiple GPU
	Each Nodes are considered as Tensor Operations
	Example:=> Matrix Add Mul Sub ... 
	Layer defined as composition of those Matrix Operations
	Building BLocks are smaller and easy to use
	Models are created inside program
	Models are easy to modify
	Best for Industry and Research
	Outperforms Theano for parallel execution across multiple GPU
	Growing very fast
	
### Keras Library:
link: https://keras.io/
	Good for starting Deep Learning
	Provides various high level API 
	Works as Object Oriented Design
	Supports beckend framework like TensorFlow & Theano
	Performance issue while using on top of TensorFlow (Not very much Optimized)
	BUT on top of Theano it works pretty well
	
### TF Learn Library:
link: http://tflearn.org/
	Basically KERAS but optimized for Tensorflow
	Better in Research
	
### Theano Library:
link: http://deeplearning.net/software/theano/
	Best for Industry and Research
	Theano outperforms TensorFlow with SINGLE GPU
	Supports Windows very smoothly
	Huge Documentation
