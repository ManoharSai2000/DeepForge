# DeepForge
Identify and discriminate a fake signature and a original signature.

# Framework
**Tensorflow/Keras**

## Intoduction
Similar to face recognition, where the model have to learn and remember a face through one or few sample, Signature Forgery detection invovles the same problem, except that it has to discriminate between fake and real signature which invovles much more complexity.

## Model
This is a specific version of the siamese model which identifies a fake signature when passed with a few shot samples of true signature.

## Metrics
Accuracy is the simple metric used, as the task can be viewed as a classification task.

## Results
Accuracy : 96%

## TODO
* The dataset is currently lisenced and privatized. Upload the dataset.

