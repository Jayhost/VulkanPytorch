# VulkanPytorch
Collect scripts / notes for Vulkan Pytorch 

## As of 13 may 2024, you must go into vulkan sdk folder and possibly run . setup-env.sh and ./vulkansdk 
## instead of python install_vulkan.py as this seems old

cd PYTORCH_ROOT
USE_VULKAN=1 USE_ROCM=0 USE_VULKAN_SHADERC_RUNTIME=1 USE_VULKAN_WRAPPER=0 python setup.py install

##To build pytorch on Vulkan ROCM must be disabled but isn't mentioned in https://pytorch.org/tutorials/prototype/vulkan_workflow.html

## Import from directory other than the one you build in
## for Reference https://github.com/pytorch/pytorch/issues/48578

