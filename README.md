## Profiling GPU usage on Google Colab

This notebook will walk you through how to correctly (as of August 2022) install/configure everything you need to be able to run GPU profiling on Google Colab with NVIDIA's DLProf and DLProfViewer.

**Note that this does not allow you to profile code running in the notebook's cells directly!**
The code you want to profile will need to be stored in regular python files. This is still useful if Colab is your main source of GPUs. 

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/wbuchwalter/colab_gpu_profiling/blob/main/GPU_Profiling_from_colab.ipynb)

