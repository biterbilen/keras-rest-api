# keras-rest-api
Keras Rest API from PyImageSearch
https://www.pyimagesearch.com/2018/01/29/scalable-keras-deep-learning-rest-api/

Tested on p2.xlarge instance with a single GPU for this example.

You can modify the code in this example to leverage multiple GPUs as well by:

- Running multiple model server processes
- Maintaining an image queue for each GPU and corresponding model process

However, keep in mind that your machine will still be limited by I/O. It may be beneficial to instead utilize multiple machines, each with 1-4 GPUs than trying to scale to 8 or 16 GPUs on a single machine.
