# cuda_kernels

[PyTorch kernels](https://github.com/pytorch/pytorch/tree/master/aten/src/ATen/native/cuda)

---

[Tensorflow kernles](https://github.com/tensorflow/tensorflow/tree/master/tensorflow/core/kernels)

---

[How to write your own CUDA kernel on Tensorflow](https://www.tensorflow.org/guide/create_opl)

- crop_op.h: header file
- crop_op.cc: Registers the new TF operation and CPU/GPU kernels. Defines CPU implementation and OpKernel.
- crop_op.cu.cc: Defines GPU kernels

[ADDING CUSTOM CUDA C++ OPERATIONS IN
TENSORFLOW FOR BOOSTING BERT INFERENCE](https://on-demand.gputechconf.com/ai-conference-2019/T1-3_Minseok%20Lee_Adding%20custom%20CUDA%20C++%20Operations%20in%20Tensorflow%20for%20boosting%20BERT%20Inference.pdf)

---

[microsoft DeepSpeed kernels](https://github.com/microsoft/DeepSpeed/tree/master/csrc/transformer)
- transformer