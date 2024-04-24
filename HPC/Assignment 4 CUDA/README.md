Before writing code =

pip install git+https://github.com/afnan47/cuda.git

%load_ext nvcc_plugin

After writing code = 

!nvcc file_name.cu -o file_name

!./file_name
