# Machine Learning Libraries

### Keras 
Keras is a high-level API that uses deep learning libraries like Theano or Tensorflow as the backend. If you run the program on a CPU, Tensorflow or Theano use **BLAS** libraries. On the other hand, when you run on a GPU, they use **CUDA and cuDNN** libraries.

**If you got an error about downloading of the database use the command below**
```
import ssl
ssl._create_default_https_context = ssl._create_unverified_context
``` 
