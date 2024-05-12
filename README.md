# VulkanPytorch
Collect scripts / notes for Vulkan Pytorch 

cd PYTORCH_ROOT
USE_VULKAN=1 USE_ROCM=0 USE_VULKAN_SHADERC_RUNTIME=1 USE_VULKAN_WRAPPER=0 python setup.py install

##To build pytorch on Vulkan ROCM must be disabled but isn't mentioned in https://pytorch.org/tutorials/prototype/vulkan_workflow.html

