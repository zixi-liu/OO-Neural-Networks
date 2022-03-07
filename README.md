# OO-Neural-Networks
Objected-oriented neural networks implementations. Understanding Pytorch's backend codebase in C/C++.

## Pytorch

**Architecture**

```bash
├── autograd
├── backends
├── contrib
...
├── csrc
│   ├── allocators.cpp
│   ├── allocators.h
│   ├── assertions.cpp
│   ├── assertions.h
│   ├── autograd
│   ├── byte_order.cpp
│   ├── byte_order.h
│   ├── copy_utils.h
│   ├── cuda
│   ├── DataLoader.cpp
│   ├── distributed
│   ├── dl.c
│   ├── DynamicTypes.cpp
│   ├── DynamicTypes.h
│   ├── Exceptions.cpp
│   ├── Exceptions.h
│   ├── expand_utils.cpp
│   ├── expand_utils.h
│   ├── Generator.cpp
│   ├── Generator.h
│   ├── generic
│   ├── jit
│   ├── Module.cpp
│   ├── Module.h
│   ├── ModuleSparse.cpp
│   ├── nn
│   ├── nnpack
│   ├── nvrtc.cpp
│   ├── onnx
│   ├── PtrWrapper.cpp
│   ├── PtrWrapper.h
│   ├── PythonTypes.h
│   ├── README.md
│   ├── serialization.cpp
│   ├── serialization.h
│   ├── Size.cpp
│   ├── Size.h
│   ├── Storage.cpp
│   ├── Storage.h
│   ├── Tensor.cpp
│   ├── Tensor.h
│   ├── THP_API.h
│   ├── THP_export.h
│   ├── THP.h
│   ├── Types.h
│   ├── utils
│   ├── utils.cpp
│   └── utils.h
├── cuda
...
├── distributed
...
├── distributions.py
├── for_onnx
...
├── jit
├── legacy
├── lib
│   ├── ATen
│   ├── build
│   ├── build_libs.bat
│   ├── build_libs.sh
│   ├── gloo
│   ├── include
│   ├── libshm
│   ├── libshm_windows
│   ├── libTH.so.1
│   ├── nanopb
│   ├── nccl
│   ├── pybind11
│   ├── README.md
│   ├── TH
│   ├── THC
│   ├── THCUNN.h
│   ├── THD
│   ├── THNN.h
│   └── tmp_install
├── multiprocessing
├── nn
├── onnx
├── optim
├── random.py
├── serialization.py
...
├── _thnn
├── _torch_docs.py
├── utils
└── _utils.py

53 directories, 110 files
```
