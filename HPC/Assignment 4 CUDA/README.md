pip install git+https://github.com/afnan47/cuda.git

%load_ext nvcc_plugin

!nvcc add.cu -o add

!./add
