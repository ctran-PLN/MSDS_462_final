# MSDS_462_final
Final project utilizing Openvino Movidius stick 2 for live style transfer. This project is built on top of user 赵巍 Zhaw's fast_mrf_cnn, link [here](https://github.com/zhaw/neural_style).

### Openvino Movidius stick 2
Follow instructions from Intel Openvino website to install the toolkit. like [here](https://docs.openvinotoolkit.org/latest/index.html).

### Optimizer
Zhaw's original model was trained in MXNet framework. This project has already converted it to Openvino's support representations in .xml and .bin in nst_vgg19 folder.

### Run before notebook
source /opt/intel/openvino/bin/setupvars.sh
