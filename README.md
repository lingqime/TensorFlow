## TensorFlow

In `exercise 1`
Instead of using `import tensorflow as tf`, we should use

`import tensorflow.compat.v1 as tf`

`tf.disable_v2_behavior()`

Otherwise we have error `module 'tensorflow' has no attribute 'random_uniform'`
